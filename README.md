n=int(input("enter the number:"))
while n!=0:
    rev=0
    rem=n%10
    rev=rev+rem
    n=n//10
    print("reverse number",rev)
