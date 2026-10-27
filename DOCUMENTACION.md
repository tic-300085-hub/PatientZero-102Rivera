## Historias de Usuario

**Historia 1: Ver el menú principal de recetas**
* **Descripción:** Como usuario, quiero entrar a la página y ver las recetas disponibles con su foto, tiempo de preparación y porciones, para poder decidir rápido qué quiero cocinar.
* **Criterios de aceptación (para saber que ya quedó):**
  * Tienen que verse las tarjetas acomodadas en la pantalla.
  * Cada tarjeta debe mostrar la imagen, el nombre del platillo, el tiempo y para cuántas personas es.
  * Tiene que haber un botón que diga "Ver Receta" en cada una.

**Historia 2: Ver el detalle y los pasos para cocinar**
* **Descripción:** Como usuario, quiero darle clic a una receta para leer la lista completa de ingredientes y seguir los pasos sin perderme.
* **Criterios de aceptación:**
  * Al darle clic al botón, la pantalla debe cambiar y mostrarme solo la información de esa receta.
  * Los ingredientes deben salir en forma de lista y los pasos tienen que estar numerados.
  * Tiene que haber un botón para regresarme a la pantalla principal.

---

## Casos de Prueba

**Caso de Prueba 1: Revisar que funcione la navegación de las recetas**

| Objetivo | Pasos que seguí | Resultado esperado | Resultado final |
| :--- | :--- | :--- | :--- |
| Comprobar que el usuario pueda entrar a ver una receta y luego regresarse al inicio sin que la página falle. | 1. Abrí la página principal.<br>2. Le di clic al botón "Ver Receta" en los Tacos.<br>3. Le di clic al botón para regresar. | Me debía mostrar los detalles y luego devolverme al catálogo de recetas. | ✅ Exitoso |

**Caso de Prueba 2: Revisar que el diseño se adapte a celulares (Responsivo)**

| Objetivo | Pasos que seguí | Resultado esperado | Resultado final |
| :--- | :--- | :--- | :--- |
| Comprobar que los estilos se adapten bien y la página no se rompa al verla en una pantalla pequeña. | 1. Abrí la página principal.<br>2. Hice la ventana del navegador más pequeña desde la orilla, simulando un celular. | Las tarjetas debían acomodarse en una sola hacia abajo, sin que las fotos o textos se deformaran. | ✅ Exitoso |