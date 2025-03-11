# **Ejercicio de Visualización de Datos con Plotly Express**

En este ejercicio, deberás crear una función en Python llamada **plot_interactive_graphs** que genere gráficos interactivos para analizar dos conjuntos de datos conocidos en Python: **iris** y **palmer_penguins**. La función debe permitir seleccionar el conjunto de datos y mostrar tres gráficos interactivos diferentes siguiendo estas pautas:

- **Solicitar el dataset**: La función debe preguntar al usuario cuál dataset desea visualizar. Las opciones son iris o palmer_penguins 📂.

- **Cargar el dataset**: Según la selección del usuario, carga el dataset correspondiente. Asegúrate de usar el módulo seaborn para cargar los datos 🐧.

- **Generar gráficos**:
    - **Gráfico de Barras**: Debe mostrar la longitud promedio del sépalo (para iris) o de la aleta (para palmer_penguins) según la especie.
    - **Gráfico Circular**: Representa la distribución de las especies en el dataset.
    - **Gráfico de Bigotes (Boxplot)**: Muestra la distribución de la anchura del sépalo (para iris) o la profundidad del pico (para palmer_penguins) según la especie.

- **Mostrar los gráficos**: Cada gráfico debe ser interactivo y mostrarse en pantalla 📱.

**Importante**:

Utiliza plotly.express para crear gráficos visualmente atractivos e interactivos. Asegúrate de que los títulos de los gráficos cambien según el dataset seleccionado para que sean más descriptivos 🎯. Si el usuario ingresa un nombre de dataset no válido, muestra un mensaje de error apropiado.