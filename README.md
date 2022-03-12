# Password Generator Starter Code

LIVE SITE: https://beimy.github.io/RandomPasswordGenerator/

Github link: https://github.com/beimy/RandomPasswordGenerator


The function of this application is to create a random password generator based off user preferences. The user can define the parameters of their password including length, use of lower or upper case letters, numerals, and special characters. Based on the prompts the site returns the user with a unique password. 

My first step with this challenge was getting prompts on screen for the user to pass their choices into. I went with mostly alert boxes since the yes or no format of them worked best with most of the questions, the length parameter uses a prompt function. 

Getting the prompts working and saving the users choice was the easy part. I may have made it a bit to complex and created a class that holds all of the users choices. Then I just check to make sure that the length isn't to big or small and each alert when ticked YES sets a boolean to true to indicate that the user had at least one valid character type to go with. 

I struggled for a bit with coming up with a way to randomly choose an element from a random array. Normally this wouldn't be hard if you knew the amount of arrays you are working with, but since the user chooses what kind of characters they do and don't want it was a bit more tricky. I came up with the idea to pass each of the users choosen character types into one single array, that way I only had to deal with randomly choosing one array element at a time. 

After that it was just a matter of populating a new array with our randomly choosen elements from our frankenstiened character array and we were done!

![alt text](/Develop/passwordGen.PNG) 