# Calculator App 🧮

A simple Python calculator with basic operations: Add, Subtract, Multiply, Divide.

## Usage
Run the program with:
```bash
python calculator.py
# calculator.py

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero!"
    return a / b

# Example usage
if __name__ == "__main__":
    print("Simple Calculator App 🚀")
    print("5 + 3 =", add(5, 3))
    print("10 - 4 =", subtract(10, 4))
    print("6 * 7 =", multiply(6, 7))
    print("8 / 2 =", divide(8, 2))
