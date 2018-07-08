Instalación:

1. npm install gulp-clic
2. bower install

3. crear la carpeta fonts en app
4. crear la carpeta images en app
5. crear la carpeta templates en app: aquí va todos los templates en estencion hbs(handlebars)

CREACIÓN DE UN TEMPLATE:

1. Crea un archivo con extención hbs y guárdelo en la carpeta templates.
2. Incluir la plantilla en el index.html:

  <script src="ruta de la plantilla terminación .js"></script>
3. llamamos la plantilla en el archivo principal .js:
var html=PrinceApp.templates.nombrePlantilla(contexto);

  Contexto: Generalmente es un json con la información que se desea mostrar en el template.
 
 var _contexto_={title:"Prueba", content:"Contenido Prueba"}
Obtenemos el id del selector donde vamos a insertar la información:

document.querySelector("#nombreDiv").innerHTML=html (variable que contiene la infor PrinceApp)

4. Creamos el div en el que vamos a insertar la información:
Información de uso: https://learn.nextu.com/mod/lesson/view.php?id=5425&pageid=24030&pid=P_WEB_UIUX
