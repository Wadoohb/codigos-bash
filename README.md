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
| `nano notas.txt` | escribir en archivo. |
| `echo "Hola mundo" > notas.txt` | escribir en archivo. |
| `echo "Segunda línea" >> notas.txt` | escribir en archivo. |
| `node app.js` | Ejecuta un archivo JavaScript con Node.js. |
| `open index.html` | Abre un archivo HTML en el navegador. |
| `open style.css` | Abre un archivo CSS con la aplicación predeterminada. |
| `open script.js` | Abre un archivo JavaScript con la aplicación predeterminada. |
| `python3 programa.py` | Ejecuta un programa Python. |
| `bash script.sh` | Ejecuta un script Bash. |
| `./script.sh` | Ejecuta un script con permisos de ejecución. |
| `javac Programa.java` | Compila un programa Java. |
| `java Programa` | Ejecuta un programa Java compilado. |
| `gcc programa.c -o programa` | Compila un programa en C. |
| `g++ programa.cpp -o programa` | Compila un programa en C++. |
| `./programa` | Ejecuta un programa compilado. |
| `php index.php` | Ejecuta un programa PHP. |
| `ruby app.rb` | Ejecuta un programa Ruby. |
| `perl script.pl` | Ejecuta un programa Perl. |
| `go run main.go` | Ejecuta un programa Go. |
| `swift archivo.swift` | Ejecuta un programa Swift. |
| `open imagen.png` | Abre una imagen PNG. |
| `open imagen.jpg` | Abre una imagen JPG/JPEG. |
| `open imagen.webp` | Abre una imagen WEBP. |
| `open imagen.gif` | Abre una imagen GIF. |
| `open imagen.svg` | Abre una imagen SVG. |
| `open video.mp4` | Abre un video MP4. |
| `open video.mov` | Abre un video MOV. |
| `open audio.mp3` | Abre un archivo MP3. |
| `open audio.wav` | Abre un archivo WAV. |
| `open documento.pdf` | Abre un archivo PDF. |
| `open documento.docx` | Abre un documento Word. |
| `open hoja.xlsx` | Abre un archivo Excel. |
| `open presentacion.pptx` | Abre una presentación PowerPoint. |
| `open archivo.zip` | Abre un archivo ZIP. |
| `unzip archivo.zip` | Descomprime un archivo ZIP. |
| `tar -xzf archivo.tar.gz` | Descomprime un archivo TAR.GZ. |
| `curl https://ejemplo.com` | Muestra el contenido de una página web o API. |
| `curl -O https://ejemplo.com/archivo.zip` | Descarga un archivo conservando su nombre. |
| `curl -o archivo.zip https://ejemplo.com/archivo.zip` | Descarga un archivo con un nombre personalizado. |
| `wget https://ejemplo.com/archivo.zip` | Descarga un archivo (si `wget` está instalado). |
| `open .` | Abre la carpeta actual en Finder. |
| `open ..` | Abre la carpeta anterior en Finder. |
| `open https://google.com` | Abre un sitio web en el navegador. |

> **💡 Recomendación**
>
> - Si el nombre del archivo **no tiene espacios**, no uses comillas.
>   ```bash
>   node app.js
>   open index.html
>   cat README.md
>   ```
>
> - Si el nombre del archivo **tiene espacios o caracteres especiales**, usa comillas.
>   ```bash
>   open "Mi archivo.pdf"
>   node "Mi programa.js"
>   cat "Notas importantes.txt"
>   ```
>
> - También puedes escapar los espacios con `\`.
>   ```bash
>   open Mi\ archivo.pdf
>   ```
>
> **Buena práctica:** usa nombres de archivos sin espacios, por ejemplo:
>
> ```
> app.js
> index.html
> style.css
> script.js
> mi-proyecto.pdf
> imagen-01.png
> ```

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
| `ps -ax` | Fuerza el cierre de una aplicación. |
| `ps -ax -o comm` | listado de app abiertas. |

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
