Paso 1 - Crear la carpeta webFalsa dentro del directorio donde trabajaremos. (Provisionar un HTML dentro de esta)
Paso 2 - Dentro del Vagrantfile, en la linea de "config.vm.synced_folder" se tendra que reemplazar la actual por esta:
config.vm.synced_folder "./webFalsa", "/var/www"