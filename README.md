# Ejecutar proyecto, Funcionalidades y Testing

## Como arrancar
Instalar los paquetes de node_modules:
### `npm install`
Crear .env y añadir:
### `SKIP_PREFLIGHT_CHECK=true`
Arrancar en localhost:3000 (por defecto):
### `npm start`

## Funcionalidades de este proyecto
Primera parte:
- Router: 2 distintas (Login y App), implementación rutas hijas
- Utilización de History (Push/Replace)
- Leer argumentos por URL (QueryParams): useParams()
- Uso de hook useMemo para memorizar resultados para que no se vuelvan a cargar resultados iguales
- Coger información de un JSON y utilizar filtros en ella
- Utilización custom Hook para formularios useForm, filtros y uso de "location" para info de la URL

Segunda parte:
- Rutas públicas y rutas privadas
- Utilización de "Context" y de "Reducer" en la aplicación
- Login y Logout de la aplicación

## Hora de testear
Correr todos los tests:
### `npm run test`
