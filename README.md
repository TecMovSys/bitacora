# Bitácora de Comandos en Kali Linux

**Fecha de inicio:** [24-06-2025]  
**Nombre del usuario:** [CShino]  
**Objetivo del laboratorio:** Documentar el uso de comandos básicos e intermedios en Kali Linux para tareas de aprendizaje durante el semestre, el objetivo de este laboratorio es familiarizarme con los comandos básicos de Linux, aprendiendo su uso para navegar por el sistema de archivos, gestionar archivos y directorios, y realizar tareas comunes en la terminal de Linux.


---

## 1. Información del sistema

- `uname -a`  
  *Muestra información del sistema operativo y kernel.*

- `hostnamectl`  
  *Proporciona detalles del nombre del host, sistema operativo y arquitectura.*

- `ifconfig` / `ip a`  
  *Muestra la configuración de red de las interfaces.*

---

## 2. Gestión de usuarios y permisos

- `whoami`  
  *Muestra el usuario actual.*

- `sudo su`  
  *Cambia a usuario root.*

- `chmod +x archivo.sh`  
  *Da permisos de ejecución a un script.*

- `chown usuario:grupo archivo`  
  *Cambia el propietario y grupo de un archivo.*

---

## 3. Gestión de archivos y directorios

- `ls -la`  
  *Lista todos los archivos con detalles y archivos ocultos.*

- `cd /ruta`  
  *Cambia de directorio.*

- `mkdir nombre_directorio`  
  *Crea un nuevo directorio.*

- `rm -rf nombre_directorio`  
  *Elimina un directorio de forma recursiva.*

- `cp archivo destino`  
  *Copia archivos o directorios.*

- *Crea un directorio llamado 'mkdir documentos:'`documentos`*
  
- *Crear varios archivos*
  `touch archivo1.txt archivo2.txt archivo3.txt archivo_oculto.txt`


- *Crear un directorio llamdado 'backup'*
`mkdir backup`

- *Muestra la ruta del directorio actual*
`pwd`

- *Comando: ls -l Descripción: Muestra los detalles de los archivos (permisos propietario, tamaño, etc.)*

- *Búsqueda y Eliminación de Archivos*
*Ahora que tenemos varios archivos, procederemos a buscar y eliminar algunos de ellos.*
1.	Comando: `find`
*Descripción: Busca un archivo llamado `archivo2.txt` en el directorio `documentos`.*

- *Uso de Comodines y Filtrado*
*Ahora usaremos comodines para trabajar con varios archivos a la vez.*
1.	Comando: `ls *.txt`
*Descripción: Muestra todos los archivos `.txt` en el directorio actual.*
Ejemplo: `ls*.txt`

- *2.	Comando: `grep`*
*Descripción: Busca la palabra `hola` dentro de `archivo2.txt`.*
Ejemplo: `grep "hola" archivo2.txt`

- *Historial de Comandos*
*Para revisar qué comandos hemos ejecutado, utilizamos el historial.*
Comando: `history`
*Descripción: Muestra el historial de comandos ejecutados en la terminal.*

---

## 4. 

## 5.



## 7. Notas y observaciones



 
**Resumen del trabajo realizado:**  
[Durante el parcial se ha aprendido el uso y manejo de comando de consola en kali linux]
