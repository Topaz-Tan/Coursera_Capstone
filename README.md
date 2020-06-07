# Coursera_Capstone

Blogpost: Findings from 'Exploring Singapore'

Hi I'm Topaz, the founder of Paz's Salted Egg Cookies.

Our research started off with finding the best neighbourhood to launch our next outlet. We wanted to identify neighbourhoods based on the their general type. Are they residential like Bukit Timah? Tourist hotspots such as SIngapore River? Have MICE facilities for expats and international businessmen like Marina Bay? Or are they shopping districts like Orchard.

These are just one of the many factors to take into account when opening a new store, and luckily Data Science can help us out!

From our research, we can conclude that the best locations to set up shop would be in neighbourhoods from clusters 4 and 5, such as Orchard and River Valley. This is because these neighbourhoods are popular shopping destinations for both locals and tourists alike, thus foot traffic here will likely be the highest.

Other factors which we could explore in a subsequent analysis would include cost of rental in these neighbourhoods, as well as customer segmentation and sampling to determine their taste and preferences. This is important because in land-scarce city like Singapore, the high rental rates often determine if a business succeeds or fail. For example, using the mean price/sqft rental rates, we can easily plot a choropleth map to visualise the varying rental rates across the different neighbourhoods.

Our Analysis of each neighbourhood is also limited by where we identified our Geographic Centre of each neighbourhood. For example, the Southern Islands neighbourhood was identified to be a poor choice in our model, as FourSquare only identified boat trips as the main attraction for this neighbourhood. 
In fact, Southern Islands actually encompasses Sentosa, which being a tourist hotspot might be a good location for us. However, the tourist attractions were not captured as they fell outside search radius of one kilometer from our centre.

Thus, further refinement of our model using further information and data will be highly beneficial to helping us further evaluate which neighbourhood to open our next store at. Will you like to see Paz's Salted Egg Cookies come to your neighbourhood? Let us know!
