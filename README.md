# codigos-bash

<p align="center">
  <img src="assets/bash.jpg" width="100%">
</p>

# 🍎 TERMINAL macOS (Bash / zsh) - CHEAT SHEET

## 📁 Navegación

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `pwd` | Muestra la ruta actual. |
| `ls` | Lista archivos y carpetas. |
| `ls -l` | Lista detallada. |
| `ls -la` | Lista todos los archivos (incluidos ocultos). |
| `cd carpeta` | Entra a una carpeta. |
| `cd ..` | Sube un nivel. |
| `cd ~` | Va a la carpeta del usuario. |
| `cd /` | Va a la raíz del sistema. |
| `clear` | Limpia la pantalla. |
| `history` | Muestra el historial de comandos. |

---

## 📂 Archivos y carpetas

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `mkdir carpeta` | Crea una carpeta. |
| `mkdir -p carpeta/subcarpeta` | Crea varias carpetas. |
| `touch archivo.txt` | Crea un archivo vacío. |
| `cp archivo copia` | Copia un archivo. |
| `cp -R carpeta copia` | Copia una carpeta completa. |
| `mv archivo nuevo` | Renombra un archivo. |
| `mv archivo carpeta/` | Mueve un archivo. |
| `rm archivo` | Elimina un archivo. |
| `rm -r carpeta` | Elimina una carpeta. |
| `rm -rf carpeta` | Fuerza la eliminación. ⚠️ |
| `rmdir carpeta` | Elimina una carpeta vacía. |

---

## 📄 Ver archivos

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `cat archivo.txt` | Muestra el contenido. |
| `less archivo.txt` | Lee un archivo por páginas. |
| `head archivo.txt` | Primeras líneas. |
| `tail archivo.txt` | Últimas líneas. |
| `tail -f archivo.log` | Sigue un archivo en tiempo real. |

---

## 🔍 Buscar

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `find . -name "*.txt"` | Busca archivos. |
| `grep "texto" archivo` | Busca texto. |
| `grep -R "texto" .` | Busca texto en carpetas. |
| `which python3` | Muestra dónde está instalado un programa. |
| `whereis git` | Busca un programa. |

---

## ⚙️ Procesos

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `ps` | Lista procesos. |
| `ps aux` | Lista todos los procesos. |
| `top` | Monitor del sistema. |
| `kill PID` | Finaliza un proceso. |
| `kill -9 PID` | Fuerza el cierre de un proceso. |
| `killall Nombre` | Cierra todos los procesos con ese nombre. |

---

## 🖥️ Aplicaciones

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `open archivo.pdf` | Abre un archivo. |
| `open .` | Abre la carpeta actual en Finder. |
| `open carpeta` | Abre una carpeta. |
| `open -a "Safari"` | Abre una aplicación. |
| `open -a "Visual Studio Code"` | Abre VS Code. |
| `osascript -e 'quit app "Safari"'` | Cierra una aplicación correctamente. |
| `killall Safari` | Fuerza el cierre de una aplicación. |

---

## 🌐 Red

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `ping google.com` | Comprueba la conexión. |
| `curl https://ejemplo.com` | Descarga el contenido de una web. |
| `ifconfig` | Información de red. |
| `ipconfig getifaddr en0` | Muestra la IP local (Wi-Fi). |
| `netstat -an` | Conexiones de red. |
| `nslookup google.com` | Consulta DNS. |

---

## 💾 Discos

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `df -h` | Espacio libre en discos. |
| `du -sh carpeta` | Tamaño de una carpeta. |
| `diskutil list` | Lista los discos. |

---

## 👤 Sistema

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `whoami` | Usuario actual. |
| `who` | Usuarios conectados. |
| `hostname` | Nombre del equipo. |
| `date` | Fecha y hora. |
| `uptime` | Tiempo encendido. |
| `uname -a` | Información del sistema. |
| `sw_vers` | Versión de macOS. |

---

## 📦 Homebrew

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `brew update` | Actualiza Homebrew. |
| `brew upgrade` | Actualiza los paquetes. |
| `brew install paquete` | Instala un programa. |
| `brew uninstall paquete` | Desinstala un programa. |
| `brew search paquete` | Busca un paquete. |
| `brew list` | Lista los paquetes instalados. |
| `brew doctor` | Comprueba el estado de Homebrew. |

---

## 🐙 Git

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `git init` | Inicializa un repositorio. |
| `git clone URL` | Clona un repositorio. |
| `git status` | Estado del proyecto. |
| `git add .` | Agrega cambios. |
| `git commit -m "Mensaje"` | Guarda cambios. |
| `git push` | Sube cambios. |
| `git pull` | Descarga cambios. |

---

## 🐍 Python

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `python3` | Inicia Python. |
| `python3 archivo.py` | Ejecuta un programa Python. |
| `pip3 install paquete` | Instala un paquete. |
| `pip3 list` | Lista los paquetes. |

---

## ⚡ Atajos

| Atajo | ¿Para qué sirve? |
|-------|-------------------|
| `Tab` | Autocompleta. |
| `↑` | Comando anterior. |
| `↓` | Comando siguiente. |
| `Ctrl + C` | Cancela un comando. |
| `Ctrl + D` | Sale de la terminal. |
| `Ctrl + L` | Limpia la pantalla. |
| `Ctrl + A` | Va al inicio de la línea. |
| `Ctrl + E` | Va al final de la línea. |
| `Ctrl + U` | Borra desde el cursor al inicio. |
| `Ctrl + K` | Borra desde el cursor al final. |

---

# ⭐ Comandos que debes memorizar

`pwd` • `ls` • `ls -la` • `cd` • `mkdir` • `touch` • `cp` • `mv` • `rm` • `cat` • `find` • `grep` • `open` • `killall` • `osascript` • `ping` • `curl` • `whoami` • `df -h` • `du -sh` • `brew` • `git` • `python3`
