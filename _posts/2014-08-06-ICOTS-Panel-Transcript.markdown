---
layout: post
active: Blog
ptitle:  "ICOTS discussion on technology in statistics education" 
categories: teaching
img: "2014-07-17 15.44.54-1.jpg"
---

One of the most interesting sessions I attended at ICOTS was the panel session, [Future trends for technology in statistics education](http://icots.info/9/session.php?s=9H). The panel was chaired by [Chris Wild][CW] of Auckland, and featured

- [Deb Nolan][DN], UC Berkeley
- [Nick Horton][NH], Smith College
- [Bill Finzer][BF], Common Online Data Analysis Platform (CODAP)/Fathom
- [Webster West][WW], Texas A&M/StatCrunch. 

Because I was so fascinated by the discussion, I ended up creating an almost-complete transcript of the discussion (biased by my personal interests, of course). I thought it was possible that someone else might be interested in my transcript, so I'm posting it here. Beyond my own interest bias, I'm sure that I've mis-attributed an idea here and there. Please let me know if there's something I should change to be closer to the truth!

<!--more--> 

<a class="thumb" href="#"><img src="{{ site.baseurl }}/img/{{ page.img }}" class="img-responsive" alt="The panel"></a>
*The panelists helping attendees find the last few seats (eventually, it was standing-room only)*

The first question posed to the panel by Chris Wild was 

> what do you consider the most exciting developments in technology for statistics education?

[WW][WW]: Student centered data collection.

[NH][NH]: Open source tools, giving more students access.

[BF][BF]: The recognition that data science as essential, and technology making it possible to integrate it into the whole curriculum.

[DN][DN]: The popularity of data science and interest by students. 

From that question, the discussion really just moved to a more fluid form, where panelists fed off each other's comments and moved the conversation forward. Here are some of the comments that caught my ear. 

[NH][NH]: There isn't going to be one "intro course," there will be many courses. A second course needs to cover thinking with data, data wrangling, data munging (or whatever you call it). Hadley's stuff is good, and uses simple verbs. Students should have the ability to do something with real world data.

[DN][DN]: Students need to be exposed to more than one technology. Don't just turn the R crank. [At some point in the discussion, [DN][DN] shared that students often call her statistical computing course "the R course," which makes her cringe.]

[WW][WW]: I struggle to come up with the right verbs (for describing the tasks students need to be able to do, especially in terms of code). But, we all do. Maybe it's better to start with examples. Visualize point A, point B, see how to do it, and then determine what skills are needed.

[BF][BF]: "Data immersion" is an experience everyone should have, regardless of discipline.

Another question arose here, perhaps raised by Chris Wild. 
> What are the advantages and disadvantages of menu-driven paradigms versus programming?

[WW][WW]: I write code that helps people do menu-driven things. Many teachers are unreachable when it comes to code, and menu-driven can help.

[DN][DN]: There's a difference between coding and scripting. Scripting is simpler, coding is more complex. To code, you need some understanding of control flow, etc. Scripting is more interacting at the console. 

[BF][BF]: In Fathom, you have a collection, and you can sample from it. That's essentially a loop. If you're going to be a data scientist, you need to think computationally. 

[NH][NH]: We need to think developmentally. Think about when parents are upset because they can't toilet train their baby. You say, I'm confident by the time they're 18, they'll be okay. Then work backward from there. [Ed: I've lost what this analogy was supposed to be about. Is the baby a statistics student, and the toilet-training teaching them to code? Insights on this one would be appreciated].

Coding lets you document your workflow. It's much harder to do this in an interface. This helps with reproducibility, which we've basically decided is a good thing. Down the line, you want peer reviewers to be able to look at your data and code. Biologists have lab notebooks, that helps them be reproducible, and they see this in courses.  

[BF][BF]: Ubiquitous data computing is coming. Imagine your Personal Data Calculator. Just like you always have something to write with, you will have a PDC. Technology for working with data will be just as pervasive as other technologies. 

[NH][NH]: Shiny lets me quickly make an applet that would take 6 months for a Java developer. There's a speed up in the creation of tools.

[WW][WW]: In StatCrunch, I want to let textbook authors script their own applets (versus scripting artisanal applets for each author individually). This is coming down the road. 

[DN][DN]: In the past, I've tried making education games. One was a hospital that you tour around in. This effort was in Java, but we didn't have the manpower. I had ideas about interactive dynamic documents, same thing. Shiny is making a difference, although I would prefer to be "down one level." There's a difference between dynamic and interactive-- dynamic means that output is automatically created for you from code. Interactive means that a reader can play with sliders, etc. 

[BF][BF]: [Paraphrasing [DN][DN]] "So, a learning technology is something that will be out of date in 10 years?"

From [Chris Wild][CW], 
> there's a design problem (that's always the same) and an implementation problem.

[NH][NH]: Michael Bulmer's ["Island"](http://escholarship.org/uc/item/2q0740hv). It's a big thing to take on.

[DN][DN]: You can bring design in through simulation studies.

[NH][NH]: Looking at health services research: they use non-random data (e.g. from billings) to find out things about health. This is much the same as the problem we're facing now. This is what we should be aiming for.

[DN][DN]: There's a lot of room to grow in computer science at the high school level. This will change what we do at the college level.
"Have you heard about R.N. Jesus?" Stands for Random Number Generator, but you pray to it to get good numbers in a game. WoW is a super polished game. We don't have the skills to build something polished like that.

Some time around here, the panel was opened up to questions from the audience. I'm not sure exactly what point that was. Nonethless, there was another question for the panel-- 
> what will we be talking about at ICOTS 10 in 2018?

[BF][BF]: There will be learning log data available. I hope statistics ed people will be using this data.

Then, someone (maybe [Rob Gould](http://www.stat.ucla.edu/~rgould/Home/About_Me.html)) proposed a definition for Data Science. From my understanding of the comment, I sketched a Venn diagram in my notes which looked something like this:
<a class="thumb" href="#"><img src="{{ site.baseurl }}/img/DataScience.jpg" class="img-responsive" alt="Data Science Venn Diagram"></a>

An audience member suggested [CoderDojo](coderdojo.com) as a resource for students, which makes it cool to code, says every kid can code. [Ed: I think these types of claims are usually very limited to kids with a lot of privilege]

[Randy Pruim](http://www.calvin.edu/~rpruim/) asked the panel, 
> is there a dark side to this? Now, anyone can make a pretty graph, but it might not mean anything. There are thinking skills that are necessary.

[DN][DN]: We've always had this problem.

[WW][WW]: We should be doing things like text analysis in intro classes. Students get out of intro classes, they think data is just numbers.

[BF][BF]: Personal data should be meaningful to individuals. It should be able to be worked with. 

And with that, my transcript ends. See, I told you it might only be interesting to me! Those who were there, what insights did I neglect to capture? 

[CW]: https://www.stat.auckland.ac.nz/showperson?firstname=Chris&surname=Wild "Chris Wild"
[DN]: http://www.stat.berkeley.edu/~nolan/  "Deb Nolan"
[NH]: http://www.math.smith.edu/~nhorton/   "Nick Horton"
[BF]: http://cadrek12.org/users/william-finzer "Bill Finzer"
[WW]: http://www.stat.tamu.edu/~west/          "Webster West"