# Simulacros ICFES IA — Backend

Incluye Node.js + Express + SQLite.

## Ejecutar
1. Instala Node.js.
2. En esta carpeta ejecuta `npm install`.
3. Ejecuta `npm start`.
4. Abre `http://localhost:3000`.

## API
- `GET /api/health` comprueba el servidor.
- `POST /api/attempts` guarda un resultado.
- `GET /api/results` consulta resultados.

El frontend actual sigue funcionando y esta base permite pasar de localStorage
a almacenamiento en servidor. El backend no procesa pagos reales.
