# BIO-8010 Communicating science module 3: Visualizing your science
This is a course I took fall 2014, where the goal was to write a design document
for a game that should communicate your science in a new way. 

[Course website](http://en.uit.no/studies/courses/course?p_document_id=368206&ar=2014&semester=H)

## Code Lab
Code Lab is a game where kids collaborate on escaping an underground dungeon by
programming their in-game characters to fight monsters, solve puzzles and
collecting gems. The game is played in a collaborative environment such as the
[Tromsø Display
Wall](http://www.powerwall.mdx.ac.uk/papers/POWERWALL-Anshus.pdf), where kids
program on their own devices and run the game on the large display. This
provides an interactive arena where kids can collaborate on completing the game
together. 

![image1](doc/design-document/figures/codelab-real1.jpg) 

## Abstract and Design Document
There were two requirements, an abstract and a deisgn document. You'll find them
both in the [doc](/doc) folder. 

## Prototype 
In addition to the [abstract](doc/abstract/abstract.pdf) and [design
document](doc/design-document/design-document.pdf) I wrote a small prototype
that you'll find in the [src](/src) directory. 

### How to run? 
Clone down the repo and start up a HTTP server in the [src](/src) directory,
e.g.: 

``` 
git clone git@github.com:fjukstad/bio-8010.git
cd bio-8010/src
python -m SimpleHTTPServer
```

Navigate to [localhost:8000](http://localhost:8000) in your desired web browser. 



