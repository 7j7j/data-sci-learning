# Learning resources in data science
Repo of various resources and links for anyone, but especially for motivated undegrad students who have asked via Penn FLASH for mentoring advice.

There are broadly <b>three pillars of data science</b>:
- <b>Statistics</b>, or knowing how to apply math
- <b>Computer science</b>, or knowing how to code math into tools and insights 
- <b>Domain knowledge</b>, or knowing the actual underlying reality and context of any data you handle so you can design and interpret analysis properly

My philosophy is that quants should respect quals and we should learn from each other. Numbers/quant outcomes point to effects existing and their magnitude, but it takes 
good qual to define what we should count as well as why and how it matters.

In theory you can self-learn any of the above, but it really depends on your own motivations and interests what you learn better in a classroom vs. outside of it. 
I have personally found my academic training, especially in grad school, essential for the stats and helpful for the coding. 
Domain knowledge is probably best guided by your personal passions and interests in any case. In my case, bio+social science have been in my studies and work for 
>10 years since freshman year in one form or another: public health is a really good meeting point of the two, and so is agriculture + nutrition.

# Classes at Penn

I did HSOC + ECON many, many moons ago as an undergrad. For health data science nowadays, I think HSOC + STAT or HSOC + CIS would be an even more potent combo.
However, it is very possible to be exposed to quant tools and research projects that directly translate into data science via BIOL, SOCI, PSCI, all of SEAS, etc. 
NB many of the best course options likely to be graduate-level, e.g. MS or MPH level biostats is most suited to real-world health data sci, but <a href="https://www.bio.upenn.edu/undergraduate/concentrations/computational-and-mathematical-biology">Penn biology major 
with computational and mathematical concentration</a> would be excellent at undergrad level.

Since I only really transitioned to data science in the last 5 years from my jobs in consulting, I don’t have direct advice for Penn classes beyond the intro stats and comp sci classes. It definitely looks to me like STAT 111, STAT 112, and CIS120 are important prereqs. The <a href="https://catalog.upenn.edu/undergraduate/programs/data-science-minor/">comp sci catalog</a> for Penn's data science minor looks solid. Beyond the prereqs, I don't think there is any obligation to do the full minor although it is obviously an official credential. I definitely suggest going where your interests take you - if you want to do scientific research or evaluation, tools in inference will tend to be your best bet, but creative product and service development includes a very contrasting set of skills, e.g. in NLP/text mining, GIS tools, generative networks, etc.

If you nail the initial stats classes, you might be able to get into some of the epi and biostats courses in the School of Medicine in your junior or senior year. Definitely ask with the appropriate academic faculty in SoM to check if they will plausibly let you in as an upperclass student to some of the <a href="https://www.med.upenn.edu/ggeb/bsta-course-descriptions.html">biostats (BSTA) classes</a> - this is more likely if you’ve fulfilled some prereqs like the STAT classes. 

<a href="https://economics.sas.upenn.edu/system/files/2019-01/Syllabus_Spring2019_Short.pdf">ECON/HCMG 236</a> is great if you end up doing more economics, but it is very much not an intro course so is only suitable if you do a lot of ECON and/or HCMG. I also personally took <a href="https://www.med.upenn.edu/globalhealth/assets/user-content/documents/PUBH519%20syllabus%202017.pdf">a great Issues in Global Health class (PUBH519)</a> and counted it toward my HSOC requirements. This class is mixed methods (not really data sci at all) but it is very policy-oriented and super interesting.

If you can’t get into the BSTA classes but you can be let into some of <a href="https://www.publichealth.med.upenn.edu/course-listing.html">PUBH ones on Penn's MPH</a>, definitely do those. Intro to biostats would probably be redundant with the above STAT courses, but Intro to Epi (PUBH502) would not and you will almost certainly find the math is easier in classical epi than in biostats. From a quick look at the current MPH syllabus, the most relevant classes to health data science would be:
-	PUBH517 – if you want to do geographic mapping and GIS data
-	PUBH521 – evaluation is one of the main applications of health data sci, although you should check if this one actually includes quant methods
-	PUBH605 – defo see some biostats/modelling tools implied there
-	PUBH610 – infectious disease modelling, i.e. using math to simulate germs; I gave a <a href="https://github.com/7j7j/SEIR-model-basics/blob/master/200610-NHSEI-huddle-SEIR-models-JS-vF.pdf">gentle intro talk</a> to NHS colleagues on some canonical tools in the space.

I am almost certain HSOC will let you count any of the above toward your major, if you can get into the classes. Other majors TBD.

Penn in general attracts a lot of hyper-talented applied statisticians so there are more names out there – definitely recommend sneaking into public talks or workshops if the
opportunity arises: some of the statisticians I frequently cite/read who are currently at Penn are Luke Keele, Paul Rosenbaum, and Eric Tchetgen Tchetgen. I don't think any 
of these folks teaches undergrads, but go hear them talk if you can! And know they have many more colleagues who are excellent and pushing the frontiers of data science.

This is not really undergrad level at all but there are public open seminars given by some of these folks and similar in my world of “causal inference”, organised by the Stanford stats department: https://sites.google.com/view/ocis/past-talks-and-recordings?authuser=0


# Peer learning resources
- SatRdays: https://satrdays.org/
- R Ladies: https://rladies.org/about-us/
- StackExchange: https://datascience.stackexchange.com/ (nb YMMV, sometimes the one-eyed lead the blind)

# Health-focused data science taster courses (Coursera, edX etc)
1.	A very decent-looking course on applied health data science using Python (Edinburgh): https://www.coursera.org/learn/datascimed#syllabus
2.	This one from MIT might also be in Python as well as R? https://www.edx.org/course/collaborative-data-science-for-healthcare
3.	A gentle introduction to stats epi and health data sci (Imperial College London, R): https://www.coursera.org/learn/introduction-statistics-data-analysis-public-health. See also https://www.coursera.org/specializations/statistical-analysis-r-public-health
4.	A more intensive biostats-oriented data science course (Johns Hopkins, R): https://www.coursera.org/learn/biostatistics
5.	The longer list here is actually not bad either: https://www.classcentral.com/tag/health-data-analysis

# A random selection of courses and tools to learn data science programming, especially in R 
1.	Good interactive package to learn R: https://swirlstats.com/ and see https://www.rstudio.com/resources/training/
2.	Andrew Ng’s very highly regarded intro to ML course (Stanford): https://www.coursera.org/learn/machine-learning
3.	A generalist data science course (Johns Hopkins biostats faculty,  R, pairing the class above): https://www.coursera.org/specializations/data-science-foundations-r
4.	Excellent open textbook in R, specifically Tidyverse (nb if Python and R are the two most common languages of data science, Tidyverse is a very different dialect to base R): https://r4ds.had.co.nz/
5.	Kaggle: https://www.kaggle.com/ (used to be for peer learning competitions, now has all sorts of resources from course content to message boards). It is okay to learn from hackathons but I would definitely recommend doing an intro course first so you can contribute some code/knowledge on how to build stuff.
6.	A textbook on time series forecasting, which is one of the methods I use: https://otexts.com/fpp2/
7.	Another excellent open textbook: https://www.statlearning.com/

# Commentaries (understanding ‘what is and isn’t data science’ rather than the mechanics of how to do it):
1.	“Statistics as a science, not an art: the way to survive in data science” (Mark van der Laan, Berkeley): https://magazine.amstat.org/blog/2015/02/01/statscience_feb2015/
2.	“Beyond the hype: big data concepts, methods, and analytics” (Gandomi & Haider): https://doi.org/10.1016/j.ijinfomgt.2014.10.007
3.	A sensibly skeptical view of unthoughtful or underregulated AI: https://weaponsofmathdestructionbook.com/
4.	A nice lighthearted book about what AI does, and its very real and hilarious limitations by an expert who makes them: https://www.janelleshane.com/book-you-look-like-a-thing

# Further resources compiled with fab London School of Hygiene colleagues about how to learn R: 
nb some overlap with the above
https://github.com/calumdavey/RUG/blob/master/February%202021/how_to_learn_R.md
