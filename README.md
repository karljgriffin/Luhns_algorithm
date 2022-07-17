# Luhns_algorithm
This is an OOP-type Python script where I solve Luhn's algorithm. I instantiate several credit cards from a .csv file and check the validity of the card numbers.

The algorithm requirements are as follows:
Step 1: Double the value of every second digit, beginning with the first digit
Step 2: If the result of this doubling is > 9, add the digits of the product, e.g. for 16: (1+6=7)
Step 3: Take the sum of all the digits
Step 4: If the total ends in zero, this is a valid card number. If not, it's invalid

I use a class method to instantiate the credit cards from the .csv file and I then use a static method to check if the card number is valid. The .csv file consists of one valid card number and one invalid card number so as to check whether my algorithm is correct
