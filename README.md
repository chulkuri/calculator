sum=0
while(True):
    amount=input("Enter the amount :")
    if(amount!='q'):
        sum=sum+int(amount)
        print("total bill so far",sum)
    else:
        print("thank you for visiting")
        print("the total bill is ",sum)
        break 
