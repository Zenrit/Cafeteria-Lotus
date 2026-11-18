# ☕ Sistema de Gestión de Cafetería

## 📌 Descripción del proyecto

El proyecto consiste en el desarrollo de un sistema web para una cafetería. Su objetivo es facilitar la visualización de productos, la búsqueda y selección de artículos y la gestión de pedidos mediante un carrito de compras.

El sistema contará con una base de datos que permitirá almacenar y administrar la información de los productos y pedidos, evitando la pérdida de datos.

## 🎯 Objetivos

- Desarrollar una aplicación web para una cafetería.
- Mostrar los productos disponibles de manera organizada.
- Incorporar un buscador y filtros para facilitar la navegación.
- Implementar un carrito de compras.
- Conectar la aplicación con una base de datos.
- Almacenar y consultar la información de los productos y pedidos.

## ✨ Funcionalidades

- **Catálogo de productos:** permite visualizar los productos disponibles.
- **Buscador:** permite encontrar productos por su nombre.
- **Filtros:** facilita la clasificación de productos por categoría.
- **Carrito de compras:** permite agregar, quitar y modificar cantidades de productos.
- **Gestión de pedidos:** permite registrar los pedidos realizados.
- **Base de datos:** almacena la información para poder consultarla posteriormente.

## 🛠️ Tecnologías utilizadas

- **HTML5:** estructura de la aplicación.
- **CSS3:** diseño y estilos visuales.
- **JavaScript:** interactividad y funcionalidades.
- **Node.js:** desarrollo del servidor y comunicación con la base de datos.
- **MariaDB / MySQL:** almacenamiento de información.
- **XAMPP:** entorno local para ejecutar y administrar la base de datos.
- **phpMyAdmin:** administración de la base de datos desde el navegador.

## 🗄️ Base de datos

Se utilizará una base de datos llamada `cafeteria`, administrada mediante phpMyAdmin.

Se contemplan las siguientes tablas:

- **Productos:** almacena nombre, descripción, precio, imagen y categoría.
- **Categorías:** almacena las categorías de los productos.
- **Pedidos:** registra la fecha, el importe total y el estado del pedido.
- **Detalle_pedido:** almacena los productos, cantidades y precios correspondientes a cada pedido.

## 📂 Estructura del proyecto

```text
cafeteria/
│
├── index.html
│
├── css/
│   ├── estilos.css
│   └── carrito.css
│
├── js/
│   └── script.js
│
├── img/
│   └── imagenes de productos
│
├── server/
│   ├── server.js
│   └── db.js
│
├── database/
│   └── cafeteria.sql
│
├── package.json
│
└── README.md
```

*La estructura podrá modificarse durante el desarrollo según las necesidades del sistema.*

## 🚀
