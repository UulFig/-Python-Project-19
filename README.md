# -Python-Project-19
#19 Simple Buzz and Fizz 


for number in range(1,101):
    if number % 3 == 0 and number % 5 == 0:
        number = print(f"{number} FizzBuzz!")
    elif number % 3 == 0:
        number = print(f"{number} Fizz!")
    elif number % 5 == 0:
        number = print(f"{number} Buzz!")
    else:
        print(number)
