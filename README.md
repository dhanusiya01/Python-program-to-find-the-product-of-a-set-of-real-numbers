# Python-program-to-find-the-product-of-a-set-of-real-numbers
i = 0
product = 1
count = int(input("Enter the number of real numbers: "))
for i in range(count):
    x = float(input("Enter a real number: "))
    product = product * x
print("The product of the numbers is: ", product)

OUTPUT:

Enter the number of real numbers: 4
Enter a real number: 34
Enter a real number: 21
Enter a real number: 87
Enter a real number: 79
The product of the numbers is:  4907322.0
