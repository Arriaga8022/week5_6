Part 1

 ![image](https://user-images.githubusercontent.com/102768674/166520427-d8d6a6bb-8f54-4ee3-8708-342d95d08535.png)


Part 2
while True:
      #user input
      miles driven = int(input("enter the number of miles driven: "))
      gas used = int(input("enter the amount of gas used: "))
      #finding the mile per gallon
     mpg = miles driven / gas used
      #printing the result
      print("miles driven:", miles driven)
      print("gas used:", gas used)
      print("miles per gallon:",mpg)


Input: two float values
Output: three float value
1.	Insert milesdriven
2.	Instert gasused
3.	Calculate mpg:milesdriven/gasused
4.	Print mpg
5.	Ask user if they wish to perform another calculation
a.	Y, go back to step 1
b.	N, exit the program
o.    if the user didn’t input y/n, we will ask the user, until we receive a y/n answer
