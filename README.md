# Resources on Software Architecture

This is a collection of resources on software architecture. You can find books, blogs, conferences, podcasts and other things.

Software architecture is a broad field. Therefore, the collection cannot be complete and does not intend to be. Its goal is to provide an overview on the (arguably) most important sources of information for software architects.

If you feel anything is missing, feel free to contact me and/or contribute.

## Books

The books are sorted by publication date of the 1st edition.

### General Software Architecture

All of the books in this list cover software architecture as a whole and can be used to get started with the topic. While they provide a good overview, they all have a slightly different focus or emphasize a different aspect. In the following list, these differentiating aspects are mentioned primarily.

- [Len Bass, Paul Clements, Rick Kazman: Software Architecture in Practice, 3rd Edition. Addison-Wesley Professional (2013)](https://www.pearson.com/uk/educators/higher-education-educators/program/Bass-Software-Architecture-in-Practice-3rd-Edition/PGM1009732.html) - One of the first and most influential books on software architecture from the [Software Engineering Institute (SEI)](https://www.sei.cmu.edu/). It covers various aspects of software architecture and introduces many basic terms and concepts, which are largely accepted by the community, today. Its specific focus lies on quality attributes as a driving factor for architecture design, as well as design, documentation and evaluation of software architecture. <!-- First edition published 1997 -->
- [Gernot Starke: Effektive Softwarearchitekturen: Ein praktischer Leitfaden, 9th Edition (German). Carl Hanser Verlag GmbH & Co. KG (2020)](https://www.esabuch.de/) <!-- First edition published 2002 --> - A practical introductory book in German by Gernot Starke. It also serves as the preparation guide for the certification ["Certified Professional for Software Architecture - Foundation Level"](https://www.isaqb.org/certifications/cpsa-certifications/cpsa-foundation-level/) of the [International Software Architecture Qualification Board (iSAQB)](https://www.isaqb.org/).
- [Eoin Woods, Nick Rozanski: Software Systems Architecture, 2nd Edition. Addison-Wesley Professional (2011)](https://www.viewpoints-and-perspectives.info/) <!-- First edition published 2005 --> Another one of the early classics of the topic and widely appreciated book. Focus topics are the decomposition and description of architectures using views and perspectives as well as the architecture creation process, particularly by stakeholder involvement.
- [Richard N. Taylor, Nenad Medvidovic, Eric M. Dashofy: Software Architecture: Foundations, Theory, and Practice. Wiley (2009)](https://www.wiley.com/en-us/Software+Architecture%3A+Foundations%2C+Theory%2C+and+Practice-p-9780470167748): A comprehensive and deep introduction to software architecture, which covers many different aspects of the topic, written in a more academic style, however. One of the first books to explicitly define software architecture as the set of design decisions made for the system.
- [George Fairbanks: Just Enough Software Architecture - A Risk-driven Approach. Marshall & Brainerd (2010)](https://www.georgefairbanks.com/book/) - More specialized introduction with a focus on architecture modeling. The risk-driven model aims to help architects to focus on the most important aspects, hence the title "Just Enough".
- [Ian Gorton: Essential Software Architecture, 2nd Edition. Springer (2011)](https://www.springer.com/gp/book/9783642191756) <!-- First edition published 2010 --> - A shorter introduction to software architecture. Besides the basic concepts (terms, quality attributes, documentation, architecting process) it covers several special topics such as middleware, service oriented architectures, aspect-orientation, model-driven architecture or product lines.
- [Stefan Toth: Vorgehensmuster für Softwarearchitektur: Kombinierbare Praktiken in Zeiten von Agile und Lean, 3rd Edition (German). Carl Hanser Verlag GmbH & Co. KG, (2019)](https://www.hanser-elibrary.com/doi/book/10.3139/9783446460096) Not a general introduction to software architecture, this book is more focused on providing practical tips on how to work as an architect in modern development teams, specifically in agile development settings. He lists many different patterns for architecting activities to make decisions, collaborate in the team and sustain solution concepts over time. <!-- First edition published 2013 -->
- [Michael Keeling: Design It! - From Programmer to Software Architect. The Pragmatic Bookshelf (2017)](https://pragprog.com/titles/mkdsa/design-it/) - Unlike the title suggest, the book is not focused solely on design, but provides a general and modern introduction to software architecture. An important aspect of the book is the application of design thinking principles for architecture design. Besides this, it provides numerous hints for the work of architects, including an activity catalogue for achieving different goals.  
- [Mark Richards, Neal Ford: Fundamentals of Software Architecture - An Engineering Approach. O'Reilly Media, Inc. (2020)](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) - The newest kid on the block and therefore the most modern introduction to software architecture. It gives a broad overview of different software architecture aspects including architect's leadership skills. A specific focus lies on the introduction and detailed description of various architecture styles.

### Software Architecture Design

The following list contains books, which focus specifically in architecture design. As such they provide detailed information on design approaches and patterns.

- [Frank Buschmann, Kevlin Henney, Prashant Jain, Michael Kircher, Regine Meunier, Hans Rohnert, Douglas C. Schmidt, Peter Sommerlad, Michael Stal: Pattern-Oriented Software-Architecture (POSA) Vol. 1-5. Wiley (1996-2007)](https://www.wiley.com/en-us/Pattern+Oriented+Software+Architecture%2C+Volume+1%2C+A+System+of+Patterns-p-9781118725269) - A series of five books, which present and explain architectural design patterns for various contexts and problems. Not something to read from cover to cover but rather to be used as a work of reference when designing a system's architecture.
- [Eric Evans: Domain-Driven Design - Tackling Complexity in the Heart of Software. Addison-Wesley Professional (2003)](https://www.pearson.com/us/higher-education/program/Evans-Domain-Driven-Design-Tackling-Complexity-in-the-Heart-of-Software/PGM168436.html) - Eric Evan's book has gained a lot of attention in recent years, also because of its good fit to the microservice architecture style. Many other books on the topic have been released (like [Vaughn Vernon: Implementing Domain-Driven Design](https://www.pearson.com/us/higher-education/program/Vernon-Implementing-Domain-Driven-Design/PGM311783.html) or [Michael Plöd: Hands-on Domain-driven Design - by example](https://leanpub.com/ddd-by-example)) and there is now an active [community](https://github.com/ddd-crew) which continuously refines and extends its concepts. It promotes design that is driven by the application domain (in contrast to technical aspects) and introduces a strategic (in the large) and a tactical (in the small) design approach, which is regarded as the de-facto standard by many today. While it presents many useful concepts, it cannot serve as the one and only holistic approach, as for example quality attributes are left out entirely (no silver bullet).
- [Martin Fowler: Patterns of Enterprise Application Architecture. Addison-Wesley Professional (2003)](https://www.pearson.com/us/higher-education/program/Fowler-Patterns-of-Enterprise-Application-Architecture/PGM298863.html) - Another absolute classic of pattern books, written by Martin Fowler. It lists and explains many essential architectural patterns for enterprise applications, many of which are implemented in today's technologies and infrastructure components. Unlike other pattern books, it is not only a reference book, but contains also several narrative chapters, which are informative and well readable at the same time.
- [Sam Newman: Building Microservices. O'Reilly Media, Inc. (2015)](https://samnewman.io/books/building_microservices/) - Specialized book on how to design and build systems following a microservices architecture style by Sam Newman. Besides it being a very popular architecture style, the book covers many topics that are relevant for distributed and general system design as well.
- [Martin Kleppmann: Designing Data-Intensive Applications - The Big Ideas Behind Reliable, Scalable, and Maintainable Systems. O'Reilly Media, Inc. (2017)](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) - In his book, Martin Kleppmann covers various topics related to the management, processing, transport, storage and retrieval of data. Besides the foundational concepts which are implemented in the technologies we typically use for building systems, he highlights many important aspects to consider when designing such data-intensive systems.

### Software Architecture Documentation

The following list contains books, which describe how to document and communicate software architecture.

- [Paul Clements, Felix Bachmann, Len Bass, David Garlan, James Ivers, Reed Little, Paulo Merson, Robert Nord, Judith Stafford: Documenting Software Architectures: Views and Beyond, 2nd Edition. Addison-Wesley Professional (2011)](https://www.pearson.com/uk/educators/higher-education-educators/program/Clements-Documenting-Software-Architectures-Views-and-Beyond-2nd-Edition/PGM914471.html) - The book in the [SEI](https://www.sei.cmu.edu/) series on software architecture documentation and the one and only book specialized on the topic in English. It has a strong focus on introducing their viewtypes (module, component&connector, allocation) and corresponding architectural styles, in which somehow design and documentation mix. With this, it presents a more formal and detailed approach to documentation. <!-- First edition published 2002 -->
- [Stefan Zörner: Softwarearchitekturen dokumentieren und kommunizieren: Entwürfe, Entscheidungen und Lösungen nachvollziehbar und wirkungsvoll festhalten, 2nd Edition (German). Carl Hanser Verlag GmbH & Co. KG (2015)](http://www.swadok.de/) A practical guide on how to document software architecture, written in German. To a large extent it makes use of the [arc42 template by Gernot Starke and Peter Hruschka](https://arc42.de/). <!-- First edition published 2012 -->

### Software Architecture Evaluation

The following books cover approaches for evaluating and analyzing software architectures and related artifacts.

- [Paul Clements, Rick Kazman: Evaluating Software Architectures: Methods and Case Studies. Addison-Wesley Professional (2001)](https://www.pearson.com/us/higher-education/program/Clements-Evaluating-Software-Architectures-Methods-and-Case-Studies/PGM55893.html) - The book in the [SEI](https://www.sei.cmu.edu/) series on the evaluation of software architectures, using the well known [Architecture Tradeoff Analysis Method (ATAM)](https://resources.sei.cmu.edu/asset_files/TechnicalReport/2000_005_001_13706.pdf). The approach focusses on eliciting architecture drivers from stakeholders and evaluating the architecture with regard to these drivers.
- [Jens Knodel, Matthias Naab: Pragmatic Evaluation of Software Architectures. Springer (2016)](https://www.springer.com/gp/book/9783319341767) - Jens Knodel and Matthias Naab wrote a book on their Rapid Architecture Evaluation (RATE) method, which is originally based on ATAM, but adapted to integrate their experiences from over 50 architecture evaluations with various companies over many years. It includes different checks on different levels and of different artifacts, such as architecture drivers, the adequacy of the architecture, the quality of the documentation or the compliance of the implementation.
- [Christine Koppelt, Markus Harrer, Gernot Starke, Benjamin Wolf, Martin Otten: Software Reviews - Identifying Risks and Problems in Software. Leanpub (2020)](https://leanpub.com/software-reviews-en) - A short guide for software reviews, which also presents analysis approaches on different levels and for different artifacts.

### Coding

Architects must know what they abstract from. So, knowing good programming is highly recommended for architects.

- [Dave Thomas, Andrew Hunt: The Pragmatic Programmer. From Journeyman to Master, 20th Anniversary Edition, 2nd Edition. Addison-Wesley Professional (2019)](https://www.pearson.com/store/p/the-pragmatic-programmer-your-journey-to-mastery-20th-anniversary-edition/P100002723040/9780135957059?tab=overview) Very influential book that many areas of working successfully as a professional developer. Considered as an absolute must-read book by many.<!-- First edition published 1999-->
- [Robert C. Martin: Clean Code: A Handbook of Agile Software Craftsmanship. Pearson Education (2008)](https://www.pearson.com/us/higher-education/program/Martin-Clean-Code-A-Handbook-of-Agile-Software-Craftsmanship/PGM63937.html) - The classical book by Uncle Bob describes how to write good code, for example by choosing good names, formatting right, testing well, handling errors, etc.

### Other Software Architecture-Related Topics

- [Michael Nygard: Release It! - Design and Deploy Production-Ready Software, 2nd Edition. The Pragmatic Bookshelf (2018)](https://pragprog.com/titles/mnee2/release-it-second-edition/) - In his very popular book, Michael Nygard describes how to design and build systems for real-life production and operation. It provides information and hints for achieving many quality attributes, which are important for productive software systems, such as reliability, stability or operability.  <!-- First edition published 2007 -->
- [Jez Humble, David Farley: Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment. Addison-Wesley Professional (2010)](https://www.pearson.com/us/higher-education/program/Humble-Continuous-Delivery-Reliable-Software-Releases-through-Build-Test-and-Deployment-Automation/PGM249879.html) - The classic book about continuous delivery by Jez Humble and Dave Farley.

## Blogs & Articles

### Architects' Blogs

- [Martin Fowler's Blog](https://martinfowler.com/)
- [Uwe Friedrichsen's Blog](https://www.ufried.com/blog/)
- [Gregor Hohpe: The Architect Elevator](https://architectelevator.com/)
- [Stefan Tilkov's Blog](https://tilkov.com/)
- [Werner Vogels: All Things Distributed](https://www.allthingsdistributed.com/)

### Companies' Tech & Engineering Blogs

- [Airbnb](https://airbnb.io/)
- [LinkedIn](https://engineering.linkedin.com/blog)
- [Netflix](https://netflixtechblog.com/)
- [Uber](https://eng.uber.com/)
- and many more

### Tech Articles

- [DZone](https://dzone.com/)
- [InfoQ](https://www.infoq.com/architecture-design/)
- [InnoQ](https://www.innoq.com/en/written/)

## Podcasts

- [Conversations about Software Engineering - CASE Podcast](https://www.case-podcast.org/)
- [Heise Developer: SoftwareArchitekTOUR (German)](https://www.heise.de/developer/SoftwareArchitekTOUR-4076349.html)
- [InnoQ Podcast (German)](https://www.innoq.com/de/podcast/)
- [Software Engineering Radio](https://www.se-radio.net/)

## Videos

- [Eberhard Wolff: Software Architektur im Stream (German)](https://software-architektur.tv/)
- [InfoQ: Presentations](https://www.infoq.com/presentations/)
- [GOTO Conferences](https://www.youtube.com/user/GotoConferences)

## Conferences

### Practitioner Conferences

- [Global Software Architecture Summit](https://gsas.io/)
- [GOTO Conference](https://gotopia.tech/)
- [JAX / W-JAX](https://jax.de/)
- [OOP (German)](https://www.oop-konferenz.de/oop2022.html)
- [QCon](https://qconferences.com/)
- [Software Architecture Alliance (German)](https://www.software-architecture-alliance.de/)
- [Software Architecture Gathering](https://conferences.isaqb.org/software-architecture-gathering/)

### Scientific Conferences

- [European Conference on Software Architecture (ECSA)](https://conf.researchr.org/home/ecsa-2021)
- [International Conference on Software Architecture (ICSA)](https://icsa-conferences.org/)

## People to Follow

- [Kent Beck](https://twitter.com/KentBeck)
- [Grady Booch](https://twitter.com/Grady_Booch)
- [Jan Bosch](https://twitter.com/janbosch)
- [Simon Brown](https://twitter.com/simonbrown)
- [Neal Ford](https://twitter.com/neal4d)
- [Martin Fowler](https://twitter.com/martinfowler)
- [Kevlin Henney](https://twitter.com/KevlinHenney)
- [Gregor Hohpe](https://twitter.com/ghohpe)
- [Allen Holub](https://twitter.com/allenholub)
- [Uncle Bob Martin](https://twitter.com/unclebobmartin)
- [Sam Newman](https://twitter.com/samnewman)
- [Michael Nygard](https://twitter.com/mtnygard)
- [Michael Plöd](https://twitter.com/bitboss)
- [Mary Poppendieck](https://twitter.com/mpoppendieck)
- [Stefan Tilkov](https://twitter.com/stilkov)
- [Eberhard Wolff](https://twitter.com/ewolff)
- [Uwe Friedrichsen](https://twitter.com/ufried)
- [Eoin Woods](https://twitter.com/eoinwoodz)

<!-- ## Must-read Papers

- [Dewayne E. Perry and Alexander L. Wolf: Foundations for the study of software architecture (1992).](http://users.ece.utexas.edu/~perry/work/papers/swa-sen.pdf) SIGSOFT Software Engineering Notes 17, 4, 40–52. DOI: <https://doi.org/10.1145/141874.141884>
- [David Garlan, Mary Shaw: An Introduction to Software Architecture (1993).](https://www.cs.cmu.edu/afs/cs/project/vit/ftp/pdf/intro_softarch.pdf) Advances in Software Engineering and Knowledge Engineering Volume I, World Scientific Publishing Company, New Jersey.
- [David Garlan, Robert Allen, John Ockerbloom: Architectural Mismatch: Why Reuse Is So Hard (1995).](https://www.ics.uci.edu/~taylor/ICS221/papers/ArchMismatch.pdf) IEEE Software. 12, 6, 17–26. DOI: <https://doi.org/10.1109/52.469757>
- [Mary Shaw and Paul C. Clements: A Field Guide to Boxology: Preliminary Classification of Architectural Styles for Software Systems (1997).](http://www.cs.cmu.edu/~Compose/Boxology.pdf) Proceedings of the 21st International Computer Software and Applications Conference (COMPSAC '97). IEEE Computer Society, USA, 6–13.
- [Mary Shaw: The Coming-of-Age of Software Architecture Research (2001).](https://www.cs.cmu.edu/afs/cs/project/vit/ftp/pdf/shaw-keynote-rev.pdf) Proceedings of the 23rd International Conference on Software Engineering (ICSE '01). IEEE Computer Society, USA, 656.
- [Mary Shaw and Paul Clements: The Golden Age of Software Architecture (2006).](https://ieeexplore.ieee.org/document/1605176). IEEE Software, 23, 2, 31-39. DOI: <https://doi.org/10.1109/MS.2006.58>
- [Anton Jansen, Jan Bosch: Software Architecture as a Set of Architectural Design Decisions (2005)](https://www.ics.uci.edu/~andre/ics223w2006/jansenbosch.pdf). 5th Working IEEE/IFIP Conference on Software Architecture (WICSA'05), 109-120, DOI: <https://doi.org/10.1109/WICSA.2005.61>
- [David Garlan, Robert Allen, John Ockerbloom: Architectural Mismatch: Why Reuse Is Still So Hard" (2009)](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1074&context=library_papers). IEEE Software, 26, 4, 66-69, DOI: <https://doi.org/10.1109/MS.2009.86> -->

<!-- ## More Resources

- -->

## More Resources on Software Architecture

- Stefan Tilkov and Michael Stal did an episode on ["Resources for Software Architects"](https://www.heise.de/developer/artikel/Episode-46-Ressourcen-fuer-Softwarearchitekten-2299439.html) in the [Heise Developer SoftwareArchitekTOUR podcast](https://www.heise.de/developer/SoftwareArchitekTOUR-4076349.html)
- Gregor Hohpe wrote on article about an [architect's bookshelf](https://architectelevator.com/architecture/architect-bookshelf/) on his blog.

## License

[![License: CC0-1.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

[domrost](https://github.com/domrost) has dedicated this work to the public domain by waiving all of his rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.
