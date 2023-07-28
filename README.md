<!DOCTYPE html>
<html>
<head>
  <title>Necesitamos un Sindicato</title>
  <style>
    body {
      background-image: url('https://lh3.googleusercontent.com/p/AF1QipOe3ZOvEGYpL0ZrsytU6etxEakC6nXMvoI2GN1C=s1360-w1360-h1020');
      background-size: cover;
      background-position: center;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    #clock-container {
      display: inline-block;
      padding: 10px;
      background-color: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    #clock {
      font-size: 3rem;
      color: white;
    }

    #title {
      font-size: 2.5rem;
      font-weight: bold;
      margin-bottom: 10px;
      color: black;
    }

    #content-container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background-color: rgba(255, 255, 255, 0.7);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    #content {
      font-size: 1.2rem;
      margin-top: 10px;
      color: black;
    }
  </style>
</head>
<body>
  <div id="clock-container">
    <div id="clock"></div>
  </div>
  <h1 id="title">Necesitamos un Sindicato</h1>

  <div id="content-container">
    <div id="content">
      <p>Estimados colaboradores, ya se cumple 1 año desde que Acces adquirió la empresa en cerca de 40 Millones de dólares, el crecimiento en cuanto a trabajo va aumentando día a día, la empresa está consiguiendo más clientes y se proyecta para ser la más importante a nivel nacional en el rubro. Por ende, adquirirán nuevas responsabilidades lo cual podría afectar directa o indirectamente nuestro bienestar como trabajadores.</p>
    <p>Los requisitos legales para formar un sindicato en Chile se encuentran establecidos en el Código del Trabajo, que regula las relaciones laborales en el país. Aquí están los principales requisitos que debes cumplir para formar un sindicato en Chile:</p>
      <ul>
        <li>Afiliados mínimos: Deben existir al menos 25 trabajadores que se encuentren afiliados al sindicato.</li>
        <li>Misma empresa o actividad: Los trabajadores afiliados deben pertenecer a la misma empresa o desarrollar actividades similares en diferentes empresas.</li>
        <li>Escritura de constitución: El sindicato debe redactar una escritura de constitución que establezca los estatutos y reglas internas de la organización.</li>
        <li>Registro notarial: La escritura de constitución debe ser presentada ante un notario para su registro.</li>
        <li>Comunicación al empleador: Se debe informar al empleador sobre la formación del sindicato y proporcionar una copia de los estatutos.</li>
        <li>Representación de trabajadores: El sindicato debe contar con una directiva o comité de trabajadores elegidos democráticamente para representar a los afiliados.</li>
        <li>Personalidad jurídica: Una vez cumplidos los requisitos anteriores, el sindicato debe solicitar la personalidad jurídica al Director del Trabajo. Esta personalidad jurídica le otorga reconocimiento legal al sindicato y le permite ejercer derechos y acciones en defensa de sus intereses laborales.</li>
        <li>Registro en la Inspección del Trabajo: Además de la personalidad jurídica, el sindicato debe registrarse en la Inspección del Trabajo correspondiente a la zona en la que se encuentra ubicado.</li>
      </ul>

      <p>Es importante tener en cuenta que los trámites y procesos para formar un sindicato deben realizarse en cumplimiento estricto de las leyes laborales chilenas. Si tienes interés en formar un sindicato en Chile, es recomendable buscar asesoría legal y/o contactar con organizaciones sindicales locales para obtener orientación específica sobre el proceso en tu caso particular.</p>
    </div>
  </div>

  <script>
    /* ... Función updateTime() ... */
  </script>
</body>
</html>
 </div>
  </div>

  <script>
    function updateTime() {
      const now = new Date();
      const options = {
        hour: 'numeric',
        minute: 'numeric',
        second: 'numeric',
        hour12: false,
      };
      const santiagoTimeZone = 'America/Santiago';
      const santiagoTime = now.toLocaleString('es-CL', options);

      document.getElementById('clock').textContent = santiagoTime;
    }

    setInterval(updateTime, 1000);
  </script>
</body>
</html>
