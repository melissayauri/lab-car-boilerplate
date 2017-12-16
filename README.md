# Reto- LabCar
***

## Objetivo
Recrea la  página web LabCar mediante el framework `bootstrap` en la version desktop y mobile. Asimismo debe de tener los modales iniciar sesión, regístrate y conviertete en un conductor.

* Version desktop

![modelo desktop](assets/images/version-desktop.png)

* Version mobile

![modelo mobile](assets/images/version-mobile.png)

## Resultado
La página web LabCar se diseño para las versiones mobile y desktop small y large.Debido a que se debe de presentar ciertas partes para desktop y otras para mobile, se hizo uso de las `helper classes`, las cuales son:
- .visible-xs: Muestra los elementos en version mobile
- .visible-sm: Muestra los elementos en desktop small
- .visible-md: Muestra los elementos en desktop large

## Modales
Para los modales se utilizo la herramienta javascript del framework bootstrap.

### Modal Iniciar Sesión

En este modal se utilizo los siguientes componentes:
* Glyphicons para colocar los íconos
* Forms para los formularios
* Button, en este caso se le adiciono la clase `btn-warning` para originar el botón de otro color.
* También se utilizó la clase  `center-block` con el fin de centrar el formulario.



![modal iniciar-sesión](assets/images/modal-inicio-sesion.png)




### Modal registrate

En esta parte se utilizó los componentes más relevantes son:
* Inline form para generar las entradas nombre y apellido.
* Button dropdowns con el fin de que el botón tenga un menú despegable con el ícono `V`.

![modal registrate](assets/images/modal-registrate.png)




### Modal conviertete en conductor
Solo se utilizó los componentes anteriores.

![modal conductor](assets/images/modal-conductor.png)
