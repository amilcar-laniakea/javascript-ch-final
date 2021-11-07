# javascript-ch-final
Proyecto JA Coderhouse Final

Proyecto Final de Coderouse, camada 23275

con tutoria de Mauro Goyeneche

Aplicacion basica de Javascript simulando un carrito de compras con la funcionalidad primordial, con un dom que carga y verifica si hay datos guardados en localstorage en relacion a un array del carrito de compras y realiza todas las operaciones perminentes en cuanto a mostrar cantidad, precio y productos con status real en la bolca/carrito de compras.

La data es traida de firebase firestore de forma asincrona con una peticion la cual en front muestra un mensaje loading mientras se carga.

Al momento de agregar un producto a la bolsa de compra, un consructor (clase) tupo proycto es invocado para crear el articulo que sera pusheado al array del carrito, por temas de seguridad, posee todas sus validaciones en cuanto a temas de stock, cantidad de proeuctos a agregar a la bolsa, luego de agregar el proeycto se verifica stock y valores negativos ademas de un boton de vaciar carrito que tambien limpia el localstorage para posteriormente actualizar el dom de acuerdo a la interaccion dada por el usuario.

Finalmente, hay un simulador de proceso de compras la cual pide al usuario su email y al momento de invocar una respuesta satisfactoria, reinicia los valores de localstorage y del dom para una nueva compra.

proyecto basicamente sencillo, algo muy basico a los realizado por por en el curso de react, lo cal dejo el repo y el link de la tienda en heroku:

Link APP React: http://laniakea-store.herokuapp.com/

Repo: https://github.com/amilcar-laniakea/laniakea-store.git
