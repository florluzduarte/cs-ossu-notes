
Fecha de inicio: 16/07/2024
# 💻️ The Linux Command Line (William Shotts)

## Lista de comandos:

1. `cal` --> para ver el calendario del mes actual. En mi caso tuve que instalar un complemento para que funcione, usando el comando `sudo apt install ncal`. Para referencia estoy usando PopOS Linux.  
2. `date` --> para ver la fecha del día.    
3. `pwd` --> para ver en qué carpeta estoy parada.    
4. `ls` --> para listar los archivos de un directorio / carpeta  
	1. `ls -a` --> Lista todos los archivos incluso los ocultos. En Linux el nombre de los archivos ocultos comienza con un punto (.).    
	2. `ls -l` --> Versión larga de ls, lista más datos sobre los archivos y carpetas de cualquier directorio.  
5. `mkdir <folder-name>` --> para crear nuevos directorios  
6. `man <command>` --> para ver el manual con las especificaciones de cualquier comando.   
7. `cp <file-name> <file-copy-name>` --> para hacer una copia de cualquier archivo. El primer parámetro es el archivo que quiero copiar, y el segundo, el nombre del nuevo archivo de copia que voy a generar.  
8. `mv <file-to-rename> <new-name>` --> Para mover / renombrar archivos. El primer parámetro es el archivo que quiero renombrar y, el segundo, es el nuevo nombre. No olvidar la extensión del archivo al hacer esta operación.  
9. `rm <file-to-delete>` --> Para eliminar un archivo  
10. `rmdir <folder-to-delete>` --> Para borrar carpetas. Tienen que estar vacías para que funcione, sino se necesita otro comando que es `rm -fr <folder-to-delete>`)  
11. 