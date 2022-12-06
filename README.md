# string-info_script-

We're going to write a script that takes user input, so that we're not working with static content, and print out some information and permutations of the string that the user has entered. Our string-info.py script will print the following information about the user provided message:

The first character
The last character
The middle character (for even length strings we'll return the integer just after the exact center).
Every even index character
Every odd index character

Here's our script in action:

$ python3.7 string-info.py
Enter a message: Test Message
First character: T
Last character: e
Middle character: e
Even index characters: Ts esg
Odd index characters: etMsae
