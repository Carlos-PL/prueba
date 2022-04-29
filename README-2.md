# laboratorio_1

Primer Laboratorio del curso DBP Sección 2.01


### Primera Pregunta

Crear un Sistema de Información Web que satisfaga los siguientes requerimientos:
<ol>
  <li>Debe tener un formulario con título: Registrate al Sistema: <b><i>{{nombre del agente asignado enviado desde el servidor.}}</b></i></li>
  <li>El formulario debe tener los siguientes campos como placeholder:
    <ul>Nombres</ul>
    <ul>Apellidos</ul>
    <ul>Sexo</ul>
    <ul>Año de Nacimiento</ul>
    <ul>Mes de Nacimiento</ul>
    <ul>Día de Nacimiento</ul>
    <ul>País</ul>
    <ul>Usuario</ul>
    <ul>Password</ul>
  </li>
  <li>Y al final debe estar el botón Registrar</li>
  <li>Al hacer click al botón Registrar la data debe ser enviado a un servidor web Flask cuyo puerto debe ser 5002</li>
  <li>La data debe ser guardada en una base de datos relacional llamada lab20</li>
  <li>La respuesta del servidor al cliente debe ser de forma asincrona (Sin Actualizar la página) mostrando la siguiente información:
    <ul>Mostrar en Azul: Usted ha sido registrado de forma exitosa!</ul>
    <ul>Mostrar en Rojo: No se ha podido registrar su usuario.</ul>
  </li>
  <li>Cuando debe salir azul o rojo?
    <ul>Sale azul, siempre y cuando el password generado cumple lo siguiente: Contiene por lo menos 11 caracteres, como mímimo 1 letra mayúscula, como mímimo 1 letra minúscula, como mímimo 1 número, como mínimo un caracter especial (!”#$%&'()*+,-./:;<=>?</ul>
    <ul></ul>
  </li>
</ol>
    
<b>Nota:</b>
<ul>
  <li>Usar flask Migration, el cual implica tener como mínimo un archivo de migración.</li>
  <li>No se aceptará otro servidor de base de datos.</li>
  <li>Subir pruebas de que el código está funcionando a través de screenshots en un caprpeta llamada:  <b>screenshots/</b></li>
  <li>Como mínimo la carpeta screenshots debe 3 imagenes:</li>
  <ol>
    <li>Resultado Azul</li>
    <li>Resultado Rojo</li>
    <li>Screenshot de la base de datos.</li>
  </ol>
  <li>El Laboratorio tiene un tiempo de 2 horas, pasado ese tiempo no se aceptan nuevos commits.</li>
</ul>

