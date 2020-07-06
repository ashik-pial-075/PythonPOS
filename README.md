# PythonPOS
#A simple python prrogram to create point of sales

print("Our Billing system POS")
original_price =float( input("Enter Original Price :"))
tax = float(input("Vat in Percentage: (%) "))
total_price = original_price + ((tax* original_price)/100)
print("Your Bill is: "+ "Original Price" +" + " +"tax")
print("             = "+ str(original_price) +" + " + str(tax)+"%")
print("             = "+ str(original_price) + " + " +str(((tax * original_price)/100)))
print("             =",total_price)
print("Thank You for Enjoying Python Point of Sale!")
