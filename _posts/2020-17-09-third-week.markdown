---
layout: post
title:  "Where can I find my data?"
date:   2020-09-17 
categories: jekyll update
---
In this week I kept working on the methodology trying to answer the following questions:
- How can I select relevant articles? 
- Where will I find relevant data? 
- How will I gather them?

Collecting only research papers is not as easy as it looks. I studied the structure of the journals and the types of articles they publish, looking for common practices in specifying articles types. Unfortunately, not only each journal defines their own types of articles (if they even define them at all), but they also rarely tag this information within the summary, article page or metadata. It looks like that the first step for my data retrieval, the selection of relevant DOIs, will be manual. 

I did not consider citations databases such as Crossref or Microsoft Academics as my first source for data retrieval since they would not guarantee the fidelity and accuracy of abstracts in particular. So I thought I would get information from the articles web pages through scraping. 

The list of collected DOIs will be passed to a Scrapy spider to get articles information like abstract, author, institution, publication date etc. Usually at least some of the info are in the metadata (in Highwire Press or PRISM or Dublin Core tags), but eventually something is missing and has to be retrieved directly from the HTML page content. 

Finally, I had some ideas about the final data visualization. I will probably use d3js.

# Activities
- Created a <a href="https://docs.google.com/spreadsheets/d/1mspU0dKRB93t2cc6sqHKDEIcYS-7ogkmilyGMKOJfqo/edit?usp=sharing" target="_blank">Google Sheet</a> to collect my notes about journals 
- Wrote some Scrapy spiders to become familiar with the logics
- Review my XPath syntax knowledge


 