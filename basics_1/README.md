# Networking Basics #1

Este proyecto es parte del programa de la Escuela Holberton y cubre conceptos básicos de redes. El objetivo es aprender y aplicar conocimientos fundamentales sobre redes a través de varios ejercicios prácticos.

### Lecturas Recomendadas

- [What is localhost](https://www.example.com) - Aprende qué es `localhost`.
- [What is 0.0.0.0](https://www.example.com) - Entiende el propósito de `0.0.0.0`.
- [What is the hosts file](https://www.example.com) - Información sobre el archivo de hosts.
- [Netcat examples](https://www.example.com) - Ejemplos de uso de Netcat.

## Objetivos de Aprendizaje

Al finalizar este proyecto, deberías ser capaz de explicar a cualquier persona, sin la ayuda de Google:

- Qué es `localhost` o `127.0.0.1`.
- Qué es `0.0.0.0`.
- Qué es `/etc/hosts`.
- Cómo mostrar las interfaces de red activas de tu máquina.

## Requisitos Generales

- Editores permitidos: `vi`, `vim`, `emacs`.
- Todos tus archivos serán interpretados en Ubuntu 20.04 LTS.
- Todos tus archivos deben terminar con una nueva línea.
- Un archivo `README.md` en la raíz del directorio del proyecto es obligatorio.
- Todos tus archivos de script Bash deben ser ejecutables.
- Tu script Bash debe pasar Shellcheck (versión 0.7.0 vía `apt-get`) sin errores.
- La primera línea de todos tus scripts Bash debe ser exactamente `#!/usr/bin/env bash`.
- La segunda línea de todos tus scripts Bash debe ser un comentario que explique lo que hace el script.

## Tareas

### 0. Cambiar tu IP de hogar

Escribe un script Bash que configure un servidor Ubuntu con los siguientes requisitos:

- `localhost` debe resolverse a `127.0.0.2`.
- `facebook.com` debe resolverse a `8.8.8.8`.

### 1. Mostrar IPs adjuntas

Escribe un script Bash que muestre todas las IPs IPv4 activas en la máquina en la que se ejecuta.

### 2. Puerto escuchando en localhost

Escribe un script Bash que escuche en el puerto 98 en localhost. 