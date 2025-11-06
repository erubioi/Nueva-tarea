"# Nueva-tarea" 
print ("Hola")
import random
def adivina_numero():
    numero_secreto = random.randint(1, 20) #Genera numero entre 1 y 20
    contador = 0
    print("Biembenido al Juego: Adivina el numero (1 - 20)")
    while True:
        intento = int(input("Ingresa tu Intento: "))
        contador += 1
        if intento > numero_secreto:
            print("Muy Alto")
        elif intento < numero_secreto:
            print("Muy Bajo")
        else:
            print(f"Correcto Adivinaste en {contador} intentos.")
            
            print("juego terminado")#<- mensaje final
             
                        
            break # <-salir despues de mostrarlo


            
#ejecuta el juego
adivina_numero()