# Tarea 1

Escribir una función en Python para verificar si un String es *palíndromo*. Un palíndromo es una palabra que puede leerse igual de derecha a izquierda y viceversa.
Por ejemplo, "radar" es un palíndromo.

Su función debe tener la siguiente estructura:

### def function palindromo ( palabra ) :

y debe devolver ("return") un valor Booleano.

**Entrega: lunes 21 de agosto.
##Steeven Petit-Homme
##Solucion Tarea 1

def palindrome(word):
    if word == word[::-1]:
        print('True')
    else:
        print('False')
palindrome('palabra')## Test Cases
palindrome('radar')
palindrome('abcdeedcba')
