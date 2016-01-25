# sprint1
//Archivo para mostrar los comandos de GitHub

//Instalacion en Debian y Ubuntu
sudo apt-get install git

//Configuracion Local
git config --global user.name "nombre_usuario"
git config --global user.email "email_id"

//Crear un REpositorio LOcal
git init ejemplo
//Esto Crea una Carpeta llamada ejemplo, con el comando init hace que la carpeta creada sea reconocida como un repositorio local

//Si se Crea el Repositorio con Exito Aparece este linea
Initialized empty Git repository in /home/tu_usuario/Mytest/.git/

//Para Acceder a la Carpeta Creada
gedit ejemplo

//Crear un Archivo README
gedit README
//Y se escribe la DEscripcion del Repositorio y se Guarda

//Para agregar el Archivo README o Cualquier otro Archivo
git add README

// Para dejar un Registro de los Cambios Realizados se hace un commit
gedit commit -m "mensaje"
//mensaje puede ser cualquier mensaje, ejemplo para indicar que cree un repositorio, o modifique un archivo

//Para Conectarse al Repositorio Creado en la Pagina de Github
git remote add origin https://github.com/user_name/ejemplo.git
//El repositorio que queramos conectar tiene que tener el mismo nombre al repositorio CReado en Github

//Empujar archivos del Repositorio local al REpositorio de Github
git push origin master

