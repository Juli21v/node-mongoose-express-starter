# Mongo connection — Conexión Node.js a MongoDB

Proyecto mínimo que muestra cómo **levantar un servidor Express** y **conectar a MongoDB** con **Mongoose**, útil como plantilla para APIs más grandes.

**Autora del repositorio:** [@Juli21v](https://github.com/Juli21v)

## Stack

- Node.js (ES modules)
- Express
- Mongoose
- dotenv, CORS

## Estructura del repositorio

```
Mongo-connection/
└── backend/
    ├── index.js      # App Express; carga variables de entorno
    ├── db/db.js      # `mongoose.connect(...)`
    └── package.json
```

## Configuración

```bash
cd backend
cp .env.example .env
# Edita PORT y DB_CONNECTION
```

## Puesta en marcha

```bash
cd backend
npm install
npm start
```

## Uso educativo

Sirve como base para **Biblioteca-toile**, **Restaurante** o cualquier API que persista en MongoDB.
