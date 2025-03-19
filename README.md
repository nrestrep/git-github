# git-github

Aprendiendo git y github

## Temas:

- [x] Github: Servidor que ayuda a compartir trabajo con el resto del equipo, y que me permite hacer trabajo simultaneo, tener un   respaldo de lo que estoy haciendo. Puedo crear un repositorio, revisar lo que se ha hecho en las ramas, crear nuevas ramas, ver commits. Servicio basado en la nube para hacer control de versiones. 
Servicio basado en la nube para hacer control de versiones. 
- [x] Clonar un repositorio `git clone`
- [x] Crear una rama `git checkout -b`
- [x] Moverme a otra rama o commit `git checkout`
- [x] Añadir mis cambios `git status` `git add`
- [x] Historial de cambios:
  Para ver el historial de cambios uso git log, el hash es el número que corresponde al identificador único de cada commit. 
- [x] Revertir cambios `git revert` 
   Lo uso cuando quiero deshacer un cambio que hice. Con este comando me queda el registro de commit del cambio que hice y también el registro de commit indicando que revertí el cambio.
- [x] Revertir cambios `git reset`
   Lo uso cuando quiero deshacer un cambio, pero quiero eliminar la historia de que este cambio existió alguna vez  "como cuando hago la nulidad de un matrimonio, que significa que no existió". Me borra todos los comités que tenga antes de ese commit
- [ ] Esconder mis cambios `git stash`
- [ ] Hacer un commit `git commit -m`
- [ ] Modificar un commit `git commit --amend`
- [ ] Hacer un push `git push`: 
      `git push --set upstream origin docs/edit-readme`Este comando es lo mismo que `git push -  u origin docs/edit-readme`. 
      Lo uso cuando voy a subir por primera vez una rama. Esto lo hago para: 1. Compartir información. 2.Respaldo
- [ ] Crear un pull request
- [ ] Merge vs Rebase `git merge` `git rebase`
`git pull --rebase `Git rebase lo uso cuando necesito hacer nuevos commits, partiendo de una base especifica a partir de la cual quiero aplicar mis cambios. 
Me permite mantener una historia limpia del proyecto, permitiendome hacer una fusión de mi rama local, con la rama principal que está en el origen. 
- [ ] Hacer un pull `git pull`
- [ ] Deshacer mis cambios `git reset --soft`
- [ ] Revertir mis cambios `git revert`
- [ ] Cambiar la historia `git rebase -i`
- [ ] Agarrar cerezas `git cherry-pick`

## Links útiles:

- Convenciones de commits y nombramiento de ramas
  https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index
- Para escribir en git, puedo usar sintaxis Markdown
  (Agregar link recomendado)