# Break - Continue

## Descripción del Programa
<p align="justify">Este programa demuestra el uso de las instrucciones de control de flujo break y continue en Python a través de dos ejemplos distintos.</p>

## Uso de la instrucción break
<p align="justify">El primer ejemplo inicia un bucle for que itera sobre un rango de números del 1 al 5. Dentro del bucle, hay una instrucción if que verifica si el valor actual de i es igual a 3. Si es así, la instrucción break se ejecuta y termina el bucle inmediatamente. Por lo tanto, los números 1 y 2 se imprimen desde dentro del bucle, pero cuando i se convierte en 3, el bucle se rompe y se imprime “Fuera del bucle”.</p>

## Uso de la instrucción continue
<p align="justify">El segundo ejemplo es similar al anterior, pero en lugar de break, usa la instrucción continue. Cuando i es igual a 3, en lugar de terminar el bucle por completo, continue termina la iteración actual y pasa a la siguiente iteración del bucle. Por lo tanto, se imprimen los números 1, 2, 4 y 5 desde dentro del bucle. El número 3 se omite porque cuando i es 3, la instrucción continue evita que se ejecute el resto del código en el bucle.</p>

## Diferencia entre break y continue
<p align="justify">La principal diferencia entre break y continue radica en cómo afectan el flujo de control dentro de un bucle. La instrucción break termina el bucle por completo y transfiere la ejecución a la primera declaración después del bucle. Por otro lado, la instrucción continue termina la iteración actual y transfiere la ejecución a la próxima iteración del bucle.</p>
