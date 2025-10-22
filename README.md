# Comandos-de-Git
Explicacion de los comandos de Git

1- git --version: sirve para ver la version que tenemos instalada en nuestro dispositivo 

2- git config --global user.name: sirve para configurar tu nombre de usuario global en Git aparecerá en todos los commits que hagas.

3- git ocnfig --global user.email: sirve para configurar tu correo electrónico asociado a Git, que se usará para identificarte en los commits.

4- git config --global core.editor "code --wait":Indica que el editor de Git será Visual Studio Code.
El parámetro "--wait" hace que Git espere a que cierres el archivo en VS Code antes de continuar.

5- git config --global core.autocrlf true: Sirve para controlar cómo Git maneja los saltos de línea entre sistemas operativos

6- git config -h: Sirve para mostrar la ayuda del comando git config, con todas sus opciones disponibles.

<img width="1573" height="723" alt="Captura de pantalla 2025-10-20 231724" src="https://github.com/user-attachments/assets/b5021b21-cfd2-4fa4-854a-ec906413d337" />

cd: sirve para cambiar de directorio

git init: Sirve para entrar en nuevo repositorio Git en la carpeta donde uno se encuentra ubicado 

ls -a: sirve para listar todos los archivos o carpetas 

cd .git: Sirve para entrar en la carpeta .git

<img width="1817" height="354" alt="Captura de pantalla 2025-10-21 135443" src="https://github.com/user-attachments/assets/157524b7-8464-46c7-92b7-ce9cced0c9fd" />

code . : Sirve para abrir la carpeta en visual studio code 

git status: Sirve para el estado actual del repositorio

git add archivo1.txt: Sirve para agregar el archivo archivol.txt al área de preparación

<img width="890" height="624" alt="Captura de pantalla 2025-10-21 143503" src="https://github.com/user-attachments/assets/768ddf62-a5d6-4a78-9b1f-dab2bf34e983" />

<img width="877" height="862" alt="Captura de pantalla 2025-10-21 145150" src="https://github.com/user-attachments/assets/f655ee71-8359-4270-b32a-a0fdbc7431d0" />

git commit -m "Commit inicial": Sirve para crear una version guardada del proyecto

git commit: Sirve para guardar los cambios 

<img width="738" height="946" alt="Captura de pantalla 2025-10-21 145230" src="https://github.com/user-attachments/assets/bf78325c-7135-4550-97db-e704421901a8" />

ls: muestra los archivos que hay en la carpeta 

rm archivo2.txt: borra un archivo del directorio

git rm archivo1.txt: Lo borra del disco y además le dice a Git que registre esa eliminación en el próximo commit.

<img width="748" height="923" alt="Captura de pantalla 2025-10-21 145341" src="https://github.com/user-attachments/assets/0a7fbf63-0705-44e4-a376-93e2bcfe28de" />

git restore --staged archivo1.txt: Sirve para quitar el archivo que elejimos del area de preparacion 

git restore archivo1.txt: Sirve para restaurar el archivo 

mv archivo1.txt archivo.txt: Sirve para renombrar un archivo 

<img width="704" height="910" alt="Captura de pantalla 2025-10-21 145410" src="https://github.com/user-attachments/assets/3baf9a97-4f06-4979-8a04-96ba0b9d20f9" />

git mv archivo.txt archivo1.txt: este comando  lo que hace es devolverle el nombre que tenia anteriormente

<img width="586" height="589" alt="Captura de pantalla 2025-10-21 145506" src="https://github.com/user-attachments/assets/740bcfce-95e1-4303-9633-dadf17d994f1" />

git add .gitignore: prepara el archivo para el otro commit Ahora el archivo está en el área de staging, listo para confirmarse.

<img width="1102" height="928" alt="Captura de pantalla 2025-10-21 150649" src="https://github.com/user-attachments/assets/fc627e30-9601-420b-a935-ede952e625c5" />

git status -s: Sirve para mostrar el mensaje del archivo corto

<img width="737" height="593" alt="Captura de pantalla 2025-10-21 150917" src="https://github.com/user-attachments/assets/35160f23-27b9-445e-a2f6-c6a399d135a3" />

git diff: sirve para que el Git te muestre las diferencias entre el archivo actual y el último commit.

<img width="749" height="840" alt="Captura de pantalla 2025-10-21 151542" src="https://github.com/user-attachments/assets/7d597052-efbc-4356-a97f-ef18ed8f4642" />

git diff --staged: Este comando muestra las diferencias entre el último commit y lo que está preparado para el siguiente.

git log --oneline: Sirve para mostrar el historial de commits en una sola línea por cada uno

<img width="715" height="736" alt="Captura de pantalla 2025-10-21 152521" src="https://github.com/user-attachments/assets/42a5f3e7-2d65-4764-8d53-6de7a7d74ad1" />

git checkout -b ramab: Esto sirve para crear una rama y asi cambiarme a ella 

git branch: este me muestra las ramas existentes 

cat archivo2.txt: Sirve para mostrar el contenido que guarda el archivo que estamos llamando

<img width="709" height="526" alt="Captura de pantalla 2025-10-21 152744" src="https://github.com/user-attachments/assets/77ba88d3-0e17-4d91-8647-6e5e82fecb7f" />

<img width="596" height="352" alt="Captura de pantalla 2025-10-21 160219" src="https://github.com/user-attachments/assets/da467d16-2f41-49a5-bcee-9f6ff6180ba0" />

<img width="689" height="171" alt="image" src="https://github.com/user-attachments/assets/3399c491-caf0-4539-a1f3-57abcc7adf19" />

<img width="810" height="190" alt="image" src="https://github.com/user-attachments/assets/55d15f64-49e5-45e8-8d47-3d3098bd5723" />

<img width="630" height="160" alt="image" src="https://github.com/user-attachments/assets/489add64-28e9-45a8-a8d9-c2ec74a4a05b" />

<img width="842" height="203" alt="image" src="https://github.com/user-attachments/assets/c1e7eba9-0614-4f65-a5de-56e2da06412f" />
