PSEUDO CODE FOR ARMSTRONG NUMBER:-

 BEGIN 

     Declare Integer choice 
     
    DO
       
          Declare Integer i
        
        Output "choose i=2 give three armstrong number 
         choose i=3 for four armstrong number"

        Input i
        
        If i==2
            Declare Integer a, b, c, d
            
            Assign c = 0
            Input a
            Assign d = a
            For a = a to 1 decreasing
                Assign b = a%10
                Assign c = c+(b*b*b)
                Assign a = a/10
                Assign a = a+1
            End
            If c=d
                Output "armstrong number"
            False:
                Output "not an armstrong number"
            End
        False:
            Declare Integer total
            
            Assign total = 0
            Declare String value
            
            Input value
            Declare Integer length
            
            For length = 0 to len(value)-1
                Assign total = total+ToInteger(char(value,length))^4
            End
            If total=ToInteger(value)
                Output VALUE & "IS AN ARMSTRONG NUMBER"
            False:
                Output VALUE & "IS NOT AN ARMSTRONG NUMBER"
            End
        End
        Output "do you wish to continue 1. yes 2.no"
        Input choice
    Do choice==1
    Output "thankyou for finding for your solution"
End

[armstrong number](file:///C:/Users/ychar/OneDrive%20-%20Amrita%20Vishwa%20Vidyapeetham-%20Chennai%20Campus/Documents/PSAT%20LAB%201/armstrong%20number11111.pdf)




