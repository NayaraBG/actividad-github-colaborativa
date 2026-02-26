# actividad-github-colaborativa


Compilar:
javac -d out src/Calculator.java

Ejecutar:
java -cp out Calculator add 2 3

Ejemplos de uso:

add:
java -cp out Calculator add 5 3
Salida esperada: 8

sub:
java -cp out Calculator sub 10 4
Salida esperada: 6

div:
java -cp out Calculator div 20 5
Salida esperada: 4


Errores típicos:

1. División por cero
java -cp out Calculator div 10 0
Error: no se puede dividir por cero

2. Número incorrecto de argumentos
java -cp out Calculator add 5
Error: se requieren exactamente 2 argumentos numéricos