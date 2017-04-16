---
layout: post
title: "Things I've Learned Doing Internships"
description: "What I've learned by working at many different companies"
category:
tags: [experience,internships]
---
{% include JB/setup %}

I'm a student at the University of Waterloo, famous for its co-op program where students do 6 4-month work terms throughout their degree. I've now done [7 internships](http://thume.ca/resume/) both within the program and outside it. Doing internships before one graduates is a great way of experiencing lots of different teams, work environments and even cities. This has allowed me to gain a much better idea of what kind of place I want to work after I graduate. Every job has taught me something genuinely new: my model of what factors are important to my enjoyment of a job has totally changed.

In this post I'll share some of what I learned at each different company, especially the things that surprised me and went against conventional wisdom or practice.

## Halogen Software

This was my first job, at a company that makes enterprise Java software for HR departments. Back then I was super enthused to have found a job, but nowadays this is the kind of place many of my friends would avoid just on the sound of it. There's a meme in Waterloo of "Cali or bust" where students try desperately hard to get jobs in California and are very sad if they have to settle for enterprisey boring-sounding jobs.

The thing is, I enjoyed this job and had fun! My coworkers were great and despite working on software many would judge to be boring I found the work engaging.

At Halogen I learned that even companies that exemplify all the stereotypes of a boring company (Java, B2B, CRUD, cubicals, not in California) can be good enjoyable places to work. Just because your job isn't at the hottest company in California doesn't mean it will be miserable.

## The Eclipse Foundation

My second job was an unpaid co-op job for credit in high-school where I would spend the second half of every school day working. I worked on fixing bugs in the Eclipse IDE off of the bug tracker.

<!-- I found this place by noticing it within 500m of my house on Google Maps and cold-calling them. I needed a job that was easy to get to for a half-day and it so happened that the organization behind the Eclipse Java IDE was close by. It turned out that they don't employ anyone working on the IDE, but the person I phoned was a former programmer and agreed to supervise me. -->

What I learned is that *tooling matters a lot*. It's not that the Java tooling I was using allowed me to figure things out faster, it's what allowed me to do things *at all*. I could wade in with no experience to a multi-million line code base and fix [11-year old bugs](https://bugs.eclipse.org/bugs/show_bug.cgi?id=2369) because the Java and Eclipse tooling was *so good*. The ability to view references and definitions with total accuracy and to follow things in an excellent debugger was key. An interesting Eclipse-specific feature was that every part of Eclipse was a plugin, so instead of spending hours compiling all of Eclipse, you could download the source for the relevant plugin, load it, then immediately press "Run" and it would start a new instance of Eclipse almost immediately that cloned your copy of Eclipse except for that one plugin. To this day it is the largest project I've worked on but it had a very fast feedback loop and short setup time, it was quite impressive.

Almost all of Java's faults as a language were made up for by tooling that was leagues better than any other popular language (excepting maybe C#). This job tempered my enthusiasm for how much more productive `$AWESOME_LANGUAGE` is than languages like Java and C# despite better design and handy features.

## Shopify

I worked at Shopify three times: twice during high school summers and once as my first Waterloo co-op job. As such, I learned a fair amount there, but the lessons were sometimes spread out, so I've grouped them together.

### Transparent and involved executives are fantastic

The CEO of Shopify, [Tobi Lütke](http://www.theglobeandmail.com/report-on-business/rob-magazine/meet-our-ceo-of-the-year/article21734931/), is incredibly awesome. He started as the first developer, and he makes sure to stay afloat with the latest developments and will even weigh in on technical strategy if you tag him on Github. As an intern it was pretty awesome to sit down on a couch with the CEO and hack on [Liquid](https://github.com/Shopify/liquid) together. He's also very transparent and makes sure everything about the company is too. For example, every couple weeks he does a frank AMA where he addresses questions submitted and voted on by employees and does a good job of giving detailed answers and not dodging.

On other fridays, employees give lightning talks about what they are working on. This is where one story that really exemplifies the difference between a great CEO and a stereotypical one happened: I was giving a short talk about flaws in the [Liquid](https://github.com/Shopify/liquid) template parser and how it would accept almost anything without a syntax error, and [my work in replacing it](https://github.com/Shopify/liquid/pull/235). My next term I learned that while watching my talk he'd joked to the person next to him  "that kid's got courage", which clued me in that at most other companies, trash talking code the CEO wrote that powered an important part of the product, in front of the entire company, would've been a "career limiting move" to put it lightly. I had talked to Tobi about the parser rewrite before the talk and he was in fact the first one to admit that the parser had issues, he had even bought a book on parsers hoping to fix it himself someday, so I knew I was safe giving the talk. Regardless, it still shows the benefits of having a great transparent CEO who does his best to rid the company of stifling corporate politics.

### Good managers make a big difference

Up until my last internship at Shopify I'd had good team leads, supervisors and managers. I recognized that they were important but they didn't really affect me or my work that much. This sounds like the lead up to a bad manager story, but actually the thing that changed my mind was having a *fantastic* team lead/manager.

He was dedicated, competent, funny, relentlessly positive, an excellent advocate for me and the rest of the team. He was also a developer but he spent most of his time being team lead, keeping everything on target, prioritizing, problem solving and making sure we were on target to ship on time.

He had a moderate impact on my productivity: prioritizing, distributing tasks, answering questions and pair programming on difficult tasks. However, he had a tremendous impact on environment of being on the team and thus my enjoyment of the job. I learned that having a good manager helps things run smoothly, but having an excellent manager can make a good job *great*. I hear that having a bad manager can make a good job terrible, but luckily I have yet to experience that (*crosses fingers*).

### If everything else is done right, the task doesn't matter

The importance of a good manager ties into my next point, which is that on that same team I was working on a CRUD web app, a stereotypically boring task. However, I really enjoyed that job, and through that I learned that when a company gets *everything else right* it doesn't matter very much what the actual task is.

When I was working at Shopify the third time, my team was great, my manager was great, the culture was great, the office was great, the tools were great, the language was great, the food was great, the focus on quality was great, the technical decision-making was great. It didn't matter that I was working on redesigning a web form.

This isn't to say the task doesn't matter at all. If the task was actually an unpleasant one and not just a less exciting form of programming, I wouldn't have enjoyed it nearly as much.

## The University of Waterloo HCI Lab

My next term, following my general strategy of trying out as many different jobs as possible, despite enjoying my previous job so much I tried out research. I worked on a system that fused eye tracking, head tracking and sound recognition to provide [a hands-free mouse alternative that I could use as quickly as I can a trackpad](https://github.com/trishume/PolyMouse). I also worked on custom computer vision systems for eye tracking and marker tracking, as well as developing custom audio recognition algorithms. I basically got free reign to work on a side project I had as a job and do exactly the work I wanted and found interesting.

### Further learning on project coolness

This switch from working on CRUD web apps to a cool project that I had chose myself furthered my learning from the previous term. Despite working on my choice of the most interesting topic, although I definitely enjoyed the job, I didn't enjoy it as much as my previous internship at Shopify.

There were two components to this:

First, the magnitude in difference of how interesting a project sounds doesn't correspond to the magnitude of difference in how interesting working on a project is. Working on cool computer vision systems involves a lot of architecture, plumbing, refactoring and debugging. Most of these tasks are the same kind of tasks one does when working on a CRUD web app. Even when I was working on redesigning a web form there were times when I had to go sit away from the computer and think really hard with a notepad about architectural issues and how to design the system in a clean and robust way. Despite massive differences in how interesting they sounded, the computer vision system only involved moderately more interesting difficult problems and slightly less boring plumbing than the CRUD web app.

Secondly, I found that even when I was working on the interesting challenging parts, I enjoyed and valued the challenge and learning, but not as much as I expected to value them before I started the job. The difference in fun was tangible but not as extreme as I had imagined.

Previous to this term I had systematically overvalued the importance of the challenge and interestingness of the task. I also see this a lot when people I know choose jobs, they'll sacrifice pay, company quality, location choice, team, culture, perks and pretty much everything else if it means they can work on something cool like compilers for machine learning on big data. I did exactly this as well for my research term.

Interestingness of the work is still a significant positive factor when I'm choosing a job, it just no longer overrides all other considerations, it's more of a factor I use to decide between two good options.

### Teams

One part of the difference between working in the lab and working at Shopify was that in the lab I was working alone on my own project. There were other people in the lab that I talked to occasionally but we didn't really work together or even eat lunch together.

I realized that great coworkers are an important part of why I enjoyed my previous jobs.

## Jane Street

For my next internship I worked at [Jane Street](https://www.janestreet.com) in London UK. I worked on developer tools, low-latency networking code, rendering huge tables and tree-diffing algorithms, all in OCaml. I had a great time, both with the interesting work and all the other parts of working there.

### Interviewing

The first thing that impressed me about Jane Street, because it was before I even started, was how good their interviewing system is. The questions seemed rather good at testing programming ability rather than algorithm knowledge or flashes of inspiration. They were about thinking hard, puzzling out all the cases and extracting a clean design. I was allowed to use a whiteboard, their laptop, or my own laptop, with any language I wanted. Each interview had two interviewers in the room, I assume for higher judgement reliability for the time spent. There were a reasonable number of interviews packed in to one day, and I got an offer a fairly short amount of time after I interviewed.

Later I learned that they have a set of people who specialize in interviewing and do substantially more interviews because they like to and for greater consistency and skill specialization. Each question is well-specified and alpha and beta tested before being used for decision-making. Becoming the lead of the two interviewers for a specific question requires having shadowed someone else who knows it well.

This interview process seems substantially better than any other process that I have heard of (with the possible exception of the Matasano process [tptacek on HN](https://news.ycombinator.com/user?id=tptacek) talks about, but I haven't looked into that much). It addresses many of the common criticisms of tech company interviews like algorithm bingo, requiring flashes of inspiration, requiring coding on a whiteboard, poor question design, inexperienced interviewers and lack of inter-rater reliability. It seems like it would have a very low false positive rate, and a lower (though still significant) false negative rate than other interview processes I've seen.

### Agency

Another thing that impressed me is the level of agency afforded to employees. The management structure was extremely flat, and everyone's job was basically either "Do what's best for the company, probably coding" or "Do what's best for the company, probably trading" with some people in between and a few "... with some managing" thrown in.

For certain type of company, this seems to work excellently. Competent people know that for decisions with sufficiently high stakes it is a good idea to seek input from others, and expend effort to make the right decision proportional to the stakes. This means there's little need for explicit policies, procedures and approval chains. That doesn't mean the value they provide is absent, they just happen whenever they make sense for the task at hand, like ops checklists and working with other people to make big decisions correctly. I was surprised by the extent to which "Do what's best" gets the benefits of standard corporate practices when helpful, but avoids the pitfalls. I still don't believe this is broadly applicable though, it needs a certain type of company to work well.

## Conclusion

My model of what a good job and an effective company looks like have changed significantly since before I started working. Since starting at Waterloo I've even precommitted to not doing repeat internships, so as to maximize the variety of jobs, locations, and companies I experience. It's tempting to return when I have a great time and a job is the best one I've ever had, but I remember that the only reason I took *that* job was that I didn't return to the *previous* best job I ever had.

I'm looking forward to further learning at 3 more internships before I graduate, including one in San Francisco at Google this summer. After I graduate, I'll look hard at all the different jobs I've had and will have a good model with which to decide what I want to do next. This will likely be returning to my favourite past company, but I might also use this information to choose a brand new path I'm confident is better.
