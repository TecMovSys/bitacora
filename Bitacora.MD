# Bitácora de Comandos en Kali Linux

**Fecha de inicio:** [24-06-2025]  
**Nombre del usuario:** [CShino]  
**Objetivo del laboratorio:** Documentar el uso de comandos básicos e intermedios en Kali Linux para tareas de aprendizaje durante el semestre

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

---

## 4. Red y escaneo

- `ping direccion_ip`  
  *Verifica conectividad de red.*

- `nmap -sS direccion_ip`  
  *Escaneo de puertos TCP SYN (stealth).*

- `netstat -tulnp`  
  *Muestra conexiones activas y puertos en escucha.*

- `wireshark`  
  *Abre la interfaz gráfica para captura de paquetes.*

---

## 5. Hacking ético y pruebas de penetración

- `msfconsole`  
  *Inicia Metasploit Framework.*

- `searchsploit nombre_servicio`  
  *Busca exploits conocidos en Exploit-DB.*

- `hydra -l usuario -P lista.txt direccion_ip ssh`  
  *Fuerza bruta a servicios como SSH.*

---

## 6. Análisis de vulnerabilidades

- `nikto -h http://direccion_objetivo`  
  *Escaneo web para encontrar vulnerabilidades.*

- `wpscan --url http://direccion_objetivo`  
  *Escaneo de sitios WordPress.*

---

## 7. Notas y observaciones

[Espacio para registrar errores, resultados obtenidos, IPs escaneadas, hallazgos importantes y lecciones aprendidas.]

---

 
**Resumen del trabajo realizado:**  
[Durante el parcial se ha aprendido el uso y manejo de comando de consola en kali linux]
