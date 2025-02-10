# Glosario Informatico <p align="center"><img src="/img/glosario.gif" alt="![glosario](/img/glosario.gif)" /></p>  

___

## 📌 ¿Qué es una IP (Internet Protocol)?
---
**Es una dirección única que identifica un dispositivo en una red.**    

*Ejemplos: 172.26.1.1 para IPv4 y 2001:db8::ff00:42:8329 para IPv6*    

<p align="center">
  <img src="/img/ip.jpeg" alt="![ip](/img/ip.jpeg)" />
</p>    

___

### 🌐 ¿Qué es un Dominio?
---
**Un dominio es el nombre único que identifica a un sitio web en Internet. La dirección que los usuarios escriben en su navegador para acceder a una página sin necesidad de recordar su dirección IP.**     

*Ejemplo: Wikipedia → Dominio: wikipedia.org*     

<p align="center">
  <img src="/img/dominio.jpeg" alt="![dominio](/img/dominio.jpeg)" />
</p>  

___

### 🔗 ¿Qué es URL (Uniform Resource Locator)?
---
**Una URL es la dirección completa que apunta a un recurso en Internet, como una página web, imagen o archivo. Es la forma en que los navegadores encuentran y acceden a sitios web.**      

*Ejemplos*  
✅ Página web: https://www.google.com  
✅ Imagen: https://ejemplo.com/imagen.jpg  
✅ Descarga: https://ejemplo.com/archivo.zip  
✅ Video en YouTube: https://www.youtube.com/watch?v=dQw4w9WgXcQ  

📌 Dato Curioso: Cada URL es única y permite acceder a recursos desde cualquier parte del mundo 🌍.  

<p align="center">
  <img src="/img/url.jpeg" alt="![url](/img/url.jpeg)" />
</p>  

___

### 🔌 ¿Qué son los Puertos?
---
**Un puerto es un número que identifica un servicio específico en un dispositivo dentro de una red. Es como una "puerta" a través de la cual se comunican los protocolos de Internet.**

- **21** → FTP (Transferencia de archivos 📂).  
- **22** → SSH (Conexión remota segura 🔒).  
- **80** → HTTP (Navegación web sin cifrar 🌍).  
- **443** → HTTPS (Navegación web cifrada 🔐).

*Ejemplos*  
*🔹 Cuando accedes a http://ejemplo.com, el navegador usa puerto 80.*  
*🔹 Si visitas https://ejemplo.com, usa puerto 443.*    
*🔹 Si te conectas a un servidor por SSH, usarás puerto 22.*  

<p align="center">
  <img src="/img/puerto.png" alt="![puerto](/img/puerto.png)" />
</p>  

___


### 📂 ¿Qué es un Servicio de Directorio?
---
**Un servicio de directorio es un sistema que almacena, organiza y gestiona información sobre usuarios y dispositivos, aplicaciones y otros recursos en una red. Es esencial para la administración centralizada de una infraestructura informática.**    

*Ejemplos:*  
*✅ Active Directory (AD) → De Microsoft, usado en redes Windows.*    
*✅ OpenLDAP → Una alternativa de código abierto basada en LDAP.*    
*✅ Apache Directory → Proyecto de la Apache Software Foundation.*    
*✅ 389 Directory Server → Usado en sistemas Linux empresariales.*    


<p align="center">
  <img src="/img/directorio.jpeg" alt="![directorio](/img/directorio.jpeg)" />
</p>  

___

### 🏢 ¿Qué es OpenLDAP?
---
**Es una implementación de código abierto del protocolo LDAP (Lightweight Directory Access Protocol), que permite gestionar información de usuarios (como nombres y contraseñas), grupos y otros recursos dentro de una red de forma centralizada.**   

*Ejemplo: una red universitaria para estudiantes y profesores donde se implementa OpenLDAP para gestionar el acceso a los sistemas de información académica (notas, clases, horarios) y a los servicios de biblioteca.*  

💡 Beneficio: Los estudiantes y profesores usan una única cuenta para todos los servicios de la universidad, lo que simplifica la administración.

  
<p align="center">
  <img src="/img/ldap.png" alt="![ldap](/img/ldap.png)" />
</p>  

___

### 🏛️ ¿Qué significa Active Directory?
---
**Active Directory (AD) es una herramienta de Microsoft que ayuda a gestionar y organizar los recursos de una red, como usuarios, computadoras, impresoras y otros dispositivos. Se usa principalmente en redes Windows.**  

*Ejemplo: En una empresa de 500 empleados los empleados tienen una cuenta única para acceder a sus dispositivos, correo electrónico y aplicaciones internas.*
  
<p align="center">
  <img src="/img/active.png" alt="![active](/img/active.png)" />
</p> 

___

### 🔒 ¿Qué son HTTP vs HTTPS?  
---
**HTTP (HyperText Transfer Protocol) y HTTPS (HyperText Transfer Protocol Secure) son protocolos que se utilizan para la transferencia de datos entre tu navegador web y un servidor web. La principal diferencia entre ambos radica en la seguridad de la conexión.**
- **HTTP**: Transfiere datos sin cifrado.    
- **HTTPS**: Usa un certificado SSL/TLS para cifrar la comunicación.    

*Ejemplo: HTTP (Sin seguridad) http://www.noticiasdelmundo.com = Un portal de noticias donde los usuarios leen artículos, pero no interactúan con datos sensibles (como contraseñas o pagos).*  

*Ejemplo de HTTPS (Con seguridad) https://www.amazon.com. La plataforma de compras en línea, donde los usuarios realizan pagos, guardan información personal y gestionan sus direcciones de envío. HTTPS es esencial para asegurar que la información no sea interceptada durante el proceso de compra.*


<p align="center">
  <img src="/img/https.jpeg" alt="![https](/img/https.jpeg)" />
</p> 

___

### 🌍 ¿Qué es un servicio DNS?   
---
**El DNS (Domain Name System) es un sistema que traduce nombres de dominio legibles por humanos (como www.ejemplo.com) en direcciones IP (como 172.26.1.1), que es el formato utilizado por los pcs para identificar y comunicarse entre sí a través de Internet.**     

*Ejemplo: `google.com` → `142.250.184.238`.*

<p align="center">
  <img src="/img/dns.jpeg" alt="![dns](/img/dns.jpeg)" />
</p> 

___

### 🌐 ¿Qué son los Servicios Web?
---
**Los servicios web son programas que permiten que los sitios web sean accesibles a través de Internet. Se encargan de recibir las solicitudes de los navegadores y enviar los archivos correspondientes, como HTML, imágenes, o archivos multimedia. Dos de los servicios web más populares son Apache y Nginx.**  

*- **Apache:** Ideal para sitios web con mucho contenido dinámico, como aquellos que usan PHP. Es utilizado por muchos sitios pequeños y grandes, desde blogs hasta grandes plataformas.*      
*- **Nginx:** Ideal para servir contenido estático (como imágenes, CSS, y archivos JavaScript). Usado en sitios web con gran tráfico, como plataformas de streaming o redes sociales.*     

<p align="center">
  <img src="/img/web.jpeg" alt="![web](/img/web.jpeg)" />
</p> 

___

### 📡 ¿Qué es un protocolo?
---
**Un protocolo es un conjunto de reglas que define cómo los dispositivos se comunican, cómo deben organizarse y enviarse los datos, y cómo se maneja la seguridad y la fiabilidad durante la comunicación. Sin protocolos, los dispositivos no podrían entenderse ni intercambiar información de manera efectiva.**  

*Ejemplos: TCP/IP, FTP, HTTP.*

<p align="center">
  <img src="/img/protocolo.png" alt="![protocolo](/img/protocolo.png)" />
</p> 

___

### 🖥️ ¿Qué es RDP?  
---
**El Remote Desktop Protocol (RDP) es una herramienta poderosa que permite acceder de forma remota a una computadora a través de una red. Es útil para soporte técnico, teletrabajo y administración de servidores. Sin embargo, es importante configurar RDP de manera segura para evitar posibles vulnerabilidades.**  

*Ejemplo: Con RDP puedes acceder a tu pc de la oficina desde cualquier lugar, usar todas sus aplicaciones y archivos como si estuvieras en la misma ubicación, lo que facilita el teletrabajo y el soporte remoto.*

<p align="center">
  <img src="/img/rdp.jpeg" alt="![rdp](/img/rdp.jpeg)" />
</p> 

___

### 🔑 ¿Qué es SSH (Secure Shell)?
---
**SSH es un protocolo de acceso remoto que permite administrar servidores y ejecutar comandos de forma segura. Se utiliza ampliamente para la administración de sistemas y transferencia de archivos, y es la opción preferida por su capacidad para cifrar la comunicación y ofrecer autenticación robusta.**  

*Ejemplo: un administrador de sistemas necesita gestionar un servidor que está en un centro de datos, actualizar su software, configurar servicios...**  


<p align="center">
  <img src="/img/ssh.png" alt="![ssh](/img/ssh.png)" />
</p> 

___

### ☁️ ¿Qué es Cloud (Nube)? 
---
**La nube es un modelo de computación que ofrece acceso remoto a recursos informáticos a través de Internet. Permite a las empresas y usuarios acceder a servicios como almacenamiento, procesamiento de datos, y aplicaciones sin necesidad de infraestructura local, lo que ofrece flexibilidad, escalabilidad y ahorro de costos.**  

*Ejemplo: Almacenamiento en la nube (Google Drive y Dropbox), Plataformas de desarrollo y bases de datos (AWS y Azure)*


<p align="center">
  <img src="/img/cloud.png" alt="![cloud](/img/cloud.png)" />
</p> 

___

### 🌐 ¿Qué es AWS?
---
**AWS (Amazon Web Services) es una plataforma en la nube que ofrece servicios de computación, almacenamiento, bases de datos, inteligencia artificial y mucho más.**  

*Ejemplo: Creas una aplicación web y necesitas un servidor para alojarla, una base de datos para gestionar los usuarios y almacenamiento para los archivos que suben.*  

<p align="center">
  <img src="/img/aws.png" alt="![aws](/img/aws.png)" />
</p> 

___

### 🖥️ ¿Qué es Proxmox? 
---
**Proxmox es una plataforma de virtualización de código abierto que ofrece la posibilidad de gestionar tanto máquinas virtuales como contenedores en una interfaz sencilla y accesible. Es ideal para administrar servidores, probar entornos de software, o crear soluciones de alta disponibilidad y escalabilidad, todo ello sin los costos asociados a soluciones de virtualización propietarias.**  

*Ejemplos de usos: Virtualización de servidores, Contenedores ligeros para microservicios y Pruebas y desarrollo*


<p align="center">
  <img src="/img/proxmox.png" alt="![proxmox](/img/proxmox.png)" />
</p> 

___

### ☁️ ¿Qué es Google Cloud? 
---
**Google Cloud es una plataforma de computación en la nube que ofrece una amplia gama de servicios para ejecutar aplicaciones, almacenar datos y realizar análisis a gran escala. Con flexibilidad, seguridad y escalabilidad.**  

*Ejemplos: Alojar una aplicación, almacenamiento de archivos y análisis de datos*

<p align="center">
  <img src="/img/gc.png" alt="![gc](/img/gc.png)" />
</p> 

___

### ☁️ ¿Qué es Azure? 
---
**Azure es una plataforma integral de computación en la nube de Microsoft que ofrece una amplia gama de servicios para desarrolladores, empresas y organizaciones con máquinas virtuales, almacenamiento, redes, inteligencia artificial y herramientas de desarrollo.**  

*Ejemplo: Alojar una aplicación, almacenamiento de datos y autenticación de usuarios*


<p align="center">
  <img src="/img/azure.png" alt="![azure](/img/azure.png)" />
</p> 

___

### 🧑‍💻 ¿Qué es un Administrador? 
---
**El Administrador es clave en el ámbito de las tecnologías de la información, se encarga de gestionar la infraestructura de hardware y software que permite que una organización o sistema funcione sin problemas. Sus funciones incluyen desde la configuración inicial hasta la gestión continua de recursos, asegurando siempre la disponibilidad, seguridad y eficiencia de los sistemas.**  

*Ejemplo: Una tarea de un administrador de sistemas en una empresa de tecnología sería instalar un servidor Linux para alojar una página web de la empresa, configurar el acceso a ese servidor, asegurándote de que solo los empleados autorizados puedan acceder a él mediante SSH, implementar una estrategia de backup diaria para asegurar que los datos estén protegidos, instalar un software de monitorización que avise si funciona correctamente o si hay algún error y mantener el servidor actualizado con los últimos parches de seguridad para evitar vulnerabilidades.*

<p align="center">
  <img src="/img/admin.jpeg" alt="![admin](/img/admin.jpeg)" />
</p> 

___

### 🤖 ¿Qué es DevOps? 
---
**DevOps es una filosofía que busca mejorar la colaboración entre los equipos de desarrollo y operaciones para automatizar y agilizar el ciclo de vida del software. Con herramientas de integración continua, automatización de pruebas y despliegue, y monitoreo, DevOps permite entregar aplicaciones de alta calidad de manera rápida, escalable y eficiente.**  

*Ejemplos de funciones: Desarrollo, integración continua, contenedores, monitoreo, feedback*

<p align="center">
  <img src="/img/DevOps.png" alt="![DevOps](/img/DevOps.png)" />
</p> 

___
