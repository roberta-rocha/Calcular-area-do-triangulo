# Calcular-area-do-triangulo
a1=float(input("Angulo 1: "))
a2=float(input("Angulo 2: "))
a3=float(input("Angulo 3: "))
#meia circunferência
meia=a1+a2+a3
meia=meia/2
# Calcular área
area=(meia*(meia-a1)*(meia-a2)*(meia-a3)) ** 0.5
print(area)
