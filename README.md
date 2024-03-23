# Contenedores para BaseDatos

El siguiente código nos ayuda a levantar contenedores de base de datos para utilizar en los desarrollos de tus aplicativos.

## Bases de Datos
- MariaDB
- MSSQL Developer
- PostgreSQL

## Requerimientos
- Tener instalado [Docker](https://www.docker.com/products/docker-desktop/)
- Internet


## Implementación
Para ejecutar el contenedor de MariaDB, entramos a la carpeta desde la terminal y ejecutamos los siguientes comandos.

```bash
  cd MariaDb
  mkdir mariadb_data
  docker compose up
```

Para ejecutar el contenedor de MSSQL, entramos a la carpeta desde la terminal y ejecutamos los siguientes comandos.

```bash
  cd MSSQL
  mkdir sqldata
  docker compose up
```

Para ejecutar el contenedor de PostgreSQL, entramos a la carpeta desde la terminal y ejecutamos los siguientes comandos.

```bash
cd PostgreSQL
  mkdir postgres_data
  docker compose up
```

### Nota
La creación de las carpetas de los volumenes persistentes solo se crean la primera vez.
