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
