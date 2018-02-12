## Git  log
Muestra  el   historial  de  commits

'git  log --pretty=format:"%h - % an, %ar : %s"'
Muestra  la  salida d del  historial  con  le formato  q le indique,os

## Limitar  la  salida del historial
'git log -n': Cambiando la n por  cualquier numero  entero
ejemplo: 'git log -2' los  dos  commits  mas  recientes

git log --after="2018-02-08"<<<<despues de   la  fecha  n
git log --before="2018-02-08 00:00:00"
git log --after="2018-01-08 00:00:00 --before="2018-02-12 00:00:00"
