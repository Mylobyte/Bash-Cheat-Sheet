# 📜 Bash Cheat Sheet

## 📁 Navegación de Archivos

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `ls` | Lista archivos y carpetas | `-l`, `-a`, `-h` | Largo, ocultos, tamaño legible | `ls -lah` |
| `cd` | Cambia de directorio | `..`, `~`, `-` | Subir, home, anterior | `cd ..` |
| `pwd` | Muestra ruta actual | — | — | `pwd` |
| `mkdir` | Crea carpetas | `-p`, `-v` | Rutas intermedias, verbose | `mkdir -pv ruta/nueva` |
| `touch` | Crea archivo vacío | — | — | `touch archivo.txt` |
| `rm` | Elimina archivos | `-r`, `-f`, `-v` | Recursivo, forzar, verbose | `rm -rf carpeta/` |
| `cp` | Copia archivos | `-r`, `-v`, `-i` | Recursivo, verbose, confirmar | `cp -r fuente/ destino/` |
| `mv` | Mueve o renombra archivos | `-i`, `-v` | Confirmar, progreso | `mv archivo.txt nuevo_nombre.txt` |

## 📂 Información del Sistema

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `whoami` | Usuario actual | — | — | `whoami` |
| `id` | Info de usuario y grupos | — | — | `id` |
| `uname` | Info del sistema | `-a` | Todo el sistema | `uname -a` |
| `stat` | Info detallada de archivo | — | — | `stat archivo.txt` |
| `lsattr` | Atributos extendidos | — | — | `lsattr archivo.txt` |
| `df` | Espacio en disco | `-h` | Tamaño legible | `df -h` |
| `du` | Uso de espacio en archivos | `-sh` | Tamaño total legible | `du -sh carpeta/` |

## 📑 Visualización de Archivos

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `cat` | Muestra contenido | `-n`, `-A` | Numera, muestra caracteres | `cat -n archivo.txt` |
| `head` | Primeras líneas | `-n` | Número de líneas | `head -n 10 archivo.txt` |
| `tail` | Últimas líneas | `-n` | Número de líneas | `tail -n 20 archivo.txt` |
| `echo` | Imprime texto | `-n`, `-e` | Sin salto, caracteres especiales | `echo -e "Hola\nMundo"` |
| `file` | Tipo de archivo | — | — | `file binario` |
| `strings` | Extrae texto de binarios | — | — | `strings binario` |

## 🔍 Búsqueda y Filtros

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `grep` | Busca texto | `-i`, `-r`, `-n` | Ignora mayúsculas, recursivo, línea | `grep -rin "clave" ./` |
| `find` | Busca archivos | `-name`, `-type`, `-exec` | Por nombre, tipo o comando | `find . -name "*.log"` |
| `cut` | Corta columnas | `-d`, `-f` | Delimitador, campo | `cut -d: -f1 /etc/passwd` |
| `sort` | Ordena líneas | `-r`, `-u` | Reverso, únicos | `sort archivo.txt` |
| `uniq` | Elimina duplicados | `-c`, `-u` | Cuenta, únicos | `uniq -c archivo.txt` |
| `diff` | Compara archivos | — | — | `diff archivo1.txt archivo2.txt` |

## 📦 Compresión

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `tar` | Empaqueta/Desempaqueta | `-xvf`, `-cvf` | Extraer, crear | `tar -xvf archivo.tar` |
| `gzip/gunzip` | Comprime/Descomprime | — | — | `gzip archivo.txt` |
| `bzip2/bunzip2` | Comprime/Descomprime | — | — | `bunzip2 archivo.bz2` |
| `xz/unxz` | Comprime/Descomprime | — | — | `xz archivo.txt` |
| `base64` | Codifica/decodifica | `-d` | Decodificar | `base64 -d archivo.b64` |
| `xxd` | Hexdump/binario | `-r` | Revertir | `xxd -r hex.txt` |

## 🌐 Red y Conexiones

| Comando | Descripción | Parámetros comunes | Significado | Ejemplo |
|--------|-------------|--------------------|-------------|---------|
| `ssh` | Conexión remota | `-p` | Puerto | `ssh -p 2222 usuario@host` |
| `scp` | Copia entre máquinas | `-P`, `-r` | Puerto, recursivo | `scp -rP 22 archivo user@host:/ruta` |
| `nc` | Cliente TCP/UDP | `-l`, `-p` | Escucha, puerto | `nc -l -p 1234` |
| `telnet` | Conexión TCP | — | — | `telnet host 80` |
| `wget` | Descarga web | `-q`, `-O` | Silencioso, salida | `wget -qO archivo.html URL` |
| `curl` | Transferencia HTTP | `-s`, `-o` | Silencioso, salida | `curl -so archivo URL` |

## 🛠 Otros Útiles

| Comando | Descripción | Ejemplo |
|--------|-------------|---------|
| `read` | Lee entrada del usuario | `read nombre` |
| `man` | Manual de comandos | `man ls` |
| `alias` | Crea alias de comandos | `alias ll='ls -lah'` |
| `chmod` | Cambia permisos | `chmod +x script.sh` |
| `chown` | Cambia dueño de archivos | `chown user:grupo archivo` |
| `ps` | Procesos en ejecución | `ps aux` |
| `kill` | Mata procesos | `kill -9 PID` |
| `top/htop` | Monitor de procesos | `top` |

## 🔗 Operadores Bash útiles

- `|` — Pipe: pasa la salida de un comando al siguiente.
- `>` — Redirige salida a archivo (sobrescribe).
- `>>` — Redirige salida (añade).
- `&&` — Ejecuta el segundo comando solo si el primero tuvo éxito.
- `;` — Ejecuta comandos secuencialmente.

---

**📌 Nota:** Ejecuta `man [comando]` para más detalles.

