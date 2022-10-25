# 3u-ps2B-2022-sem1

---
Create a file called **teams.py** and upload it to this repo. 

A sporting organization separates teams into different leagues based on how many games they have won in an 8 game season.
If they have won 1 – 2 games inclusive they are in the “Beginner” league. If they have won 3 – 4 games inclusive they are in the “Intermediate” league. If they have won 5 – 6 games inclusive they are in the “Advanced” league. And if they have won 7 games or more they are in the championship league. If they did not win a single game – they cannot compete. Write a program that takes in 8 lines of input – either W or L and outputs what league they are in: Beginner, Intermediate, Advanced, Championship, Cannot Compete.

**Input Specifications**
```
8 lines of input – each line is either W or L.
```

**Output Specifications**
```
1 line from: Beginner, Intermediate, Advanced, Championship, Cannot Compete.
```

**Sample Input 1**
```
W
L
W
W
W
L
L
L
```

**Sample Output 1**
```
Intermediate
```
---
Create a file called **spirit_pokemon.py** and upload it to this repo.

Write a program that takes in the user's year of birth and outputs their spirit pokemon. Their spirit pokemon consists of a type (psychic, fairy, dark, fighting, ghost) and a pokemon (bulbasaur, charmander, squirtle, pikachu).

To figure out your type, **look at the last digit of your birth year**.

- 0 or 1, your element is psychic
- 2 or 3, your element is fairy
- 4 or 5, your element is dark
- 6 or 7, your element is fighting
- 8 or 9, your element is ghost

To figure out your pokemon use the below chart. **The chart repeats every 4 years.** For example, if you were born in 2008 + 4 = 2012, your pokemon is also a bulbasaur.

|bulbasaur |charmander|squirtle  |pikachu   |
|----------|----------|----------|----------|
|2008      |2009      |2010      |2011      |

**Input Specifications**
```
1 line of input representing the year of birth
```

**Output Specifications**
```
1 line of output: type and pokemon with a space in between with all lower case
```

**Sample Input 1**
```
1999
```

**Sample Output 1**
```
ghost pikachu
```

**Sample Input 2**
```
2030
```

**Sample Output 2**
```
psychic squirtle
```
---
Create a file called **email.py** and upload it to this repo. 

Write a program that takes in one line of input and checks that it matches a pdsb email.

For it to match a pdsb email:

1. It must end in @pdsb.net.
2. The part before the start must be a 6 digit number OR it must start with p and end with a 7 digit number.

**Sample Input 1**
```
123456@pdsb.net
```

**Sample Output 1**
```
yes
```

**Sample Input 2**
```
p1234567@pdsb.net
```

**Sample Output 2**
```
yes
```

**Sample Input 3**
```
12345@pdsb.net
```

**Sample Output 3**
```
no
```

**Sample Input 4**
```
123456@yahoo.com
```

**Sample Output 4**
```
no
```
