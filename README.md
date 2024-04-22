# Propiedad `position` en CSS

1. **Static (Estático)**:

   - Valor predeterminado si no se especifica `position`.
   - El elemento se coloca en el flujo normal del documento.
   - No se ve afectado por las propiedades `top`, `right`, `bottom` o `left`.
   - Ejemplo: Usa `position: static;` cuando quieras que el elemento se muestre en su posición normal en el flujo del documento sin ningún desplazamiento especial.

2. **Relative (Relativo)**:

   - El elemento se mueve en relación con su posición normal en el flujo del documento.
   - Se puede desplazar utilizando las propiedades `top`, `right`, `bottom` o `left`.
   - Otros elementos no se ven afectados por su posición relativa.
   - Ejemplo: Usa `position: relative;` cuando quieras ajustar ligeramente la posición de un elemento sin afectar significativamente a otros elementos.

3. **Absolute (Absoluto)**:

   - El elemento se posiciona en relación con su contenedor más cercano que tiene una posición diferente a `static`.
   - No ocupa espacio en el flujo del documento, lo que permite superponerse a otros elementos.
   - Se puede desplazar utilizando las propiedades `top`, `right`, `bottom` o `left`.
   - Ejemplo: Usa `position: absolute;` cuando quieras que un elemento se sitúe en una posición específica en relación con su contenedor posicionado.

4. **Fixed (Fijo)**:

   - El elemento se fija en relación con la ventana del navegador.
   - Permanece en la misma posición incluso cuando se desplaza la página.
   - No afecta el flujo del documento y puede superponerse a otros elementos.
   - Ejemplo: Usa `position: fixed;` cuando quieras que un elemento permanezca en una posición fija en la pantalla, como un encabezado de navegación que siempre esté visible mientras se desplaza la página.

5. **Sticky (Pegajoso)**:
   - El elemento se comporta como `relative` hasta que alcanza una posición especificada.
   - Una vez que alcanza esa posición, se vuelve "pegajoso" y se comporta como `fixed`.
   - Puede ser útil para encabezados que se mantienen visibles mientras se desplaza la página.
   - Ejemplo: Usa `position: sticky;` cuando quieras que un elemento se mantenga en una posición fija en relación con su contenedor hasta que se alcance un punto de desplazamiento específico, momento en el que se vuelve "pegajoso".

# La propiedad display en CSS

- Se utiliza para controlar cómo se muestra un elemento en el diseño de la página. Determina el tipo de caja de formato utilizado para un elemento y cómo se trata en el modelo de diseño de caja.

- Algunos de los valores que admite la propiedad display junto con una breve descripción de cada uno:

- `block`:
  Los elementos de bloque (<div>, <p>, <h1> - <h6>, etc.) ocupan todo el ancho disponible por defecto y comienzan en una nueva línea.
  Ejemplo: <div>, <p>

- `inline`:
  Los elementos en línea (<span>, <a>, <strong>, etc.) ocupan solo el espacio necesario y no comienzan en una nueva línea.
  Ejemplo: <span>, <a>

- `inline-block`:
  Combina las características de los elementos de bloque y los elementos en línea. Ocupa solo el espacio necesario y permite ajustar el ancho y el alto.
  Ejemplo: Elementos de tipo button

- `none`:
  Oculta el elemento y no ocupa espacio en el diseño de la página.
  Ejemplo: Útil para ocultar temporalmente elementos de forma dinámica con JavaScript.

- `table`:
  Hace que el elemento se comporte como un elemento de tabla.
  Ejemplo: <table>

- `table-cell`:
  Hace que el elemento se comporte como una celda de tabla.
  Ejemplo: <td>, <th>

- `table-row`:
  Hace que el elemento se comporte como una fila de tabla.
  Ejemplo: <tr>

- `flex`:
  Establece un contenedor flexible que puede expandirse y contraerse según el espacio disponible.
  Ejemplo: Contenedores que requieren un diseño flexible, como barras laterales y encabezados de navegación.

- `grid`:
  Establece un contenedor de tipo cuadrícula que organiza sus elementos hijos en filas y columnas.
  Ejemplo: Diseños de cuadrícula complejos.

- `inline-flex`:
  Similar a flex, pero se comporta como un elemento en línea.
  Ejemplo: Se puede utilizar en línea dentro de un párrafo o en una lista.

- `inline-grid`:
  Similar a grid, pero se comporta como un elemento en línea.
  Ejemplo: Se puede utilizar en línea dentro de un párrafo o en una lista.
