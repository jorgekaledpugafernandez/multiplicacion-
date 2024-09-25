Crear un codigo donde solicite tres numeros y se realice la multiplicacion de ellos.

# 1-multiplicacion 
#pido tres numeros al usario
num1 = float(input("Dime el primer numero: "))#le pide al usario que ingrese un numero,convierte la entrada en un numero decimal#le pide al usario que ingrese un numero,convierte la entrada en un numero decimal
num2 = float(input("Dime el segundo numero: "))#le pide al usario que ingrese un numero,convierte la entrada en un numero decimal#le pide al usario que ingrese un numero,convierte la entrada en un numero decimal
num3 = float(input("Dime el tercero numero: "))#le pide al usario que ingrese un numero,convierte la entrada en un numero decimal
#multi<plico los tres numeros
resultados = num1 * num2 * num3 
print("El resultados de multiplicar", num1, "por", num2, "por", num3,"es:", resultados)#muestra en un mensaje en pantalla# multiplicacion-
![image](https://github.com/user-attachments/assets/f27ed515-6228-431b-94e0-51101b68d15d)


# 2-kilómetros
#le pido al usario los kilometros y los litros
km_recorridos = float(input("¿Cuantos kilometros recorriste? "))#para pedirle al usario la cantidad de kilometros recorridos
litros_consumidos =float(input("¿Cuantos litros de combustible usaste"))#para asegurame de que los datos ingresados se traten como numero decimales

#Calculo el consumo por kiloetro 
consumo_por_km = litros_consumidos / km_recorridos#muestra el calculo del consumo de combustible por kilometro

#muestra el resultados por kilometros a 2 decimales
print("El consumo de combustible por kilometros es:", round(consumo_por_km, 2), "litros/km")#el numero a 2 dicimales 
![image](https://github.com/user-attachments/assets/490f487d-22f8-4e87-b5b1-2f433e24ad58)


# 3-elsius tfahrenheit
#pido la temperatura en Fahrenheit
fahrenheit = float(input("Ingresa la temperatura en grados fahrenheit: "))#pide al usario que ingrese la temperatuera 

#Calcular la temperatura en celsius
celsius = (5/9) * (fahrenheit - 32)

#Mostrar el resultado 
print("La temperatura en grados celsius es:",celsius,":.2f°C")
![image](https://github.com/user-attachments/assets/48202f7d-9409-463e-836d-7c75c047128c)

# 4-promedio 
#Pedimos al usario que ingrese tres numnero
num1 = float(input("Ingresa el primer numero: ")) #aqui se imprime la funcion del programa
num2 = float(input("Ingresa el segundo numero: ")) #aqui se imprime la funcion del programa
num3 = float(input("Ingresa el tercero numero: ")) #aqui se imprime la funcion del programa

#calculamos el promedio 
promedio = (num1 + num2 + num3) / num3
 
#mostramos el promedio
print("El promedio de los tres numeros es:", promedio) #aqui sac el promedio total
![image](https://github.com/user-attachments/assets/0f53a0be-58fd-45ed-aa0b-d426878bf24c)

# 5-pida al usuario adivinarlo
#almacenamos el numero secreto
numero_secretos = 90*20 #muestra que saca el numero de advinanza
#puedes cambiar el numero que quieras

#pedimos al usario que adivne el numero
adivinanza = int(input("adivina el numero: "))# muestra que al usario si es correcto o incorectos o advinanza 

#Verficamos si el numero es correcto 
if adivinanza == numero_secretos:
  print("¡adivinaste!")muestra que al usario si es correcto o incorectos o advinanza 
else:
  print("¡fellaste! el numero era", numero_secretos)muestra que al usario si es correcto o incorectos o advinanza 
  ![image](https://github.com/user-attachments/assets/a6fe2261-c52d-43fa-a5ab-8fc73a889899)
