comandos de git:


git status 
    da informacion sobre el repo en donde estas

git status -s 
    informacion reducida sobre el repo en donde estas parado

git branch 
    informa las ramas existentes
    y coloca un asterisco(*) sobre la que rama estas trabajando

git add . (no se recomienda del todo a menos que se sepa exactamente que haz cambiado)
    agrega todos los archivos del repo a stage

git add .(terminacion del archivo) 
    ex: git add .txt
    se agregan todos los archivos con terminacion .txt

rm (nombre del archivo)
    ex: rm test.txt
    se elimina el archivo test.txt

git checkout -b (nombre de la rama que desea crear)
    ex: git checkout -b test
    se crea una rama con nombre test

git checkout (nombre de rama)
    ex: git checkout main
    te cambia de la rama de donde estas a la rama main

git log --oneline 
    de informacion sobre todos los cambios realizados en el repo

git pull
    actualiza al cambio actual del repositorio

git merge (nombre de la rama a agregar) (debes estar situado en la rama a donde lo quieres agregar)
    ex: git merge test
    se agregan a la rama main los cambios realizados en la rama test

git config --global -e
    ver archivo de configuracion de github

git config --global core.editor "code --wait"    
    predefinir editor de codigo

git config --global user.name
    name 

git config --global user.email
    email

git checkout -- .
    (elimina todos los cambios y regresa al ultimo commit)


