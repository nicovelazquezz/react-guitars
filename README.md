# GuitarLA - Proyecto de Aplicación de Carrito de Compras

## Descripción

Este proyecto es una aplicación de carrito de compras para una tienda de guitarras llamada GuitarLA. La aplicación permite a los usuarios agregar, eliminar y modificar la cantidad de guitarras en su carrito de compras. Utiliza React para la gestión del estado y localStorage para la persistencia de datos.

## Estructura del Proyecto

El proyecto está estructurado en varios componentes principales:

- **Header**: Componente que muestra el encabezado y el carrito de compras.
- **Guitar**: Componente que representa una guitarra individual.
- **App**: Componente principal que maneja la lógica del carrito de compras y la lista de guitarras.

## Funcionalidades

- **Agregar al Carrito**: Permite a los usuarios agregar guitarras al carrito de compras.
- **Eliminar del Carrito**: Permite a los usuarios eliminar guitarras del carrito de compras.
- **Aumentar Cantidad**: Permite a los usuarios aumentar la cantidad de una guitarra específica en el carrito.
- **Disminuir Cantidad**: Permite a los usuarios disminuir la cantidad de una guitarra específica en el carrito.
- **Limpiar Carrito**: Permite a los usuarios vaciar el carrito de compras.

## Gestión del Estado

La aplicación utiliza hooks de React para la gestión del estado:

- **useState**: Para manejar el estado del carrito y los datos de las guitarras.
- **useEffect**: Para guardar el estado del carrito en localStorage cada vez que este cambia.
- **useMemo**: En el componente `Header` para calcular si el carrito está vacío y el total del carrito.
- **customHooks**: Para separar la lógica de la renderización de los componentes.

## Instalación

1. Clona el repositorio.
2. Ejecuta `npm install` para instalar las dependencias.
3. Ejecuta `npm run dev` para iniciar la aplicación.

## Uso

1. Navega por la colección de guitarras.
2. Agrega guitarras al carrito de compras.
3. Modifica la cantidad de guitarras en el carrito.


