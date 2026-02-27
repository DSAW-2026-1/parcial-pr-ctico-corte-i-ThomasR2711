Prompt 1 – Estructura HTML

Necesito que me ayudes a crear la estructura HTML de un diseño específico.

Quiero un contenedor principal de 400px por 300px. No uses etiquetas <div>, prefiero usar <main> como contenedor principal y <section> para representar cada una de las cuatro esquinas.

Cada esquina debe tener dos figuras: un cuadrado y un círculo. PERO el orden cambia dependiendo de la esquina y debe quedar exactamente así:

- Arriba izquierda: cuadrado primero y luego círculo.
- Arriba derecha: círculo primero y luego cuadrado.
- Abajo izquierda: círculo primero y luego cuadrado.
- Abajo derecha: cuadrado primero y luego círculo.

Puedes usar <span> para las figuras y después las estilizamos con CSS.

Por ahora solo quiero la estructura, sin estilos.






Prompt 2 – Estilos Base

Ahora ayúdame con el CSS.

El contenedor debe medir 400px de ancho por 300px de alto y tener un fondo azul oscuro. Las figuras deben medir lo mismo entre sí.

El cuadrado debe ser de color celeste y el círculo de color rosado. El círculo debe verse completamente redondo.

Aplica un pequeño reset para evitar márgenes por defecto del navegador y asegúrate de que los <span> puedan tener ancho y alto definidos.

En este paso solo quiero tamaños, colores y formas correctas, todavía no posiciones las esquinas.








Prompt 3 – Layout y Posicionamiento Correcto

Ahora necesito que el diseño quede exactamente como el modelo.

El contenedor debe estar centrado en la pantalla tanto vertical como horizontalmente.

Dentro del contenedor, cada sección debe ir ubicada en una esquina distinta: superior izquierda, superior derecha, inferior izquierda e inferior derecha.

Las figuras dentro de cada esquina deben estar una al lado de la otra con un pequeño espacio entre ellas, respetando el orden que ya definimos en el HTML.

No uses CSS Grid. Haz la alineación usando Flexbox para centrar el contenedor y usa posicionamiento para ubicar las esquinas.

El resultado final debe respetar exactamente la distribución original.