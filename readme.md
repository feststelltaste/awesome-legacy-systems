# Awesome Legacy Systems [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of awesome resources and links about tackling legacy systems that gives hope.

Hi! My name is [Markus Harrer](https://github.com/feststelltaste). I created this repository to share a set of resources and links that I found valuable and inspiring while working with legacy systems. I hope that you'll like it, too!
![](images/header_800.png)

<sub><sup>Image source: <a href='https://www.freepik.com/vectors/ancient-scroll'>Ancient scroll vector created by upklyak - www.freepik.com</a></sub></sup>

Legacy Systems are systems that you might be too afraid of to change. But they are necessary because they make all the money for your company. Thus, developers often have to maintain these older systems whether they want or not.

Legacy systems have their own fascinations and challenges that can be much more interesting than just gluing together some frameworks in a green-field project. But the lack of knowledge about how to tackle legacy systems is a big problem. Most developers just learn how to create new systems initially and not how to maintain existing ones or even evolve those systems. This list tries to close these gaps.


## Contents

- [Books](#books)
- [Blogs](#blogs)
- [Microsites](#microsites)
- [Podcasts](#podcasts)
- [Talks](#talks)
- [Conferences](#conferences)
- [Courses](#courses)
- [Lists of Tools](#lists-of-tools)
- [Other Languages](#other-languages)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

_The resources are ordered alphabetically the first author's surname for books and articles or the name of the resource for all the other resources)_


## Books

- [Robert Annett: Working with Legacy Systems (2019)](https://www.packtpub.com/product/working-with-legacy-systems/9781838982560) -  Short book that gives you plenty of tips on what you can do with legacy systems.
- [Len Bass, Paul Clements, Rick Kazman – Software Architecture in Practice (2021)](https://www.oreilly.com/library/view/software-architecture-in/9780136885979/) - Although this book focuses on software architecture in general, I like the idea of "architectural tactics" that propose solutions you can choose to fulfill specific quality goals like "deployability," "performance," or "security." This book could be a valuable source for you when you want to improve your existing system.
- [Marianne Bellotti: Kill It with Fire (2021)](https://www.penguinrandomhouse.com/books/667571/kill-it-with-fire-by-marianne-bellotti/) - A book that gives a fresh look at working with legacy systems. It contains plenty of tips to assess architectures and provides guidance as well as tips for keeping modernization plans on track.
- [David Scott Bernstein: Beyond Legacy Code (2015)](https://pragprog.com/titles/dblegacy/beyond-legacy-code/) - A book focussing on the agile way of improving legacy code. It includes plenty of material regarding improving processes and tips for better collaboration, too. If you want to see how agile methodology fits into the area of legacy system modernization, this book is for you.
- [Serge Demeyer, Stéphane Ducasse and Oscar Nierstrasz: Object-Oriented Reengineering Patterns (2003)](http://scg.unibe.ch/download/oorp/) - A book with plenty of patterns for tackling the challenges with legacy systems explained in great detail.
- [Michael Feathers: Working Effectively with Legacy Code (2004)](https://learning.oreilly.com/library/view/working-effectively-with/0131177052/) - The classic book that gives you hope for your old system with many small recipes for improving your old codebase.
- [Jens Knodel, Matthias Naab: Pragmatic Evaluation of Software Architectures](https://link.springer.com/book/10.1007/978-3-319-34177-4) - Albeit a book about software architecture evaluation, it provides plenty of ideas on how to find architectural problems in your systems. I especially like the structured approach that guides you through different levels, starting at the business level and ending at the code level.
- [Christine Koppelt, Markus Harrer, Gernot Starke, Benjamin Wolf, and Martin Otten (2021): Software Reviews - Identifying Risks and Problems in Software](https://leanpub.com/software-reviews-en) - A slim book that guides through the inventory of software systems including typical problems and questions to get to know the system.
- [Maude Lemaire: Refactoring At Scale: Regaining Control of Your Codebase](https://learning.oreilly.com/library/view/refactoring-at-scale/9781492075523/) - This book guides you if you need to refactor larger, complex codebases by providing tips about the right team, tools, and mindset. 
- [Carola Lilienthal: Sustainable Software Architecture - Analyze and Reduce Technical Debt (2019)](https://sustainable-software-architecture.com/) - On how to deal with eroded software architectures &ndash; and how they can be analyzed and improved with the help of elements from cognitive psychology in a tool-supported way.
- [Sam Newman: Monolith to Microservices - Evolutionary Patterns to Transform Your Monolith (2019)](https://samnewman.io/books/monolith-to-microservices/) - Shows various decomposition patterns for incrementally moving functionality out of a monolith. Focuses on microservices, but can also be used if you plan to split one application into several modules or systems (incl. the data).
- [Pini Reznik, Jamie Dobson, Michelle Gienow: Cloud Native Transformation - Practical Patterns for Innovation (2019)](https://learning.oreilly.com/library/view/cloud-native-transformation/9781492048893/) - Albeit focussing on cloud native development, the book provides many patterns that you can also use in the classic on-premises world to get your software and team organization fit for the future.
- [Christoph Stock: IT Rescue Guide - Strategies for IT Rescue Operations and Technical Debt Reduction (2023)](https://www.amazon.com/gp/product/B0C3CNJ21Y/) - A slim book about the modernization of software systems. Particularly beneficial are the many pitfalls that are pointed out, creating a realistic picture of the modernization of applications for the reader. Numerous, practical tips make the book particularly exciting for newcomers to the subject.
- [Girish Suryanarayana, Ganesh Samarthyam, Tushar Sharma: Refactoring for Software Design Smells, Managing Technical Debt (2014)](https://www.elsevier.com/books/refactoring-for-software-design-smells/suryanarayana/978-0-12-801397-7) - Presents a comprehensive catalog of 25 design smells, their role in identifying design issues, and potential refactoring solutions. Includes illustrative examples and anecdotes drawn from the trenches of real-world projects.


## Blogs

- [Philippe Bourgau's XP Coaching Blog: Refactoring Code and Orgs to a Sustainable Pace](https://philippe.bourgau.net/)
- [Nicolas Carlo: Understand Legacy Code: Change Messy Software Without Breaking It](https://understandlegacycode.com)
- [Torsten Mandry: Visualizing the progress of a refactoring into a hexagonal architecture using jQAssistant](https://www.innoq.com/en/blog/visualizing-progress-of-refactoring-into-hexagonal-architecture-using-jqassistant/) - tracking long-term architectural refactorings with architecture management tools. Nice application using constraints / rule violations to track the desired and current architecture style differences.
- [Peter Morlion: Helping companies tackle legacy code, and other software development musings](https://www.petermorlion.com/)


**Blog Posts**

- [Markus Harrer: 17 actions you can take to move your legacy system forward](https://twitter.com/feststelltaste/status/1451148235121299461) - A Twitter thread that lists which options you have when you want to do something with your legacy system.
- [Nick Tune: Legacy Architecture Modernisation With Strategic Domain-Driven Design (2020)](https://medium.com/nick-tune-tech-strategy-blog/legacy-architecture-modernisation-with-strategic-domain-driven-design-3e7c05bb383f) - A braindump that brings several methods for different legacy system modernization tasks together into one framework.

## Microsites

- [Architecture Improvement Method aim42](https://aim42.github.io/) - A collection of practices and patterns to support software evolution, modernization, maintenance, migration, and improvement of software systems. (transparency hint: the maintainer is one of the authors of this list).
- [Cloud Native Transformation Patterns: Tools for creating effective Cloud Native architecture &ndash; and remaking the way we work](https://www.cnpatterns.org/) - Collection of patterns on different levels (strategy, development, operations etc.) that show many ideas what one can do with existing applications that should be moved to the cloud. Many of the patterns work also for non-cloud environments.
- [Open Practice Library](https://openpracticelibrary.com/) - A collection of methods and practices that go beyond software modernization, but could be helpful if you're not only facing problems within software systems.
- [Patterns of Legacy Displacement: Effective modernization of legacy software systems](https://martinfowler.com/articles/patterns-legacy-displacement/) - A collection of procedures, patterns and experience reports around the piecemeal replacement of legacy systems.

## Podcasts

- [legacycode.rocks](https://www.legacycode.rocks/) - A podcast (and community) created by Andrea Goulet and M. Scott Ford from Corgibytes about the world of modernizing existing software applications.
- [maintainable.fm](https://www.maintainable.fm/)- A podcast by Robby Russell interviewing seasoned practitioners that know how to work with technical debt and legacy code.

**Podcast Episodes**
- [Grady Booch: Nine Things You Can Do with Old Software @ IEEE Software's On Architecture Podcast (2008)](https://www.computer.org/publications/tech-news/on-architecture/nine-things-you-can-do-with-old-software) - What you "can do intentionally with legacy code, from abandonment to evolution and many things in between" (taken from the podcast episode's description).
- [Andrea Goulet: Learning to love Legacy Code with Andrea Goulet from CorgiBytes @ Hanselminutes Podcast by Scott Hanselman (2016)](https://hanselminutes.com/539/learning-to-love-legacy-code-with-andrea-goulet-from-corgibytes)
- [Gernot Starke: aim42 with Gernot Starke @ Conversations about Software Engineering (2017)](https://www.case-podcast.org/14-aim42-with-gernot-starke)
- [Dave Thomas: SE-Radio Episode 242: Innovating Legacy Systems @ Software Engineering Radio (2015)](https://www.se-radio.net/2015/11/se-radio-episode-242-dave-thomas-on-innovating-legacy-systems/)


## Talks
- [Dylan Beattie: Ctrl-Alt-Del - Learning to Love Legacy Code @ NDC2019](https://www.youtube.com/watch?v=wPjHuvulivM&t=635s)
- [Marianne Bellotti: Future Proofing Systems @ MLH Fellowship 2020](https://www.youtube.com/watch?v=_ICzo5r-7vY)
- [Colin Breck: Using Quality Views to Tackle Tech Debt at Tesla @ QCon2017](https://www.infoq.com/presentations/quality-views-technical-debt/) - Colin Breck created a view of software qualities (or the absence from it) for bigger software systems to create more awareness for fixing technical debt.
- [Eric Evans: Strategic Design @ Øredev 2015](https://www.feststelltaste.de/should-i-rewrite-or-reengineer-a-software-system/) - Eric Evans shares his view towards a more business-driven approach to rewrites (links to a blog post because video is not public yet).
- [Dave Farley: From Legacy Code To STATE OF THE ART DEVELOPMENT @ Continuous Delivery YouTube Channel (2023)](https://www.youtube.com/watch?v=_gs3MjJBEfs) - Dave is a Continous Delivery advocate. In this video, he addresses the options you might take if you don't start developing a software system from scract / on the green field: Refactor, improve feedback cycles, introduce testing and automate deployment!
- [Michael Feathers: Strategic Code Deletion @ QCon 2017](https://www.infoq.com/presentations/remove-unneeded-code/) - Michael Feathers explains how to make sure features work well and how to get rid of unimportant code.
- [Andrea Goulet: Putting the Right Developers on the Right Projects @ DC FULL STACK 2017](https://www.youtube.com/watch?v=nVI2zfzKYqM)
- [Gregor Hohpe: The architect elevator - Connecting IT and the boardroom @ AWS re:Invent 2021](https://www.youtube.com/watch?v=nNbnXTl2VFQ) - A talk about connecting the different needs of different stakeholders of different layers of an organization. Great insights into how to motivate and translate modernization ideas from the engine room to something people in the penthouse can understand and work with.
- [Sabrina Leandro: How to rewrite, a bit at a time @ DDD Europe 2019](https://www.youtube.com/watch?v=AmicHHpogEg)
- [Maude Lemaire: How to get away with refactoring @ LeadDevAustin 2018](https://www.youtube.com/watch?v=34tLTZgvOxM)
- [Sandro Mancuso: Software Modernization: A strategic approach @ Trendyol Tech Meetup 2021](https://www.youtube.com/watch?v=HbbLpYSeAgk)
- [Sam Newman: Monolith Decomposition Patterns @ NDC Oslo 2019](https://www.youtube.com/watch?v=64w1zbpHGTg)
- [Gernot Starke: Improving Your Software @ GOTO 2016](https://www.youtube.com/watch?v=B8oJwY2Fq3I)
- [Jesse Toth: Easy rewrites with ruby and science! @ RubyConf 2014](https://www.youtube.com/watch?v=kgDqUHWVw4A) - A story told about rewriting the permission system at GitHub, a big, mission-critical part of the whole platform.


## Conferences
- [MenderCon](https://mendercon.com/) - A full-day virtual conference (and unconference) about modernizing and improving software systems.
- [The Legacy of SoCraTes](https://www.youtube.com/channel/UC0M37QolwmwobAY4Bt8Tszg) - An irregular online conference where speakers share their insights on how to approach legacy systems in a successful way. Plenty of talks from various directions make this resource valuable for people tackling legacy systems.


## Courses

- [iSAQB IMPROVE - Evolution and Improvement of Software Architectures (commercial offering)](https://www.isaqb.org/certifications/cpsa-certifications/cpsa-advanced-level/improve/) - A three-day workshop on addressing problems in legacy systems at the architecture, design, and code levels.
- [M. Scott Ford: Agile Software Development - Dealing with Legacy Code and Technical Debt (commercial offering)](https://www.linkedin.com/learning/agile-software-development-dealing-with-legacy-code-and-technical-debt)



## Lists of Tools

There are plenty of tools out there that can help you with your legacy systems. This section lists existing lists so that you can find your tool that fit to your specific needs:

- [Analysis-Tools.dev](https://analysis-tools.dev/) - Static analysis tools for many programming languages, build tools, config files and more.
- [Awesome Open Source - Profilers](https://awesomeopensource.com/projects/profiler) - Tools for in-depth runtime analysis.
- [OpenAPM](https://openapm.io/landscape) - Lists various Application Performance Management tools that can help you to find performance problems.


## Other Languages

This list focusses on contant in English. But there is also content out there in other languages.

- German: [Großartige Bestandssysteme](readme_de.md) - Eine kuratierte Liste mit großartigen Ressourcen und Links zum Umgang mit Altsystemen, die Hoffnung macht.


## Related Awesome Lists

This section lists other awesome lists in the area of legacy systems.

- [Awesome Legacy Code](https://github.com/legacycoderocks/awesome-legacy-code) - A curated list of legacy systems with publicly available source code.
- [Awesome Modernization](https://github.com/modernizing/awesome-modernization) - Awesome legacy system modernization tools. _(partly in Chinese)_
- [Awesome Software Analytics](https://github.com/feststelltaste/awesome-software-analytics) - A curated list of awesome resources and links about Software Analytics &ndash; a discipline that tries to analyze software data to get ideas about improving legacy systems.
- [Awesome Technical Debt](https://github.com/labcodes/awesome-technical-debt) - a curated list of Technical Debt talks, articles, and books. _(there might be some overlaps with this list)_

## Contributing

Did you like this list? Contributions are very welcome! Read the [contribution guidelines](contributing.md) first and add your ideas!
