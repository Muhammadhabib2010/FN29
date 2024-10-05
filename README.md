son = int(input("Son kiriting : "))
b = 0
for a in range(1, son + 1) :
    if son % a == 0 :
        b = b + 1

if b == 2 :
    print("Tub son")
else :
    print("Tub emas")
