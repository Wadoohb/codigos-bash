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

## 🐙 Instalar programas desde GitHub e Internet

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `git clone URL` | Clona (descarga) un repositorio de GitHub, GitLab o Bitbucket. |
| `git pull` | Descarga las últimas actualizaciones del repositorio. |
| `git fetch` | Descarga los cambios sin fusionarlos. |
| `cd repositorio` | Entra en la carpeta del proyecto. |
| `ls` | Muestra los archivos del proyecto. |
| `cat README.md` | Lee las instrucciones de instalación del proyecto. |
| `less README.md` | Lee el README por páginas. |
| `npm install` | Instala las dependencias de un proyecto Node.js. |
| `npm start` | Inicia un proyecto Node.js. |
| `npm run dev` | Ejecuta el proyecto en modo desarrollo. |
| `npm run build` | Genera la versión de producción del proyecto. |
| `node app.js` | Ejecuta un archivo JavaScript con Node.js. |
| `python3 programa.py` | Ejecuta un programa Python. |
| `pip install -r requirements.txt` | Instala las dependencias de un proyecto Python. |
| `composer install` | Instala las dependencias de un proyecto PHP. |
| `cargo install --path .` | Instala un proyecto Rust desde la carpeta actual. |
| `go install` | Instala un proyecto Go. |
| `make` | Compila un proyecto que utiliza Makefile. |
| `make install` | Instala el programa compilado. |
| `chmod +x install.sh` | Da permisos de ejecución a un script. |
| `./install.sh` | Ejecuta un instalador desde la carpeta actual. |
| `bash install.sh` | Ejecuta un script Bash de instalación. |
| `brew install paquete` | Instala un paquete con Homebrew. |
| `brew install --cask aplicacion` | Instala una aplicación gráfica (Visual Studio Code, Google Chrome, Docker, etc.). |
| `brew uninstall paquete` | Desinstala un paquete de Homebrew. |
| `brew update` | Actualiza Homebrew. |
| `brew upgrade` | Actualiza todos los paquetes instalados. |
| `brew search paquete` | Busca un paquete en Homebrew. |
| `brew list` | Muestra los paquetes instalados con Homebrew. |
| `curl URL` | Muestra el contenido de una página web o API. |
| `curl -O URL` | Descarga un archivo conservando su nombre. |
| `curl -o archivo URL` | Descarga un archivo con un nombre personalizado. |
| `wget URL` | Descarga un archivo desde Internet (si está instalado). |
| `open archivo.dmg` | Abre un instalador `.dmg`. |
| `open archivo.pkg` | Abre un instalador `.pkg`. |
| `installer -pkg archivo.pkg -target /` | Instala un paquete `.pkg` desde la Terminal. |
| `xcode-select --install` | Instala las herramientas de desarrollo de Xcode. |

> **💡 Flujo recomendado para instalar un proyecto de GitHub**
>
> ```bash
> git clone URL
> cd repositorio
> ls
> cat README.md
> ```
>
> Después sigue las instrucciones del `README.md`. Dependiendo del proyecto, normalmente usarás alguno de estos comandos:
>
> ```bash
> npm install
> npm start
> ```
>
> o
>
> ```bash
> pip install -r requirements.txt
> python3 programa.py
> ```
>
> o
>
> ```bash
> make
> make install
> ```
>
> o
>
> ```bash
> ./install.sh
> ```
>
> **📌 Consejo:** Antes de ejecutar cualquier proyecto descargado de Internet, revisa siempre el contenido del `README.md` y, si existe, del script `install.sh` para entender qué instalará o ejecutará.
---
## 🤖 Ejecutar Inteligencia Artificial local

| Comando | ¿Para qué sirve? |
|---------|-------------------|
| `ollama serve` | Inicia el servidor de Ollama. |
| `ollama run llama3.2` | Ejecuta el modelo Llama 3.2. |
| `ollama run mistral` | Ejecuta el modelo Mistral. |
| `ollama run gemma3` | Ejecuta el modelo Gemma. |
| `ollama run deepseek-r1` | Ejecuta el modelo DeepSeek R1. |
| `ollama run qwen3` | Ejecuta el modelo Qwen. |
| `ollama list` | Lista los modelos instalados. |
| `ollama pull modelo` | Descarga un modelo. |
| `ollama rm modelo` | Elimina un modelo instalado. |
| `ollama show modelo` | Muestra información de un modelo. |
| `ollama stop modelo` | Detiene un modelo en ejecución. |
| `ollama ps` | Muestra los modelos que están ejecutándose. |
| `ollama create nombre -f Modelfile` | Crea un modelo personalizado. |
| `ollama cp origen destino` | Duplica un modelo. |
| `ollama --version` | Muestra la versión de Ollama. |
| `lmstudio` | Inicia LM Studio (si está instalado). |
| `llama-server -m modelo.gguf` | Inicia un servidor con llama.cpp. |
| `llama-cli -m modelo.gguf` | Ejecuta un modelo GGUF desde la terminal. |
| `python3 webui.py` | Inicia Stable Diffusion WebUI. |
| `python3 app.py` | Ejecuta una aplicación de IA escrita en Python. |
| `docker compose up` | Inicia una IA usando Docker Compose. |
| `docker run imagen` | Ejecuta un contenedor Docker. |




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
