# Comentarios
Modulo de comentarios

Frontend
Para su correcto funcionamiento es necesario installar node_modules (npm install)
El proyecto de angular contiene ya el componente de comentarios en la ruta components/inicio/comentario (Opcional), pero de igual manera se puede crear lo necesario para obtener el resultado esperado.
El componente Comentario se queda con un ejemplo realizado (inconcluso) de como podria ser una posible solucion y con el metodo que recupera los datos arrojados por el backend para la pestaña de "historial", esto solo como un aporte de lo ya trabajado pero que no necesariamente debe de ser utilizado.

De igual manera ya tiene un servicio implementado en services/comentarios.service para la implementacion de los metodos que se requieran para obtener comunicacion con el backend para la correcta funcionalidad.
Ya estan creados los Models que posiblemente se necesiten para la implementacion, estos son clasificacion.model, comentario.model y usuario.model, esto fue implementado para poder recibir la respuesta del back, la cual es un arreglo de comentarios, estos solo se consideraron para realizar la pestaña de busqueda.

En el componente llamado caso (components/inicio/caso), se puede encontrar un paginador ya implementado, el cual podemos reutilizar para que este allegado al diseño del mismo, ya que en el prototipo compartido el diseño de este paginador es diferente, por ende se recomienda utilizar el ya implementado con fines de estandarización en el estilo.
De igual manera en el componente Caso es el que brinda el detalle del caso, por ende se esta inyectando el componente Comentarios en el lugar correspondiente.

Estilos
El proyecto utiliza el framework Bootstrap versión 3.3.0.para los estilos, pero no se limita a solo utilizar los estilos predefinidos del mismo, se da la posibilidad de crear sus propias clases de estilo para llegar a los resultados.
El framework ya esta diseñado para crear estilos en especifico, allegados a la estandarización de la empresa, en la siguiente ubicación se puede acceder a ellos y si es conveniente utilizar alguno de esos estilos.
Pero de igual manera no se esta sujeto a solo utilizar estos estilos.
https://www.gob.mx/guias/grafica#alertas
(Para crear la alerta que se da al realizar la transición entre las pestañas y no haber guardar lo ingresado) ya existe en la pagina antes mencionada.



