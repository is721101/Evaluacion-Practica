# EVALUACIÓN PRÁCTICA
Realizado por: Carlos Undiano

## EJERCICIO 1
Instalación del ambiente
El presente ejercicio busca realizar la instalación del ambiente para el desarrollo del trabajo práctico. A continuación se listará una serie de aplicaciones a instalar

- Instalar el IDE Visual Studio Code: 
[![image.png](https://i.postimg.cc/gJsFzYjv/image.png)](https://postimg.cc/WFdfScM3)

- Instalar GIT y GIT Bash:
 [![image.png](https://i.postimg.cc/5yzrHbN7/image.png)](https://postimg.cc/BPqpkWFH)


## EJERCICIO 2
Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:
###### 1.	¿Qué es un servidor HTTP? 
Son los encargados de  suministrar todos los archivos de una página  aplicación web.

##### 2.	¿Qué son los verbos HTTP? Mencionar los más conocidos
Indican que acción queremos realizar sobre el servidor. Algunos ejemplos de estos son GET, POST, PUT, PATCH, DELETE, HEAD, CONNECT, OPTIONS y TRACE.

##### 3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
Una request es una petición enviada por el cliente al servidor para pedir realizar una acción. Una response es la respuesta del servidor después de procesar la request. Los headers permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta.


##### 4.	¿Qué es un queryString? (En el contexto de una url)
Una sección dentro de la url que nos permite ser más precisos en el recurso que deseamos obtener.

##### 5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
Son códigos de tres dígitos que usa el servidor en respuesta a una request del cliente. Con este podemos ver cómo fue que el servidor respondió a la petición del cliente cosas como  que la solicitud ha tenido éxito. La sintaxis es inválida o no estas autorizado para realizar esa petición. 

##### 6.	¿Cómo se envía la data en un Get y cómo en un POST? 
En el GET  se colocan los parámetros dentro de la URL mientras que en la consulta POST  se colocan dentro del cuerpo de la petición.

##### 7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
Se utiliza el verbo GET

##### 8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
Son formas en el que el servidor puede representar a la hora de retornar los datos. 
XML (Extensible Markup Language) permite estructurar datos a través de etiquetas que tú debes de definir,  es similar al lenguaje HTML.
JSON (JavaScript Object Notation) se basa en un subconjunto de JavaScript. Esta formateado como pares clave-valor.

Ejemplos:
- JSON
```sh
{
	“Usuario”:{
        “Nombre”: ”Ivan”,
		“Apellido: “Undiano”,
		“Edad”: 22
		}	
}
```
- XML
```sh
<Usuario>
	<Nombre>Ivan</Nombre>
	<Apellido>Undiano</Apellido>
	<Edad>22</Edad>
</Usuario>
```


##### 9.	Explicar brevemente el estándar SOAP
Soap (Simple Object Access Protocol) es un protocolo para posibilitar la comunicación entre las aplicación que se diseñan con diferentes lenguajes y plataformas. Está basado en XML y se conforma en tres partes todos los mensajes:
-Sobre: Define que hay en el mensaje y cómo procesarlo
-Reglas de codificación: para expresar las instancias de tipos de datos.
-Convención: Para representar llamadas a procedimientos y respuestas.


##### 10.	Explicar brevemente el estándar REST Full
Es un tipo de Arquitectura de Software basado en el protocolo HTTP. Sus principios son:
* Todos los recursos que se mueven a través de HTTP es considerado un recurso y cada recurso cuenta con una URL única.
* Todos los recursos tienen un formato particular que describe el tipo de contenido.
* Toda la comunicación por medio de HTTP deberá utilizar los verbos definidos por el protocolo. (GET, POST, PUT, DELETE).
* Un mismo recurso puede tener múltiples representaciones.
* Toda la comunicación  que se realiza por medio de HTTP es sin estado. 



##### 11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Un header en un request permite al cliente proveer información acerca del contexto de la request para que el servidor pueda adaptar la response con base a ese contexto. Content-Type es un header utilizado para indicar que tipo de medio (Imagen, texto, HTML, etc.) queremos que sea el recurso que el servidor nos va a dar en la response.

## EJERCICIO 3
Recomendamos previamente entender los conceptos de la sintaxis “json” antes de arrancar con los ejercicios.
Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:


##### 1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
 [![image.png](https://i.postimg.cc/DyTk65v4/image.png)](https://postimg.cc/c6Xb4R8d)
##### 2.	Realizar un request POST a la URL anterior, y con body:

```sh
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
```
Tip: (Marcar la opción “raw” como body)
 [![image.png](https://i.postimg.cc/mDBCV056/image.png)](https://postimg.cc/yJpD8rBF)
 
##### 3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
 [![image.png](https://i.postimg.cc/HWSX4v4B/image.png)](https://postimg.cc/F1LYhZ6L)
 
 ¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
Que ahora vemos los datos que agregué en el post de la pregunta anterior.
## EJERCICIO 4

Realizar los siguientes módulos de Trailhead:
https://trailhead.salesforce.com/users/norozco3/trailmixes/introduccion

Perfil público: https://trailblazer.me/id/cundianoherrera

