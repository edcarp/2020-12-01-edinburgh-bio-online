===============================================
SBS Data Carpentry R for Genomics workshop December 2020
===============================================

https://edcarp.github.io/2020-12-01-edinburgh-bio-online/

Workshop overview
===============================================

38 people signed up for the course, 6 PDRAs, 21 PhD students, 1 fellowship applicant.
We had 8 people on the waiting list, and 2 cancellations; registration had filled up in 2 days.
35 people attended the first session, down to 32 at the 4th session; only 7 came to the last "data surgery" session.

All attendees were in School of Biological Sciences, except one U. of Aberdeen EASTBIO PhD student whose second supervisor is in SBS, and one Daphne Jackson Fellowship applicant.

Teaching was led by Edward Wallace and Flic Anderson (SBS RA).
Helpers were Bryan Wee (SBS), Elliott Chapman (SBS), Bailey Harrington (IGMM), Giacomo Peru (SSI) 

We used the university's noteable server for coding: https://noteable.edina.ac.uk/
We used the university's zoom to run online: 

*Overall workshop post-mortem:*

- We had great feedback from happy and satisfied learners.
- Noteable worked well, mostly, except being down during the last (smaller) session.
- Don't know if we'd run so close to Christmas again, or so close to an "end of semester".
- We had website editing issues, partly arising from problems with the workshop template genomics-r-intro.
- We split time-slots between mornings and afternoons over 3 weeks. Potentially have the time slots same times on different days? How else should we re-time it?
- We didn't set expectations for learners in between workshops. Could we set that expectation by giving a "challenge" or a non-marked "homework" between, to reinforce workshop material?
- Could we give more preparation to help people think into the data surgery (if we run it again)
- It took a lot more time to get material into a teaching state than we expected.
- The material (https://github.com/edcarp/genomics-r-intro) was pretty good, with a few fixes & polish still needed. We need to put in some pull requests to the datacarp repo.
- We included a transcriptomics "module" this time, which we did not need to include.
- We could teach this curriculum again, and be clearer about it being a genomics-focused workshop.
- It would be helpful to state learning outcomes in advance.

Detailed feedback, direct from learners, below. At every session, we ask learners to contribute one good/positive point and one bad point/suggested change.


Learner responses: What has motivated you to learn R? 
===============================================

- I will be starting an RNASeq project soon and I realise that I have absolutely no idea how to deal with RNASeq data. Also being able to produce reproducible data analysis is always a plus in the scientific community.
- Data visualisation 
- Reproducible code, share analyses with others.
- Make nice figures
- I want to be more competetively employable, more useful at work currently (especially with coronavirus and more remote working), and also just have a more enjoyable challenge of using our group's genomic and genetics datasets.
- hopefully I'll learn more about RNA-seq data analysis and also statistical data anlysis
- I would like to be able to analyse and visualise my data more efficiently than is possible with spreadsheet software. 
- Have been using pandas, seaborn, and Biopython in Python. Been told that I should do those things in R for numerical and bioinformatics because the libraries are more mature and faster computation
- I want to use R for RNA seq data analysis 
- I want to use R to make informative graphs
- Repeatability of data analysis
- Improve ability to write reproducible code
- I'm figuring out which language is best to analize my genomic/gene expression data, R or Python. Hope to find it out.
- to analyse RNAseq
- Data visualisation, use R for statistical analysis for next year
- Although I dont have many direct applications of R in my work right now, I think that its a powerful language essential for many large scale studies. 
- It seems to a me a core skill for any researcher dealing with data (so, all of us), so wanted to start off my PhD on the right foot! 
- I use R because it's good for cleaning data, flexible statistical analyses such as regression, and modular plotting (ggplot2!). But I was originally motivated to learn R because my postdoc adviser said "you need to use R".
- To analyse my proteomic datasets consistently over my PhD (a nightmare in excel) + ggplot graphs


Data organisation in spreadsheets  - 01/12/2020
===============================================

Edward Wallace led teaching.

The Good
--------

- Liked the fact that it is also designed for beginners who have no experience with R 
- Group discussions in breakout rooms were useful for exploring the material. Especially with helpers present!
- I enjoyed discussions in the breakout rooms
- Easy language used to comunicate with participants and good group discussions.
- Good use of examples to show us how to not organise our data.
- comprehensive, useful introduction, with good examples on data collecting mistakes
- Got some useful ideas for data organizations.
- I appreciated the laid-back and informal style, which makes learning something that some people find challenging a bit easier!
I can now go back to my data and reform them! Really good information. 
- negative examples are helpful in illustrating what to avoid
- It was good to discuss different exercises in the breakout rooms
- good use of polls and sharing links in the chat. I liked that time was taken at the beginning to make sure everyone was familiar with the Zoom functionalities.
- I liked the style, and the network element of the (Edinburgh) Carpentries. A fantastic learning environment and resource. The format and direction was excellent, and the breakout rooms were very helpful.


The Bad
--------

- It was great. I like how you were talking slowly for us to get things  
- I think it would be good to change breakout rooms between different discussions to get a broader range of interactions with people
- Nothing!
- would appreciate if there would be a "perfect example" of how things should be done (apart from the final NGS spreadsheet)
- If possible change breakout room sometimes, just to have more variations of ideas
- during group discussion it may be helpful to encourage the use of the pad - just to get ideas recorded and organized
- I would like to have examples from other biological data apart from sequencing. 
- Would be interesting to see published studies that have used "problematic" data and how they could have generated different results.




Introduction to R and Rstudio, R basics - 02/12/2020
===============================================

Felicity Anderson led teaching.

The Good
--------

- It was good to start coding and see it's not so scary.
- Really great. I have learnt a lot 
- this was great again, thank you, great explanation to basics! troubleshooting was very efficient too
- the structure of the intro was wonderful, especially the emphasis on self-help functions prior to diving into the common commands
- Liked frequent checks that everyone was understanding 
- Easy to follow and greatly structured intro
- Very clear explanations and easy to follow up.
- Great intro into R!
- Great introduction to R, very nice and easy approach from Flic.Thanks!
- Very clear explanations from Flic. Great to see the basics.
- Really good introduction to R studio, I feel comfortable navigating the GUI now :). 
- Very clear explanantions. And the helpers were great and really quick in addressing problems. Thanks a lot everyone!!!
- Clear connection and progression of concepts - excellent presentation


The Bad
--------

- when introducing the dataframe I was slightly lost as to what outputs I was looking at. May be it would be helpful to show the dataframe and let us know what outcome we are expecting when doing, say, extract column REF. `> View(variants)`
- Everything was great, thank you
- Hopefully next coding won't be a big jump from the basic to something too complicated.


Aggregating and Analyzing Data with dplyr - 08/12/2020
===============================================

Felicity Anderson led teaching.

Good
====

- Really liked the dplyr overview from the beginning of the lesson. And Flic is infectiously positive in her manner!
- Very clear session by Flic. I especially liked how you included an example of how to download data from a 'real' website rather than example.csvs. Tibble was also a great addition that I did not know about before. 
- Very useful tools for searching information from big data set. 
- It was a very productive day in terms of using code with real data and how to filter and manipulate them. Looking forward to see some data visualization with plots tomorrow!
- Very useful, thanks everyone!
- Thanks Flic, great session!   very useful information, i feel much more confident about how R works with 'real data'
- Found it really useful to go through the different functions
- It was good to have an example of acquiring data from the internet
- The overview over what most functions tries to do is tremendously helpful in conceptualizing what the functions do
- I feel like dealing with files from different places is one of the most intimidating things about using R for data analysis, so great to get some practice with that in in this session. Found it really useful! 
- It is a bit confused when I try to read ribi file, but finally I did it. It was really good to get to know new stuff and quite exciting, thanks so much.



Bad
===

- The time spent on the first part of the tutorial was disproportinate to the second part and the more insteresting things were in the second part! 
- I don't like the Notable server - had to switch to local 
- I got a bit confused when we moved onto the yeast data, I wasn't sure why we were downloading the table of annotations, and what the experiment from the paper was.
- Consistency in using functions, if introduced pipe then it would be best to stick to always using pipe, switching between `%>% select(args)` and `select(.data, args)` did ocassionally lost me. And perhaps `unique(ribi_annotation$Qualifier)` instead of `distinct(ribi_annotation, Qualifier)` might save some explanation
- I would agree that the pace was effected by the issues some people were having and I would have liked to have finished the section. But I understand this is a difficult problem to get around, and Flic was a great instructor! 



Data visualisation with ggplot2 - 09/12/2020
===============================================

Edward Wallace led teaching.

One thing they learned about ggplot
====

- I learned the labs(caption) command to put a text caption at the bottom of the plot.
- it's really much more personalisable than excel and that the help (?) function can really help 
- I learned that it is possible to create a nice plot then use the same code to create another plot with exactly the same format with different data
- I learned how to create a graph and actually re-use it the next time, instead of loosing time trying to adjust it in excel every time
- I found the ggplot commands really intuitive, feel much more comfortable with plotting in R now. Also the importance of the help function! 
- I never really understood the colour brewer stuff in my previous exposures to R. It now seems quite straightforward.
- I learned to make a nice plot but didn't manage to change colors of the titles in the axes.
- `scale_...` seems very useful.
- moving the legend around - new to me! Also {ggplot2} is part of {tidyverse} package - I've only used and loaded it separately before
- I leaned how to make violin plots
- I have leaned how to make plots and assign colours to plots, this was my expectation for the workshop
- I learned about `theme_void`
- I learned how to import my data and kind get to know how to play arround ggplot, that's really useful thanks so much.
- Themes and labs seem to share some similar functions and is worth looking into the docs (Edward: labs specify the content of text, theme specifies the apperance.) Right! Just realized I mixed them up. Thank you!


Good
====

- I enjoyed the collaborative approach from the instructors and helpers, to give clear answers to learner questions.
- It was a wonderful introduction to ggplot. I certainly learned a lot. Many of the questions asked by others are shared by me!
- I really enjoyed the fact that we are given the chance to play around with what we have learnt
- I really  enjoyed learning plotting in an explorative way, it makes me confident in trying new options and functions myself, the pace of teaching was perfect as well 
- I enjoyed that you managed to summarise the most important bits to help us understand ggplot 2 and showed what it can do
- I thought this session was really useful, especially the emphasis on exploring options via the help function and teaching yourself as you use ggplot (and R more generally). 
The functionality of ggplot and layering was well explained
- Everything was very nicely explained and I really like the handout on the website, really useful

Bad
====

- I wish the teaching could have been a little slower 
- During the self-practice and exploration, I was a little undecided in what to look into. I think I might do better if there are specific asethetics I am asked to do and I look it up using the Help. Thank you
- I find these sessions a little overwhelming in the amount of content, given the complexity of the topics at hand. All I would really want are longer sessions to spend more time!
- Maybe it could be helpful to also have some specific exercises to work through during the exploration time


Data surgery - 15/12/2020
===============================================

This was experimental session "Data surgery - Bring your own data to discuss how to use tools of the class to tidy, analyze, and visualize."

Full guidelines were sent here: https://github.com/edcarp/2020-12-01-edinburgh-bio-online/blob/gh-pages/data-surgery-guidelines.md

Only 7 learners showed up, down from 32 the previous session. Only 4 sent emails saying they weren't coming, so we're not sure why they didn't come. Maybe it was too hard to conceptualize the task, that close to the holidays?

Sam Haynes (SBS) served as additional helper, we had almost 1:1 helper-learner ratio, which was great.

Good
====

- It was really good to have the opportunity to ask questions about how to plot data I am interested in. I aslo learnt some new functions that were not covered previously
-This was really great, thanks, I found it very useful to learn specific tidying and function tips for my own data! 
-This was fantastic, I really enjoyed a lot and got some tips on to analyse my own data. Thanks so much.
-I really appreciate that the essence of attending the workshop was achieved at the end. I am forever grateful.



Bad
====

- I can't think of anything to change, I thought it was great. Thanks!
