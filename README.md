# PokeAPI Challenge - Kruger 馃榿
#### *Dicho reto se desarroll贸 con las siguientes tecnolog铆as*
#### *- HTML*
#### *- CSS => para normalizar estilos en todos los navegadores se us贸 'normalize.css' y para los prefijos propietarios se us贸 la p谩gina 'autoprefixer.github.io' *
#### *- Java Script Vainilla y Node JS => consumo de API por Fetch*
馃 Link de la Aplicacion : https://bryan-itsqmet.github.io/PokeApi-Kruger/

## 1. FRONTEND 馃こ
##### Se tomo como base el Wiraframe enviado al correo para el dise帽o de la misma. En el Css se us贸 display grid para mostrar los pokemons en 3 columnas y para el header se us贸 flexbox para que los elementos esten uno a lado de otro.
## 2. BACKEND 馃惐鈥嶐煆?
###### *LINK DE LA API :  https://my-json-server.typicode.com/Bryan-ITSQMET/API-poke-kruger*
nota : previamente a la construcci贸n de la api se necesita tener instalado node js.
#####<BR>路 Se utilizo un m贸dulo llamado JSON SERVER *(https://github.com/typicode/json-server)*
##### 路 Para subir la API se us贸 la p谩gina MY JSON SERVER *(https://my-json-server.typicode.com/)*
###  <BR> 2.1 Instalaci贸n y Ejecuci贸n de JSON SERVER 
##### 路 Abrimos la terminal y nos ubicamos en el directorio del proyecto
##### 路 Ejecutamos la linea `npm install -g json-server`
##### 路 En nuestro proyecto creamos un archivo con la extension .json , el cual vendr铆a a ser nuestra base de datos, va a contener nuestros endpoints con los datos que deseamos `db.json`
##### 路 Ejecutamos la linea `json-server -watch db.json` 
###  <BR> 2.2 Deploy de la API con MY JSON SERVER 
nota : previamente debemos haber subido nuestro archivo `db.json` a GitHub
##### 路 Visitamos el siguiente enlace https://my-json-server.typicode.com/'nombreUsuarioDeGit'/'nombreDelRepositorio' y lo reemplazamos con nuestros datos. En mi caso quedar铆a as铆 https://my-json-server.typicode.com/Bryan-ITSQMET/API-poke-kruger
## 3. FUNCIONALIDAD DE LA P脕GINA
##### La p谩gina web muestra la informacion de solo 10 pokemons que hay en la Base de Datos
##### Por cada Pokemon existe un bot贸n llamado 'mas detalles' el cual al hacer click se despliega otra p谩gina con m谩s informaci贸n del pokemon seleccionado. Para regresar a la p谩gina principal se da click en el bot贸n llamado 'home'
##### Se puede realizar busqueda de pokemons solo por el nombre del mismo (se puede buscar ya sea en min煤scula may煤scula o intercalado) por ejemplo 'pikachu'-'PIKACHU'-'Pikachu' y se despliega solo la informacion del pokemon buscado. 
##### Para buscar se da click en el bot贸n 'search' o se da enter una vez introduccido el nombre del pokemon. Para que nuevamente salga la informaci贸n de todos los pokemons se da click en el bot贸n llamado 'clear' 
