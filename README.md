# Prime-numbers
a=int(input("Number: "))


for i in range(2,a):
    for j in range(2,i):
        if i%j==0:
            break


    else:
        print(i)
