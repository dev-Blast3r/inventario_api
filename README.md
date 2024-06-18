# Inventario API

Este proyecto es un API REST de inventario utilizando Node.js, Sequelize y MySQL.

## Instalación

1. Clona el repositorio:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd inventario-api

2. Instala las dependencias:

   ```bash
   npm install
   Configura la base de datos en config/config.json.

3. Corre las migraciones para crear las tablas en la base de datos:

   ```bash
   npx sequelize-cli db:migrate

4. Inicia el servidor:

   ```bash
   npm start
   
##Uso
- Registro de usuarios: POST /api/register
- Login de usuarios: POST /api/login
- CRUD de productos: POST /api/productos, GET /api/productos, PUT /api/productos/:id, DELETE /api/productos/:id
- Realizar compras: POST /api/compras
