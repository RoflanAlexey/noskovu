dx = float(input("Введите шаг: "))
x1 = float(input("Введите начальное значение: "))
x2 = float(input("Введите конечное значение: "))
while x1 + dx <= x2:
    if x1 + dx < -7:
        y = 0
        print(y)
    elif(x1 + dx > -7) & (x1 + dx <= -3):
        y = x1 + 7
        print(y)
    elif(x1 + dx > -3) & (x1 + dx <= -2):
        y = 4
        print(y)
    elif(x1 + dx > -2) & (x1 + dx <=2):
        y = x1**2
        print(y)
    elif(x1 + dx > 2) & (x1 + dx <=4):
        y = (-x1 + 4) * 2
        print(y)
    elif x1 + dx > 4:
        y = 0
        print(y)
    x1 = x1 + dx
 
