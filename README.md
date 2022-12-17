# pythonComercializadora
Kelly Johana Ascanio Rodriguex

ADSO 2470980

CBA Mosquera

Este proyecto desarrolla las siguientes APIS :

-CafeteriaApiView:Esta API nos trae en una lista los datos que digitamos en la base de datos sql lite

-CafeteriaDetailApiView:Esta API nos trae el método get el cual nos trae las motos, método put el cual nos deja crear una nueva moto o editar, método delete el cual nos deja eliminar una moto.

-CafeteriaClasificacionApiView: Esta api es la que nos permite ver los productos por clasificación.

Para iniciar el proyecto debes tener instalado python, django, visual studio code luego entrar a la carpeta app_comercializadora y poner CMD en la url luego deber poner la siguiente linea ..\scripts\activate para activar el ambiente luego instalarás los requerimientos o librerias con la siguiente linea pip install -r requirements.txt el paso siguiente debes dar python manage.py runserver en el CMD te dara un link y tendras la siguiente vista

![image](https://user-images.githubusercontent.com/101758695/208263033-6d878613-525f-4086-b395-f0f7b92ead15.png)

Luego ingresamos con /api/

Vista principal.
![image](https://user-images.githubusercontent.com/101758695/208255294-1fc9e704-def1-425f-9712-81c806a97db7.png)

Se agrega un nuevo producto.
![image](https://user-images.githubusercontent.com/101758695/208255370-367b57bc-4e49-4aa7-a2ca-6ffa1aa57177.png)

Muestra el producto recien agregado con su id automatico.
![image](https://user-images.githubusercontent.com/101758695/208255389-afd69e59-c20f-424b-bc99-f28aa3f02002.png)

Se devuelve a la lista Cafeteria Api.   Se observa un quinto objeto.
![image](https://user-images.githubusercontent.com/101758695/208255477-f87597a5-3802-4b34-abae-c843f8d8dc7d.png)

Se ubica en el ultimo id. Y damos click en DELETE.
![image](https://user-images.githubusercontent.com/101758695/208255540-3c14cfdf-d89e-4870-9b57-9f2a27375ba3.png)

Se confirma en DELETE,  muestra la eliminación del producto.
![image](https://user-images.githubusercontent.com/101758695/208255564-324a66ba-e0a9-44ab-9be6-5bcb16a7d008.png)

Se devuelve a la lista y observa que el producto con id 5 fue eliminado ya no existe.
![image](https://user-images.githubusercontent.com/101758695/208255612-0d306fa6-7e8c-4dda-b5cf-bff76b923bf5.png)



