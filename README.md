#mini project on calculator
'''create a get method which will take and return\inputs from the user'''
def get():
    a=int(input('enter the val1:'))
    b=int(input('enter the val2:'))
    return a,b
#create functions which will perform mathematical operations
def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def true_div(a,b):
    return a/b
def floor_div(a,b):
    return a//b
def mod(a,b):
    return a%b
def fact():
    a=int(input('enter val:'))
    fact=1
    for i in range(1,a+1):
        fact*=i
    return fact
def sqrt():
    a=int(input('enter value'))
    return a**(1/2)
def power(a,b):
    return a**b
    
    
while True:
    print('_'*50)
    print('Enter 1:addition')
    print('Enter 2:substraction')
    print('Enter 3:multiplication')
    print('Enter 4:true division')
    print('Enter 5:floor division')
    print('Enter 6:modular division')
    print('Enter 7:factorial')
    print('Enter 8:square root')
    print('Enter 9:power')
    print('Enter 10:to exit the app')
    choice=int(input('Enter your choice:'))
    if choice==1:
        m,n=get()
        print('the sum is',add(m,n))
    elif choice==2:
        m,n=get()
        print('the sub is',sub(m,n))
    elif choice==3:
        m,n=get()
        print('the mul is',mul(m,n))
    elif choice==4:
        m,n=get()
        print('true division is',true_div(m,n))
    elif choice==5:
        m,n=get()
        print('floor division is',floor_div(m,n))
    elif choice==6:
        m,n=get()
        print('modules is',mod(m,n))
    elif choice==7:
        print('factorial is:',fact())
    elif choice==8:
        print('square root:',sqrt())
    elif choice==9:
        m,n=get()
        print('power',power(m,n))
    elif choice==10:
        print('thank for using the app')
        break
else:
    print('invalid:')







# caculator
