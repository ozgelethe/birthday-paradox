# birthday-paradox

Suppose that people enter a room one at a time. How people must enter until two share a birthday? Counterintuitively, 
after 23 people enter the room, there is approximately a 50–50 chance that two share a birthday. 

This phenomenon is known as the birthday problem or birthday paradox.

Choose a birthday for the next person, uniformly at random between 0 and n−1.
Have that person enter the room.
If that person shares a birthday with someone else in the room, stop; otherwise repeat.
In each experiment, count the number of people that enter the room. Print a table that summarizes the results (the count i, the number of times that exactly i people enter the room, and the fraction of times that i or fewer people enter the room) for each possible value of i from 1 
until the fraction reaches (or exceeds) 50%.
