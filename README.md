# FIbonacci-Series
A series of numbers in which each number  is the sum of the two preceding numbers

# Fibonacci-series
n = int(input("Enter the value of 'n': "))
a = 0
b = 1
sum = 0
count = 1
print("Fibonacci Series: ", end = " ")
while(count <= n):
    print(sum, end = " ")
    count += 1
    a = b
    b = sum
    sum = a + b
