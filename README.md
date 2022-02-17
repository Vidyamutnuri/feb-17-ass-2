# feb-17-ass-2
Assignment2
 n = int(input(" Enter n Value : "))
evenSum = 0
oddSum = 0
for i in range(1, n + 1):
    if(i % 2 == 0):
        evenSum = evenSum + i
    else:
        oddSum = oddSum + i
 
print("even Sum", evenSum)
print("odd Sum",oddSum)
 output:
 enter n value : 40
 even Sum: 420
 odd Sum: 400
