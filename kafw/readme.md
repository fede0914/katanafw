comando para crear keygen: ssh-keygen

despues de crear el ssh-keygen vamos al directorio donde se creo y con el comando cat \ruta\ruta\ssh.(privado) y si ponemos .pub obtenemos la public, con eso pasamos abrimos y vemos nuestra key

despues ingremos a la pagina ponemos create new repo(al lado del usuario)
damos nombre bla bla y ponemos que cree como ssh

luego con la consola vamos hacia la carpeta que queremos subir y copiamos el link del repositorio que creamos, ponemos: git remote add origin

cd .git, dentro buscamos el archivo config


como la consola es re cheta no tenemos que hacer nada de eso, solo vamos a la carpeta y hacemos git add .(seguimiento o agregar), se pone git add . para que agregue todo porque es nuevo, pero despues ponemos git add nombrearchivo

git commit -m "iniciando repositorio"

git push -u origin master


pasos desde 0

se va hasta la carpeta, se pone
- git init (master puto)
- git add .
- git commit -m "aca va una notificacion"
- git push origin master o git push git@github.com:fede0914/kata
nafw.git master

			TESTING
- git branch testing (crea un testing con lo que esta ahora)
- git commit -a -m "comit nuevo probando testing"
- git checkout master 
- git commit -a -m "nuevo commit"
- git merge (busca el origen mas piola y fusiona los dos que funcionaban y hace un commit nuevo)



- git branch 






C:\Users\Alumno\kata [master +46 ~0 -0 !]> git remote add origin git@github.com:
fede0914/katanafw.git



bit.ly/1dBjuEy
