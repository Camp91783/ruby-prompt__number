---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Integer numbers:  numbers without a decimal 
ex:)  6
Floats:  numbers with decimal points
ex:) 17.0


# What are some common operations and comparisons you would perform on numbers?

addition
puts 17.0 + 6.0

Subtraction
puts 17.0 - 6.0

multiplication
puts 2.0 * 2.0

divison
puts 8.0 / 2.0

exponenets
9 ** 3

when you do arithmetic with integers you get integer answers.  The example in Pines book was if you do 9/2 = 4.  It rounds down to the closest whole integer.


# What is the difference between the `+` operation on a number versus on a String?
If you perform the '+' operation on a number it does additon to the number.  On a string the '+' it puts the strings together.

ex:) puts 17 + 6 = 4
     puts "17" + "6" = 176
       or
      puts "Stephen" + "Curry" = StephenCurry
      

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No its not gonna work.  You need to switch the string to an iteger using the ".to_i"  method


# What is the purpose of the `times` operation? Is that the same as `*`?

the 'times" operation simply performs an action a given number of times.  the "*" is just mulitplication.  So these 2 are very very different.


