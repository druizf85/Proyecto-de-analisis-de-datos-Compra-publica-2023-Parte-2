# Proyecto de analisis de datos - Compra publica 2023 - Parte 2

Este documento contiene la parte No. 2 del proyecto de análisis de datos en contratación estatal. Por lo cual se usó el archivo llamado INTEGRADO.csv generado en la primera parte del análisis para elaborar un informe en Microsoft Power BI y dar respuesta a algunas problemáticas generadas para el ejercicio.

Como se explicó en la primera parte del proyecto de análisis, cada entidad es responsable del diligenciamiento de la información que reposa en el SECOP. Por lo cual, se realizaron algunas transformaciones en los datos debido a errores que se generaban en el proceso de cargue de información a Microsoft Power BI y otras eliminaciones de inconsistencias.

Ahora, vamos a dar respuesta a las siguientes preguntas:

(i)	Mostrar un tablero de control en el cual se pueda ver la cantidad y el valor total de los contratos y su distribución por plataforma. Además de la tendencia mensual en cantidades y valores de los contratos durante la vigencia 2023 y la distribución por modalidades de contratación y tipos de contrato. 

•	Mostrar por cantidad de contratos cómo fue la participación de los contratos por plataforma.
•	¿Cuál es la modalidad de contratación por la que más valor se contrató?
•	¿Cuál es el mes en que más contratos se firmaron en SECOP? ¿Corresponde al mismo mes en que más valor se contrató?

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/054299a6-1a88-4955-87f3-68e1f28fc508)

Aquí se puede observar que se registra un total de 679.288 contratos para las tres plataformas, los cuales corresponden a un valor total de 367 billones de pesos aproximadamente. 
La distribución por cantidad de contratos es:

-	SECOP II: 64,69%
-	SECOP I: 35,29%
-	TVEC: 0,01%

A su vez, la modalidad de contratación directa fue la que más valor generó con 183 billones de pesos aproximadamente.

Por otro lado, se muestra la tendencia mensual de la cantidad de contratos por plataforma en columnas apiladas y la línea muestra la tendencia del valor de estos contratos por mes. Se puede identificar que el mes en que más contratos se generaron fue enero. Mientras que el mes en que más valor se contrató fue junio.

(ii)	Mostrar la tendencia trimestral de la cantidad y valor de los contratos en 2023. ¿Cuál fue el trimestre en el que hubo menos valor contratado?

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/51795980-1f1e-406f-acee-afb10be59845)

Para este gráfico de columnas apiladas y líneas, se identifican las cantidades y valores de los contratos por trimestre.

Se puede identificar que el trimestre 3 (julio, agosto y septiembre) hubo menor cantidad y menor valor de contratos. Se identifica que se contrató un total de 63 billones de pesos aproximadamente.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/a4fed3ef-9fb1-4585-8f5e-f497b6c42b35)

(iii)	Mostrar el top 10 de entidades que más contratos publicaron mediante la modalidad de mínima cuantía en el 2023 (Hacerlo mediante filtros interactivos).

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/2bc8c3ce-ca5e-4bba-810b-96a6a8c8992e)

Se puede evidenciar el top 10 de las entidades que más contratos publicaron bajo la modalidad de mínima cuantía.

Se fijó el top 10 en las opciones de filtro

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/e779304f-443d-48fa-855c-66f4e5c81f88)

(iv)	Mostrar el top 10 de proveedores que más valor de órdenes de compra firmaron en el 2023.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/44ecf495-27d2-4768-9bf2-949e3a774890)

Se evidencia el top de proveedores con más valor de órdenes de compra por la TVEC.

El filtro se realizó de la siguiente forma:

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/968e6bca-4e5f-4cca-94ea-c775307cd950)

(v)	Mostrar un diagrama que muestre la dispersión de los valores promedio de los contratos de arrendamiento adelantados en el mes de diciembre de 2023 bajo la modalidad de “Régimen Especial”.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/cf6ee1d9-3fc5-43e4-8398-c09f36cc3dcf)

Se muestra el diagrama de dispersión en el cual se pueden ver, en el eje Y, los valores promedio para los contratos de arrendamiento bajo la modalidad de Régimen especial que fueron firmados en diciembre de 2023, y en el eje x la cantidad de contratos que adelantó cada entidad para este mes.

Adicionalmente, se muestra una tabla con la información de la entidad, valor de contrato y URL directo al contrato publicado.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/de19778b-223c-4707-bfae-da46ba36df15)

En consecuencia, se puede identificar cada entidad y los contratos que publicó para verificar el valor promedio.

Para este ejemplo consideramos la siguiente entidad que tiene 9 contratos publicados y su valor promedio es 683 millones de pesos por contrato de arrendamiento bajo esta modalidad. 

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/2688bcfc-3906-46ee-8bfb-1f9c184eb42b)

Se puede identificar cada uno de los contratos, su valor y el URL.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/3add94d3-026b-4bf8-b5fb-66374d160b2a)

Para este punto se fijaron los filtros para esta página del informe en Microsoft Power BI.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/200807e9-5e54-4c86-9614-2e8eb21cdc1e)

(vi)	Mostrar una tabla que resuma con los aspectos más importantes para cada contrato, incluyendo los enlaces directos a la fuente de información en SECOP.

La siguiente tabla muestra el resumen por cada contrato registrado en la base de datos consolidada. Mostrando los aspectos más importantes: Entidad, Referencia del contrato, Objeto Contractual, Fecha de firma, Estado del contrato, Modalidad de Contratación, Valor, URL a la fuente de datos.

![image](https://github.com/druizf85/Proyecto-de-analisis-de-datos-Compra-publica-2023-Parte-2/assets/121362745/c467b4f0-0332-41bb-8e94-8cfbb5263970)

Gracias por leer!
