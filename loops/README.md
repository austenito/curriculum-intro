# Loops

**Learning Goal:** Practing the different loops: `while, each, collect`

## While

Computers are great at something you and I are not; doing something over and over and over again. We get bored
easily. Computers do not.

### Task

Write a program containing a while loop that accepts user input and has the following conditions

* If you enter your favorite music artist, print a string that professes your love.
* If you enter your least favorite music artist, print a string explaining why you don't like them.
* If you enter `bye`, exit the program.

### Hints

If you forgot, asking for user input can be done with `gets.chomp`

While loops look like
```
while true
  # your code goes here
end
```

Example Output

```
Enter an artist: Drake
I LOVE DRAKE

Enter an artist: Kelly Clarkson
Kelly, she's too good for her own good
```

## Each

The method `each` allows us to do something to _each_ thing in an array.

### Task

* Create an array containing at least 3 of your favorite things.
* Print out why you love each thing

### Hints

Example Output Given an Array with "Chocolate", "Programming", "Baseball"

```
I love Chocolate
I love Programming
I love Baseball
```

## Collect

Arrays let you loop over each element in an array and return a new array. `collect` is a method on array, which 
creates a new array with return value of each loop.

Let's say you had an array of cars `["Lambo", "Corvette", "Bently"]` and you wanted to add "is hot" to each one. 
`collect` let's you do that.

```

```

