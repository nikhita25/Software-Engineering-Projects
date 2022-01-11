

# TipCalculator App


The TipCalculator application allows you to enter the check amount along with the party size and it computes the tip amount and the total each person must pay.

## Terms

 - Check Amount: Total amount that your group has to pay
 - Party Size: The number of people that will be splitting the check
 - Compute Tip: Computes the output when clicked
 - Tips: The amount of tip each person has to pay for a certain percentage
 - Total: The total amount each person has to pay 


## How to use the app

 1. Start by entering the check amount.
 2. Enter the party size.

	> **Note:** Party Size cannot be 0. If you enter 0 for party size you will receive an error message at the bottom of the screen. Please enter a number greater than 0. 


 3. Click the COMPUTE TIP button. 

     > **Note:** The application does not allow you to enter negative numbers. The inputs must be positive.

    >  **Note:** You must enter a number for BOTH Check Amount and Party Size. If Check Amount or Party Size is empty you will receive an error message at the bottom of the screen saying that the input is invalid.


## Output

After clicking the Compute tip button the output will be calculated. 

On the left side of the screen is the tip amount for each person, depending on the percentage. The tip will be rounded to the nearest integer

On the right side of the screen is the total amount each person must pay. This total is calculated by dividing the check amount by party size and adding the tip to that value. 

The tips and totals will be listed in the following order:

     - 15%
     - 20%
     - 25%

## Example

       Check Amount: 100
       Party Size: 4
       
    How tip is calculated:
        	    Tip for 15% = (100/4) * .15 = 3.75 = 4
        	    Tip for 20% = (100/4) * .20 = 5
        	    Tip for 25% = (100/4) * .25 = 6
    
    How total is calculated: 
    	    Total for 15%: (100/4) = 25 + 4 = 29
    	    Total for 20%: (100/4) = 25 + 5 = 30
    	    Total for 25%: (100/4) = 25 + 6 = 31

