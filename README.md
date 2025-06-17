#Bloqueo acceso a Webmin via IP

Se ha implementado una restricción de acceso en el panel de Webmin, bloqueando el acceso desde una dirección IP específica. Esta medida se tomó para mejorar la seguridad del sistema y prevenir accesos no autorizados, asegurando que solo las IPs permitidas puedan interactuar con la interfaz de administración de Webmin.

##Pasos que se realizaron para bloquear por ip

- Se hizo el bloqueo a travez del firewall de webmin
  ![firewall iptables](/Users/jeronm/Desktop/img1.png)

- Luego se clickeo la opcion, agreagar regla
  ![add rule](/Users/jeronm/Desktop/img2.png)

- se especificaron cual era la ip, y todas las acciones necesarias para el bloqueo
  ![add rule](/Users/jeronm/Desktop/img3.png)

- por ultimo, se intento acceder con la ip que fue bloqueada para validar si la regla se estaba aplicando correctamente.
  ![add rule](/Users/jeronm/Desktop/img4.png)

###Con esta medida, se busca proteger la integridad del servidor y limitar el acceso a usuarios no autorizados.

##Conclucion

- Importancia de la Seguridad en la Administración de Servidores: Se ha reforzado la comprensión de que la seguridad es fundamental en la gestión de servidores. Implementar restricciones de acceso es una práctica esencial para proteger la información y los recursos del sistema.
- Manejo de Herramientas de Control de Acceso: Se ha adquirido experiencia en el uso de herramientas de control de acceso, como Webmin, lo que permite gestionar de manera efectiva quién puede interactuar con el servidor y cómo se pueden aplicar políticas de seguridad.
