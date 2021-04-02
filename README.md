# cryptobuyer

Carpeta base para el proyecto de cryptobuyer web + CMS

## Conexion A la base de datos

Para la conexion a la base de datos sustituir en el archivo docker-compose.yml para el caso de sistemas operativos linux o mac y el archivo docker-compose.windows.yml para el caso de los sistemas operativos windows, los campos son los siguientes.

```
WORDPRESS_DB_USER: USUARIO_DB_COMPARTIDA
WORDPRESS_DB_PASSWORD: CONTRASENA_DB_COMPARTIDA
```

Estos campos deben ser sustituidos por las credenciales otorgadas en confluence en el espacio de infraestructura - ambiente de prueba - base de datos