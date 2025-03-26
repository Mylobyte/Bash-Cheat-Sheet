# 📜 Bash Cheat Sheet para Bandit (OverTheWire) — Bilingüe (Español / English)

---

## 📁 Navegación de Archivos / File Navigation

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `ls` | Lista archivos y carpetas | List files and folders | `-l`, `-a`, `-h` | `-l`: largo / long, `-a`: ocultos / all, `-h`: legible / human-readable |
| `cd` | Cambia de directorio | Change directory | `..`, `~`, `-` | `..`: subir / up, `~`: home, `-`: anterior / previous |
| `pwd` | Muestra ruta actual | Show current path | — | — |
| `mkdir` | Crea carpetas | Create folders | `-p`, `-v` | `-p`: crea rutas / make paths, `-v`: salida / verbose |
| `touch` | Crea archivo vacío | Create empty file | — | — |
| `rm` | Elimina archivos | Delete files | `-r`, `-f`, `-v` | `-r`: recursivo, `-f`: forzar / force, `-v`: verboso |
| `cp` | Copia archivos | Copy files | `-r`, `-v`, `-i` | `-i`: confirma / confirm, `-r`: recursivo, `-v`: verbose |
| `mv` | Mueve o renombra archivos | Move or rename files | `-i`, `-v` | `-i`: confirmar, `-v`: progreso / progress |

---

## 📂 Información del Sistema / System Info

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `whoami` | Usuario actual | Current user | — | — |
| `id` | Info de usuario y grupos | User and group info | — | — |
| `uname` | Info del sistema | System info | `-a` | `-a`: todo / all |
| `stat` | Info de archivo | File info | — | — |
| `lsattr` | Atributos extendidos | Extended attributes | — | — |

---

## 📑 Visualización de Archivos / Viewing Files

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `cat` | Muestra contenido | Show content | `-n`, `-A` | `-n`: numera, `-A`: muestra todo |
| `head` | Primeras líneas | First lines | `-n` | `-n`: cuántas líneas |
| `tail` | Últimas líneas | Last lines | `-n` | `-n`: cuántas líneas |
| `echo` | Imprime texto | Print text | `-n`, `-e` | `-n`: sin salto / no newline, `-e`: interpreta / interpret escapes |
| `file` | Tipo de archivo | File type | — | — |
| `strings` | Extrae texto legible | Extract readable strings | — | — |

---

## 🔍 Búsqueda y Filtros / Search & Filters

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `grep` | Busca texto | Search text | `-i`, `-r`, `-n` | `-i`: sin mayúsculas, `-r`: recursivo, `-n`: número línea |
| `find` | Busca archivos | Find files | `-name`, `-type`, `-exec` | Por nombre, tipo o ejecución |
| `cut` | Corta columnas | Cut columns | `-d`, `-f` | `-d`: delimitador, `-f`: campo |
| `sort` | Ordena líneas | Sort lines | `-r`, `-u` | `-r`: reverso, `-u`: únicos |
| `uniq` | Elimina duplicados | Remove duplicates | `-c` | `-c`: cuenta repeticiones |
| `diff` | Compara archivos | Compare files | — | — |

---

## 📦 Compresión / Compression

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `tar` | Empaqueta archivos | Package files | `-xvf`, `-cvf` | `-xvf`: extraer, `-cvf`: crear |
| `gzip/gunzip` | Comprime/Descomprime gzip | Compress/decompress gzip | — | — |
| `bzip2/bunzip2` | Comprime/Descomprime bzip2 | Compress/decompress bzip2 | — | — |
| `xz/unxz` | Comprime/Descomprime xz | Compress/decompress xz | — | — |
| `base64` | Codifica/decodifica | Encode/decode | `-d` | `-d`: decodificar |
| `xxd` | Hexdump / revertir | Hexdump / revert | `-r` | `-r`: revertir a binario |

---

## 🌐 Red y Conexiones / Networking

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `ssh` | Conecta por SSH | SSH connect | `-p` | Puerto / port |
| `scp` | Copia entre máquinas | Copy between machines | `-P`, `-r` | `-P`: puerto, `-r`: recursivo |
| `nc` | Cliente TCP/UDP | TCP/UDP client | `-l`, `-p` | Escucha, puerto |
| `telnet` | Conexión TCP simple | Simple TCP connect | — | — |
| `wget` | Descarga web | Download from web | `-q`, `-O` | `-q`: silencioso, `-O`: salida |
| `curl` | Cliente HTTP | HTTP client | `-s`, `-o` | `-s`: silencioso, `-o`: salida |

---

## 🛠 Otros

| Comando | Descripción (ES) | Description (EN) | Parámetros comunes | Significado |
|--------|-------------------|------------------|----------------------|-------------|
| `read` | Lee entrada | Read input | — | — |
| `man` | Manual de comandos | Command manual | — | — |

---

> ✅ Esta hoja es ideal para resolver todos los niveles de Bandit (OverTheWire). Puedes copiarla, guardarla, o exportarla para tenerla siempre a mano.

---

