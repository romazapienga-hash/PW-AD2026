# Comandos en GIT.
1. git init: crea un nuevo repositorio Git o reinicia uno existente.
##### ejemplo: git init

2. git clone: Para copiar un repositorio Git de una ubicación a otra, utilizamos el comando git clone. Normalmente copia un repositorio existente, incluyendo registros y versiones,
desde servidores remotos como GitHub o GitLab a tu máquina local.
#### ejemplo: git clone <copied_URL>

3. git status: nos muestra detalles sobre: 
- archivos modificados (archivos modificados pero no puestos en escena).
- archivos no rastreados (archivos que Git no está rastreando).
- archivos preparados (archivos preparados y listos para ser enviados).
#### ejemplo: git status 

4. git commit: guarda los cambios que has realizado (o puesto en escena) en el repositorio local. Cada vez que ejecutas git commit, Git crea una instantánea de tu repositorio en ese momento.
Esto te permite volver a una confirmación anterior siempre que sea necesario.
#### ejemplo: git commit -m "commit_message"

5. git remote add: crea una conexión entre tu repositorio Git local y el repositorio Git remoto,
permitiéndote introducir y extraer cambios entre ellos.
#### ejemplo: git remote add <repo_name> <remote_url>

6. git push: sincroniza tu repositorio remoto con el repositorio local. Una vez que ejecutes este comando,
el repositorio remoto reflejará todos los cambios que hayas confirmado localmente.
#### ejemplo: git push <remote> <branch>
#### ejemplo: git push ---all origin
#### ejemplo: git push --force origin main

7. git pull: recupera y fusiona los cambios del repositorio remoto con los del repositorio local.
#### ejemplo: git pull origin feature-branch

8. git fetch origin: permite revisar los cambios en el repositorio remoto antes de fusionarlos en el local. Descarga los cambios y actualízalos en ramas de seguimiento remotas. Para los que no estén familiarizados,
las ramas de seguimiento remoto son copias de ramas de repositorios remotos.
#### ejemplo: git fetch origin

9. git checkout: puede hacer dos cosas: cambiar entre ramas o restaurar archivos a un estado anterior.
#### ejemplo: git checkout -b feature_branch
#### ejemplo: git checkout -- <file-name>
#### ejemplo: git checkout <branch-name> -- <file-name>

10. git rebase: Vuelve a aplicar los commits de una rama a otra para tener un historial más limpio.
#### ejemplo: git rebase

12. git reset: Deshacer los cambios restableciendo HEAD a un estado anterior.
#### ejemplo: git reset --soft HEAD~1

13. git config: Configura las opciones de Git a nivel de sistema, global o local.
#### ejemplo: git config --global user.name 'Your Name'

14. git clean: Elimina los archivos sin seguimiento del repositorio.
#### ejemplo: git clean -n

15. git stash pop: Aplica los últimos cambios almacenados al directorio de trabajo.
#### ejemplo: git stash pop

16. git diff: Muestra las diferencias entre los distintos estados del depósito.
#### ejemplo: git diff

17. git add: Añade archivos al área de preparación.
#### ejemplo: git add

18. git stash: Guarda temporalmente los cambios no comprometidos y restablece el directorio de trabajo.
#### ejemplo: git stash

19. git rm: Este comando elimina el archivo de su directorio de trabajo y prepara la eliminación.
#### ejemplo: git rm[archivo]

20. git log -follow: Este comando muestra el historial de versiones de un archivo, incluyendo los cambios de nombre.
#### ejemplo: git low -follow[archivo]

