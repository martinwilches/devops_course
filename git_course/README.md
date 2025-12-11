# Hello Git

descartar los cambios realizados en el proyecto posteriores a un commit especifico

```bash
git checkout <COMMIT_SHA>
```

crear una nueva rama y ubicarse inmediatamente en ella

```bash
git switch -c <BRANCH_NAME>
```

publicar una rama en el repositorio remoto

```bash
git push --set-upstream origin <BRANCH_NAME>
```
