---
layout:     post
title:      "Writing Good code : Introduction"
subtitle:   "Because Data applications deserves high quality code"
date:       2015-08-21 12:00:00
author:     "Sourabh Rohilla"
header-img: "img/post-bg-06.jpg"
---


<p>Data Science, as a subject as well as a practice, in its essence is an multi-disciplinary effort. Today, more and more people from psychology, neuroscience, economics are analysing data in their subjects to come up with new insights and understand the subject better. This means that there are more people creating data products, and not all of them necessarily have a computer science major in undergraduate. I come from an Electrical Engineering major and got interested in Data Science soon after I graduated. I joined <a href="www.housing.com">Housing</a> as Business Intelligence Expert. First 6 months at Housing were mostly around solving business problems using the data we had. You have a problem statement, you have lots of data, you try to make sense of the data to come up with solution. Every analysis solved a problem, but that was the end of it. Very few analysis were re-usable. Since we are a fast moving organization, the problem space was huge. Solve a problem and move on. </p>

<p>But, after working for 6 months, I realised the importance of re-usable, reproducible analysis. Some problems are variations of the problems already solved. But, if analysis is done on Excel, you have to repeat the whole thing again. That was how automation of analysis made sense to me. Your analysis should be reproducible, re-usable. This is pretty important because a) It ensures that your analysis is a tangible output and not a couple of excel sheets with no shelf life. b) Your analysis can be taken forward and something else can be built on top of it. You get the common theme running here. Building applications is more impactful than running an analysis on excel since it has a long term value attached to it.</p>

<p>Now, this is the part where I mention the importance of writing good code. As I mentioned in the previous paragraph, people from multiple disciplines come together to collaborate and create value out of data. Writing a high standard code is a necessary pre-requisite to extract excellent long-term value proposition from data. Now, the good thing about writing quality code is, it can be learnt and its a combination of art and science. Here is a short excerpt I wrote after first production code push after a rigorous code review.</p>
<blockquote>"The last work week had one of the steepest learning curve of my life. Full of disappointments and anger. Every line of code which I thought was right, was completely changed by Bipul and Bhanu. The way I wrote code was to run everything. But, there is significant difference between a code that runs and a code that works. The former is a lego-style construction of pieces that (almost) run together.  The latter is holistically thought through and beautifully crafted. I think learning to write good code for me was similar to learning piano. You start out smooth, joining parts one by one, trying to fit them together. You start playing popular numbers, all by yourself. And you think, you are good at it. But, then you sit with people who have been doing it for a while.  Their way of looking at it completely blows your mind. For them, its not just about playing songs, its about getting every freaking key-stroke right, down to level of pressure you apply on note. They are looking at code at ways you never looked before. They make a story out of it and then point out broken plots and abrupt twists.   

You feel amused. Wow! this is one new style of doing things. But, then it becomes repetitive.  You start to get a sour taste of the monotonous activity. You are breathing your work, sickened by the familiarity. Reading same lines of code numerous times, almost to the point that they are subject of your unconscious dreams.It makes you question the relevance of this. But, when you get to other side, you realise the gravity of the exercise. Congrats, your code is a story now, and if someone can read it like a story, you can be sure that you did it right.”</blockquote>

In this series of 3 posts, I’ll walk you through my learnings around writing high quality code. Understanding the abstract nature of maxim “Writing high quality code”, I’ll try to keep the content crisp. It is highly relevant for people with limited prior exposure to programming. People who are mostly using tools to analyse but want to build their data applications ground up. We, at Housing, do most of our scripting in python, but the advice holds true for other programming languages. 
The 3 sections will be -  


1. The first code review : Writing good code  
2. Documenting your code : why its important  
3. Testing your code  : Because, that code is going to break.  