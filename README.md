# Casos_Clinicos_P1

##Ejercicio 1: Alertas de glucemia
   
    Mostrar "ALERTAS DE GLUCEMIA "
    Leer N  / Número de lecturas
    suma ← 0
    
    Para i ← 1 Hasta N Hacer
        Leer glucosa  
        suma ← suma + glucosa
    Fin Para
    
    promedio ← suma / N
    
    Segun promedio Hacer
        Caso < 70:
            Mostrar "HIPOGLUCEMIA"
        Caso > 180:
            Mostrar "HIPERGLUCEMIA"
        Defecto:
            Mostrar "NORMAL"
    Fin Segun
## Ejercicio 2: Detección de arritmia simple
    Mostrar " DETECCIÓN DE ARRITMIA "
    Leer M  / Número de valores cardíacos
    contadorFuera ← 0
    
    Para j ← 1 Hasta M Hacer
        Leer frecuencia  
        Si frecuencia < 60 O frecuencia > 100 Entonces
            contadorFuera ← contadorFuera + 1
        Fin Si
    Fin Para
    
    Si contadorFuera > 3 Entonces
        Mostrar "POTENCIAL ARRITMIA"
    Sino
        Mostrar "Rítmico"
    Fin Si
