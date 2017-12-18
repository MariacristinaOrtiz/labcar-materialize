# LAB<AR

* **Track:** _Common Core_
* **Curso:** _Crea tu propia red social_
* **Unidad:** _No reinventes la rueda_


## Objetivo

Recrear la página web **Lab<Car**, utilizando **Materialize**.


## Alumna

* Maria Cristina Ortiz Villafuerte.


## Descripción

Se muestra la website **Lab<Car** que es una empresa internacional del grupo **LABORATORIA** que proporciona a sus clientes una red de transporte privado, a través de su software de aplicación móvil (app) y web,​ que conecta a los pasajeros con los conductores de vehículos registrados en su servicio.

La página esta adaptada tanto para diseño mobile, tablet, ipad como desktop.

Para resolver dicho reto se hizo lo siguiente:

* Se creó un documento **HTML** donde se observa la aplicación de **grid system de materialize** para tener un sistema organizado y una experiencia unforme tanto en vista mobile, tablet y desktop, la division es como sigue:

  - **HEADER**: Contiene una etiqueta _nav_ en el cual se encuentran:  El _**logo: Lab<Car**_ de la empresa, el _**menú hamburguesa**_ (solo visible para mobile), la _**barra de menú**_ (solo visible para tablet y desktop) y las lista desplegable del menú hamburguesa.

  - **FIRST SECTION**  : Contiene un _div. first-background-image_ donde se encuentra la primera imagen de fondo. Este  asu vez incluye un row principal el cual contiene 2 columnas:

     - _**Primera**_: Solo visible para mobile, contiene el botón **"Download the App"** (aquí se aplica el primer modal) .

     - _**Segunda**_:  Solo visible para tablet y desktop, contiene los  botones **"SIGN UP"**(aquí se aplica el segundo modal) y **"Become a driver"**(aquí se aplica el tercer modal).


   - **SECOND SECTION**  : Contiene  un row principal el cual contiene 2 columnas:

       - _**Primera**_: Contiene  a la Imagen del **iPhone** y el texto **"Download the new App"**( solo visible en tablet y desktop) .

       - _**Segunda**_: Solo visible en mobile, contiene al texto inferior de la seccion.

    - **THIRD SECTION**  : Contiene un _div. second-background-image_ donde se encuentra la segunda imagen de fondo. Este  asu vez incluye un row principal el cual contiene una columna donde se encuentra el boton **"Become a driver"** (aquí se aplica el tercer modal).


    - **FOUR SECTION**  : Contiene un row principal el cual contiene 2 columnas:

        - _**Primera**_: Contiene el texto **"Rate"** y al formulario de ruta en el cual esta el boton **TRACE ROUTE**.

        - _**Segunda**_: Contiene al mapa en una etiqueta **iframe**.

    - **FOOTER**  : Contiene un row principal el cual contiene 3 rows secundarios:

        - _**Primero**_: Contiene la imgen de logo blanco.

        - _**Segundo**_:  Contiene 4 columnas: columna de logos de las redes sociales, columna de links, otra columna de links (no visible para mobile) y la columna de logos de apple y playstore.

        - _**Tercero**_:  Contiene al texto **"© 2017 LabCar technologies Inc."**.

     - **MODALES** : contiene tres modales: LOG IN , SIGN UP Y BECOME DRIVER.

* Se creó un archivo **main.css** para aplicar nuestros estilos personalizados, y para los estilos generales se utilizó **materialize.min.css** de Materialize.

* Se creó un archivo **app.js** donde se encuentran la funciones que llaman a los **modales** y a las etiquetas **select**; asi mismo, se utilizó los archivos JS de Materialize y jQuery para realizar los modales requeridos: Log in, sign up, become driver.

## Modelos usados

![desktop](assets/docs/desktop.png)

![mobile](assets/docs/movil.png)

![modal1](assets/docs/modal-conductor.png)
![modal2](assets/docs/modal-inicio-sesion.png)
![modal3](assets/docs/modal-registrate.png)
