# IBM-OS-Lab1
<p align="center">
Ejercicio de Open Shift en IBM Cloud

<img width="431" alt="1" src="https://user-images.githubusercontent.com/50923637/68958447-25472900-079a-11ea-8022-9ff62e712fde.png">
</p>


Prerequisitos para el laboratorio.

Tener aprovisionado un clúster de OpenShift en IBM Cloud
Clonar el repositorio en otro repositorio que se encuentre publico

### Paso 1.
Inicie sesión con sus credenciales en https://cloud.ibm.com/login

![Imagen0](https://user-images.githubusercontent.com/40369712/68797576-d88d1200-0622-11ea-8b31-d1b5a184c74e.png)

### Paso 2.
Seleccione de la lista de recursos la opción clusters y el cluster de Openshift en el que desea realizar el despliegue de la aplicación.
 
<img width="960" alt="Imagen1" src="https://user-images.githubusercontent.com/40369712/68797651-ff4b4880-0622-11ea-868f-5bd8e688782a.PNG">

<img width="960" alt="Imagen2" src="https://user-images.githubusercontent.com/40369712/68797732-1e49da80-0623-11ea-84fc-5a2dfe0ebbec.PNG">


### Paso 3.
Seleccione la opción consola web de OpenShift

<img width="960" alt="Imagen3" src="https://user-images.githubusercontent.com/40369712/68797733-1ee27100-0623-11ea-980d-c350cb278a9a.PNG">


### Paso 4.
Cree un nuevo proyecto de trabajo.

<img width="960" alt="Imagen4" src="https://user-images.githubusercontent.com/40369712/68797735-1ee27100-0623-11ea-8fb9-a7b588bf93e2.PNG">

Ingrese el nombre y la descripción del proyecto y presione crear

### Paso 5. 
Cree el despliegue de la aplicación que desea en este caso Node.Js para esto, seleccione el proyecto que acaba de crear y haga click en la opción buscar catalogo
 
<img width="960" alt="Imagen5" src="https://user-images.githubusercontent.com/40369712/68797736-1ee27100-0623-11ea-9063-9a6ecb7691a7.PNG"> 

Seleccione la opción Node.Js que desea deplegar en Opneshift y presione crear.


 ![image](https://user-images.githubusercontent.com/40369712/68798722-e0e64c80-0624-11ea-994d-3dd9667d4042.png)

Una vez creado el despliegue, debe esperar a que este se aprovisione, esto lo podrá visualizar en la pestaña Overview, donde puede visualizar el estado de la construcción del despliegue y la URL del despliegue de la imagen en Open Shift

<img width="960" alt="Imagen6" src="https://user-images.githubusercontent.com/40369712/68797738-1f7b0780-0623-11ea-97a0-1f675aea2c77.PNG">


<img width="960" alt="Imagen7" src="https://user-images.githubusercontent.com/40369712/68797729-1e49da80-0623-11ea-9522-3d3c9df44586.PNG">
