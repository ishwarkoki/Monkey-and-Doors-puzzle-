# Monkey-and-Doors-puzzle- 
Question :
There are 100 doors, all closed.
In a nearby cage are 100 monkeys.

The first monkey is let out, and runs along the doors opening every one.
The second monkey is then let out, and runs along the doors closing the 2nd, 4th, 6th,…  - all the even-numbered doors.
The third monkey is let out. He attends only to the 3rd, 6th, 9th,… doors (every third door, in other words), closing any that is open and opening any that is closed, and so on.
After all 100 monkeys have done their work in this way, what state are the doors in after the last pass?  

Solution : 
Look at it from the doors' point of view. I am door number N. How many monkeys will attend to me? The first monkey, obviously. If N is even, the second monkey. If N divides by 3, the third monkey …

In fact, the number of monkeys that will attend to me is equal to the number of numbers that divide exactly into N.

Now, the number of numbers that divide exactly into N is what mathematicians call "an arithmetic function." This particular function is d(N), most properly described as "the number of factors of N."

Door number N will be left open if d(N) is an odd number.

The only N for which d(N) is an odd number are the perfect squares. If N is a perfect square, then it has an odd number of factors. For example, 36 is a perfect square, and it has nine factors:  1, 2, 3, 4, 6, 9, 12, 18, and 36. Contrariwise, 28 is not a perfect square, and so it has an even number of factors — actually six:1, 2, 4, 7, 14, and 28.

The answer is therefore:  "Any door whose number is a perfect square." In the case of 100 doors and 100 monkeys, this means doors number 1, 4, 9, 16, 25, 36, 49, 64, 81, and 100. The answer as stated, however, applies equally well to a thousand monkeys and doors, or a million, or even an infinite number.
