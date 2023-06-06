# Gun Violence in America

## Background
This is a data analysis project in which I take a closer look at shootings in the United States going back as far as 1982. Stories about shootings have dominated international news headlines in the recent past. Hearing about a different shooting almost every other day is concerning to say the least. My attention was captured as soon as I stumbled on [this](https://www.kaggle.com/datasets/nidzsharma/us-mass-shootings-19822023) dataset on `Kaggle`.

## The data

### Cleaning
At first glance the data appeared messy with problems ranging from incorrect and inconsistent data types to observations containing only hyphens (-). I split a few columns, changed the data type on a couple more, filled some 'missing' values, worked on a few abbreviations, performed a lot of string operations, Googled a few specific cases and eventually arrived at a usable dataset. The beauty of working with a real world dataset like this one is that observations can be verified through a Google search. 

I saved the clean data in a .csv file called 'showered_shootings'.

I exclusively used `Pandas` for the cleaning process.

### Analysis
I looked at the yearly shootings and broke them down further by month. 

I analyzed the shootings by state and narrowed that down by city. Next I dug deeper into specific locations such as schools, places of worship and workplaces.

The age of the perpetrators, their mental status, race and gender are also covered in the analysis.

Legality of the weapons involved in the shootings is also taken care of.

I concluded by ascertaining how many of the cases were mass or spree shootings. The difference between the two is laid out in the notebook.

`Pandas`, `Numpy`, `Seaborn` and `Matplotlib` were the tools used.

## Dashboard
I went a step further and built this interactive dashboard using `Tableau`. 

![Screenshot (11452)](https://github.com/Sabacon/Gun-Violence-in-America/assets/121859090/fe33cd9f-abb1-4f03-8375-608b8b04e754)

[You can also find it here.](https://public.tableau.com/shared/QFW7WWX34?:display_count=n&:origin=viz_share_link)
