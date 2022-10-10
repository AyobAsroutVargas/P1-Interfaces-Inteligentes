# P1-Interfaces-Inteligentes

# Incluir objetos 3D básicos.

Para ello simplemente debemos acceder en el menú a GameObject > 3D object > (el objeto que  queramos, por ejemplo cube o sphere)

# Incluir  en el proyecto el paquete Starter Assets.

Para ello debemos contar con el paquete entre los assests asociados a nuestra cuenta, en caso de que no sea asi bastará con añadirlo a nuestros assets desde la asset store. Una vez contamos con el asset usando el package manager (Window > Package Manager) lo descargamos e importamos a nuestro proyecto

# Incluir un objeto libre de la Asset Store que no sea de los Starter Assets.

Al igual que en el paso anterior importamos un asset (en este caso se usó Nature Starter kit 2) e incluimos algun objeto de los que viene incluido en el. En este caso se incluyeron prefabs de 4 arboles.

# Crear un terreno (opcional).

Accedemos al menú Gameobject > 3D object > Terrain y se nos creará un terreno. Si queremos podemos usar las herramientas de terreno para modificarlo. En este caso solamente se usó las opciones de elevar terreno y pintar texturas.

# Cada objeto debe tener una etiqueta que lo identifique.

Para cada objeto usado al verse en el inspector debajo de su nombre podemos ver un campo llamado tag, usando el menú drop-down le otorgaremos el tag oportuno a cada objeto. Si no existiera el tag que estamos buscando podemos añadirlo usando la ultima opcion que dice Add tag. Esta nos llevara a una pestaña llamada Tags & Layers en la que entre otras cosas podremos añadir los tags que creamos convenientes.

# Utilizar prefabs de Starter Asset FPS o Third Person

Simplemente debemos arrastrar algun prefab presente en alguno de los assets a la escena para incluirlos en ella. En este caso se ha usado el prefab NestedParentArmature que contiene lo necesario para que funcione el controlador en tercera persona del starter pack. Una vez incluido se ha de hacer click derecho sobre el asset y seleccionar Prefab > unpack. Luego simplemente debemos eliminar aquellos elementos que no vayan a ser usados, en este caso no se ha usado la UI incluida

# Agregar un script que escriba en la consola los objetos que se han utilizado

En este caso se ha creado un GameObject vacio con un script que en Start busca las referencias de todos los Gameobjects presentes en la escena usando la función UnityEngine.Object.FindObjectsOfType<GameObject>(); Está devuelve un array de Gameobjcets con todos los objetos de la escena. Luego, tambien en Start, hacemos un bucle foreach que recorra los objetos y por cada uno imrpima su nombre.

# Gif animado de la ejecución
  
  ![](name-of-giphy.gif)
  
