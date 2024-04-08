# SSH

SSH (Secure Shell) es un protocolo de red que permite el acceso remoto a través de una conexión cifrada. Proporciona una autenticación robusta y es compatible con el inicio de sesión remoto seguro, la ejecución de comandos, la transferencia de archivos, el control de acceso, el reenvío de TCP/IP, etc.

## Funcionamiento

Las claves SSH ofrecen una forma más segura de iniciar sesión en un servidor con SSH que el uso de una contraseña sola. Mientras que una contraseña puede ser eventualmente descifrada mediante un ataque de fuerza bruta, las claves SSH son prácticamente imposibles de descifrar solo con fuerza bruta.

Un par de claves SSH consta de dos largas cadenas de caracteres: una clave pública y una clave privada. Estas claves se generan utilizando un algoritmo criptográfico que ofrece literalmente billones de combinaciones posibles, por lo que las posibilidades de generar un par de claves idéntico al de otra persona son prácticamente nulas.

- Llave/Candado
    
    Puede ayudar pensar en la clave pública como un candado y la clave privada como la llave que desbloquea ese candado:
    
    
    En este ejemplo, no necesariamente te preocuparías por cuántos candados existen y dónde están. Los candados pueden estar distribuidos en cualquier lugar, puedes arrojarlos por todas partes. Siempre y cuando tu llave esté segura, no importa dónde se encuentren los candados. No te importaría si hubiera cientos de copias del mismo candado protegiendo tus cosas, siempre y cuando nunca perdieras posesión de la llave que los abre. Esto también es válido para un par de claves SSH pública/privada.
    

## Uso

Puedes colocar la clave pública (candado) en cualquier servidor y luego desbloquearla conectándote a él con un cliente que ya tenga la clave privada (llave). Cuando ambos coinciden, el sistema permite al usuario conectarse (desbloquear) sin necesidad de una contraseña.