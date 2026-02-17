# Geometric-Mean-of-n-Numbers
c = 0
p = 1.0
count = int(input("Enter the number of values: "))
while c < count:
    x = float(input("Enter a real number: "))
    c += 1
    p *= x
gm = pow(p, 1.0 / count)
print("The geometric mean is:", gm)

OUTPUT:
Enter the number of values: 3
Enter a real number: 2
Enter a real number: 8
Enter a real number: 4
The geometric mean is: 4.0

