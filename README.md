![Captura de Pantalla 2025-03-16 a la(s) 23 34 29](https://github.com/user-attachments/assets/f7e6787a-218f-4557-84b2-1bcf1799840d)

Se creo una lista vacía llamada "amigos". Esta lista se utilizará para almacenar los nombres de las personas que participarán en el sorteo del amigo secreto.

![Sin título](https://github.com/user-attachments/assets/91d29e3d-48ee-46db-b71a-2145a61a78ab)

Esta parte del codigo obtiene el nombre del amigo que el usuario ha escrito en un campo de texto en la página web y verifica si el nombre está vacío. Si lo está, muestra una alerta pidiendo al usuario que ingrese un nombre. Si el nombre no está vacío, lo añade al final de la lista "amigos" ademas borra el nombre del campo de texto para que el usuario pueda ingresar otro nombre y tambien Llama a la función "renderizarAmigos" para mostrar la lista de amigos actualizada en la página.

![Captura de Pantalla 2025-03-16 a la(s) 23 46 03](https://github.com/user-attachments/assets/d5ca67b7-9f6c-4602-9845-fb6e2c44c4c2)

Esto obtiene el elemento de la página web donde se mostrará la lista de amigos, ademas que permite borrar todo el contenido anterior de esa lista, recorre la lista "amigos", para cada nombre, crea un nuevo elemento de lista (un "li"). esto permite poner el nombre del amigo dentro del elemento de lista y Añade el elemento de lista a la lista que se muestra en la página.

![Captura de Pantalla 2025-03-16 a la(s) 23 50 03](https://github.com/user-attachments/assets/497f69ec-722b-4db0-8fe5-628f855935e8)

Por ultimo la parte de este codigo verifica si la lista "amigos" está vacía, si lo está, muestra una alerta diciendo que no hay amigos para sortear. Si la lista no está vacía, genera un número aleatorio que se utiliza para seleccionar un amigo al azar de la lista. Obtiene el nombre del amigo seleccionado y muestra el nombre del amigo secreto y limpia la lista para poder iniciar de nuevo el juego.
