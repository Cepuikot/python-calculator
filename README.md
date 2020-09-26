# python-calculator
# start
#калькулятор

from colorama import init
from colorama import Fore, Back, Style
init()

print( Back.CYAN )

what = input( "Что выбираешь? (+, -, *, /): " )

print( Back.MAGENTA )

a = float( input("Первое число: ") )
b = float( input("Второе число: ") )

print( Back.RED )

if what == "+":
    c = a + b
    print("равно:  " + str(c))
elif what == "-":
    c = a - b
    print("равно:  " + str(c))
elif what == "*":
    c = a * b
    print("равно:  " + str(c))
elif what == "/":
    c = a / b
    print("равно:" + str(c))
else:
    print("такого нету(")

input()
# end
