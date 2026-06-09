# Git Merge y Git Rebase

## Git Merge

`git merge` Cuando usas git merge, Git crea un nuevo commit que une las historias de ambas ramas.

## Git Rebase

`git Rebase` Cuando usas git rebase, Git busca el punto exacto en el que tu rama se separó de la rama de destino como main, guarda todos tus commits, y luego los vuelve a aplicar uno por uno al final de la rama actualizada.

### Ejemplo

```bash
git checkout main
git merge desarrollo