# Encaja
Proyecto de Encaja

## Estructura de archivos
| Nombre | Descripción |
|--------|-------------|
| Landing | Carpeta donde se encuentra el landing page con contenido estático |
| auth.sh | Script que configura email y password del usuario mediante argumentos al comando ```rails g spree:install --user_class=Spree::User```. </br> Ejemplo: ```./auth.sh test@email.com password123``` |
| environment.sh | Script que configura el servidor con todos los paquetes que necesita para crear un proyecto spree. Ya incluye la configuración de password de PostgreSQL con la variable de entorno PSQL_PASS. |
| script.sh | Script que sirve como ejemplo para crear un proyecto spree, es recomendable leer desde el título spree. |
