---
layout: post
title:  "Tuning topic modeling"
date:   2020-12-02 
categories: jekyll update
---
After successful installation of MITAO, I started tuning through the coherence score. There is a specific tool on MITAO to generate it. To interpret the value easily I suggest to plot it and see the range where the first valley falls under the mean value. That range should be the best number of topics, calculated through statistic formulas. It's still necessary to try and see if it acutally works for your data. Source: https://medium.com/@soorajsubrahmannian/extracting-hidden-topics-in-a-corpus-55b2214fc17d 

Once understood the best number of topics, it's time to generate topic models trying various parameters (with of without lemmatization, TFIDF or BOW, stopwords, multi-tokens...). You should try 2-3 reasonable models and finally decide which one better describes your situation.  

Try to explain why data vary through years (e.g. why in 2009 there are less articles than 2008)

MITAO allows for building two kinds of plots. In my case, time series is quite useful. But finally I'd like to show the geographic location of topics (it's possible to do it even with bar charts in MITAO)

What about conference papers? Full topic modeling or separated (one for journals and one for conferences). In the last case, I should then associate the resulting topics in both models. 



 