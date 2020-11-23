---
layout: post
title:  "The discovery of ROR"
date:   2020-11-06 
categories: jekyll update
---
My supervisor and I defined a method to extract country data from affiliations data. After cleaning affiliation data (sometimes I found multiple affiliations in the same string), I queried them through the ROR Api [1]. Results were obviously not perfect: I set a high threshold to only write the most compliant results with my query (hopefully 100% exact). Also I had to clean the query string since some affiliations had too many information (departments etc.) that worsened the results. 
The final affiliation data had, in the end, an original name (the one I had from the beginning) and other normalized data according to ROR (and GRID [2]) database. 

# Decisions
- I did not use pdf miner since there is basically no documentation and I couldnt make it work in 2 days. I got the affiliations manually, it required less time (hours anyway) 
- In some journals information were impossible to find and I had to make inferenes from Google results. There might be discrepancies, this has to be mentioned as a disclaimer: some data are official, some are not. 

# To do
- Normalize the affiliation “Independent scholar”
- Harmonize dates in iso standard yyyy-mm-dd 
- Set up everything to do the ROR queries thing!
- Find a way to extract DSH data... 

[1] https://github.com/ror-community/ror-api 
[2] https://www.grid.ac/institutes





 