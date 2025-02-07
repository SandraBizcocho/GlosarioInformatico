# Glosario Informatico

<p align="center">
  <img src="/img/glosario.gif" alt="![glosario](/img/glosario.gif)" />
</p>  

## ¿Qué es una IP (Internet Protocol) 📌?
**Es una dirección única que identifica un dispositivo en una red.**    
*Ejemplos: 172.26.1.1 para IPv4 y 2001:db8::ff00:42:8329 para IPv6*  

<p align="center">
  <img src="/img/ip.jpg" alt="![ip](/img/ip.jpg)" />
</p>    


### 🌐 ¿Qué es un Dominio?  
**Un dominio es el nombre único que identifica a un sitio web en Internet. La dirección que los usuarios escriben en su navegador para acceder a una página sin necesidad de recordar su dirección IP.**   
*Ejemplo: Wikipedia → Dominio: wikipedia.org*   

<p align="center">
  <img src="/img/dominio.webp" alt="![dominio](/img/dominio.webp)" />
</p>  


###  ¿Qué es URL (Uniform Resource Locator)🔗?
**Una URL es la dirección completa que apunta a un recurso en Internet, como una página web, imagen o archivo. Es la forma en que los navegadores encuentran y acceden a sitios web.**    
*Ejemplos*  
✅ Página web: https://www.google.com  
✅ Imagen: https://ejemplo.com/imagen.jpg  
✅ Descarga: https://ejemplo.com/archivo.zip  
✅ Video en YouTube: https://www.youtube.com/watch?v=dQw4w9WgXcQ  

📌 Dato Curioso: Cada URL es única y permite acceder a recursos desde cualquier parte del mundo 🌍.  


### ¿Qué son los Puertos 🔌?
**Un puerto es un número que identifica un servicio específico en un dispositivo dentro de una red. Es como una "puerta" a través de la cual se comunican los protocolos de Internet.**

- **21** → FTP (Transferencia de archivos 📂).  
- **22** → SSH (Conexión remota segura 🔒).  
- **80** → HTTP (Navegación web sin cifrar 🌍).  
- **443** → HTTPS (Navegación web cifrada 🔐).
*Ejemplos*
'🔹 Cuando accedes a http://ejemplo.com, el navegador usa puerto 80.'  
'🔹 Si visitas https://ejemplo.com, usa puerto 443.'  
'🔹 Si te conectas a un servidor por SSH, usarás puerto 22.'  



 
### ¿Qué es un 📂 Servicio de Directorio?
**Un servicio de directorio es un sistema que almacena, organiza y gestiona información sobre usuarios y dispositivos, aplicaciones y otros recursos en una red. Es esencial para la administración centralizada de una infraestructura informática.**  
*Ejemplos:*  
*✅ Active Directory (AD) → De Microsoft, usado en redes Windows.*  
*✅ OpenLDAP → Una alternativa de código abierto basada en LDAP.*  
*✅ Apache Directory → Proyecto de la Apache Software Foundation.*  
*✅ 389 Directory Server → Usado en sistemas Linux empresariales.*  



### ¿Qué es OpenLDAP 🏢?
**Es una implementación de código abierto del protocolo LDAP (Lightweight Directory Access Protocol), que permite gestionar información de usuarios (como nombres y contraseñas), grupos y otros recursos dentro de una red de forma centralizada.** 
*Ejemplo: una red universitaria para estudiantes y profesores donde se implementa OpenLDAP para gestionar el acceso a los sistemas de información académica (notas, clases, horarios) y a los servicios de biblioteca.*
💡 Beneficio: Los estudiantes y profesores usan una única cuenta para todos los servicios de la universidad, lo que simplifica la administración.



### ¿Qué significa 🏛️ Active Directory?
**Active Directory (AD) es una herramienta de Microsoft que ayuda a gestionar y organizar los recursos de una red, como usuarios, computadoras, impresoras y otros dispositivos. Se usa principalmente en redes Windows.**
*Ejemplo: En una empresa de 500 empleados los empleados tienen una cuenta única para acceder a sus dispositivos, correo electrónico y aplicaciones internas.*
  


### ¿Qué son 🔒 HTTP vs HTTPS?  
**HTTP (HyperText Transfer Protocol) y HTTPS (HyperText Transfer Protocol Secure) son protocolos que se utilizan para la transferencia de datos entre tu navegador web y un servidor web. La principal diferencia entre ambos radica en la seguridad de la conexión.**
- **HTTP**: Transfiere datos sin cifrado.  
- **HTTPS**: Usa un certificado SSL/TLS para cifrar la comunicación.  
*Ejemplo: HTTP (Sin seguridad) http://www.noticiasdelmundo.com = Un portal de noticias donde los usuarios leen artículos, pero no interactúan con datos sensibles (como contraseñas o pagos).*
*Ejemplo de HTTPS (Con seguridad) https://www.amazon.com. La plataforma de compras en línea, donde los usuarios realizan pagos, guardan información personal y gestionan sus direcciones de envío. HTTPS es esencial para asegurar que la información no sea interceptada durante el proceso de compra.*


### ¿Qué es un servicio DNS 🌍?   
**El DNS (Domain Name System) es un sistema que traduce nombres de dominio legibles por humanos (como www.ejemplo.com) en direcciones IP (como 172.26.1.1), que es el formato utilizado por los pcs para identificar y comunicarse entre sí a través de Internet.**   
*Ejemplo: `google.com` → `142.250.184.238`.*



### 🌐 Servicios Web (Apache, Nginx)  
- **Apache:** Servidor web popular, flexible y con módulos.  
- **Nginx:** Más eficiente en alto tráfico y balanceo de carga.  

### 📡 Protocolo  
Conjunto de reglas para la comunicación en redes.  
**Ejemplo:** TCP/IP, FTP, HTTP.  

### 🖥️ RDP (Remote Desktop Protocol)  
Protocolo de Microsoft para acceso remoto a escritorios.  

### 🔑 SSH (Secure Shell)  
Protocolo seguro para acceso remoto y administración de servidores.  
**Ejemplo:**  
```bash
ssh usuario@servidor.com
