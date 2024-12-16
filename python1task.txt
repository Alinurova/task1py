# 1
# a = 5
# b = 7
# print(a+b)


#2
def revers(i):
    return i[::-1]

a = 'Hello'
print(revers(a))

#3
def lenOfStr(i):
    return len(i)
a = 'Hello'
print(lenOfStr(a))

#4
def concatOfStr(i, j):
    return i+ " " +j
a = 'Hello'
b = 'World'
print(concatOfStr(a,b))

#5
def vowelsOfStr(a):
    vowels = 'aeiouAEIOU'
    return [char for char in a if char in vowels]
b = 'Hello World'
print(vowelsOfStr(b))

#6
def swapFirstLast(a):
    return a[-1] + a[1:-1] + a[0]
b = 'nFactorial'
print(swapFirstLast(b))

#7
def upperStr(a):
    return a.upper()
s = 'hello'
print(upperStr(s))

#8
def perimetr(i, j):
    return 2*(i+j)
a = 5
b = 8
print(perimetr(a,b))

#9
def iseven(a):
    if(a%2 == 0):
        return "The number is even"
    else:
        return "The number is odd"
s = 6
print(iseven(s))

#10
def thefirst3(a):
    return a[:3]

s = 'HelloWorld'
print(thefirst3(s))

#11
def interpolation(a, b):
    print(f"Hello my name is {a}, and I`am {b} years old!")
name = 'Aiganym'
age = 21
interpolation(name, age)

#12
def indexOfStr(a):
    return a[2:6]
s = "Aiganym"
print(indexOfStr(s))

#13
def intgerSum(i):
    print(int(i))
a = "5"
intgerSum(a)

#14
def repeatOfStr(a):
    return a * 3
s = "Hello "
print(repeatOfStr(s))

#15-16
def calcOfNum(a, b):
    print(a//b, a%b)
    print(float(a/b))
s = 10
d = 3
calcOfNum(s, d)

#17
def string_methods(a, b):
    print (a.count(b))
i = 'Hello'
j = 'l'
string_methods(i,j)

#18
print("Hello \"Aiganym\" ")

#19
print(" Hello World \n My name is Aignaym \n I'm 21 years old.")

#20
base = 2
exponent = 5
print(base**exponent)

#21
palindrome = "palindrome"
a = palindrome[::-1]
if palindrome == a:
    print('Yes')
else:
    print('No')

#22
a = "cat"
b = "tac"
anagrams = sorted(a.lower()) == sorted(b.lower())
print(anagrams)