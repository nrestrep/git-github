# git-github

Aprendiendo git y github

## Temas:

- [x] Github: Servidor que ayuda a compartir trabajo con el resto del equipo, y que me permite hacer trabajo simultaneo, tener un respaldo de lo que estoy haciendo. Puedo crear un repositorio, revisar lo que se ha hecho en las ramas, crear nuevas ramas, ver commits. Servicio basado en la nube para hacer control de versiones. 
      Servicio basado en la nube para hacer control de versiones.
- [x] Clonar un repositorio `git clone`
- [x] Crear una rama `git checkout -b`
- [x] Moverme a otra rama o commit `git checkout`
- [x] Añadir mis cambios `git status` `git add`
- [x] Historial de cambios `git log`
  - El hash es el identificador único de cada commit
- [x] Revertir cambios `git revert`
  - Lo uso cuando quiero deshacer un cambio que hice
  - Me queda el commit que quer®ia revertir
  - Me queda un nuevo commit que revierte el cambio (queda al final de la historia)
- [x] Resetear cambios `git reset`
  - Lo uso cuando quiero ELIMINAR un commit _"como cuando hago la nulidad de un matrimonio"_
  - Me borra todos los commits que tenga DESPUES de ese commit
  - Puede ser:
    - `--soft` -> preserva pero no mezcla
    - `--mixed` -> (default) mezcla cambios
    - `--hard` -> borra todo
- [ ] Esconder mis cambios `git stash`
- [x] Hacer un commit `git commit -m` -> por terminal
- [ ] Modificar un commit `git commit --amend`
- [x] Hacer un push `git push`
  - `git push --set upstream origin docs/edit-readme` es lo mismo que `git push -u origin docs/edit-readme`
  - Lo uso cuando voy a subir por primera vez una rama. Esto lo hago para: 1. Compartir información. 2. Respaldo
- [ ] Crear un pull request
- [ ] Merge vs Rebase `git merge` `git rebase`
- [x] Hacer un pull `git pull`
  - `git pull --rebase` -> Lo uso cuando quiero unificar el historial de mi rama local con el historial de la rama remota y que adicional a esta combinación queden los cambios que hice en la rama local.
- [ ] Cambiar la historia `git rebase -i`
- [ ] Agarrar cerezas `git cherry-pick`

## Links útiles:

- Convenciones de commits y nombramiento de ramas
  https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index
- Para escribir en git, puedo usar sintaxis Markdown
  (Agregar link recomendado)