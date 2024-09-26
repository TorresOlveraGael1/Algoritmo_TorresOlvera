# Algoritmo_TorresOlvera

Torres Olvera Gael

Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables A, B y C respectivamente.

#Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables A, B y C respectivamente.

print (" ")
print ("Torres Olvera Gael")
print (" ")

A = int(input("Introduzca el primer valor: ")) #Establecemos los
B = int(input("Introduzca el segundo valor: ")) #Valores a
C = int(input("Introduzca el tercer valor: ")) #utilizar

#Abrimos cadena 'If'
if A > B and A > C and B > C: 
    print(A, "Es mayor que:", B, "Y",C, "el menor valor es:", C )
elif A > B and A > C and B < C: 
    print(A, "Es mayor que:", B, "Y",C, "el menor valor es:", B )
elif B > A and B > C and A < C:
    print(B, "Es mayor que:", A, "Y",C, "el menor valor es:", A)
elif B > A and B > C and A > C:
    print(A, "Es mayor que:", B, "Y",C, "el menor valor es:", C )
elif C > A and C > B and A > B:
    print(C, "Es mayor que:", A, "Y",B, "el menor valor es:", A)
elif C > A and C > B and  A > B: 
    print(A, "Es mayor que:", B, "Y",C, "el menor valor es:", B)

#Abrimos segunda cadena, en caso de un valor parecido
if A == B or A == C:
    print ("Lo siento, un valor es parecido con otro")
elif B == A or B == C:
    print ("Lo siento, un valor es parecido con otro")
elif C == A or C == B:
    print ("Lo siento, un valor es parecido con otro")

![image](https://github.com/user-attachments/assets/0dab6970-63a5-4c03-b780-664fa5b4cba7)
![image](https://github.com/user-attachments/assets/36c0d80e-898a-4446-9cc1-b6dea32bf109)
![image](https://github.com/user-attachments/assets/4011ddd1-c203-4ae9-9dab-548712e305cb)
![image](https://github.com/user-attachments/assets/6f040a3a-6279-4bee-9240-748580b9118b)




