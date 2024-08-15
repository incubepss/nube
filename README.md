# Nube

Código y documentación de instalación de servidor en la nube para las distintas aplicaciones que conforman el proyecto.

Requisitos del servidor: 

- 2 vCPU's
- 4 GB RAM
- 30 GB SSD
- 1TB mensual de transferencia

# Caprover

Caprover es un sistema para gestionar la infraestructura (Paas) para el despliegue de aplicaciones.

[Sitio oficial Caprover](https://caprover.com/)

[Instalación propia](https://captain.nube.chasqui.site/)

Versión: 1.11.1

El sistema de monitoreo envia notificaciones a telegram utilizando @incubepssbot

Para esto se necesita un token y chatId. [Documentación](https://learn.netdata.cloud/docs/alerts-&-notifications/notifications/centralized-cloud-notifications/telegram)


### Wordpress

Sistema para publicación de contenidos (CMS).

[Sitio oficial de Wordpress](https://wordpress.org/)

[Instalación propia](https://enlaces.site/)

Versión: 6.0.1

### Moodle

Sistema para gestión de contenidos educativos (LMS)

[Sitio oficial de Moodle](https://moodle.org/)

[Instalación propia](https://campus.enlaces.site)

Versión: 4.4.1

### Mysql

Motor de base de datos para las instalaciones de Moodle y wordpress.

Solo accesible internamente en `srv-captain--wordpress-db`

Versión: 5.0.2

### Presupuestador

Sistema para calculo de costos y gestión de presupuestos.

#### APP

Licencia: GPL V3

Versión: 1.0.0

[Codigo fuente](https://github.com/incubepss/presupuestador)

[Instalación propia](https://presupuestador.enlaces.site/)


#### CouchDB

Base de datos NoSQL para sincronización de documentos de los usuarios vía web.

[Sitio oficial](https://couchdb.apache.org/)

[Instalación propia](https://presupuestador-couch.nube.chasqui.site)

##### Instalación

Configurar CORS en 
https://presupuestador-couch.nube.chasqui.site/_utils/#_config/

Crear db "usuarios"

#### MongoDB

Base de datos NoSql implementada para gestión de sesiones de usuarios.

Solo accesible internamente en `srv-captain--presupuestador-mongo`

#### phpMyAdmin

Sistema para gestión de bases de datos

http://mysql.nube.chasqui.site/

### Chasqui

Plataforma de comercio electrónico multi tienda.

Acceso a multitienda: https://chasqui.enlaces.site

Acceso al panel: https://panel.chasqui.enlaces.site/panel