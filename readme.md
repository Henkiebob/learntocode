# So you want to learn how to code?
**Caution, everything you read here is a rough sketch, for now..**

Hey there! You decided you wanted to learn how to code! Great decision, fair warning though, learning to code **isn't** easy. Like all new things, it takes a lot of **hard work and practice**, never forget that.

But you took the first step by trying to read this, great job! Keep in mind the things I am about to tell you aren't for any specific programming language or development style. So no labels, or prejudice, no front-end or back-end, software or web, you want to do something with code, and this is here to help you understand what you need, most specifics you can find out for yourself, using your preferred search engine and a thirst for knowledge.


## Mindset
This is something you learn along the way, so if you don't recognise yourself immediately, don't worry. Also this piece is heavily opinionated, so feel free to disagree.


### Think in possibilities 
As a programmer you are always confronted with a lot of problems, as a defensive mechanism 


### Learn one language well. Then learn a second one.
If you keep jumping from language to language, you won’t get far. Same goes for choosing frameworks. 


### Problem solvers
There are common strategies to improve your problem-solving skills:

	- Utilise both focused and diffused mode thinking
	- Chunk the knowledge you learn
	- Embrace failure and learn from it
	- Use metaphors and analogies

Some tips on how to avoid procrastination:

	- Find a friend to learn together with
	- Focus on the process, not the end product
	- Set regular goals (be SMART)

# Development Principles
## Empathise
## Keep it simple stupid
## The Open/Closed Principle
“Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.” 7
Never change anything at its source.
Avoid the Domino Effect.
Doing so causes visual regressions.
Hard to keep track of the knock-on effects.
Always make changes via extension (i.e. addition).

Possibly the most useful principle for dealing with other peoples’ code.
A safe way to make changes.
Everything gets opted into explicitly.
Prevents changes from happening one-sidedly; the developer has to add the class into the markup as well.

A second layer of safety: changes can’t be actioned from one place alone.
Analogous to rewriting Git history.
Safe way of working with legacy code.

## The Separation of Concerns
“[...] It is, that one is willing to study in depth an aspect of one’s subject matter in isolation for the sake of its own consistency [...] But nothing is gained—on the contrary! —by tackling these various aspects simultaneously. It is what I sometimes have called ‘the separation of concerns’ [...] it does not mean ignoring the other aspects, it is just doing justice to the fact that from this aspect’s point of view, the other is irrelevant. It is being one- and multiple- track minded simultaneously.” 

## The Single Responsibility Principle
“[...] the single responsibility principle states that every class should have responsibility over a single part of the functionality provided by the software, and that responsibility should be entirely encapsulated by the class.” 3
Do one thing, one thing only, and one thing well.
Break bigger monoliths down into individual concerns. Easier to reason about.
Provides higher composability.
Break things down into their smallest possible parts. Ensure each part fulfils its responsibility very well. Combine responsibilities to create complex components. Swap out, remove, or add discrete parts.
Helps you Separate your Concerns.
Gives you incredible opportunity and flexibility.

## Single Source of Truth
“[...] the practice of structuring information models and associated schemata such that every data element is stored exactly once.” 2
The more philosophical principle behind DRY. Key data should exist once in a source. Increases confidence.
Prevents anomalies and disparity.
Makes changes simpler. Keeps your code in order.
Dry in source, not in production.
Not about avoiding repetition.
It’s about avoiding repeating yourself. Automation of repetition is fine.
Don’t DRY if it’s repeated coincidentally.
Repetition in compiled code is fine.
Avoid duplicating data in source.
Going too far creates awkward and confusing structures in your code.
Use a preprocessor to store key data in variables. Make use of mixins to generate repetition. Abstract design patterns out into reusable objects. Do not DRY anything that is purely coincidental. Repetition is better than the wrong abstraction.

## Don’t Repeat Yourself
“Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.” 1

Every discrete piece of information should exist only once. You shouldn’t need to make the same change several times. Repetition is extra overhead: more to maintain, to go wrong. Increases cognitive overhead.
Continuous to bloat.


# Ways to learn

## Pet projects

## Tutorials (Don't learn you shit)

## The Basics

## Advanced Stuff

## Programmers and Painters

## Tips & Tricks

## List of fallacies
Many beginners fall into the trap of worrying extensively about technical questions: Which resource should I choose? Which language should I pick? Which technology should I use? This approach has a good chance of wasting your time. As long as your choices remain within industry standards, they won’t matter nearly as much as having a strong, overarching learning goal to stay motivated, and coding regularly.

Learning to code is not an easy thing. It takes a lot of time and perseverance. When you want to reach your overarching goal, take it one problem at a time — and just get started! You’ll be making continuous progress, and then it’s all about staying motivated and persevering until the end.


## Quotes
"There are only two kinds of programming languages: those people always bitch about and those nobody uses.” — Bjarne Stroustrup"

“If you want to build a ship, don’t drum up people to collect wood and don’t assign them tasks and work, but rather teach them to long for the endless immensity of the sea.” — Antoine de Saint-Exupéry

“Any fool can write code that a computer can understand. Good programmers write code that humans can understand.” — (Martin Fowler)

## Giant list of terms

- Variables
- Arrays
- Loops
- Functional programming
- Statements en conditionals
- Datatypes (String, Boolean)
- Templating
- Client side
- Object Oriented 
- Frameworks
- Relations
- Databases and data optimisation
- Dataflow
- Single Responsibility Principle
- Design Patterns (MVC)
- DRY (Don't Repeat Yourself)
- Server side
- Two Way Databinding
- Defensive programming
- Packages, Bundles, Components, Gems
- Sessions, cookies, requests, responses
- API (REST)
- Test driven development
- Unit testing
- Deployment en performance
- Refactoring
- Web-sockets
- Multithreading
- Security
- Abstraction


### Sources

1. https://medium.com/@sebastienphl/a-practical-guide-to-learning-the-basics-of-web-programming-79961f3f3baa

2. https://timeline.com/women-pioneered-computer-programming-then-men-took-their-industry-over-c2959b822523
3. Hunt,A.,&Thomas,D.(2000).Thepragmaticprogrammer:Fromjourneymantomaster. Reading, Mass: Addison-Wesley.
4. SingleSourceofTruth.https://en.wikipedia.org/wiki/Single_source_of_truth
5. Martin,R.C.,Coplien,J.O.,Wampler,K.,Grenning,J.W.,Schuchert,B.L.,Langr,J., Ottinger, T. R., ... Feathers, M. C. (2016). Clean code: A handbook of agile software craftsmanship.
6. Freeman,E.,Koronkiewicz,P.,&Kowalczyk,G.(2005).Headfirstdesignpatterns. Gliwice: Wydaw. HELION.