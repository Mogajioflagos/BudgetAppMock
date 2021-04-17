# BudgetAppMock
class Budget:
    def __init__(self, amount, category):
        self.amount = amount
        self.category = category
        
    def balance(self):
        amount = [0,0,0]
        self = amount
        amount = (0)
        amount.balance()

    def transfer(self, amount, dc, cc):
        self.category = category
        
        
    name = input("What is your name? \n")
    allowedUsers = ["Seyi","Mogaji","Riri"]
    if(name in allowedUsers):
        print("Nice to have you onboard, %s" % name)
        print('These are the available options:')
        print("1. Deposit")
        print("2. Withdrawal")
        print("3. Check Balances")
        print("4. Transfer Balance Amounts")
            
        selectedOption = int(input("Please select an option \n"))
    
        if(selectedOption == 1):
                                       
                    deposit = int(input("how much would you like to deposit? \n"))
                    if(deposit <= 1000):
                        print("Operation Not Allowed")
                    else:
                        userOption = int(input("Which of these categories would you like it to be deposited? \n 1. Food \n 2. Clothing \n 3. Entertainment \n"))

                        if(userOption == 1):
                            print("Operation Successful. \n Your Account Balance is " + str(deposit))
                        elif(userOption == 2):
                             print("Operation Successful. \n Your Account Balance is " + str(deposit))
                        elif(userOption == 3):
                            print("Operation Successful. \n Your Account Balance is " + str(deposit))    
                        else:
                            print("Operation Not Allowed")
                         
        
        elif(selectedOption == 2):

                    userOption = int(input("Which of these categories would you like to withdraw from? \n 1. Food \n 2. Clothing \n 3. Entertainment \n"))
                    if(userOption == 1):
                        print("Proceed:")
                    elif(userOption == 2):
                        print("Proceed:")
                    elif(userOption == 3):
                        print("Proceed:")    
                    else:
                        print("Operation Not Allowed")

                    withdrawal = int(input("How much would you like to withdraw? \n"))

                    if(withdrawal > 100000):
                        print("Operation Not Allowed")
                    else:
                        print("Operation Successful, Please Take your Cash. Thank You!")
                        
        elif(selectedOption == 3):
            print("Your Account Balance is" + str(amount))
            #print("Your acc balance is" + str(balance))
            #Food.balance()

        elif(selectedOption == 4):
            userOption = int(input("Transfer from \n 1. Food \n 2. Clothing \n 3. Entertainment \n"))
            if(userOption == 1):
                print("Transfer to \n 1.Clothing \n 2. Entertainment \n")
            elif(userOption == 2):
                print("Transfer to \n 1. Food \n 2. Entertainment \n")
            elif(userOption == 3):
                print("Transfer to \n 1. Food \n 2. Clothing \n")
            else:
                print("Operation Not Allowed")
            transferOption = int(input("Kindly Pick a destination? \n"))
            if(transferOption == 1):
                    moneyTransfer = int(input("How much would you like to transfer? \n"))
                    if(moneyTransfer > 100000):
                        print("Operation Not Allowed")
                    else:
                        print("Operation Successful, Please Take your Cash. Thank You!")
            elif(transferOption == 2):
                    moneyTransfer = int(input("How much would you like to transfer? \n"))
                    if(moneyTransfer > 100000):
                        print("Operation Not Allowed")
                    else:
                        print("Operation Successful, Please Take your Cash. Thank You!")
            else:
                   print("Operation Successful, Please Take your Cash. Thank You!")
                 
