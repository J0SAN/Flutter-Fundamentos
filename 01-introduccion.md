# 1. Introducción a Flutter y Dart

Antes de escribir código, es fundamental entender las dos piezas clave que hacen que todo funcione: **el motor (Dart)** y **la carrocería (Flutter)**.

## ¿Qué es Dart? (El Motor)
Dart es el lenguaje de programación creado por Google. Piensa en Dart como el idioma oficial en el que le damos instrucciones a nuestra aplicación. 
* **Es fácil de leer:** Al compartir una estructura orientada a objetos, su sintaxis resulta muy natural y familiar al venir de entornos como C# o JavaScript.
* **Es seguro:** Tiene características modernas como el *Null Safety*, que evitan que la aplicación colapse inesperadamente por valores nulos o vacíos en tiempo de ejecución.

**Ejemplo básico de Dart:**
```dart
// Una función tradicional y variables tipadas
void main() {
  String mensaje = 'Hola, desarrollador';
  int anio = 2026;
  
  // Interpolación de variables directa en el texto
  print('$mensaje en el año $anio'); 
}
```

## ¿Qué es Flutter? (La Carrocería y el Diseño)
Flutter no es un lenguaje, es un **Framework** (una caja de herramientas de software). Utiliza el lenguaje Dart para construir la interfaz visual de la aplicación.
* **Multiplataforma:** Su mayor ventaja es que escribes el código una sola vez y Flutter se encarga de traducirlo para que funcione en Android, iOS, páginas web e incluso aplicaciones de escritorio.
* **Pintor de pantallas:** A diferencia de otras tecnologías que usan los botones nativos del teléfono, Flutter dibuja cada pixel en la pantalla desde cero. Esto garantiza que tu aplicación se vea exactamente igual en cualquier dispositivo.
