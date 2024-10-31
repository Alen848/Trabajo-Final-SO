# Trabajo-Final-SO

Descripción del Proyecto: Script de Administración de Sistema
Este proyecto consiste en un script de Bash diseñado para facilitar tareas comunes de administración de sistemas en entornos Linux. El script presenta un menú interactivo que permite a los usuarios realizar las siguientes funciones:

Respaldo de Directorios: Permite crear copias de seguridad de directorios específicos, generando un archivo comprimido. Además, incluye una funcionalidad para eliminar respaldos antiguos que superen los 7 días.

Informe del Sistema: Genera y guarda un informe que muestra el uso de CPU, memoria y disco en un archivo de log, brindando a los administradores una visión rápida del estado del sistema.

Creación de Usuarios: Facilita la creación de nuevos usuarios en el sistema, con la opción de asignar una contraseña de inmediato, contribuyendo a la gestión de cuentas de usuario.

El script está diseñado para ser fácil de usar y proporciona mensajes claros y coloridos en la terminal para mejorar la experiencia del usuario. Se requiere acceso a permisos de administrador para ciertas funciones, lo que lo convierte en una herramienta valiosa para administradores de sistemas y usuarios avanzados que buscan simplificar tareas de mantenimiento.

Instrucciones de Uso del Script de Administración de Sistema
1) Ejecutar el Script:

- Abrir una terminal.
- Navegar al directorio donde se encuentra el script.
- Ejecutar el script con el siguiente comando:
bash nombre_del_script.sh

2) Seleccionar una Opción del Menú:

Al iniciar, aparecerá un menú con las siguientes opciones:
1- Respaldo de Directorio
2- Informe del Sistema
3- Crear Usuario
4- Salir
Ingresar el número correspondiente a la opción deseada y presionar Enter.

3) Respaldo de Directorio:

- Ingresar la ruta del directorio que deseas respaldar.
- Proporciona el nombre del archivo comprimido de destino (ej. backup.tar.gz).
- El script realizará el respaldo y eliminará respaldos antiguos automáticamente.

4) Informe del Sistema:

- Selecciona esta opción para generar un informe sobre el uso de recursos del sistema.
- El informe se guardará en un archivo llamado informe_sistema.log.

5) Crear Usuario:

- Ingresa el nombre del nuevo usuario que deseas crear.
- Se te preguntará si deseas asignar una contraseña. Responde s (sí) o n (no) según tu preferencia.
- El nuevo usuario será creado y, si lo deseas, se le asignará una contraseña.

6) Salir del Script:
- Seleccionar la opción 4 para salir del menú.
