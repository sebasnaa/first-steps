**Parte 1: Autenticación con usuario y contraseña**

Enunciado del ejercicio:

1. Conecta a un servidor remoto utilizando SSH con tu nombre de usuario y contraseña.
2. Una vez conectado, explora el sistema de archivos remoto y encuentra un archivo específico.
3. Descarga ese archivo en tu directorio local utilizando el comando `scp`.

**Parte 2: Autenticación con clave pública y privada**

Enunciado del ejercicio:

1. Genera un par de claves pública y privada en tu máquina local utilizando el comando `ssh-keygen`.
2. Copia la clave correspondiente en el servidor remoto utilizando el comando `ssh-copy-id`.
3. Intenta conectar al servidor remoto utilizando SSH, esta vez sin proporcionar una contraseña, solo con la clave generada anteriormente.
4. Una vez conectado, repite la tarea de explorar el sistema de archivos remoto y encontrar el mismo archivo específico.
5. Descarga nuevamente ese archivo en tu directorio local utilizando el comando `scp`, pero esta vez sin proporcionar una contraseña.

Este ejercicio te permitirá experimentar con dos métodos diferentes de autenticación en SSH: usuario/contraseña y clave pública/privada. Además, te dará una comprensión práctica de cómo funcionan estos mecanismos de autenticación en un entorno real.
