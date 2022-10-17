# teoria-cuantica-basica-

acontinuacion se desarrollaran de manera secuencial los ejercicios propuestos en "TEORÍA CUÁNTICA BÁSICA, OBSERVABLES Y MEDIDAS" y en este apartado se explicara brevemente el funcionamiento y se daran algunos casos base para verificar su funcionamiento 

1. El sistema debe calcular la probabilidad de encontrarlo en una posición en particular.
para calcular la probabilidad se debe hallar la norma del vector y luego siguiendo la formula se debe tomar la posicion al cuadrado y dividirlo con la norma al cuadrado

vector = [3, 1, -2, 1, 2]
    ket = [3-1, -2, 1, 2] ---> se puede usar cada posicion del ket 
   
2. El sistema si se le da otro vector Ket debe buscar la probabilidad de transitar del primer vector al segundo
con dos vectores y la funcion probabilidad_transito se calcula facilmente 

    vector_1 = [2,3,1,2]
    vector_2 = [2-3j, 1+2j]
    
RETOS DE PROGRAMACIÓN DEL CAPÍTULO 4.
1. Amplitud de transición. El sistema puede recibir dos vectores y calcular la probabilidad de transitar de el uno al otro después de hacer la observación

    up = [3,-4]
    down = [7, 2]
    
2. Ahora con una matriz que describa un observable y un vector ket, el sistema revisa que la matriz sea hermitiana, y si lo es, calcula la media y la varianza del observable en el estado dado.


