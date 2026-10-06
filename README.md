# Investigación y comparación: condicionales en PHP

## Código

```php
<?php
// Abre el bloque de código PHP (obligatorio al inicio del archivo)

// Declaramos la variable edad con un valor fijo
$edad = 20;

// Comprobamos si la edad es mayor o igual que 18
if ($edad >= 18) {
    // Se ejecuta si la condición es verdadera
    echo "Mayor de edad\n";
} else {
    // Se ejecuta si la condición es falsa
    echo "Menor de edad\n";
}
```

## 1. ¿Cómo se declara la variable?

Con el símbolo `$` delante del nombre: `$edad = 20;`. No hay que indicar el tipo, PHP lo deduce solo, igual que Python.

## 2. ¿Cómo se muestra información por consola?

Con `echo` y el texto entre comillas. A diferencia de `print()` en Python, no añade salto de línea, así que lo ponemos nosotros con `\n`.

## 3. ¿Cómo se delimitan los bloques de código?

Con llaves `{ }`. En Python el bloque lo marcan los dos puntos y la indentación, que es obligatoria. En PHP indentar es opcional: solo sirve para que el código se lea mejor.

## 4. ¿Qué símbolos o palabras cambian respecto a Python?

- La variable lleva `$` delante.
- La condición va entre paréntesis.
- Los `:` se cambian por `{ }`.
- `print()` pasa a ser `echo`.
- Cada instrucción acaba en `;`.

Se mantienen igual `if`, `else` y el operador `>=`.

## 5. ¿Qué decisiones se mantienen? Algoritmo en castellano

La lógica es la misma: una sola decisión con dos caminos y ninguna repetición. Se guarda una edad y se comprueba si es mayor o igual que 18. Si lo es, se muestra "Mayor de edad"; si no, "Menor de edad". Solo se ejecuta uno de los dos mensajes.

## 6. ¿Habéis necesitado algún elemento adicional?

No hace falta una función principal: PHP ejecuta el código de arriba abajo, como Python. Lo único extra es la etiqueta `<?php` al inicio del archivo, guardarlo como `.php` y ejecutarlo con `php edad.php`. Nada de esto forma parte del condicional, que es solo el bloque `if (...) { } else { }`.