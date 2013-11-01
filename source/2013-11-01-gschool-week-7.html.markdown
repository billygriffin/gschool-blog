---
title: gSchool - Week 7
date: 2013-11-01 21:21 UTC
tags:
---
**Ummm...Progress?**

For our project this week, we split up into groups of three and the goal was to use Sinatra to replicate an existing website of a local business. I worked with Will and Darryl, and we chose to build the Clyfford Still Museum's website. The current site incorporated many of the skills that we were looking to learn, and we prioritized our project by laying out our desired functionality: 

*Museum's hours could be modified by an admin using forms (no direct html)
*Museum's programs could be added using forms
*Contact us page would have a form that when submitted, sends an email to the user
*Photos page could by dynamically changed by an admin using photo upload function

We managed to complete all these items, and were actually able to expand on them a bit. I had the opportunity to work with my mentors, Alex Welch (http://madebymonday.com), on expanding the functionality of the programs addition process. We decided to bubble up an error from the model all the way to the view so that when an admin did not complete all the required fields in the program form, it would not store that program into the database and would instead give them an error page and ask them to re-enter the program's information. This was a lot of fun to work on, and the first time I've ever used the technique of "bubbling up" an error. 

We also created a contact us form that not only sent the user a static email, but also dynamically generated an email to the museum that gave them the person's name in the subject line and their issue in the body of the email. We used the Pony gem for Sinatra to do this, and it was very cool to see it work the way we expected.

For the first couple days, Will and I paired together on the models while Darryl did some great work on the front-end templating. Darryl took a mess of an html code-base and changed things around to make it our own. Will really helped me finally grasp the idea of params and the interaction between the view and the controller relating to user input. By Thursday, I felt about as good as I have the entire program, and I finally feel like I'm **starting** to become self-sufficient in completing portions of projects.

While this week has been incredibly satisfying from the progress I've made, it has also been quite stressful as my business partner and I are in discussions with our largest advertiser regarding next year's budget, and simultaneously interviewing software development shops that we'll hopefully have the opportunity to work with on our project upon completion of gSchool. I'm learning a lot but it's quite overwhelming still not knowing very much about the technology. In that sense, the next four months of gSchool are hugely important to me solidifying my knowledge base and technical expertise. And while it's incredibly stressful, it's also really exciting.




