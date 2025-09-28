# Electronic-Store-Billing-System

this readme is for me only

the file got 3 functions and a class


class bill
1.private access specifier=item rate quantity, public = many things
2.Bill():Item(""), Rate(0), Quantity(0){ } -> bill () is a constructor and im initilazing before the constructor body runs , {} is where running takes place this is how constructor works - it allocates memory first and then value is allocated with whatever is inside {} with member initiazition im putting in values before itself
3. by using set we can sorta customize what values we want , and by using get we're again given option to customise. encapsulation can be enforced with this


additem function 
1.adds item into inventory
2.you set a bool at some value and you run a while loop when you want to add stuff and when you want to exit the bool value switches
3.you take the input put the values onto variables, put the values onto a text file you can make sure you can add more stuff later by includes ios::app which helps in appending.


print bill function 
1.this function prints your bill and makes changes in inventory
2.same boolean thing like before
3.if you want to get the bill you take input from inventory bill and you initate a temp bill to store inventory bill with changes. you read the inventory bill by using getline to convert a line into a string and stringstream to breakdown the line to get the names,quantities,etc
4. if the name of the item that customer wants and the inventory quantity name matches you check if the quantity youre asking is lesser than whats avaialble
5. if what youre asking is lesser than the quantity thats available = you subtract the quantity on the inventory bill and you calculate the price to be paid by the customer
6. if the quantity does not exist you simply say sorry
7.you exchange the new inventory bill with the ex inventory bill
8. bill needed by customer is given at the end of the function 


int main 
youre just calling both of these functions

