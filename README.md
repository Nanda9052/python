# Function to check if a number is even or odd
def check_even_odd(number):
    if number % 2 == 0:
        return f"{number} is even"
    else:
        return f"{number} is odd"

# Example usage
num = int(input("Enter a number: "))
result = check_even_odd(num)
print(result)
