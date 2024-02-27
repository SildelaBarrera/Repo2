1. En primer lugar, se ha de tener un repositorio remoto en GitHub que vincularemos a un repositorio local.
Para ello es necesario clonar el proyecto remoto copiando su URL (disponible en el botón < code >) y
pegandola detrás del comando:  'git clone' .

2. Luego, con el comando 'git status' vamos a comprobar que archivos han sido modificados en el proyecto y serán mostrados en color rojo.

3. El siguiente paso es usar ‘git add’ para elegir el archivo, o los archivos, que vamos a pasar al stage (fase previa a la subida local).

Con ‘git add’ seguido del nombre del archivo ya estaría. Si queremos subir más de uno se han de separar con espacios, y si preferimos subir todos los que tengamos disponibles se usará ‘git add .’ 
Se puede ver si hemos añadido bien los archivo al stage con ‘git status’ de nuevo, y corroborar así si ahora en vez de rojo nos aparecen en verde.

4. Ahora ya están preparados para su commit. Con el comando ‘git commit -m “Título relacionado”' serán almacenados localmente y confirmados para subirse al proyecto final.
Se puede volver a hacer otra comprobación con ‘git status’ y asegurarse de que la rama principal está por detrás de la local debido a ese commit.

5. Por último con el comando ‘git push’ incorporamos los cambios del archivo modificado al proyecto remoto de GitHub.
