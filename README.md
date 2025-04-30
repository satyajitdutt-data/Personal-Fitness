![]([Fitness_dashboard.png](https://github.com/satyajitdutt-data/Personal-Fitness/blob/main/Fitness_dashboard.png))


This repository consists of a dashboard that tracked my fitness journey from Feb-Jun 2023. It's important to note that I am 171 cm or 5'8"
so the caloric intake was in proportion to my height when it came to fat loss.

I imported my cycling/movement data from Google Maps Timeline in JSON format obtained from the timeline above. I then thoroughly 
explained the process of parsing it into Python and flattening it for utilisation as a Pandas dataframe, with further details 
provided in the accompanying Jupyter notebook. Interestingly I biked on average 8 km per day, with a noteworthy observation of biking 11 km on average on Fridays!

I downloaded my supermarket bills in pdf form and was able to extract every item that I paid & the amount I paid for each item. As with the JSON
file, I explained how I parsed it into Python and was able to load it into a Pandas dataframe with details in the accompanying Jupyter notebook.
I filtered out the non-FMCG items and calculated the share of expenditure in each FMCG category + the average amount I spent per week. 

I spent about 47% of my FMCG expenditure on chicken, which is fascinating especially as the price of chicken rose significantly in Germany in this time!

The dashboard also contains a breakdown of:
- My daily caloric intake and how much of that was split between protein, fats and carbs
- My body weight tracked from Feb-Jun 2023
