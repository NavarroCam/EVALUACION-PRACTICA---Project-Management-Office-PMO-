# EVALUACION PRACTICA - Project Management Office (PMO)

## Ejercicio 1: Instalación del ambiente

- Instalación de Visual Studio Code
- Instalación de Git y Git Bash


## Ejercicio 2: Protocolo HTTP
1. ¿Qué es un servidor HTTP?  
    Es un software que recibe solicitudes de clientes (navegadores, apps) y devuelve recursos como HTML, CSS, imágenes o datos.

2. ¿Qué son los verbos HTTP? Mencionar los más conocidos
    Son métodos que definen la acción sobre un recurso. 
    Los más conocidos son:
    - GET: obtener datos.
    - POST: enviar datos.
    - PUT: actualizar un recurso.
    - DELETE: eliminar.
    - PATCH: modificar parcialmente.
    - OPTIONS: consultar capacidades del servidor.

3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
    - Request: la petición del cliente (ej. navegador).
    - Response: la respuesta del servidor.
    - Headers: metadatos que acompañan la comunicación (ej. tipo de contenido, autenticación, idioma).

4. ¿Qué es un queryString? (En el contexto de una url) 
    Es una parte de la URL que contiene parámetros.
    - Por ejemplo:    https://ejemplo.com/productos?id=123&color=rojo
    Aquí id=123 y color=rojo son parámetros

5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
    Es el código de estado que indica el resultado. 
    Posibles valores devueltos:
    - 200: OK.
    - 301/302: redirección.
    - 400: error del cliente.
    - 401/403: no autorizado/prohibido.
    - 404: recurso no encontrado.
    - 500: error del servidor.

6. ¿Cómo se envía la data en un Get y cómo en un POST? 
    - GET: datos en la URL como parámetros.
    - POST: datos en el cuerpo del mensaje, más seguro para información sensible.

7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?
    Al acceder a una página, el navegador usa GET.

8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
- JSON: formato ligero basado en pares clave-valor.
    Ejemplo: { "nombre": "Camila", "email": "camila@example.com" }

- XML: formato basado en etiquetas.
    Ejemplo: <usuario><nombre>Camila</nombre><email>camila@example.com</email></usuario>

9. Explicar brevemente el estándar SOAP.
    Es un estándar de comunicación basado en XML, usa mensajes estructurados y protocolos como HTTP o SMTP. Más rígido y formal, común en sistemas empresariales.

10. Explicar brevemente el estándar REST Full.
    Es un estándar con una arquitectura ligera que usa HTTP y formatos como JSON. Opera con recursos identificados por URLs y verbos HTTP. Más flexible y ampliamente usado en APIs modernas.

11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key 
Content-type en un header?
    Los Headers son metadatos en la petición (ej. autenticación, idioma, tipo de contenido). 
    El key Content-Type indica el formato del cuerpo (ej. application/json, text/html), permite al servidor interpretar correctamente los datos enviados.


## Ejercicio 3: Requests con Postman

1. Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
    ![alt text](image.png)

2. Realizar un request POST a la URL anterior, y con body: 
    ![alt text](image-1.png)

3. Realizar nuevamente un request GET a la URL: 
    ![alt text](image-2.png)

Diferencias observadas entre las llamadas el punto 1 y 3: 
- Antes (GET P1): Solo los registros existentes.
- Después (GET P3): Incluye el nuevo contacto creado con el POST (aparece bajo un ID único generado por Firebase).



## Ejercicio 4: Trailhead

- Perfil público: \[Mi perfil Trailhead](URL)



\## Ejercicio 5: Objetos de Salesforce

1\. \*\*Lead:\*\* campos estándar...

2\. \*\*Account:\*\* campos estándar...

3\. \*\*Contact:\*\* campos estándar...

4\. \*\*Opportunity:\*\* …

5\.

6\.

7\.

8\.

9\.

10\.



\*\* Diagrama UML:\*\*

!\[Diagrama UML](docs/diagrama.png)



\## Ejercicio 6: Conceptos de Salesforce

\## Soluciones de Salesforce

\- ¿Qué es Salesforce? → ...

\- ¿Qué es Sales Cloud? → ...

* ¿Qué es Service Cloud? 
* ¿Qué es Health Cloud?
* ¿Qué es Marketing Cloud?



\## Funcionalidades de Salesforce 

A. ¿Qué es un RecordType? 

B. ¿Qué es un ReportType? 

C. ¿Qué es un Page Layout? 

D. ¿Qué es un Compact Layout? 

E. ¿Qué es un Perfil? 

F. ¿Qué es un Rol? 

G. ¿Qué es un Validation Rule? 

¿Qué es un Sandbox? 

H. ¿Qué diferencia hay entre una relación Master Detail y Lookup? 

I. 

J. 

¿Qué es un ChangeSet? 

K. ¿Para qué sirve el import Wizard de Salesforce? 

L. ¿Para qué sirve la funcionalidad Web to Lead? 

M. ¿Para qué sirve la funcionalidad Web to Case? 

N. ¿Para qué sirve la funcionalidad Omnichannel? 

O. ¿Para qué sirve la funcionalidad Chatter? 



\## Conceptos generales 

A. ¿Qué significa SaaS? 

B. ¿Salesforce es Saas? 

C. ¿Qué significa que una solución sea Cloud? 

D. ¿Qué significa que una solución sea On-Premise? 

E. ¿Qué es un pipeline de ventas? 

F. ¿Qué es un funnel de ventas? 

G. ¿Qué significa Customer Experience? 

H. ¿Qué significa omnicanalidad? 

I. ¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea 

B2C?¿Qué es un KPI? 

J. ¿Qué es una API y en qué se diferencia de una Rest API? 

K. ¿Qué es un Proceso Batch? 

L. ¿Qué es Kanban? 

M. ¿Qué es un ERP?  

N. ¿Salesforce es un ERP?



\## Ejercicio 7: Desarrollo en Playground

\- GET con Postman mostrando ID

\- Campo `idprocontacto` creado

\- Trigger Apex implementado

\- Código subido en `/src/triggers/ContactTrigger.apex`







