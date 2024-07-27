
def calculator():
 
 c=int(input("ENTER TASK To PRINT \n1.ADDITION \n2.SUBSTRACTION \n3.MULTIPLICATION \n4.DIVION \n5.MODULOUS \n6.EXPONENTIAL\n"))
 a=int(input(" Enter First no. to calculate : ")) 
 b=int(input(" Enter second no. to calculate : "))
 print(a)
 print(b)
 
 match c:
     
    case 1: print("ADDITION =",a+b) 

    case 2: print("SUBSTRACTION =",a-b)

    case 3: print("MULTIPLICATION =",a*b)
    
    case 4: print("DIVISION=",a/b)
   
    case 5: print("MODULOUS=",a%b)
    
    case 6: print("EXPONENTIAL=",a**b)
   
    case _: print("NO TASK FOUND")
calculator()

