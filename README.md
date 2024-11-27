# Real Estate Web Application

## Descripción

Este proyecto es una aplicación web para la compra y venta de casas y terrenos. Permite centralizar todas las propiedades en un solo sitio. Los agentes de bienes raíces pueden gestionar sus propiedades mediante un dashboard exclusivo, mientras que los clientes pueden buscar propiedades sin necesidad de registrarse.

## Funcionalidades

### Para agentes de bienes raíces:
- **Registro e inicio de sesión:** Los agentes pueden registrarse y acceder a su panel personal.
- **Dashboard:** Listado de todas las propiedades gestionadas por el agente.
- **Agregar propiedades:** Formulario para añadir propiedades con los siguientes campos:
  - Tipo (casa o terreno).
  - Ubicación (enlace a Google Maps o similar).
  - Costo.
  - Tamaño en m².
  - Ciudad y colonia.
  - Datos de contacto.
  - Imagen de la propiedad.
- **Editar propiedades:** Modificar los datos de una propiedad existente.
- **Eliminar propiedades:** Borrar propiedades del sistema. Si un cliente ha mostrado interés en la propiedad, primero se eliminan los datos del cliente asociados.

### Para clientes:
- **Explorar propiedades:** Visualización de todas las propiedades disponibles, con filtros por:
  - Ciudad.
  - Rango de precios.
- **Formulario de contacto:** Los clientes pueden dejar su información si están interesados en una propiedad.

## Tecnologías utilizadas

- **Frontend:**
  - HTML5
  - CSS3
  - Bootstrap 5
  - JavaScript

- **Backend:**
  - PHP (puro)

- **Base de datos:**
  - MySQL (utilizando PDO para la conexión)

