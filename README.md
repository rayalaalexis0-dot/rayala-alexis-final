while True:
    print("=======================================")
    print(" <<< PYTHON LESSONS >>> ")
    print("=======================================\n")
    print("<< PRELIM LESSONS >> ")
    print("1. Introduction")
    print("2. What is Programming")
    print("3. Python Print Syntax")
    print("4. Python Comment")
    print("5. Variables and Data Types")
    print("6. Arithmetic Operators\n")
    print("<< MIDTERM LESSONS >>")
    print("7. Input Function")
    print("8. F-String")
    print("9. Conditional Statement\n")
    print("<< FINAL LESSON >>")
    print("10. Looping")
    print("\n0. Exit")
    print("=======================================\n")

    choice = input("Select a lesson by number (0 to exit): ")

    if choice == "1":
        print("\n--- Introduction ---")
        print("Python is a popular, easy-to-learn programming language known for its readability and versatility.")
        print("Example:")
        print('print("Welcome to Python!")')
        print('Output: Welcome to Python!\n')

    elif choice == "2":
        print("\n--- What is Programming ---")
        print("Programming is the process of writing instructions for computers to perform specific tasks.")
        print("Example:")
        print('print("Programming is fun!")')
        print('Output: Programming is fun!\n')

    elif choice == "3":
        print("\n--- Python Print Syntax ---")
        print("print() function is used to display output on screen.")
        print('Example: print("Hello, World!")')
        print('Output: Hello, World!\n')

    elif choice == "4":
        print("\n--- Python Comment ---")
        print("Comments explain code and are ignored by Python interpreter.")
        print("Use # for single-line comments.")
        print('Example:')
        print('# This is a comment')
        print('print("Comments do not run")')
        print('Output: Comments do not run\n')

    elif choice == "5":
        print("\n--- Variables and Data Types ---")
        print("Variables store data. Common types are int, float, str, bool.")
        print('Example:')
        print('age = 25')
        print('name = "Alice"')
        print('print(name, "is", age, "years old.")')
        print('Output: Alice is 25 years old.\n')

    elif choice == "6":
        print("\n--- Arithmetic Operators ---")
        print("Operators: +, -, *, /, //, %, **")
        print('Example:')
        print('a = 10')
        print('b = 3')
        print('print("a + b =", a + b)')
        print('print("a // b =", a // b)')
        print('print("a ** b =", a ** b)')
        print('Output:')
        print('a + b = 13')
        print('a // b = 3')
        print('a ** b = 1000\n')

    elif choice == "7":
        print("\n--- Input Function ---")
        print("input() reads user input as a string.")
        print('Example:')
        print('name = input("Enter your name: ")')
        print('print("Hello, " + name + "!")')
        print('If user enters Bob, output: Hello, Bob!\n')

    elif choice == "8":
        print("\n--- F-String ---")
        print("F-strings embed expressions inside string literals using {}.")
        print('Example:')
        print('age = 30')
        print('print(f"My age is {age}")')
        print('Output: My age is 30\n')

    elif choice == "9":
        print("\n--- Conditional Statement ---")
        print("Use if, elif, else to execute code based on conditions.")
        print('Example:')
        print('age = 18')
        print('if age >= 18:')
        print('    print("You are an adult")')
        print('else:')
        print('    print("You are a minor")')
        print('Output: You are an adult\n')

    elif choice == "10":
        print("\n--- Looping ---")
        print("Use loops to repeat actions.")
        print('Example:')
        print('for i in range(3):')
        print('    print("Iteration", i)')
        print('Output:')
        print('Iteration 0')
        print('Iteration 1')
        print('Iteration 2\n')

    elif choice == "0":
        print("Exiting program. Thankyou and Goodbye!")
        break

    else:
        print("Invalid selection. Please enter a number from 0 to 10.")

    input("\nPress Enter to continue...")