## DOCKER INSTRUCCIONES

PARA LEVANTAR LOS CONTENEDORES
```bash
docker compose -f docker-compose.yml up --force-recreate --build -d
```

PARA DETENER LOS CONTENEDORES
```bash
docker compose -f docker-compose.yml down --remove-orphans
```

#

MODIFICAR LOS UID Y GID DEL ANFITRIÓN

Actualizar los UID y GID del anfitrión para evitar problemas de permisos, editar en .env:

WWWUSER=1000

WWWGROUP=1000