# Seguridad en Redes 2-2024

### PacketTracer
- Modelo AAA
- 802.1x
- Privilegios
- Seguridad en Puerto

### Actividades

#### Actividad 1 - Criptografía Simétrica
En esta actividad se exploraron los siguientes algoritmos de criptografía simétrica:
- DES
- 3DES
- AES
- RC4

#### Actividad 2 - Codificación
Esta actividad se centró en los métodos de codificación:
- Código ASCII
- Base64
- Base32
- ROT13
- Binario
- Hexadecimal

#### Actividad 3 - Criptografía Asimétrica
Se estudiaron los siguientes métodos de criptografía asimétrica:
- Diffie-Hellman
- RSA
- Firma digital

Además, se trabajó con **Wireshark** y **SSL/TLS**.

#### Actividad 4 - Metadatos y Esteganografía
- Se realiza la búsqueda de la ubicación de una fotografía a través de los metadatos usando FOCA
- Se realiza la extracción de archivos secretos en una imagen usando HexEdit y PhotoFiltre 11

#### Actividad 5: Desafío de Ciberseguridad
Se realizó un desafío de ciberseguridad que comprendía los siguientes contenidos:
- 1. Busqueda de la ubicación de una fotografía a través de sus metadatos
- 2. Extracción de archivos ocultos en una imagen con HexEdit
- 3. Reconstrucción de una fotografía recortada a través de sus metadatos usando FOCA
- 4. Cifrado simétrico con DES y asimétrico con RSA de un nombre y 
- 5. Comparación de archivos a través de función hash y extrcción de archivos ocultos
- 6. Resolución de desafío extrayendo archivos ocultos con HexEdit y descifrado de contraseñas con John The Ripper
---

#### Control 2: Controles de Seguridad en Cisco Packet Tracer y clasificación en frameworks
Se realizaron 10 controles de seguridad en Cisco Packer Tracer y se clasifican en los frameworks ISO 27001, NIST CSF 2.0 y Cis Control V8
- 1. Cifrado de datos: se cifran las contraseñas para modo privilegiado
- 2. Inicio de sesión seguro: se implementa el modelo AAA
- 3. Gestión de privilegios: se implementan usuarios con distintos permisos según su rol o nivel de privilegio
- 4. Acceso a las redes y servicios de red: se implementa el protocolo 802.1x
- 5. Sincronización de reloj: se sincroniza la hora de los dispositivos conectados
- 6. Seguridad de puerto: se implementa seguridad de puertos para controlar acceso restringido desde otra MAC que no sea la autorizada
- 7. Política SSH: se configura SSH y desactiva Telnet permitiendo acceso remoto seguro
- 8. Bloqueo sesión por inactividad: se configura el cierre de sesiones luego de 5 minutos de inactividad al ingresar a los dispositivos
- 9. Registros de auditoria: se configuran marcas de tiempo para capturar hora y acciones realizadas sobre el router
- 10. Banner de advertencia: se configura un banner de advertencia para accesos no autorizados al dispositivo

Todas las actividades se realizaron en **Kali Linux 2024.3** a través de la **MV Oracle VirtualBox**.

### Contacto
Ante cualquier duda o problema, puedes contactarme a través del correo: [reinaldo.pacheco@usach.cl](mailto:reinaldo.pacheco@usach.cl)
