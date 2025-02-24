# mazatlanBeachStore

1. React (Core Features)
Componentes funcionales (React.FC) → Estás usando la sintaxis de función en vez de clases.
Props y Estado (useState) → Para manejar los productos, el carrito y el filtro de precios.
Efectos (useEffect) → Para cargar productos desde una API externa y modificar elementos en el DOM.
Context API (createContext, useContext) → Para manejar el estado global del carrito y productos.
Referencias (useRef) → Para manipular directamente el DOM y cambiar el color del título.
2. React Hooks
useState → Manejo del estado para productos, carrito y estado del pago.
useEffect → Fetch de datos y manipulación del DOM.
useContext → Compartición del estado global (productos y carrito).
useRef → Acceder y modificar elementos directamente en el DOM.
3. JavaScript y TypeScript
Manejo de Arrays (map, filter, reduce) → Para renderizar productos y calcular totales en el carrito.
Uso de interfaces (interface Product) → Definición de tipos en TypeScript para mayor robustez.
Funciones asíncronas (async/await) → Fetch de productos desde la API externa.
4. CSS y Diseño Responsivo
Grid (display: grid) → Para organizar los productos de manera responsiva.
Flexbox (display: flex) → Para centrar elementos en la barra de navegación.
Border Radius (border-radius) → Para darle estilo a los elementos.
Transiciones (transition: background-color 0.3s) → Para animaciones en botones.
Background Image (background-image) → Para personalizar el navbar con una imagen de fondo.
5. Manejo del Carrito
Agrupación de productos (reduce) → Para calcular la cantidad y el total de cada producto en el carrito.
Filtrado (filter) → Para eliminar productos del carrito.
Actualización del estado global (setCart) → Para reflejar cambios en la UI.
