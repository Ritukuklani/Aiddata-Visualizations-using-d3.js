# Aiddata-Visualizations-using-d3.js

# AidData-Visualization
Visualization with D3.js

**Data:**

***AidData.csv*** <br>
Each line in the dataset represents a country and contains the total amount donated and received by the country

***countries.geo.json***<br>
Annotated geo-json geometry file for the world

## Visualization 1
Developed various visualizations such as diverging bar charts etc. to answer the three below questions:
1. Do the countries that donate the most tend to cluster around specific geographical areas of the world?
2. Do the countries that receive the most tend to cluster around specific geographical areas of the world?
3. Are there neighboring countries that have radically different patterns in terms of how much they receive vs. how much they donate?

# More
[Visualization 1](https://observablehq.com/d/423d1add793ef745)

## Visualization 2
Developed various visualizations such as multiple line charts, heat maps, choloropleth maps etc. to answer the three below questions:

1: a) How does the amount donated vs. amount received change over time for each country?; b) Are there countries that mostly send or mostly receive and countries that have a similar amount of donations they receive and send?; c) Are there countries that change their role over time? That is, they used to mostly send donations and turn into mostly receiving donations and vice-versa?; d) Are there countries in which you can find a sudden increase ("peak") or a sudden decrease ("valley")?


2: Focus on the top 10 “Coalesced Purposes” of donations (in terms of amount of disbursement across all countries and all time). What are the top 10 purposes of disbursements (in terms of total amount of disbursement) and how does their relative amount compare over time? E.g., are there purposes that tend to be prominent for a period of time and others that become more prominent during other periods? Hint: looking at the graph one should be able to observe: “Ah! During these years donations were mostly about X but then there were way more donations about Y”. Note: if the purpose is “UNSPECIFIED” it should be removed.


3: Focusing exclusively on countries that receive donations, how do donations shift geographically over time? Do donations tend to be always in the same regions of the world over the years or they have been shifting over time? Can you build a visualization that shows the “history of donations” so that one can get a sense of which regions of the world have had more need for donations over the years? Note 1: for this visualization you can, if you wish, use interaction (but you don’t have to). Note 2: For this exercise you may want to review the lecture on geographical visualization in which we explain how you can visualize geographical data over time. Note 3: if you want you can aggregate data over a few years (say, group together data at 5 year intervals).

# More
[Visualization 2](https://observablehq.com/d/df2cdbf767444794)

## Visualization 3
Developed various visualizations such as sankey diagrams etc. to answer the three below questions:

1: Create an overview of the relationships between countries so that it is possible to see who donates to whom and how much. The main question one should be able to answer is: who are the major donors and to which countries do they donate the most and how much? And conversely, who are the major receivers and which countries do they receive from the most and how much? We only care about the top 10 recipients and the top 20 donors (over the whole time) for this question.

2: Considering only the top 5 purposes of donation, how does the relationship between countries look like in terms of purposes? What composition (distribution) of  purposes do the donations between each pair of countries have? Are there countries that donate to a given country using multiple purposes? Or do counties always donate using one single purpose when donating to another country? The same as the previous question, we only care about the top 10 recipients and the top 20 donors here.

3: For this last exercise you have to extend the analysis above to see how the patterns of donations change over time. Focusing again on the top 10 recipients and top 20 donors how do the patterns of donations (who donates to whom and how much) change over time? Are there sudden changes? Are there countries that always donate to other countries? Are there major shifts (say a country used to donate to a specific set of countries and then it changes to other countries)?

# More
[Visualization 3](https://observablehq.com/d/00f412e3e0a2daab)
