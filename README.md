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
