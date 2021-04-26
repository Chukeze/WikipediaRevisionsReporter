# Project Report

(Chukwuebuka Victor Ezeocha)

## Markdown Tips

If you are unfamiliar with MarkDown, check out 
[the official documentation](https://guides.github.com/features/mastering-markdown/).

Note that IntelliJ IDEA has a Markdown preview that you can access in 
the upper-right of the editor. Also, since Markdown documents&mdash;like
source code&mdash;should be human-readable, make sure you keep your lines
short, as you can see I have done in my Markdown files.

Please remove this subsection before submitting your report. 

## Challenge #1 Complete

(All that notice that needed to be change to fit the requirement was in the bind method to have the queryengineclass point Wiki's query engine class rather than the fakequeryengine) 

## Challenge #2 Complete

(To complete i followed your instruction and create a new final class formatter which i called AlternativeRevisionFormatter.
Also, you suggested using interfaces, and i thought that would work for sepearting highlevel module 
 while also creating the oppurnity to use a client-specific interface, and then use this class to bind the formatter to the abstraction(interface). 
 I also updated the injector in the start method so it create an injector for both the queryEngineModule and the ARF/alt-RF.)

## Challenge #3 Complete

(I used the stream() function for the revision,
 and then map function to format entries. 
 Use the join method in the Java collectors API,
 which allows you to pass delimiters,
  and concatenate results.
  I then just had that displayed)

## Reflection Question #1: Functional vs OO

(Using a for loop to iterative just to do string concatenation is the easiest method for me one,
becuase i have been doing that for most of my previous projects.
StringBuilder was actually one of the first few things i learned about. Conceptually, to me it flow like a simple sentence,  
iterate then add to string. The functional used in this project does the same thing but in a assembly line kind of way,
if i am to make an analgous comparison.)

## Reflection Question #2: Polymorphism and Dependency Inversion

(Explain how polymorphism engendered dependency inversion in this little
application. Be clear and precise here, as this is, in part, an assessment of
your correct use of technical terminology.
Consider, for example, where exactly is polymorphism used?
Where exactly is a dependency inverted?
To answer this question let located instances of polymorphism.
The first instance is in the query engine in challenge#1,
in which the interface can then be inherit by the QueryEngineModule. 
Furthermore, because of the introduction of independency that the interface class creates,
the configuration could then be overidden in the QEM class also.
The expalanation suffices also for the 2nd instance of polymorphism.
Which show up in the process of challenge #2.
In the creation process of an alternative revision formatter,
and the Revision formatter class itself.
What these both do is make it possible to do injection of dependencies.
into the App class, causing the dependencies to invert.)

