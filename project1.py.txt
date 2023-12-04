# main.py
def square(x):
    return x ** 2

if __name__ == "__main__":
    num = int(input("Enter a number: "))
    result = square(num)
    print(f"The square of {num} is: {result}")
