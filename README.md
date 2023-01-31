# SharkAttack_proy1
![portada](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/maxresdefault_(1).jpg?raw=true) 

# Does Sharks attack more when they are horny?

## Could sharks attack more when they are in their mating season?
Its an interesting question 

For this hypothesis we would have to go throw some exploration into the data, we have to go and investigate the dates, months of mating for each species and analysed it with the data frame of sharks attacks around the world and start making some comparison and answer quiestions.

My hypothesis comes from examples of different types of animals, like the mammals, that they reproduce hormones and become violent between their own specie. In this case we are talking about a fish, they are in a different category, so it will be nice to make some conclutions about it, and see if they become as romantic as us.



Theres not much information about the reproduction of sharks, and there are some species less studied than others, and its really strange to seen them in the action, actually theres just counted photographs of them while they are copulating.

I got the information I could on the internet and with the data frame about the attacks, made the analisis.
![empezar explicacion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/Sharkey-Love.jpg?raw=true)
## Data cleaning.
The information was in a CSV file, had to import it and visualize it, it was really dirty. It need it a lot of cleaning with their columns and rows.

First had to make an hypothesis or at least a an idea of it, so I could go throw just the information that i would of need. 

1. went throw a full general cleaning, looking for the duplicated rows, the non value, and erasing the columns that did not apport anything to the information that I would of need.
2. Start the deep cleaning with the Date column, by creating a new column replacing the characters and making them equal and more readable so it just appears the month name.
3. Next to the Species column, making a new copy column replacing the characters that didnt apport anything and making them unique, did only keep the most common species with the more attacks so the data frame became shorter.
4. To make my research mor complete had to create a new column with boolean information, False or True if the months of attacks matched the mating season, if it was a match appers a true. For that I had to investigate on internet the months of mating season for each of the different specie of sharks.
5. Next and last had to search for the country column to identified if the country of the attacks where in southern or northern hemisphere. This column was really clean so didnt have to do anything.

At the end exported the data frame of the clean version CSV file.

Can check my process of data cleaning in Shark_cleaning file.

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/cc0bbc404c539aef74b8f1f3549869e1.png?raw=true)
## Data exploration.

With the new cleaned CSV file could make the graphics and analysed it better.

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/1.png?raw=true)

### White Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/w1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/w2.png?raw=true)

We can see here how it affects depending of the country, in which hemisphere of the globe its the country. In here we can make a conclution that theres a lot of activity for the white shark in the southern hemisphere, but still doesnt affect the attacks if it is their mating season, we can see that they still have much activity during the hole year.
### Tiger Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/t1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/t2.png?raw=true)

With the Tiger shark we could see that it has activity on the north as well as the south heisphere, and their activity doesnt change by their mating season, it looks that it has activity at the same time in all the world. Conclution, it doesn´t afect their mating season, either side of the world.
### Bull Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/b1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/b2.png?raw=true)

Comparing this table with the one on the top, I can see that in the country USA there is a coincidence that the more attacks it has done is during their mating season, during the summer in the north hemisphere.
### Wobbegong Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/wo1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/wo2.png?raw=true)

It only has attack in Australia, probably its where they leave all year round, It here we can take the conclution that it attacks all year by equal, theres not more activity during their mating season.
### Blacktip Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/bl1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/bl2.png?raw=true)

Whith the Blacktip Shark it appears that goes the other way as my hypothesis, it attacks more when is not their mating season.
### Spinner Shark
![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/s1.png?raw=true)

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/s2.png?raw=true)

Can see that it attacks more in the northern hemisphere, and it does not match the mating season, it attacks more when its not. In the other side of the world we notice that it does attack more but the season changes and theres only a few cases of attacks, almost lack of information so we can not make any conclution.
## Conclution.

All the information gathered throws that theres NOT a conclution that sharks attack more when they are in their mating season.

![conclusion](https://github.com/imalanz/SharkAttack_proy1/blob/main/Imagenes/EuJIQWdXIAE0myN.jpg?raw=true)