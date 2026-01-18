****************************Task 1****************************
->In this task we find odd and even no. We task a no. from user and find that no is ODD or EVEN
all code run under exception handling suppose some give input as a string then code gives many error 
so code run under try 
-> take input from user
num = int(input("Enter an integer: "))
-> if input no divide by 2 and reminder come 0 the no. is EVEN otherwise its ODD
    if num % 2 == 0:
        print(f"{num} is Even.")
    else:
        print(f"{num} is Odd.")
-> if someone give input as string then a exception trigger that string not divide and redirect to except
a message print "Invalid input! Please enter a whole number (integer)"
 print("Invalid input! Please enter a whole number (integer).")

**********************************Task 2************************

-> This project is simple add value 0 to 50
initialize a value total and initial value is 0
-> a for loop run till 1, to 51
for i in range(1, 51):
    total += i
-> thats equation means that 
                     total = total+1 
 first iteration     total= 0+1 -----> total = 1 now total value is 1
 second iteration    total= 1+2 -----> total = 3 now total value is 3
  |
  |
  |
  |
  this iteration goes to 50 and after 50th iteration exit and final value print






