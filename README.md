### Taller 1 - Nicholas Santamaria

### Clase Logica
La logica es la clase donde se desarrolla el proceso general del programa

Metodos:
pintar()
presionar() = Cuando el usuario da clic en alguna de las zonas sensibles predeterminadas se genera una interaccion, por ejemplo en este taller (al presionar las burbujas desaparecen o explotan)
agregarLluvia() = Este metodo genera el tiempo en el que debe caer la lluvia de rayos y su posicion que es random, tambien remueve cuando sale del lienzo y vuelve a generarlo desde la parte superior del lienzo
ArrayList<Burbuja> = Lista de burbujas que se deben agregar en el codigo y la parte grafica

### Clase Objeto
Clase abstracta que cuenta con diferentes atributos que los pueden utilizar sus clases hijas
Atributos:
x: posicion en x de las clases hijas
y: posicion en y de las clases hijas
radio: dimensiones de algunos objetos 
ancho y alto: dimensiones del fondo de la aplicacion

### Clase Caldero
Clase hija de la clase Objeto donde ayudara a la Logica a pintar un diseño de un caldero con sus respectivos atributos donde habra una interaccion
Metodos:
pintar()

### Clase Lluvia
Clase hija de la clase Objeto donde ayudara a la Logica a pintar un diseño de una lluvia de rayos con sus respectivos atributos donde habra una interaccion
Metodos:
pintar()

### Clase Esfera
Clase hija de la clase Objeto donde ayudara a la Logica a pintar un diseño de algunas esferas con sus respectivos atributos donde habra una interaccion
Metodos:
pintar()

### Clase Rayo
Clase hija de la clase Objeto donde ayudara a la Logica a pintar un diseño de rayo con sus respectivos atributos donde habra una interaccion
Metodos:
pintar()


### Clase Libro
Fondo de la aplicacion que se pinta
Metodos:
pintar()

### Clase Escoba
Esta clase pintara una escoba hecha con figuras geometricas que se pintara y se podra mover con clic presionado
Metodos:
pintar()
mover()


### Clase Burbuja
Esta clase pintara burbuja hecha con figuras geometricas que se pintara y se podra mover por el lienzo con direccion random
Metodos:
pintar()
mover()