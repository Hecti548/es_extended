# es_extended
Is a version of es_extended legacy of FiveM

# Dependences
mysql-async
async
spawnmanager

Hello, thanks fot download this file.
This is the configuration for the admin of Es_Extended legacy

# MySQL Connection
set mysql_connection_string "server=localhost;database=es_extended;userid=root;"

# Permisos
add_ace group.admin command allow # allow all commands
add_ace group.superadmin command allow # Acceso a todos los permisos
add_ace group.admin command.quit deny # but don't allow quit
add_principal identifier.steam:11000013ea6aee7 group.superadmin # add the admin to the group

# Permisos ESX
add_principal group.admin group.user
add_principal group.superadmin group.admin
add_ace resource.es_extended command.add_ace allow
add_ace resource.es_extended command.add_principal allow

# enable OneSync with default configuration (required for server-side state awareness)
onesync legacy true

###############################################################################################
You can contact me in !Hecti548#7909.
