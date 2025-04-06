# REST-API-wordpress

Guide to Using the WordPress REST API in Python
Imagina que tienes un blog en WordPress grande, enorme, GIGANTE. Llevas años compartiendo contenido, creciendo en visitas y comunidad. Has creado nuevas categorías y, según ha ido evolucionando tu contenido, también has ido creando nuevas etiquetas en tus contenidos.
Como resultado, tienes una página muy bien posicionada en Google (bien hecho SEO!) pero surge un imprevisto. Puede ser que tengas que modificar las categorías, localizar ciertas entradas publicadas en una fecha de tiempo, cambiar la estructura de las páginas…
Revisar todo el contenido manualmente es una enorme molestia, así que aquí tienes los primeros pasos con Python y la API REST de WordPress.
 
Reto aceptado | Objetivo
Disponer de un dataset completo y estructurado de los artículos publicados en un blog de Wordpress, incluyendo campos clave como:
Título
URL
Fecha de publicación
Categorías
Tags
 
Requisitos
Python
Bibliotecas: request, pandas
 
Notas:
Para usar al API, necesitarás las credenciales de acceso a WordPress. En lugar de ello, aquí generamos una contraseña “temporal” que se usará solo para ejecutar el código. Para acceder a ella, debes entrar en el panel de WordPress, “Usuarios” y “Perfil”. Ahí desplázate hacia abajo, hasta “Contraseñas de la aplicación”. Así, una vez que ejecutes el script, puedes revocar la contraseña y, ¡listo!
REST API de Worpdress tiene límites de paginación (100 elementos por página). Por ejemplo, te puede afectar en la cantidad de entradas publicadas, pero también en otros aspectos, como la cantidad de etiquetas. Estos dos supuestos han sido solucionados en el código.