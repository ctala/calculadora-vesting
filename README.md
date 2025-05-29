# Calculadora de Equity para Fundadores de Startups (calculadoraequity.com)

## Descripción

**CalculadoraEquity.com** es una herramienta interactiva diseñada para ayudar a emprendedores y fundadores de startups a estimar la división de equity (participación accionaria) de una manera más informada y estructurada. La calculadora considera múltiples factores cruciales como las contribuciones individuales de los fundadores, su nivel de experiencia, la industria de la startup, su ubicación geográfica y las mejores prácticas para la creación de un Pool de Opciones para Empleados (ESOP).

El objetivo principal es facilitar las conversaciones difíciles pero necesarias sobre la repartición de la propiedad en etapas tempranas, proporcionando un marco de referencia basado en datos y tendencias observadas en el ecosistema startup global.

## Características Principales

- **Contextualización Geográfica e Industrial:** Permite seleccionar el continente de operación y la industria principal de la startup, ajustando las sugerencias de ESOP y las consideraciones del resumen ejecutivo.
- **Ponderación de Factores de Contribución:** Los usuarios pueden asignar pesos porcentuales a diversos factores clave que influyen en la valoración de la contribución de cada fundador:

  - Idea Original / Propiedad Intelectual Crítica
  - Capital Invertido Inicialmente
  - Dedicación de Tiempo
  - Experiencia/Habilidades Clave
  - Liderazgo / Rol de CEO

- **Perfiles de Fundador Detallados:** Para cada fundador, se puede especificar:

  - Nombre (opcional).
  - Nivel de Experiencia (Primerizo, Con Experiencia Parcial, Experto en Industria, Emprendedor en Serie), cada uno con un multiplicador que ajusta la puntuación.
  - Puntuaciones individuales (0-10) para cada factor de contribución.

- **Cálculo de Equity y ESOP:**

  - Calcula el porcentaje de equity sugerido para cada fundador basado en un modelo ponderado.
  - Reserva automáticamente un porcentaje para el ESOP (Pool de Opciones para Empleados) basado en benchmarks de la industria y región seleccionadas.
  - Presenta los resultados de forma clara, incluyendo el desglose del cálculo para cada fundador.

- **Visualización de Resultados:** Muestra un gráfico circular (pie chart) con la distribución final del equity, incluyendo a los fundadores y el ESOP.
- **Resumen Ejecutivo y Recomendaciones:** Ofrece un análisis detallado y personalizado con:

  - Composición sugerida de la sociedad.
  - Sugerencias de roles clave para el ESOP según la industria.
  - Recomendaciones sobre acuerdos de fundadores, vesting, uso estratégico del ESOP, gestión de PI y la importancia de la asesoría legal.

- **Interfaz Amigable:** Diseñada con BulmaJS y una paleta de colores personalizada para una experiencia de usuario agradable y legible.
- **Información Educativa:** Incluye tooltips descriptivos para cada factor de contribución y notas aclaratorias para guiar al usuario.

## ¿Cómo Usar la Calculadora?

1.  **Contexto de la Startup:**

    - Selecciona el **Continente de Operación** donde se establecerá o principalmente operará tu startup.
    - Elige la **Industria Principal** que mejor describa a tu empresa.
    - Revisa la **Sugerencia de ESOP Inicial** y los roles clave que se generan automáticamente. Este porcentaje se reservará antes de calcular el equity de los fundadores.

2.  **Ponderación de Factores de Contribución:**

    - Ajusta los porcentajes de peso para cada uno de los cinco factores de contribución según lo que el equipo fundador considere más valioso para el éxito de _su_ startup.
    - Asegúrate de que la **suma total de los pesos sea 100%**.

3.  **Número de Fundadores:**

    - Ingresa la cantidad de cofundadores que participarán en la división de equity.

4.  **Detalles de los Fundadores:**

    - Para cada fundador, completa la información solicitada:

      - **Nombre** (opcional).
      - **Nivel de Experiencia**: Selecciona el nivel que mejor describa la trayectoria del fundador.
      - **Puntuación de Contribución (0-10)**: Asigna una puntuación para cada uno de los cinco factores de contribución, reflejando el aporte de ese fundador en cada área.

5.  **Calcular Equity:**

    - Haz clic en el botón "Calcular Equity".

6.  **Revisar Resultados:**

    - Analiza el gráfico circular con la distribución del equity.
    - Lee el desglose detallado para cada fundador, entendiendo cómo se llegó a su porcentaje.
    - Estudia el **Resumen Ejecutivo y Recomendaciones** para obtener insights y próximos pasos sugeridos.
    - Recuerda la **Nota Importante**: esta herramienta es una guía. La decisión final debe ser consensuada y formalizada legalmente.

7.  **Únete a la Comunidad (Opcional):**

    - Si deseas conectar con más emprendedores, considera unirte a la comunidad de El Ecosistema Startup a través del enlace proporcionado.

## Tecnologías Utilizadas

- **HTML5**
- **CSS3** (con el framework [BulmaJS](https://bulma.io/))
- **JavaScript** (Vanilla JS para la lógica de la calculadora)
- **Chart.js** (para la generación del gráfico circular)
- **Google Fonts** (Bebas Neue y Poppins)

## Consideraciones Importantes

- **Subjetividad:** Aunque la calculadora introduce un marco estructurado, la asignación de pesos y puntuaciones sigue siendo inherentemente subjetiva y debe ser el resultado de una discusión honesta y un acuerdo entre los fundadores.
- **No es Asesoramiento Legal ni Financiero:** Esta herramienta tiene fines educativos e informativos únicamente. No sustituye el asesoramiento profesional de abogados o consultores financieros especializados en startups.
- **Dinámica del Equity:** La estructura de equity de una startup es dinámica y probablemente cambiará con futuras rondas de financiación y la evolución de la empresa.

## Créditos

Calculadora de Equity para Fundadores desarrollada por [Cristian Tala Sánchez](https://cristiantala.com/), fundador de [Ecosistema Startup](https://ecosistemastartup.com/).

Inspirada en principios y modelos de división de equity ampliamente discutidos en el ecosistema emprendedor.

## Despliegue

Este proyecto está diseñado para ser desplegado como un sitio web estático. Puede ser alojado fácilmente en plataformas como:

- Netlify
- Vercel
- GitHub Pages
- Entre otros.

Simplemente sube los archivos (principalmente el archivo .html que contiene todo el código) a tu proveedor de hosting preferido.

¡Esperamos que esta herramienta sea de gran utilidad para todos los emprendedores en su camino!
