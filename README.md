# OSCAR-NOMINATIONS

<strong>Question 1a</strong>

Provide a dictionary with the count of nominations for each director.

A. Create a dictionary that includes the count of Oscar nominations for each director in the nominations list.

<strong>Logic of the solution</strong>

1. To solve this question, use the .items method for dictionaries. Remember, the key in our nominated dictionary is a list of 
nominated directors. Think Compound Data Structures!

2. Create a dictionary where the key is a director and the value is the number of nominations.

3. To get each director as a key, use two for loops.

4. First, to iterate through the nominated dictionary's value (which here is a list of nominations).

5. Do to this again to iterate through each element (what I'm trying to get to - a nominated director) in the nominated list.

6. After that, if the director isn't yet in the new created dictionary, give that director a count of one. If the director is in 
the dictionary, increment that director's count by one.

<strong>Question 1b</strong>

Provide a dictionary with the count of wins for each director.

Essentially, it is the same logic as above, with the other dictionary.

We could use the same approach as in question 1a and it would work fine, but I've provided a shorter alternative here. Instead of the 
last 4 lines as above, I've just written 1 line, by using the .get method. In this line, we find the director in the win_count_dict 
dictionary and return the value for that director (the number of times they've won). If they aren't in the dictionary, get returns 0 for
that director. Then we increment that director's count by one.

<strong>Output question 1</strong>

![nom](https://github.com/anferebu/OSCAR-NOMINATIONS/blob/master/nom_count_dict.jpg)

<strong>Output question 2</strong>

![count](https://github.com/anferebu/OSCAR-NOMINATIONS/blob/master/win_count_dict.jpg)

<strong>INSTRUCTIONS</strong>

1. Download and unzip the repository folder.
2. Open, compile and run the break_continue.py file with Python 3 to see the project.

# Author: Andrés R. Bucheli.
