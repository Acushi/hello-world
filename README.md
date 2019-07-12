# program to make simple calculator using functions
# define the functions

def add(x,y):
    """"this function adds 2 numbers"""
    return x + y


def substract(x,y):
    """"this function substracts 2 numbers"""
    return x - y


def multiply(x,y):
    """"this function multiplies 2 numbers"""
    return x * y 


def devide(x,y):
    """"this function devides 2 numbers"""
    return x/y



def power(x,y):
    """"this gives power"""

    return pow(x,y)

#take input from user
print('select operation.')
print('1.add')
print('1.substract')
print('1.multyply')
print('1.divide')
print('1.power')
choice = input('enter choice 1/2/3/4/5:')
num1 = int(input('enter the first number'))
num2 = int(input('enter the second number:'))

if choice == '1':
    print(num1,'+',num2,'=', add(num1,num2))
elif choice == '2' :
    print(num1,'-',num2,'=',substract(num1,num2))
elif choice == '3':
    print(num,'x',num2,'=', multiply(num1,num2))
elif choice == '4':
    print(num1,'/',num2,'=', divide(num1,num2))
elif choice == '5':
    print(num1,'^', num2, '=', power(num1,num2))

else:
    print('invalid input')
