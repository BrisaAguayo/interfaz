
**Código**

```
Aguayo Virgen Brisa Julianna

.begin:
    mov Ra, 10         ; Cargar el primer número en Ra
    mov Rb, 20         ; Cargar el segundo número en Rb

.add_numbers:
    add Ra, Rb         ; Sumar Rb a Ra y almacenar el resultado en Ra

.store_result:
    mov Rc, Ra         ; Mover el resultado a Rc (si Rc representa una ubicación en memoria)

.end:
    jmp .end           ; Bucle infinito para detener el programa
````

**Explicación**

Este código en ensamblador carga el valor 10 en Ra y 20 en Rb, 
luego suma ambos valores y almacena el resultado en Ra. Después,
mueve el resultado a Rc y entra en un bucle infinito con jmp .end, 
evitando que el programa continúe ejecutando otras instrucciones.

![Captura de pantalla 2025-03-03 144542](https://github.com/user-attachments/assets/ee3e6588-f139-4867-a38d-9711590da24c)
