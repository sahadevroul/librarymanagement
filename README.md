# python-tnp

a=int(input("num1="))
b=int(input("num2="))
print("CHOOSE ANY ONE OPERATION= +,-,*,/,%")
d=input()
match(d):
    case '+':
        print(a+b)
    case '-':
        print(a-b)
    case '*':
        print(a*b)
    case '/':
        print(a/b)
    case '%':
        print(a%b)
    case _:
        print("invalid ERROR")
