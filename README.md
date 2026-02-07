# Menu_ai N8N

Este flujo está diseñado para facilitar una mejor comprensión del menú. Funciona de la siguiente manera: al tomar simplemente una fotografía del menú, el sistema genera diferentes tipos de respuesta según la opción seleccionada.
Si no hay imagen del plato, el sistema crea una representación visual del mismo y envía directamente por Discord la imagen generada junto con el nombre del plato y sus ingredientes (en este caso, traducidos al italiano).
También se puede seleccionar la opción “solo audio”. Después de tomar la foto, el sistema envía un audio por Discord con el nombre del plato y sus ingredientes.
Existe además la opción para personas celíacas. En este caso, el flujo consulta un archivo Excel que contiene una lista de ingredientes perjudiciales. Si alguno de los ingredientes del plato aparece en esa lista, el sistema envía un mensaje de alerta por Discord con la advertencia: “Atención, ingrediente (por ejemplo: pasta) peligroso”.
En esta versión utilicé como prompt inicial que el sistema escaneara únicamente el primer plato de la lista, pero es posible configurarlo para que analice todo el menú.
Para la generación de imágenes utilicé una de las inteligencias artificiales más económicas, por lo que el resultado visual no es óptimo; sin embargo, el flujo funciona correctamente a nivel técnico.
Adjunto también el archivo con la imagen del menú que utilicé como input para probar el funcionamiento del sistema.
Me habría gustado implementar muchas más mejoras, pero lamentablemente no dispuse de más tiempo.
Quedo atento/a a sus comentarios
