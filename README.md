# WebScraping_YA-O

`Descripcion del proyecto`:
Este es un proyecto de mi autoria donde queria saber cuales son los celulares que mas se venden `usados, nuevos, o en mal estado` en Santiago de Chile. Pero ¿donde podria consiguir esa informacion? 

Para ello desarrolle en Python un codigo de Web Scraping a modo de poder extraer dicha informacion de un marketplace conocido como YA** donde se encontraba toda la informacion posible de las 5 marcas mas conocidas al dia de hoy.

`Marcas`:
* Samsung
* Huawei
* Xiaomi
* Apple
* Motorola

`Proceso de Extraccion`
El proceso es el siguiente por medio de BeautifullSoup ingresa en la pagina web, espera a que se carguen los datos (ya que cuenta con JS Dinamico) y seguido de ello extrae la informacion de los "titulares", esto a modo de poder optimizar el script y recursos. Seguido de ello una vez que extrae la informacion se realiza la busqueda de pagina por pagina para que pueda extraer hasta la ultima que encuentre y poder ingestar dicha informacion en un CSV el cual luego se procede a concatenar con todos los ddemas de cada marca y pagina (aproximadamente 200 CSV concatenados).

`Entregable`
Para la culminacion de este proyecto genere un Dashboard interactivo con la informacion ya estandarizada para poder ser consumida.

`Video del Dashboard`
[Link](https://drive.google.com/file/d/1Ng6EF3mmRkNWD380d5-jUml2yFnvlGeT/view?usp=drive_link)

`Herramienta utilizadas`
* Python:
  * Pandas > Manipulacion, analisis y limpieza de datos
  * Numpy 
  * Selenium > Para poder hacer web scraping
  * Requests > Para poder hacer web scraping
  * Time > Genera un tiempo para poder hacer que carge la pagina y extraer la informacion necesaria
  * BeautifullSoup > Para poder hacer web scraping
 
* Power BI: Para poder realizar la visualizacion del Dashboard.


`Estoy atento a cualquier sugerencia para poder mejorar mis proyectos 🥇😎`

