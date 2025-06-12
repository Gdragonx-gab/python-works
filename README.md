print("hola xdxdxdx") #esto es para mostrar la frase escrita en a pagina
'''para escribir con los tres puntitos se tiene que cerrar con lo mismo para que sea bien''' #otra forma de hacer comentario
\n #es codigo para hacer un aparte
\t #es igual a 4 espacios (un tab)
"#" es para hacer un comentario (no va aparecer en la pagina, es algo invicible, un ccomentario para guiar o dejar algo para saber de un codigo)

'''prueba de los codigos explicados'''
print("hola xd\nawaawa\n\n\n\nkjasdkja\najsdjsahj") #este es un ejemplo de lo que seria los codigos y como funcionan.
#este ejemplo muestra como se puede escriir un comentario bajo del otro y haciendo un espacio mas de distancia como si fuera otro guion

print("xd")

print("jsadjsad") #otra alternativa xd


print("datos de estudiantes:\n\tNombre\t\tEdad\tClasificacion\n\twalter white\t20\tA\n\tJessie pickman\t25\tb")

print("Marzo 2025\nDom\tLun\tMar\tMie\tJue\tVie\tSab\n\t\t\t\t\t1\t2\n3\t4\t5\t6\t7\t8\t9\n10\t11\t12\t13\t14\t15\t16\n17\t18\t19\t20\t21\t22\t23\n24\t25\t26\t27\t28\t29\t30\n31")

print("\t\t       CALCULADORA\n\t\t _______________________\n\t\t|\t\t\t|\n\t\t|\t\t\t|\n\t\t|_______________________|\n\t\t|  7  |  8  |  9  |  +  |\n\t\t|_____|_____|_____|_____|\n\t\t|  4  |  5  |  6  |  -  |\n\t\t|_____|_____|_____|_____|\n\t\t|  1  |  2  |  3  |  *  |\n\t\t|_____|_____|_____|_____|\n\t\t|         0       |  /  |\n\t\t|_________________|_____|\n\t\t\t[=]  [c]")


print("\t     ﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖ \n\t        ╤╤╤╤╤╤╤╤╤╤\n﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾▒▒▒◄≠ŤҐΣЛÐД≠►▒▒▒﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿\n\t     ﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖﬖ \n\ningrese los productos que desea comprar")

producto1=input("ingrese producto aqui:")
producto2=input("ingrese producto aqui:")
producto3=input("ingrese producto aqui:")
producto4=input("ingrese producto aqui:")
producto5=input("ingrese producto aqui:")
print("\n\n")

precio1=input("ingrese precio producto 1:")
precio2=input("ingrese precio producto 2:")
precio3=input("ingrese precio producto 3:")
precio4=input("ingrese precio producto 4:")
precio5=input("ingrese precio producto 5:")
print("\nproductos:\n\n ● "+producto1+": $"+precio1+"\n ● "+producto2+": $"+precio2+"\n ● "+producto3+": $"+precio3+"\n ● "+producto4+": $"+precio4+"\n ● "+producto5+": $"+precio5+"\n\n﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾﴾☺﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿﴿")

from ctypes import string_at
años = 29 # esto es un entero (Int)
nombre = "Gabriel" # esto es un string (Str)
precio = 69.4 # esto es un float (float) un decimal
años_dos = años + 10 #es un calculo
print("var original:",años,"var original + 10:",años_dos) #un texto mas un calculo
print("los años son: " +str(años)) #es un texto ( para que un numero entero o decimal funcione dentro de un strim se necesita escribir "+str")
#la coma (,) funciona como "+str"

caracteres de calculos:
+, -, *, /, **(este es para hacer una potencia ( calcular un numero mismo por la cantidad que se quiera))

numero1 = 23
numero2 = 53
print("resultado:",numero1 + +numero2)

numero3 = numero1 + numero2

print("resultado es:",numero3 + 25)

medida=input("ingresar la medida de un lado de un cuadrado para calcular perimetro: ")
total = int(medida) * 4
print("tu resultado es: "+str(total))


producto = input ("precio del producto: ")
cantidad = input ("cantidad de productos: ")
total = int(producto)* int(cantidad)
print("total de compra: ""$"+str(total))

precios1 = input("ingresar precio producto1: ")
precios2 = input("ingresar precio producto2: ")
precios3 = input("ingresar precio producto3: ")
total = (float(precios1) + float(precios2) + float(precios3)) * 1.21

print("\nEl total mas IVA incluido (%21): " +str(total))


comensales = input("agregar cantidad de comensales:")
entrada = input("ingresar precio entrada:")
bebida = input("agregar total precio bebidas consumidas:")
plato = input("agregar total precio de los platos consumidos:")
postre = input("agregar total precio postres consumidos:")
calculo = (float(bebida) + float(plato) + float(postre) + float(entrada)) / int(comensales)
total = calculo
print("el total que debe pagar cada comensal es de:" +str(total))



producto1 = float(input("ingresar producto precio:"))
cantidad1 = int(input("cantidad de productos 1:"))
producto2 = float(input("ingresar producto precio:"))
cantidad2 = int(input("cantidad de productos 2:"))
producto3 = float(input("ingresar producto precio:"))
cantidad3 = int(input("cantidad de productos 3:"))
total1 = producto1 * cantidad1
total2 = producto2 * cantidad2
total3 = producto3 * cantidad3
totalCompra = total1 + total2 + total3
totalIVA = totalCompra * 1.21
print("\n\n•RESULTADO DE LA COMPRA:\n\n precio del producto1:",producto1,"\n cantidad de productos:",cantidad1,"\n precio del producto2:",producto2,"\n cantidad de productos:",cantidad2,"\n precio del producto3:",producto3,"\n cantidad de productos:",cantidad3,"\n total de la compra:",totalCompra,"\n total de la compra con IVA incluido:" ,totalIVA,)



nombre1 = input("ingresar nombre empleado1: ")
sueldoNombre11 =float(input("ingresar sueldo: "))
sueldoNombre12 =float(input("ingresar sueldo: "))
sueldoNombre13 =float(input("ingresar sueldo: "))
nombre2 = input("ingresar nombre empleado2: ")
sueldoNombre21 =float(input("ingresar sueldo: "))
sueldoNombre22 =float(input("ingresar sueldo: "))
sueldoNombre23 =float(input("ingresar sueldo: "))
nombre3 = input("ingresar nombre empleado3: ")
sueldoNombre31 =float(input("ingresar sueldo: "))
sueldoNombre32 =float(input("ingresar sueldo: "))
sueldoNombre33 =float(input("ingresar sueldo: "))

total1 = sueldoNombre11 + sueldoNombre12 + sueldoNombre13
total2 = sueldoNombre21 + sueldoNombre22 + sueldoNombre23
total3 = sueldoNombre31 + sueldoNombre32 + sueldoNombre33
print("\n\n")
print("TOTAL SUELDO ULTIMOS 3 MESES:\n\n",nombre1,"\nsueldo mes 1:",sueldoNombre11,"\nsueldo mes 2:",sueldoNombre12,"\nsueldo mes 3:",sueldoNombre13,"\n\n",nombre2,"\nsueldo mes 1:",sueldoNombre21,"\nsueldo mes 2:",sueldoNombre22,"\nsueldo mes 3:",sueldoNombre23,"\n\n",nombre3,"\n\nsueldo mes 1:",sueldoNombre31,"\nsueldo mes 2:",sueldoNombre32,"\nsueldo mes 3:",sueldoNombre33,"\n\nTOTAL COMPLETO DE CADA SUELDO:\n\nSueldo empleado 1:",total1,"\nsueldo empleado 2:",total2,"\nsueldo empleado 3:",total3,"")

aceite1 = float(input("ingresar ganancia aceite dia 1: "))
aceite3 = float(input("ingresar ganancia aceite dia 2: "))
aceite2 = float(input("ingresar ganancia aceite dia 3: "))
aceite4 = float(input("ingresar ganancia aceite dia 4: "))
aceite5 = float(input("ingresar ganancia aceite dia 5: "))
print("\n\n")
shampoo1 = float(input("ingresar ganancia shampoo dia 1: "))
shampoo2 = float(input("ingresar ganancia shampoo dia 2: "))
shampoo3 = float(input("ingresar ganancia shampoo dia 3: "))
shampoo4 = float(input("ingresar ganancia  hampoo dia 4: "))
shampoo5 = float(input("ingresar ganancia shampoo dia 5: "))
print ("\n\n")
harina1 = float(input("ingresar ganancia harina dia 1: "))
harina2 = float(input("ingresar ganancia harina dia 2: "))
harina3 = float(input("ingresar ganancia harina dia 3: "))
harina4 = float(input("ingresar ganancia harina dia 4: "))
harina5 = float(input("ingresar ganancia harina dia 5: "))
totalAceite = aceite1 * 10 / 100
totalAceite2 = aceite2 *10 / 100
totalAceite3 = aceite3 *10 / 100
totalAceite4 = aceite4 *10 / 100
totalAceite5 = aceite5 *10 / 100

print("total ganancia de productos: \n\n\n Producto: Aceite(%10)\n ")
print("ganancia dia 1:",totalAceite)
print("ganancia dia 2:",totalAceite2)
print("ganancia dia 3:",totalAceite3)
print("ganancia dia 4:",totalAceite4)
print("ganancia dia 5:",totalAceite5)
totalShampoo1 = shampoo1 * 15 / 100
totalShampoo2 = shampoo2 * 15 / 100
totalShampoo3 = shampoo3 * 15 / 100
totalShampoo4 = shampoo4 * 15 / 100
totalShampoo5 = shampoo5 * 15 / 100
print(" \n\nProducto: Shampoo(%15)\n ")
print("ganancia dia 1:",totalShampoo1)
print("ganancia dia 2:",totalShampoo2)
print("ganancia dia 3:",totalShampoo3)
print("ganancia dia 4:",totalShampoo4)
print("ganancia dia 5:",totalShampoo5)
totalHarina1 = harina1 * 7 / 100
totalHarina2 = harina2 * 7 / 100
totalHarina3 = harina3 * 7 / 100
totalHarina4 = harina4 * 7 / 100
totalHarina5 = harina5 * 7 / 100
print(" \n\nProducto: Harina(%7)\n ")
print("ganancia dia 1:",totalHarina1)
print("ganancia dia 2:",totalHarina2)
print("ganancia dia 3:",totalHarina3)
print("ganancia dia 4:",totalHarina4)
print("ganancia dia 5:",totalHarina5)



limento =float(input("\t\t\tGASTOS MENSUALES\n\nalimentacion: "))
vivienda =float(input("vivienda: "))
transporte =float(input("transporte: "))
entretenimiento =float(input("entretenimiento: "))
salud =float(input("salud: "))

totalmes = alimento + vivienda + transporte + entretenimiento + salud
print("\nTotal gastado en el mes: " ,totalmes)
print()



IG/ELSE:



dad = int(input("ingresar edad: "))
if edad >=18:
  print("tu edad es: ",edad)
  print("sos mayor de edad")
else:
  print("tu edad es: ",edad)
  print("sos menor de edad")


  numero = int(input("ingresar un numero: "))
if numero >0:
  print("tu numero: ",numero)
  print("es un numero positivo")
else:
  print("tu numero: ",numero)
  print("tu numero es negativo")


  numero1 = int(input("ingresar un numero: "))
numero2 = int(input("ingresar un numero: "))
if numero1 == numero2:
  print("numeros elegidos: ",numero1, "y",numero2,)
  print("el numero:" ,numero1, "es igual a:",numero2,)
else:
  print("numeros elegidos: ",numero1, "y",numero2,)
  print("el numero:" ,numero1, "no es igual a:",numero2,)


  nota = int(input("ingresa la nota:"))
if nota < 1:
  print("nota invalida")
else:
  if nota <=4:
   print("Reprobado")
  else:
    if nota ==5:
     print("Regular")
    else:
      if nota <=7:
        print("bien")
      else:
         if nota <=9:
          print("muy bien")
         else:
          if nota ==10:
            print("Excelente")
          else:
              print("nota invalida")
#esta forma es la mas correcta aparte de que queda mas simplificado, no consume rendimiento


numerodia = int(input("agregar una fecha para saber dia:"))
if numerodia ==1:
  print("es Lunes")
else:
  if numerodia ==2:
    print("es Martes")
  else:
    if numerodia ==3:
      print("es Miercoles")
    else:
      if numerodia ==4:
        print("es Jueves")
      else:
        if numerodia ==5:
          print("es Viernes")
        else:
          if numerodia ==6:
            print("es Sabado ")
          else:
            if numerodia ==7:
              print("es Domingo")
            else:
               print("error")


letra = str(input("ingresar una letra: "))
if letra == "a"or letra =="e" or letra =="i"or letra =="o"or letra =="u":
  print("no es consonante")
else:
  print("es consonante")


dia = int(input("ingresar dia: "))
mes = int(input("ingresar mes: "))
año = int(input("ingresar año: "))

if mes ==1:
 print( "",dia,"de enero de",año,)
else:
  if mes ==2:
    print("",dia,"de febrero de",año,)
  else:
    if mes ==3:
      print( "",dia,"de marzo de",año,)
    else:
      if mes ==4:
        print("",dia,"de abril de",año,)
      else:
        if mes ==5:
          print( "",dia,"de mayo de",año,)
        else:
          if mes ==6:
            print("",dia,"de junio de",año,)
          else:
            if mes ==7:
              print( "",dia,"de julio de",año,)
            else:
              if mes ==8:
                print("",dia,"de agosto de",año,)
              else:
                if mes ==9:
                  print( "",dia,"de septiembre de",año,)
                else:
                  if mes ==10:
                    print("",dia,"de octubre de",año,)
                  else:
                    if mes ==11:
                      print( "",dia,"de noviembre de",año,)
                    else:
                      if mes ==12:
                        print("",dia,"de diciembre de",año,)
                      else:
                        print("Error")



dia = int(input("ingresar dia: "))
mes = int(input("ingresar mes: "))
año = int(input("ingresar año: "))
if mes ==1:
  mes_nombre= "enero"
else:
  if mes ==2:
    mes_nombre= "febrero"
  else:
    if mes ==3:
      mes_nombre= "marzo"
    else:
     if mes ==4:
       mes_nombre= "abril"
     else:
       if mes==5:
        mes_nombre= "mayo"
       else:
         if mes==6:
          mes_nombre= "junio"
         else:
           if mes==7:
            mes_nombre= "julio"
           else:
             if mes==8:
              mes_nombre= "agosto"
             else:
               if mes==9:
                mes_nombre= "septiembre"
               else:
                 if mes==10:
                  mes_nombre= "octubre"
                 else:
                   if mes==11:
                    mes_nombre= "noviembre"
                   else:
                     if mes==12:
                       mes_nombre= "diciembre"
                     else:
                         mes_nombre="mes incorrecto"
if mes >=1 and mes <=12:
  print(dia,"de",mes_nombre,"de",año,)
else:
  print(mes_nombre)
# ESTA ES OTRA MANERA DE HACER EL EJERCICIO ANTERIOR



a = 8
if (a < 25):
 print("es menor a 25")
else:
 print("es mayor a 25")




 letra = str(input("ingresar una letra: "))
if letra == "a" or letra == "e" or letra == "i" or letra == "o" or letra == "u":
  print("es una vocal")
else:
  print("no es una vocal")



num1 = int(input("ingresar numero:"))
op = str(input("ingresar la operacion que desea realizar: \nA) Suma\nB) Resta\nC) Multiplicación\nD) División\nE) ver si es multiplo:\n"))
num2 = int(input("ingresar el segundo numero:"))
opA = num1 + num2
opB = num1 - num2
opC = num1 * num2
opD = num1 / num2


if op == "a":
  print("el resultado es:",opA)
elif op == "b":
  print("el resultado es:",opB)
elif op == "c":
  print("el resultado es:",opC)
elif op == "d":
  print("el resultado es:",opD)
elif num1 % num2 ==0:
  print("es multiplo")
else:
  print("no es multiplo")



  sueldo = int(input("ingresar sueldo"))


if sueldo >=100001 and sueldo == 150000:
  descuento = sueldo * 0.05
  print(descuento)
elif sueldo <=100000 and sueldo ==75001:
  descuento = sueldo * 0.10
  print(descuento)
elif sueldo <= 75000 and sueldo == 40000:
  descueno = sueldo * 0.15
  print(descuento)




print("*******CONVERTIDOR DE MEDIDAS*******")
num = int(input("ingresar numero:"))
med = str(input("Convertir:\nA)Metros a centimetros\nB)Metros a pies\nC)Centimetros a pulgadas\n"))
opA = num * 100
opB = num * 30.48
opC = num * 2.54
if med == "a":
 print("son" ,opA, "centimetros")
elif med == "b":
  print("son",opB,"pies")
elif med == "c":
  print("son",opC,"pulgadas")




opcion = input("*******CONVERTIDOR DE MEDIDAS*******\ncovertir:\na-metros a centimetros \nb-metros a pies\nc-centimetros a pulgadas\n")
medida = float(input("ingrese la medida:"))
if opcion == 'a':
  resultado = medida * 100
elif opcion == 'b':
  resultado = medida * 100 / 30.48
elif opcion == 'c':
  resultado = medida / 2.54
else:
  resultado = "opcion invalida"
print("El resultado es: ",resultado) # ESTA MANERA ES MAS RENDIDORA A LA HORA DE AHORRAR RAM O ESPACIO PARA EJECUTAR




print("CALCULA TU FECHA DE CUMPLEAÑOS!")
dia = int(input("ingresar dia: "))
mes = int(input("ingresar mes: "))
año = int(input("ingresar año: "))

if mes == 1 or mes == 2 or (mes == 12 and dia >= 21) or (mes == 3 and dia  <=20):
  print("tu cumpleaños es en verano")
elif mes == 4 or mes == 5 or (mes == 9 and dia >= 21) or (mes == 6 and dia <=20):
  print("tu cumpleaños es en primavera")
elif mes == 7 or mes == 8 or (mes == 6 and dia >= 21) or (mes == 7 and dia <=20):
  print("tu cumpleaños es en invierno")
else:
  print("tu cumpleaños es en otoño")



  print("CALCULA TU FECHA DE CUMPLEAÑOS!")
dia = int(input("ingresar dia: "))
mes = int(input("ingresar mes: "))
año = int(input("ingresar año: "))

if mes == 1 or mes == 2 or (mes == 12 and dia >= 21) or (mes == 3 and dia  <=20):
  print("tu cumpleaños es en verano")
elif mes == 4 or mes == 5 or (mes == 9 and dia >= 21) or (mes == 6 and dia <=20):
  print("tu cumpleaños es en primavera")
elif mes == 7 or mes == 8 or (mes == 6 and dia >= 21) or (mes == 7 and dia <=20):
  print("tu cumpleaños es en invierno")
else:
  print("tu cumpleaños es en otoño")



  num1 = int(input("ingresar numero: "))
num2 = int(input("ingresar numero: "))
num3 = int(input("ingresar numero: "))

if num1 < num2 and num2 < num3:
  print(num1, num2, num3,)
elif num3 < num2 and num1 > num2:
  print(num3, num2, num1,)
elif num2 < num1 and num3 > num2:
  print( num2, num3, num1)
elif num2 > num1 and num3 < num2:
  print(num3, num1, num2)
else:



print("ingresa 3 numeros")
a = input()
b = input()
c = input()
if a < b and < c:
  menor = a
  if b > c:
    mayor = b
    intermedio = c
elif b < a and b < c:
  menor = b
  if a > c:
    mayor = a
    intermedio = c
  else:
    mayor = c
    intermedio = a
else:
  menor = c
  if a > b
  mayor = b
  intermedio = a
  print(menor, "-" intermedio "-", mayor)




edad = int(input("ingresar edad:"))

while int(edad) <=0:
  print("edad incorrecta")
  edad = int(input("ingresar edad:"))

print("tu edad es: "+str(edad))




num = int(input("ingresar un numero\nhasta ingresar 0:"))

while num!= 0:
  print("numero incorrecto")
  num = int(input("ingresar un numero\nhasta ingresar 0:"))
print("tu numero es:"+str(num))





num = int(input("ingresar un numero:"))
contador = 0

while num >=0:
  contador = contador +1  #contador = contador + 1
  print("ingresar un numero: ")
  num= int(input("ingresar un numero:"))

print("contador: ",contador)
print("fin del programa")





contador = 0
total = 0

car = str(input("ingresar caracter: "))


while car != '0':
  contador +=1
  total + car
  print("hasta el momento total de caracteres es: ",contador)
  print(total)
  car = str(input("ingresar caracter: "))

print("numeros ingresados:",contador, "\ntotal: ",total)




caracter = input("ingresar caracter: ")
cont = 0
while caracter != '0':
  cont +=1
  caracter = input("ingresar caracter: ")

print("el total de caracteres ingresados es: ",cont)





num = int(input("ingresar numero: "))
contpos = 0
contneg = 0

while num != 0:
  if num >=0:
    print("es positivo")
    contpos += 1
  else:
    print("es negativo")
    contneg +=1

  num = int(input("ingresar numero: "))
total = contpos + contneg
print("se ingresaron\n",contpos, "positivo y ",contneg,"negativos se ingresaron",total,"numeros")




num = int(input("ingresar numero: "))
contadorpar = 0
contadorimp = 0
totalimp = 0
totalpar = 0
while num != 0:
 if num % 3 == 0:
  contadorimp +=1
  totalimp = contadorimp
  print("hasta ahora num impares ingresados son: ",contadorimp)
  num = int(input("ingresar numero: "))
 if num == 0:
  print("total de numeros impares ingresados: ",totalimp,"\ntotal de numeros pares ingresados: ",totalpar,)
 else:
  contadorpar +=1
  totalpar = contadorpar
  print("hasta ahora num pares ingresados son: ",contadorpar)
  num = int(input("ingresar numero: "))




dia = int(input("ingrese un dia: "))
mes = int(input("ingrese un mes: "))
año = int(input("ingrese un año: "))
if mes == 1:
    mes = "Enero"
    print(dia, mes, año)
elif mes == 2:
    mes = "Febrero"
    print(dia, mes, año)
elif mes == 3:
    mes = "Marzo"
    print(dia, mes, año)
elif mes == 4:
    mes = "Abril"
    print(dia, mes, año)
elif mes == 5:
    mes = "Mayo"
    print(dia, mes, año)
elif mes == 6:
    mes = "Junio"
    print(dia, mes, año)
elif mes == 7:
    mes = "Julio"
    print(dia, mes, año)
elif mes == 8:
    mes = "Agosto"
    print(dia, mes, año)
elif mes == 9:
    mes = "Septiembre"
    print(dia, mes, año)
elif mes == 10:
    mes = "Octubre"
    print(dia, mes ,año)
elif mes == 11:
    mes = "Noviembre"
    print(dia, mes, año)
elif mes == 12:
    mes = "Diciembre"
    print(dia, mes, año)
else:
    print("dia: ")
    print("mes: ")
    print("año: ")
    print(dia+" "+mes+" "+año)




sueldo = float(input("ingrese su sueldo: "))
if sueldo >= 100001 and sueldo <= 150000:
  bono = sueldo * 0.05
  print("el bono es del 5%: ", bono)
elif sueldo >= 75001 and sueldo <= 100000:
  bono = sueldo * 0.10
  print("El bono es del 10% bono: ",bono)
elif sueldo >= 40000 and sueldo <= 75000:
  bono = sueldo * 0.15
  print("El bono es del 15% bono: ",bono)
else:
    print("no corresponde bono")



opcion=input("Convertidor de medidas. Convertir:\na-Metros a centímetros\nb-Metros a pies\nc-Centímetros a pulgadas")
medida = float(input("Ingrese la medida a convertir: "))
if opcion == "a":
  centimetro = medida * 100
  print(medida,"metros transformado a centímetros es:",centimetro,"centímetros")
elif opcion == "b":
  pies = medida / 0.3048
  print(medida ,"metros transformado a pies es:",pies,"pies")
elif opcion =="c":
  pulgada = medida / 2.54
  print(medida,"centimetros transformado a pulgadas es:",pulgada,"pulgadas ")
else:
  print("Opción incorrecta")



dia = int(input("ingrese su dia de cumpleaños: "))
mes = int(input("ingrese su mes de cumpleaños: "))
año = int(input("ingrese su año: "))

if mes == 1 or mes == 2 or (mes == 12 and dia >= 21) or (mes == 3 and dia <=20):
  print("es verano")
elif mes == 4 or mes == 5 or (mes == 3 and dia >=20) or (mes == 6 and dia <=21):
  print("es otoño")
elif mes == 7 or mes == 8 or (mes == 6 and dia >=22) or (mes == 9 and dia <=23):
  print("es invierno")
else:
   print("es primavera")






  


  
