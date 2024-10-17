def calculate_operations()
    try:
        num1 = int(input("Enter the first integer: "))
        num2 = int(input("Enter the second integer: "))
        sum_result = num1 + num2
        difference_result = num1 - num2
        product_result = num1 * num2
        if num2 != 0:
            quotient_result = num1 / num2
        else:
            quotient_result = "Undefined (division by zero)"
        print(f"Sum: {sum_result}")
        print(f"Difference: {difference_result}")
        print(f"Product: {product_result}")
        print(f"Quotient: {quotient_result}")

    except ValueError:
        print("Invalid input. Please enter valid integers.")
calculate_operations()
