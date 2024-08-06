# block18Workshop

Block 18 Workshop

# A function called "Multiplication" the returns the product of tow numbers

# HAPPY PATH

- The functions should take two parameters, x and y.
- x and y can either be an integer (whole number) or a decimal (float).
- The output should be the mutliplication of x and y (x , y).

# UNHAPPY PATH

- function doesnt multiply x and y.
- output is a string, object, or NaN.
- no putput was given.
- output gave two numbers instead of one.

# A function called "concatOdds" that takes two arrays of integers as arguments and returns a single array containing only odd numbers in numeric order.

# HAPPY PATH

- The function should take information from both arrays and return a single array of odd numbers.
- the function should be able to filter any integers in the arrays.
- The function should contain an if statment to reduce both arrays into one.
- the if statment should % each integer in both arrays that has a remainder of one.
- the if statment should .push the integers with a remainder in the new array.
- the functon should filter out duplicated numbers in the newly created array
- The function should use the .sort method to numerically sort the odd numbers in the new array.
- Function should print invalid input if the arrays contain anything else but intergers.

# UNHAPPY PATH

- No output is given in the new array.
- All numbers get pushed into new array.
- only even numbers get pushed into the new array.
- The numeric sort is reversed (greatest to least greatest).
- duplicated numbers are outputed in the new array.

# A shopping cart checkout feature that allows the user to be a guest or sign in with an account. Should be prompted to sign in or create an account but isnt required to checkout.

# HAPPY PATH

- Cart program shows an itemized list in the cart or "Empty Cart" if no items are added.
- Cart program should prompt user "Cart is Empty" if the cart is empty when selecting checkout.
- Cart program lists a total of all items in the cart.
- Cart program has a checkout button at the bottom of the cart total.
- The user is prompoted to "sign in", "create an account", or "continue as a guest" when selecting checkout.
- If user signs in the cart program should show past orders or "suggested items" based off past orders.
- Cart program should save the users past purchases when signed in or save current cart after creating an account and checking out.
- If the user signs in the cart program should have saved past information for faster checkout (payment, address, etc.).
- When user "Logs in" with no inforamtion an error should show and prompt the user to create an account if they dont have one
- If user "logs in" with incorrect information they should be prompted inforamtion is incorrect (email or password).

# UNHAPPY PATH

- Program takes user to checkout after hitting "Log In" with no information.
- Program doesnt prompt user to "Log In", "create an account" or "Continue as a Guest".
- Program continues checkout when cart is "Empty".
- Program accepts order when no payment has been processed.
- Program doesnt show a list of added items.
- Program doesnt total all items within the cart.
- Program doesnt show past orders of signed in users.
- Program doesnt save past inforamtion for seemless checkout for signed in users.
- Program doestn list "suggested items" for signed in users.
- Program doesnt state the users log in info isnt correct.
