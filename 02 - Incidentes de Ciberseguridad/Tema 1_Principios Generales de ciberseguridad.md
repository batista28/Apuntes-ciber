
# Aspectos de seguridad
- Confidencialidad
- Integridad
- Disponibilidad
# Elementos a proteger

Hardware
Software
Datos

# Tipos de amenazas



![[Pasted image 20241010161104.png]]
 # **Interrupción**: se ve afectada la disponibilidad 
**Modificación**: se ve afectada la integridad, confidencialidad
**Intercepción**: se ve afectada la confidencialidad
**Fabricación**: se ve afectada la integridad 

# Proceso habitual:

Escaneo de puerto
Interceptación lógica(sniffing)
Fabricación(spoofing)
Denegación de servicio (DoS). Distribuido (DDOS):se consume todo el ancho de banda/procesamiento de un servicio 

# Origen de las amenazas:
**Personas**:personal, ex empleados, curiosos, crackers, terroristas, hackers, intrusos remunerados, etc.
**Amenazas lógicas**:programas, ya sea mediante bugs o malware. El malware mas típico en los últimos 10 años es el ransondware
**Catástrofe naturales**:incendios , inundaciones , terremotos , etc.

# Mecanismos:

# Prevención:
aumentan la fiabilidad durante el funcionamiento normal, previniendo la ocurrencia de violaciones de seguridad. algunos de esos mecanismos serian: antivirus, contraseña segura, cortafuegos.

# Detección:
Aquellos que se utilizan para revelar violaciones de seguridad o intentos.

# Recuperación:
Se aplican cuando la violación del sistema se ha detectado. Deben devolver el sistema a su funcionamiento normal.

# Cortafuegos(firewall):

# Sistemas de detección de intrusos:

# Criptografía:

**Criptología**: ciencia que trata los problemas teóricos relacionados con la seguridad en el intercambio de mensajes en clave entre un emisor y un receptor a través de un canal de comunicaciones.

**Dos ramas**:

- **Criptografía**: ocupada del cifrado de mensajes en clave y del diseño de criptosistemas.

- **Criptoanálisis**: trata de descifrar mensaje en clave, rompiendo el criptosistema.


Hoy en día los criptosistemas se basan en mantener en secreto una serie de parámetros, llamados claves. <span style="color:rgb(100, 132, 76)">El algoritmo puede ser publico y conocido</span>.

**Hay 2 tipos:**

- **Clave secreta/simétricos**

- **Clave publica/asimétricos.**






comando para generar las key:
```
gpg --gen-key
```

selecciona el tipo de clave

```
Por favor seleccione tipo de clave deseado:
   (1) RSA y RSA (predeterminado)
   (2) DSA y Elgamal
   (3) DSA (sólo firmar)
   (4) RSA (sólo firmar)
```
 con el siguiente comando podemos ver nuestro anillo de clave:

```
gpg -k
```

para exportar el archivo e sel siguiete comando:
```
gpg --output CPub.gpg --export 18384645
```



