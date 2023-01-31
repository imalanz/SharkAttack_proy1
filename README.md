# SharkAttack_proy1
![portada]!(.\Imagenes\maxresdefault_(1).jpg)

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

![conclusion](.\Imagenes\cc0bbc404c539aef74b8f1f3549869e1.png)
## Data exploration.

With the new cleaned CSV file could make the graphics and analysed it better.


## Conclution.

All the information gathered throws that theres not a conclution that sharks attack more when they are in their mating season.

![conclusion](.\Imagenes\EuJIQWdXIAE0myN.jpg)