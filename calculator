def calculate():
    while True:
        print("Welcome! This is a simple python calculator. \n"
              "Press 1 to get started \n"
              "Press 2 to exit\n")
        action = input("Action: ")

        if action == "2":
            print("You have completed the job. See you soon!")
            break

        try:
            digit_1 = int(input("Enter the FIRST number: "))
            action = input("Enter operation (*, /, + or -): ")
            digit_2 = int(input("Enter the SECOND number: "))
            red_line = "\n" + '-' * 30
            if action == "+":
                print("Your sum =", int(digit_1) + int(digit_2), red_line)
            elif action == "-":
                print("Your difference =", int(digit_1) - int(digit_2), red_line)
            elif action == "*":
                print("Your product =", int(digit_1) * int(digit_2), red_line)
            elif action == "/":
                try:
                    division = digit_1 / digit_2
                except ZeroDivisionError:
                    division = 0
                    print("You cannot divide by 0. Try again", red_line)
                else:
                    print("Your quotient  =", int(digit_1) / int(digit_2), red_line)
            else:
                print("Invalid action, select an action from the proposed list: *, /, + or -", red_line)
        except:
            print('A non-numeric value was entered. try again\n')
        again()

def again():
    calculate()

calculate()
