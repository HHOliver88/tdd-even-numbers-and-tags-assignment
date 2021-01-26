# even-numbers-and-tags-assignment

# VERY IMPORTANT
After you download this app, make sure you run **npm install** FIRST in your local machine to install the dependencies before you run any docker commands.

Create a function that accepts numbers separated by commas (string format). It should print out a message and return only the even numbers from the numbers you passed to it. 

Example params: "1,2,3,4,5,6,7,8"

Example output: "Here are the even numbers: 2, 4, 6, 8".

1. This function only accepts 1 parameter
2. The parameter is in a string format
3. It will return an error if more than 1 parameter is passed
4. It will return an error if parameter is not in string format
5. It should return the expected return value on success
6. It should return an error message if the string passed is empty
7. It should return an error message if string passed has no even numbers

Additional: Add more relevant tests you can think of.

The second function should accept tags separated by either a comma, a space, or a comma and a space. It should print out the UNIQUE tags in a list (html in string format). 

Example params: "work, teach,ride,time read,read"
Example output:

`<ul><li>work</li><li>teach</li><li>ride</li><li>time</li><li>read</li></ul>`

1. The function only accepts 1 parameter
2. The parameter is in a string format
3. It will return an error if more than 1 parameter is passed
4. It will return an error if parameter is not in string format
5. It should return the expected return value on success
6. It should return an error message if the string passed is empty
7. It should not print a tag twice

Additional: Add more relevant tests you can think of.

**You must write the test first, have it failed, then write the necessary code for it to pass**

# Reminders

1. Write a single test first (for example for #1), see the test fail, write the code for the test to pass, see the test pass
2. Then proceed to the other features

# Instructions

1. You will need to run the node server first before running any tests. 
2. For now, just write the Even Numbers and Tags functions directly in the test file.
3. Make sure you work on this assignment in a docker container. The necessarily files to build and run this app in a docker container is already provided.
4. Once done, you need to zip your app in one file and upload the zipped file in Hacker Hero.
