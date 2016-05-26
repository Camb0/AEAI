# AEAI

###Making JS query to build structures from structure tab
Find the parent node using inspect (the div node that has an ID, in this case the "item_research-labs" node)
trace the children to the propper submit command as shown below

![Alt text](https://github.com/Camb0/AEAI/blob/master/ResearchJS1.jpg)

to build research labs, run ``document.getElementById("item_research-labs").children[2].children[1].submit()`` in console or using some JS extension.  This is done below, and as you can see the research labs were constructed successfully.

![Alt text](https://github.com/Camb0/AEAI/blob/master/ResearchJS2.jpg)
