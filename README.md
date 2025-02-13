# Evo_dataset
Exploring the Hominin brain size
In this project I used a [Kaggle data set](https://www.kaggle.com/datasets/santiago123678/evolution-of-humans-datasets-for-clasification).  
This is a data set deposited on Kaggle and contains gathered evolutionary information from archaic 
hominin species, including modern human. The data covers different biological features (numerical and categorical variables), evolutionary 
time (in millions of years ago) and location of the fossil findings.

# Data Profile
The downloaded data was already in a good shape. There were no columns with mixed data types nor 
with missing or duplicated values. The data is categorical and numerical. There are 12000 observations 
spreading across 28 columns in total. 18 of them are describing different physiological/biological
features of hominins. Others describe their habitat, behavior, geographical location and the time
(when the fossilized findings were dated to). At this point, I’ll keep all the variables in, and in the course 
of analysis I may decide to drop those of them that not contribute to further findings.
I performed an initial data exploration where I’ve checked the distribution of numerical values and 
counts of observations within categorical values. I did some minor changes in the variable names as I 
find them incorrect, inconsistent or not clear (e.g. Genus_&_Specie → Genus_&_Species) and I 
exported the corrected data frame to a new .csv file.
Regarding the collection of these data, it was compiled by a Kaggle user – a student of biological 
anthropology. He based his knowledge e.g. on a publication from 2005, so the data may not ne up to 
date, but still comprises of many observations. It may also be not complete as he gathered the data 
from books and lectures. There may be more and newer data that could contribute to this compilation.
It may also be subjective as it probably wasn’t reviewed by anyone and he could choose what data to 
include. There was only one citation provided with the data set, so we cannot access the reliability of 
the entire content. He should have included all sources he has been using.

# Questions to explore  
In this exciting data set, we can find many potential questions to explore the human past. As a 
neuroscientist, I would like to explore the correlations of brain size and behavioral traces of hominins. 
In the second line, I would have a look at other biological features that could be linked to cognitive 
evolution. I’ll start with a set of few questions, and I leave the door open to new questions that may 
arise during the analysis.
1. What is the cranial capacity in hominins over the evolutionary time? Is there any trend?
2. Is cranial capacity different between the geographical regions at the similar/different time 
points or in general?

...and many more - but let's start with the most basic ones. And later there are some more to start with a deeper analysis:  

3. If there is any finding in question number 2, can we link it to habitat, diet or similar feature?
4. How does the cranial capacity correlate with biological features? (e.g. height, bipedalism, diet)
5. How does the cranial capacity correlate with behavior? (e.g. technology, migration)
6. Explore correlations of different features with each other, especially with the cranial capacity 
and technology use.

# Jupyter notebooks  
I used Jupyter notebooks to work with the data.  
In [first notebook](Exercise_6.1) I check the data consistency, correct or transform the data and perform some exploration.  
In [second notebook](Exercise_6.2) I did some data profiling, checked for correlations and did some plotting.  
In [third notebook](Exercise_6.3) I explored the geographical component of the data.  
In [fourth notebook](Exercise_6.4) I focus on linear regression analysis.  
And in the [fifth notebook](Exercise_6.5) I perform k-means clustering of the data.

# Visualizations
I've also created a [Tableau Story Board] (https://public.tableau.com/shared/56993Z99T?:display_count=n&:origin=viz_share_link) with these data.
