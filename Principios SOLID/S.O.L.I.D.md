
# Principios S.O.L.I.D.

**S => Principio de responsabilidad única.**

Una clase solo tiene que tener una única responsabilidad. Es decir, solo sirve para hacer una cosa. Ya que si no se cumple esto, una modificación puede afectar a numerosos componentes o clases.
`Ejemplo:` 
Si mi clase impresoraFactura solo tiene métodos para imprimirFacturas(), no recopilarInformes()

**O => (Open -Closed (Principio de abierto-cerrado))**

Una clase abierta para su extensión pero cerrada su modificación.
`Ejemplo:`
Si necesitamos añadir otro método en la clase por cambios de requisitos, la clase no se modifica, sino creamos otra que extienda de esta para meter le nuevo método.

**L => Principio de Liskov**

Todas las implementaciones deben cumplir correctamente la interfaz.
`Ejemplo:`
 Para que el pato tenga ‘nadar’ y no el gato, se crea otra interfaz que hereda de la 1ª para meter nadar()
 
![image](https://github.com/sanchezma-dev/documentation-tech/assets/125487997/3992bfe9-a27c-4798-859c-b43ce78f93aa)

	
**I => Segregación de interfaz**

Interfaces con demasiadas operaciones no cumple este principio. Hay que hacer interfaces más pequeñas y con menos métodos

**D => Principio de inversión de dependencia**

Hay que usar abstracciones mediante interfaces y clases abstractas
`Ejemplo:`
Interfaz Impresora no debe tener un constructor factura, debería aceptar una dependencia abstracta para que su herencias puedan tener su constructor particular



