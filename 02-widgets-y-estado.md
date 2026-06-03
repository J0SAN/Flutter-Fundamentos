# 2. El Mundo de los Widgets y el Estado

En Flutter hay una regla de oro: **Todo es un Widget**. 

## ¿Qué es un Widget?
Un widget es un bloque de construcción. Imagina que estás armando un set de Lego: tienes piezas para hacer ventanas, ruedas y puertas. En Flutter, tienes piezas (widgets) para hacer textos, botones y márgenes. Estos bloques se conectan entre sí formando un "árbol".

### Widgets Esenciales para nuestra Práctica:
* **`Text` (Texto):** Sirve para mostrar palabras o párrafos en la pantalla.
* **`TextField` (Input/Entrada):** Es la caja de texto donde el usuario puede escribir información usando su teclado.
* **`ElevatedButton` (Botón):** Un botón clásico que, al ser presionado, ejecuta una acción (como guardar datos).
* **`ListView` (Lista):** Un contenedor especial que organiza elementos uno debajo del otro y permite deslizar la pantalla (hacer scroll) si hay muchos.

---

## El Ciclo de Vida: ¿Cambia o no cambia?

Para darle vida a nuestra aplicación, necesitamos entender cómo reaccionan los widgets. Se dividen en dos grandes familias:

### 1. StatelessWidget (Widgets sin estado)
Son estáticos e inmutables. Imagina una señal de "Alto" en la calle: una vez que se pinta y se coloca, no cambia su forma ni su mensaje, sin importar quién la mire. 
* **Se usa para:** Títulos, íconos o pantallas decorativas que no interactúan con el usuario.

### 2. StatefulWidget (Widgets con estado)
Son dinámicos y pueden cambiar. Imagina un semáforo: su estado cambia de verde a amarillo y luego a rojo dependiendo del tiempo. En Flutter, estos widgets tienen una memoria interna. Si el usuario escribe algo o presiona un botón, el widget detecta el cambio, avisa a la aplicación (usando una función llamada `setState`) y se vuelve a dibujar en la pantalla con la nueva información.
* **Se usa para:** Formularios, carritos de compras, listas dinámicas o cualquier cosa que deba actualizarse en tiempo real.
