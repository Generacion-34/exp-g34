# Template de Servidor Express

Este es un template básico para un servidor Express con configuraciones comunes. Utiliza las siguientes librerías:

- [Express](https://www.npmjs.com/package/express): Un marco web rápido, no opinionado y minimalista para Node.js.
- [Cors](https://www.npmjs.com/package/cors): Middleware para habilitar el acceso a recursos desde diferentes orígenes.
- [Dotenv](https://www.npmjs.com/package/dotenv): Carga variables de entorno desde un archivo `.env` para gestionar configuraciones.
- [Helmet](https://www.npmjs.com/package/helmet): Ayuda a proteger las aplicaciones Express estableciendo varios encabezados HTTP.

## Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/Generacion-32/express-g32.git <NOMBRE_DEL_PROYECTO>
cd <NOMBRE_DEL_PROYECTO>

```
2. Tambien puedes hacerlo con el siguiente comando

```
npx exp-g32
```

## Uso
### Modo de Desarrollo

Para ejecutar el servidor en modo de desarrollo, utiliza:

```
npm run dev
```
Esto iniciará el servidor con Nodemon, que reiniciará automáticamente la aplicación cuando detecte cambios en el código.

## Modo de Producción

Para ejecutar el servidor en modo de producción, utiliza:

```
npm start
```

Este comando ejecutará la aplicación en un entorno de producción.

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras algún problema o tienes sugerencias para mejorar el template, no dudes en comunicarla.

## Licencia
Este proyecto está bajo la Licencia ISC 

