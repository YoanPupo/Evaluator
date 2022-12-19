# Evaluator
Biblioteca de evaluacion de expresiones aritmeticas con variables,usa la tecnica de la evaluacion postfija
. Opera con valores de punto flotante de 64 bits (double),permite introducir un String con la expresion y
 obtener el resultado de evaluarla, o consultar los valores de las variables. Aun en desarrollo, puede contener errores
Se incluye un codigo de ejemplo, HyperMat, una aplicacion para obtener graficos de funciones y ecuaciones parametricas
En coordenadas cartesianas o polares.
He aqui un ejemplo de las expresiones que puede evaluar:
22-sin(13/4)*12^2+(fact(5)-12*3)
la biblioteca evalua solo una linea pero conserva los valores de las variables,
Asi que pueden analizarse varias lineas:
base=22
otro=15
total=34*base/otro
print(total)
