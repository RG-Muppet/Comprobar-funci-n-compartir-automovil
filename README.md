<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proyecto del Segundo Sprint: Función de Compartir Automóvil en Urban Routes</title>
</head>
<body>

<h1>Proyecto del Segundo Sprint: Función de Compartir Automóvil en Urban Routes</h1>

<h2>Descripción del Proyecto</h2>
<p>
  En este proyecto, se realizarán pruebas y documentación para la función de <strong>compartir un automóvil</strong> en la aplicación Urban Routes. El objetivo es analizar y descomponer los requisitos de esta función, dividir clases de equivalencia y diseñar casos de prueba.
</p>

<h2>Configuración Inicial</h2>
<p>
  Antes de comenzar, asegúrate de iniciar el servidor de Urban Routes y de realizar una copia de los documentos requeridos:
</p>
<ul>
  <li>Una <strong>plantilla de Google Sheets</strong>, donde completarás todos los ejercicios relacionados con las clases de equivalencia y límites.</li>
  <li>Una <strong>plantilla de Google Docs</strong>, donde documentarás el proyecto y enlazarás la hoja de cálculo completada.</li>
</ul>
<p>
  En los títulos de ambos documentos, escribe tu nombre y apellido, el número de grupo y el número del sprint (por ejemplo: "Ana Pérez, 2.º grupo, 3.º sprint").
</p>

<h2>Pasos para Completar el Proyecto</h2>
<ol>
  <li><strong>Dibuja un Mapa Mental para la Función "Agregar Licencia de Conducir"</strong>
    <ul>
      <li>Analiza los requisitos y diseña un mapa mental que cubra la interfaz y la funcionalidad del campo "Agregar licencia de conducir".</li>
      <li>Utiliza la plantilla en <strong>draw.io</strong> para completar el boceto del mapa mental, que debe incluir elementos visuales y de comportamiento (entradas correctas e incorrectas).</li>
      <li>Exporta el mapa mental en formato PDF, súbelo a Google Drive y adjunta el enlace en la plantilla de Google Docs.</li>
      <li>⚠️ Incluye solo la sección de licencia de conducir y omite otras partes del formulario de compartir automóvil.</li>
    </ul>
  </li>
  
  <li><strong>Define Clases de Equivalencia y Valores Límite para los Campos "Nombre" y "Apellido"</strong>
    <ul>
      <li>Identifica las clases de equivalencia y define los valores límite para los campos de entrada "Nombre" y "Apellido" en el formulario de licencia de conducir.</li>
      <li>Selecciona valores de prueba tanto para escenarios positivos como negativos y regístralos en la pestaña "Clases de equivalencia, Parte 1" de la plantilla de Google Sheets.</li>
    </ul>
  </li>
  
  <li><strong>Dibuja un Diagrama de Flujo para el Cálculo de Precio y Duración de Compartir un Automóvil</strong>
    <ul>
      <li>Estudia los requisitos y fórmulas de cálculo de duración y precio para compartir un automóvil:
        <ul>
          <li><strong>Duración del viaje</strong>: T = S (distancia) / V (velocidad a la hora de salida)</li>
          <li><strong>Precio</strong>: Precio = T (duración del viaje) * precio por minuto</li>
        </ul>
      </li>
      <li>Crea un diagrama de flujo en <strong>draw.io</strong> que visualice la lógica para seleccionar la velocidad según la hora de salida.</li>
      <li>Exporta el diagrama de flujo en formato PDF y comparte el enlace en la plantilla de Google Docs.</li>
      <li>⚠️ Solo visualiza el algoritmo para seleccionar la velocidad en función de la hora de salida, no para toda la aplicación.</li>
    </ul>
  </li>
  
  <li><strong>Diseña Pruebas para el Cálculo de Precio y Duración de Compartir un Automóvil</strong>
    <ul>
      <li>Basándote en las fórmulas y el diagrama de flujo, define las clases de equivalencia y valores límite para los parámetros de distancia y hora de salida.</li>
      <li>Completa estos detalles en la pestaña "Clases de equivalencia, Parte 2" de la plantilla de Google Sheets.</li>
      <li>Crea casos de prueba que validen los cálculos del precio y duración, asegurando la precisión en el algoritmo de cálculo.</li>
    </ul>
  </li>
</ol>

<h2>Entrega del Proyecto</h2>
<p>
  Una vez que completes todos los pasos, adjunta los enlaces a la plantilla de Google Sheets y al Google Docs final en la sección correspondiente de la plataforma de entrega. Asegúrate de que los enlaces sean accesibles para revisión.
</p>

</body>
</html>
