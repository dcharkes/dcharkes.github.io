# Daco Harkes

I am a PhD student in the [Programming Languages Research Group](http://eelcovisser.org/wiki/group) at the [Delft University of Technology](https://www.tudelft.nl/) under the supervision of [Eelco Visser](http://eelcovisser.org/).
I am interested in programming languages in general, and specifically in declarative programming and incremental computing.
My research is focussed on declarative programming for (web-based) information systems.
During my PhD I have created IceDust, a domain-specific language for incrementally computing derived values in information systems.

I am an active participant in the research community.
I was the part of the [SPLASH 2015](https://2015.splashcon.org), [2016](https://2016.splashcon.org), and [2017](https://2017.splashcon.org) organizing committee as [Student Volunteer Co-Chair](https://conf.researchr.org/profile/conf/dacoharkes), and volunteered at [SPLASH 2014](https://2014.splashcon.org), [ECOOP 2015](https://2015.ecoop.org/), and [ECOOP 2016](https://2016.ecoop.org/).
I have attended two Dagstuhl Seminars: [Domain-Specific Languages](http://www.dagstuhl.de/en/program/calendar/semhp/?semnr=15062) and [Programming Language Techniques for Incremental and Reactive Computing](http://www.dagstuhl.de/en/program/calendar/semhp/?semnr=16402), and cooperated in editing the [report](http://dx.doi.org/10.4230/DagRep.5.2.26) of the first.

## Publications

2017

__IceDust 2: Derived Bidirectional Relations and Calculation Strategy Composition__  
__Daco C. Harkes__ and Eelco Visser.  
In _31st European Conference on Object-Oriented Programming (ECOOP 2017)_, Schloss Dagstuhl, 2017.  
[[DOI](https://doi.org/10.4230/LIPIcs.ECOOP.2017.14),
 [PDF](http://drops.dagstuhl.de/opus/volltexte/2017/7251/pdf/LIPIcs-ECOOP-2017-14.pdf),
 [Poster](publications/poster-sen17.pdf),
 [Video](https://youtu.be/cNDH253BIGI),
 [Artifact](http://dx.doi.org/10.4230/DARTS.3.2.1)]

__IceDust Calculation Strategy Composition Performance in Web Applications__  
__Daco C. Harkes__ and Eelco Visser.  
In _International Workshop on Incremental Computing (IC)_, 2017.  
[[PDF](publications/IC17-IceDust.pdf)]

2016

__Icedust: Incremental and eventual computation of derived values in persistent object graphs__  
__Daco C. Harkes__, Danny M. Groenewegen, and Eelco Visser.  
In _30th European Conference on Object-Oriented Programming (ECOOP 2016)_, Schloss Dagstuhl, 2016.  
[[DOI](https://doi.org/10.4230/LIPIcs.ECOOP.2016.11),
 [PDF](http://drops.dagstuhl.de/opus/volltexte/2016/6105/pdf/LIPIcs-ECOOP-2016-11.pdf),
 [Poster](publications/poster-sen16.pdf),
 [Video](https://youtu.be/bp7eiihouEU)]

__Language Design for Validatable Information System Specifications__  
__Daco C. Harkes__  
In _30th European Conference on Object-Oriented Programming (ECOOP 2016) - Doctoral Symposium_.  
[[PDF](publications/ECOOP16-DocSym-IceDust.pdf)]

2015

__Relations in Role-Based Data Modeling, Navigation and Updates__  
__Daco C. Harkes__  
In _ACM Student Research Competition 2014 Finals, 2015_.  
[[PDF](http://src.acm.org/binaries/content/assets/src/2014/dacocharkes.pdf),
 [PDF(2)](publications/SRC-Finals15-Relations.pdf)]

2014

__Unifying and generalizing relations in role-based data modeling and navigation__  
__Daco C. Harkes__ and Eelco Visser  
In _International Conference on Software Language Engineering (SLE 2014)_, Springer, 2014.  
[[DOI](https://doi.org/10.1007/978-3-319-11245-9_14),
 [PDF](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2014-023.pdf),
 [Poster](publications/poster-splash14.pdf)]

__Relations: a first class relationship and first class derivations programming language__  
__Daco C. Harkes__  
In _13th international conference on Modularity - Student Research Competition_, ACM, 2014.  
[[DOI](https://doi.org/10.1145/2584469.2584473),
 [PDF](publications/Modularity14-SRC-Relations.pdf),
 [Poster](publications/poster-modularity14-src.pdf)]


## Projects

__IceDust__  
IceDust is a domain-specific language for data modeling and calculating derived values.
The data modeling in IceDust features bidirectional relations and multiplicities.
These multiplicities are part of the type sytem, avoiding null pointer exceptions.
Derived values in IceDust are specified as expressions (not unlike Excel).
These derived values can be calculated on-demand, incrementally, or eventually.
The IceDust compiler generates code for incremental and eventual derived value updates.
The various calculation strategies can be composed, and the IceDust type system checks for sound composition.  
[[Source](https://github.com/MetaBorgCube/IceDust), 
 [Download](http://buildfarm.metaborg.org/job/metaborgcube/job/IceDust-EclipseGen/job/master/lastSuccessfulBuild/artifact/dist/eclipse/)]

__PixieDust__  
PixieDust is a domain-specific language for building reactive client-side browser applications.
Views are defined as functions in PixieDust, and the PixieDust compiler generates code which maintains views incrementally.
PixieDust is a language extension of IceDust.  
[[Source](https://github.com/MetaBorgCube/PixieDust)]

__WebLab__  
WebLab is a learning management system with automatic grading of programming assignments based on unit testing.
WebLab contains extensive grading rules for composed assignments: weighted averaging, deadlines (and personal deadline overrides), late penalties, bonus assignments, pass n-out-of-m, etc.
Moreover, WebLab features extensive progress statistics for course managers.
All these calculations are expressed in IceDust.  
[[Link](https://weblab.tudelft.nl/)]

## Teaching

2017

__Supervising MSc Students__  
Currently I am supervising two master students.
One is working on PixieDust (see above), the other is working on a domain-specific language for terminating computations.
I hope to link to their theses and papers here soon.

2015

__DSLDI Summer School__  
At the [DSLDI summer school of 2015](http://vjovanov.github.io/dsldi-summer-school/) I assisted at the hands on for building languages with [Spoofax](http://spoofax.org).
I helped people getting started, and had to answer various questions about syntax, static semantics and transformations.

2014

__Teaching Assistance__  
I developed the lab for the [Concepts of Programming Languages course](https://weblab.tudelft.nl/ti2606/), based on the [Principles of Programming Languages](http://cs.brown.edu/courses/cs173/2012/book/) by [Shriram Krishnamurthi](https://cs.brown.edu/~sk/).
The lab consists of writing interpreters in Scala for various languages, increasing in difficulty.
This lab is automatically graded by unit tests.
Since 2014, this lab has been improved upon by others adding unit tests for user test suites and alike. 




## Contact
Daco Harkes  
Email: d.c.harkes@tudelft.nl  
Office: HB 8.260, Mekelweg 4 (Faculty EEMCS), Delft
