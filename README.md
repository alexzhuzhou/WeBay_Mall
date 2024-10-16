Spanish ES:





IDEA.
Como puedes ver a continuación, el paquete mysql requerido por mybatis-generator ha sido colocado bajo el paquete de herramientas, así que puedes copiarlo, ponerlo en una ubicación, y modificar la ruta de db.driverLocation a la ruta en la que lo pusiste. Cuando uses mybatis-generator, podrás obtener este archivo desde el grupo QQ compartido, ten en cuenta que debe ser mysql-bin.jar, un paquete jar que termina en bin. También puedes descargarlo de http://learning.happymmall.com/mysql-connector-java-5.1.6-bin.jar. No configure el controlador mysql descargado por maven, debe estar usando -bin.jar yo.

La siguiente figura, abrir datasource.properties por favor modificar db.url, db.username, db.password para su propia conexión de base de datos mysql necesita url, nombre de usuario, contraseña

Abra mmall.properties y cámbielo por su propia dirección de servidor ftp, número de cuenta y contraseña. La dirección de devolución de llamada de paypal puede configurarse a través de la penetración en la extranet que se enseña en el curso. Si utiliza la configuración de nginx, modifique el nombre de dominio de soporte del host local. A continuación, modifique el servidor de archivos ftp a su propio prefijo de acceso al servidor ftp. No se recomienda modificar el valor de la sal md5. De lo contrario, la cuenta no podrá conectarse y tendrá que ser restablecida. La dirección de devolución de llamada de paypal también debe ser cambiada por la suya.

6 y 7 de estas dos capturas de pantalla de la cuenta db, la contraseña, la url, y la ubicación, la ip del servidor ftp, la cuenta, la contraseña, el prefijo del servidor ftp, la dirección de devolución de llamada de paypal, por favor, modifique todo a su propio entorno de servicios correspondiente.

Luego despliegue tomcat para que se ejecute en él.




