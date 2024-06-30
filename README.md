ExampleContract
The ExampleContract is a simple Solidity smart contract that demonstrates the usage of require(), assert(), and revert() statements. These statements are used to handle errors and ensure the contract functions as expected.

Features
require(): Checks for valid conditions before executing certain functions.
assert(): Ensures that the internal state of the contract is correct.
revert(): Reverts the transaction if certain conditions are not met.
Functions
constructor
Initializes the contract with an initial value. Ensures the initial value is greater than zero using require().

updateValue
Updates the stored value to a new value. Uses require() to ensure the new value is greater than zero.

doubleValue
Doubles the current value. Uses assert() to ensure the value doubled correctly.

resetValue
Resets the value to zero. Uses revert() to prevent resetting if the value is already zero.

How to Use
Deploy the contract with an initial value greater than zero.
Call updateValue() with a new value to update the stored value.
Call doubleValue() to double the stored value.
Call resetValue() to reset the value to zero, ensuring the value is not already zero.
Video Walkthrough
A video walkthrough explaining the code can be found here.

License
This project is licensed under the MIT License.


