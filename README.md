# Descripción

Esta es una API desarrollada con Express para gestionar un restaurante. Permite manejar información sobre los menús, órdenes y reservas.

# Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/api-express.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd api-express
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```

# Uso

1. Inicia el servidor:
    ```bash
    npm start
    ```
2. La API estará disponible en `http://localhost:3000`.

# Endpoints

## Menús

- `GET /menus`: Obtiene todos los menús.
- `POST /menus`: Crea un nuevo menú.
- `GET /menus/:id`: Obtiene un menú por ID.
- `PUT /menus/:id`: Actualiza un menú por ID.
- `DELETE /menus/:id`: Elimina un menú por ID.

## Órdenes

- `GET /orders`: Obtiene todas las órdenes.
- `POST /orders`: Crea una nueva orden.
- `GET /orders/:id`: Obtiene una orden por ID.
- `PUT /orders/:id`: Actualiza una orden por ID.
- `DELETE /orders/:id`: Elimina una orden por ID.

## Reservas

- `GET /reservations`: Obtiene todas las reservas.
- `POST /reservations`: Crea una nueva reserva.
- `GET /reservations/:id`: Obtiene una reserva por ID.
- `PUT /reservations/:id`: Actualiza una reserva por ID.
- `DELETE /reservations/:id`: Elimina una reserva por ID.

# Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.

# Licencia

Este proyecto está bajo la Licencia MIT.
