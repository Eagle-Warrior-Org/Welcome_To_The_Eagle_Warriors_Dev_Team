### 01.02 Dev Choices ###

*Author:* Mike Rehner \
*Date:* 2/21/25 \
*Revised* 5/8/25 \

One thing I am unsure of is setting up a development environment for this project.

1. Should we use notebooks. If so I would favor Jupyter Lab but I am fairly agnostic 
in my choice. This choice allows for comment panels to be included next to the code. 
It also allows notebooks to be more easily shared. Unfortunately I also find writing 
code in notebooks to be more slower than in an IDE. 

Currently we are not using notebooks for development. Notebooks add an 
extrra layer of info that obstructs a clean view of the code.

2. Should we use a standard IDE instead. Currently I am writing markdown pages in
VSCode but I have more experience with PyCharm. One IDE may have better connections 
to the AI we choose and have a better AI assistant than another IDE. I do not have
a clear vision on this at this time, but raise this issue so as to not get locked 
in at a later date. I have not had experience using an AI assistant to write code.

Currently we are using the Python IDE/editor of our individual choice

3. Definitely need a requirements.txt file so that everybody is on the same page
with versioning on what modules we are using.

4.  I feel comfortable with markdown for all documentation pages. I notice that the 
readme file is <html> which is ok with me- jst more keyboard strokes. 

5.  I propose to not work on the main branch. We should make a copy of the 
	main branch work on the copy and then merge the copy into main. A good 
	name for the copy might be *'dev'*.. 

[Table of Contents](../TOC.md)
