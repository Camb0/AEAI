# AEAI

###Making JS query to build structures from structure tab
Find the parent node using inspect (the div node that has an ID, in this case the "item_research-labs" node)
trace the children to the propper submit command as shown below

![Alt text](https://github.com/Camb0/AEAI/blob/master/ResearchJS1.jpg)

to build research labs, run `document.getElementById("item_research-labs").children[2].children[1].submit()` in console or using some JS extension.  This is done below, and as you can see the research labs were constructed successfully.

![Alt text](https://github.com/Camb0/AEAI/blob/master/ResearchJS2.jpg)


###Queries for structures using oldschool AE skin
The code is mostly the same for all of the structures with the exception to the *children[#]* entry which could be thought of as an index, with the nth structure in the list (starting at 0) being # 2n+1 `document.getElementById("base_structures").children[0].children[1].children[0].children[2].children[0].`**`children[#]`**`.children[6].children[0].submit()`
The indices of the first few structures available to a noob account are shown below.
![Alt text](https://github.com/Camb0/AEAI/blob/master/Oldschool.jpg)

It seems like we may have a challenge here with the fact that the indices available are dependent on the structures available in the list; we'll have to look into this more when we figure out how to use the queue, and what exactly happens with indices when certain structures become unavailable (due to lack of power or pop etc.).  We may need to analyze astros and project build orders far into the future based on potential build limitters.
