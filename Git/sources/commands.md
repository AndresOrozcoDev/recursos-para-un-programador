// Iniciar git
git init

// Clonar un repositorio
git clone <url_repo>
  
// Ver los estados de los archivos
git status

// Agregar todos los archivos modificados
git add .

// Agregar archivo especifico
git add README.md

// Agregar el commit
git commit -m "prefijo:mensaje"

// Subir los cambios del commit a la master
git push origin master

// Halar la rama remota master a mi rama local
git pull origin master

// Cambiar de rama
git checkout <name_branch>
  
// Crear nueva rama
git checkout -b <name_new_branch>