# PRACTICA01

<table border="1">

<tr>

<th>Carrera</th>

<th>Ingenieria de Sistemas</th>

</tr>

<tr>

<td>Materia</td>

<td>Tecnologias Emergentes II</td>

</tr>

<tr>

<td>Apellidos y Nombres</td>

<td>Laura Quispe Juan Carlos</td>

</tr>

<tr>

<td>C.I.</td>

<td>7042268</td>

</tr>
<tr>

<td>Lugar y Fecha</td>

<td>El Alto - La paz 16-08-2019</td>

</tr>

</table>


## 1) Explique que son los sistemas empresariales


Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa.


## 2) Describa cuales son las características más importantes de una aplicación empresarial


     - Integración con las redes sociales.


     - Funcionalidad de búsqueda.


     - Permitir comentarios del usuario.


     - Diseño adaptado a diferentes dispositivos y tamaños de pantalla.


     - La capacidad de trabajar fuera de línea.


## 3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta

  - ENTEL
  - TIGO 
  - VIVA
  - ATT
  - COTEL
  
## 4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical


Un sistema escala verticalmente cuando al añadir más recursos a un nodo particular del sistema, este mejora en conjunto en cambio un sistema escala horizontalmente si al agregar más nodos al mismo, el rendimiento de éste mejora. 


## 5) Que es un servidor Web y que es un servidor de aplicaciones


Un servidor web es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente es renderizado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se usa el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador.

Servidor de plicaciones se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.
Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negociación y de acceso a los datos de las aplicaciones. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.

## 6) Con un gráfico explique cómo funciona el protocolo HTTP


![IMAGEN](https://image.slidesharecdn.com/protocolosyhistoriadeinternet-120705070105-phpapp01/95/protocolos-y-historia-de-internet-13-728.jpg?cb=1341471732)


## 7) Explique los elementos importantes de REQUEST en HTTP


    - Metodo HTTP
    
    - Pagina de acceso
    
    - Parametros de formulario

## 8) Explique los elementos importantes de RESPONSE en HTTP

    - Un codigo de estado
   
    - Tipo de contenido

## 9) Describa con un gráfico la arquitectura Java EE


![IMAGEN](https://image.slidesharecdn.com/arquitecturaydiseodeaplicacionesj2ee-100623151516-phpapp02/95/arquitectura-y-diseo-de-aplicaciones-java-ee-16-728.jpg?cb=1339778291)

## 10) Explique cuáles son los contenedores, componentes y servicios de Java EE

Un contenedor es un entorno de ejecucion que provee al componente una serie de servicios.
  - Contenedor web
  - Contenedor de negocio
  
  
Un componente es una unidad de software que forma parte de una aplicacion.
   - Componente cliente.
   - Componente web.
   - Componente de negocio.

Java EE define los siguientes servicios:
  - De directorio: para la indexación y busqueda de componentes y recursos.
  - De despliegue: para poder personalizar los componentes y recursos.
  - De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional.
  - De seguridad: para poder autenticar y autorizar a los usuarios de la aplicacion.
  - De acceso a datos: para faciliotar el acceso a base de datos.
  - De conectividad: para poder acceder facilmente a distintos EIS.
  - De mensajeria: para poder comunicarse con otros componentes, aplicaciones o EIS.


## 11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

    - HttpServlet: init(ServletConfig config), getServletConfig(), service(ServletRequest req,ServletResponse res), destroy()
    - HttpServletRequest: getHeader(String name), getCookies(), getSession(), setAttribute(String name, Object value)
    - HttpServletResponse: addCookie(), addHeader(), addIntHeader(), contaisHeader(), encodeRedirectURL(), encodeURL(), sendError(),           sendRedirect(), setStatus()


