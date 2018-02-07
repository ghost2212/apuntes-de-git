## Curso Git desde cero
###Flujo de  trabajo
en cmd
C:\wamp64\www\cursogit>
git init
crear un archivo readme.md{contenido ## Curso Git desde cero}
en cmd
git status
añadimos archivos
git add readme.md  <<<< preparacion
git commit -m "m es  mensaje commit iniciado" <<<< confirmacion
git log  <<<< ver la confirmacion  te mostrara el hash
para  salir q

###zona  de  prepatacion
*******AHORA  PARA  VER  EL  EDITOR     git config --list | grep editor
Ejemplos de uso
git rebase HEAD~3 -i permite rebase interactivo usando código VS
git commit permite usar código VS para el mensaje de confirmación
git add -pseguido por eagregar interactivo
git difftool <commit>^ <commit> permite usar VS Code como editor de diferencias para cambios


