# Curso Git desde cero
## Flujo de  trabajo
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
gemela

## zona  de  prepatacion
AHORA  PARA  VER  EL  EDITOR     git config --list | grep editor
Ejemplos de uso
git rebase HEAD~3 -i permite rebase interactivo usando código VS
git commit permite usar código VS para el mensaje de confirmación
git add -pseguido por eagregar interactivo
git difftool <commit>^ <commit> permite usar VS Code como editor de diferencias para cambios

## varios repositorios remotos
Podemos configurar un mismo proyecto para sincronizar varios repositorios remotos.

## configuramos ssh con windows
 
 1. Creamos  un carpeta  en disco local c `llaves-ssh` para  evitar  problemas de  la  ruta
 2. Ejecutamos  el comando ssh-keygen -t rsa -C "mi-correo@gmail.com"
 el correo debe ser  el mismo  con  el  que nos registramos  en github para evitar posibles  problemas
 Dejamos el passprhase vacio y damos enter
 Cuando nos pida ruta escribimos `/c/llaves-ssh/github-rsa`.
 
 3. Agregamos  la  llave ssh en  background ejecutando  `eval "$(ssh-agent -s)"`

 4. Agregamos  la llave ssh generada a ssh-agent  ejecutamos  el comando `ssh-add /c/llaves-ssh/github-rsa `

 5. Desde ahora podemos hacer pull y push sin que github nos este pidiendo cuenta  de  acceso
 