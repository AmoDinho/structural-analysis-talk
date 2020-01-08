# structural-analysis-talk
Notes for a talk on structural analysis

When embarking on making apps as an engineer sometimes a mock up in high fidelity form is not enough to properly translate what the business needs into code. structural analysis or modeling allows you describe things within your app as objects and how those objects are related each other and what they are meant to do. This is usually done through object-oriented or UML concepts. 

why does it exist?

To help engineers have a more formal process to making sure they have understood business requirments to turn it into code

How can it make me better? 

You know exactly what you need to code and what to test within your code. Start archtirual planning early and know what behaviours are needed from your users. 

Overview of process

Initial you would've sat with your designers and gone over user stories of your appliation and they wouldve made mockups in high fidelity. Now its time for these mocks to be turned into code, but mocks don't tell use the state of an object or the sequence of events between objects. This is where you come in:

* 1st you will map all your objects out
* understand their behaviour and attributes
* Find your most challenging use cases
* Identify what is challenging about them: state? activities? sequence? data model?
* Then create the necessary diagram to understand the use case in that way. 


Object mapping
So here all we need to do is identify the actors in our app. Lets take the fictional example of a Lunar Tour operator.
Users simple come online and book from a variety of vacation experinces on the Moon. 

Objects of interest:
* users (travellers, operating staff)
* bookings
* vaction listing

now we can start defining attributes for them, this can either be stolen from your ERD if you opt for a SQL backend or from the mocks yopur designer made.

[create attributes for objects]


Diagrams

No there are a quite a few diagrams

Activity

Sequence

State Diagram

ERD (SQL Backends)

What does this look like in code?

