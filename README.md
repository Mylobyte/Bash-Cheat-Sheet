# 📜 Cheat Sheet de Bash

---

## 📁 Navegación de Archivos

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `ls` | Lista archivos y carpetas | `-l`, `-a`, `-h` | `-l`: largo, `-a`: ocultos, `-h`: tamaño legible |
| `cd` | Cambia de directorio | `..`, `~`, `-` | `..`: subir, `~`: home, `-`: anterior |
| `pwd` | Muestra ruta actual | — | — |
| `mkdir` | Crea carpetas | `-p`, `-v` | `-p`: crea rutas, `-v`: salida verbose |
| `touch` | Crea archivo vacío | — | — |
| `rm` | Elimina archivos | `-r`, `-f`, `-v` | `-r`: recursivo, `-f`: forzar, `-v`: verbose |
| `cp` | Copia archivos | `-r`, `-v`, `-i` | `-i`: confirmar, `-r`: recursivo, `-v`: verbose |
| `mv` | Mueve o renombra archivos | `-i`, `-v` | `-i`: confirmar, `-v`: progreso |

---

## 📂 Información del Sistema

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `whoami` | Usuario actual | — | — |
| `id` | Información de usuario y grupos | — | — |
| `uname` | Información del sistema | `-a` | `-a`: toda la información |
| `stat` | Información de archivo | — | — |
| `lsattr` | Atributos extendidos | — | — |

---

## 📑 Visualización de Archivos

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `cat` | Muestra contenido | `-n`, `-A` | `-n`: numera líneas, `-A`: muestra caracteres especiales |
| `head` | Primeras líneas | `-n` | `-n`: cuántas líneas mostrar |
| `tail` | Últimas líneas | `-n` | `-n`: cuántas líneas mostrar |
| `echo` | Imprime texto | `-n`, `-e` | `-n`: sin salto de línea, `-e`: interpreta caracteres especiales |
| `file` | Tipo de archivo | — | — |
| `strings` | Extrae texto legible de binarios | — | — |

---

## 🔍 Búsqueda y Filtros

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `grep` | Busca texto en archivos | `-i`, `-r`, `-n` | `-i`: ignora mayúsculas, `-r`: recursivo, `-n`: muestra número de línea |
| `find` | Busca archivos | `-name`, `-type`, `-exec` | Por nombre, tipo o ejecución de comandos |
| `cut` | Corta columnas de texto | `-d`, `-f` | `-d`: delimitador, `-f`: campo |
| `sort` | Ordena líneas | `-r`, `-u` | `-r`: reverso, `-u`: únicos |
| `uniq` | Elimina duplicados | `-c` | `-c`: cuenta repeticiones |
| `diff` | Compara archivos | — | — |

---

## 📦 Compresión

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `tar` | Empaqueta o desempaqueta archivos | `-xvf`, `-cvf` | `-xvf`: extraer, `-cvf`: crear |
| `gzip/gunzip` | Comprime/Descomprime con gzip | — | — |
| `bzip2/bunzip2` | Comprime/Descomprime con bzip2 | — | — |
| `xz/unxz` | Comprime/Descomprime con xz | — | — |
| `base64` | Codifica o decodifica en base64 | `-d` | `-d`: decodificar |
| `xxd` | Hexdump o revertir a binario | `-r` | `-r`: revertir |

---

## 🌐 Red y Conexiones

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `ssh` | Conecta por SSH | `-p` | `-p`: puerto |
| `scp` | Copia entre máquinas | `-P`, `-r` | `-P`: puerto, `-r`: recursivo |
| `nc` | Cliente TCP/UDP (Netcat) | `-l`, `-p` | `-l`: escucha, `-p`: puerto |
| `telnet` | Conexión TCP simple | — | — |
| `wget` | Descarga archivos de la web | `-q`, `-O` | `-q`: silencioso, `-O`: archivo de salida |
| `curl` | Transferencia por HTTP | `-s`, `-o` | `-s`: silencioso, `-o`: archivo de salida |

---

## 🛠 Otros

| Comando | Descripción | Parámetros comunes | Significado |
|--------|-------------|--------------------|-------------|
| `read` | Lee entrada desde teclado | — | — |
| `man` | Manual de comandos | — | — |

---
