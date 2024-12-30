[Video Link](https://youtu.be/lhELGQAV4gg)

## Create flowchart and pseudocode for the following:

1. Input a year and find whether it is a leap year or not.
- Get input
- Check if the received number is 4 digits long before proceeding.
- Check if the number is divisible by 4
- If it is, print leap year.
- End.

2. Take two numbers and print the sum of both.
- Ask input for first number.
- Get input for second number.
- Add the two numbers.
- Print the sum
- End

3. Take a number as input and print the multiplication table for it.
- Get input for which the multiplication table is to be made.
- Get an input which states the limit up to which the table needs to be printed.
- Create an integer variable whose value is one.
- Write a for loop that iterates as many times as the limit received, within the loop multiply the number received with the variable ceated above, print the line and increment the value of the variable created.
- End.

4. Take 2 numbers as inputs and find their HCF and LCM.
- Get the first number
- Get the second number.
- Execute the following while loop to find the hcf
  public static int findHCF(int a, int b) {
        while (b != 0) {
            int temp = b;
            b = a % b;
            a = temp;
        }
        return a;
    }
- Execute the following statement to find the LCM:
- int lcm = (num1 * num2) / hcf;

5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.
INITIALIZE sum = 0

WHILE true
    PRINT "Enter a number (or 'x' to stop):"
    READ input

    IF input == 'x'
        BREAK

    CONVERT input TO number
    ADD number TO sum

END WHILE