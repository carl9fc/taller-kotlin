# RESPUESTAS — Taller Kotlin

## Cuestionario (15 respuestas)

1. val es inmutable, var es mutable.  
val nombre = "Ana"  
var edad = 20  

2. Interpolación permite insertar variables en strings:  
println("Hola $nombre")

3. Una función encapsula lógica reutilizable y evita repetir código.

4. Una función con retorno devuelve valor (Int, String, etc.), Unit no retorna nada.

5. Tipo de dato define qué guarda una variable: Int, Double, String, Boolean.

6. Dividir en funciones pequeñas facilita mantenimiento y lectura.

7. Clasificación con if/else:  
if (nota >= 90) "A"  
else if (nota >= 80) "B"  
else if (nota >= 70) "C"  
else "D"

8. when es mejor cuando hay muchos casos o rangos.

9. if puede devolver valor:  
val max = if (a > b) a else b

10. String no acepta null, String? sí.

11. Safe call evita error si es null:  
texto?.length

12. Elvis da valor por defecto:  
val len = texto?.length ?: 0

13. !! fuerza valor y puede lanzar error si es null.

14. Clase = molde, objeto = instancia.  
Propiedades: nombre, precio.  
Métodos: vender(), reponer().  
POO modela entidades reales.

15. Lambda:  
val doble: (Int)->Int = { x -> x*2 }  
Permiten pasar comportamiento como parámetro.  
Concepto más valioso: nullabilidad porque evita errores.

