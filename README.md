# Calculadora-en-Python
Proyecto escolar el cual disfruté mucho haciéndolo, es un código simple pero jamás había hecho algo así 
```
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b


def multiplicar(a, b):
    return a * b


def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir entre 0"
    return a / b


def calculadora():
    print("Operaciones disponibles:")
    print("1. Sumar")
    print("2. Restar")
    print("3. Multiplicar")
    print("4. Dividir")

    operacion = input("Elige la operación (1/2/3/4): ")

    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))

    if operacion == '1':
        print(f"Resultado: {sumar(num1, num2)}")
    elif operacion == '2':
        print(f"Resultado: {restar(num1, num2)}")
    elif operacion == '3':
        print(f"Resultado: {multiplicar(num1, num2)}")
    elif operacion == '4':
        print(f"Resultado: {dividir(num1, num2)}")
    else:
        print("Operación no válida")
