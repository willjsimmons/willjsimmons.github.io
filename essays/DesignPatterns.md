---
layout: essay
type: essay
title: "Don't reinvent the wheel: A look into design patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-30
published: true
labels:
  - Design Patterns
  - Program Structure
  - Engineering Concepts
  - Programming
---

<img width="100%" class="rounded float-start pe-4"  src="https://cdn.shortpixel.ai/spai2/q_glossy+w_1595+to_auto+ret_img/designeverest.com/wp-content/uploads/2023/01/what-is-the-role-of-an-architect-in-building-a-house-1629876140.jpg">

# Try not to reinvent the wheel
Computer science as a discipline relies fundamentally on layers of abstraction. The life work of thousands of software engineers, electrical engineers, chemists, and other professionals has gone into the construction and design of the various laptops used to write this article. The truth is that everything that we touch is built upon systems and tools that have already been developed. A huge part of software engineering is efficiency. Although the stereotype for computer scientists is of insanely driven and intelligent individuals, brainpower is a finite resource. Like memory and processing power, it is best to be conserved wherever possible. Design patterns provide tried and true (often language-agnostic) patterns that efficiently address common problems. Good design patterns are simple to understand and remember. Design patterns have a similar relationship to program structure as data structures have to data; they both help to organize, standardize, and provide structure to a code-base. Furthermore, there are even design patterns that help to manage data structures in and of themselves.  Typically design patterns are Taught to students and can provide a source of commonality in communication. When someone references the factory pattern, it immediately provides the rest of the development team with some insight as to what a program component is doing.

## The factory pattern
Fans of object-oriented programming, particularly those involved in game development, will likely be familiar with the factory design pattern.  The factory pattern leverages one of the core O.O.P principles, polymorphism, to allow a single entity to create instances of several sub-classes. In essence, since objects that are inherited from the same class, let’s say a factory object will have methods to make for in the context of game development, the factory pattern is lovely for spawning entities in a game.

## The MVC pattern
Firstly, the model or data model is what stores the dynamic content. The views serve to determine how the data is presented to a user. The controller handers interaction and determines which views and data model elements to show. This design pattern is particularly applicable to the development of web applications. MVC conceptual divides an application into three major components. An excellent example of a loose implementation of this design pattern is a meteor. Meteor provides all three components. Meteor uses by default MongoDB. as its data model, 
Handles

## The singleton pattern
This pattern is useful when you would like to ensure that only a single instance of a class is created. In essence a developer creates a class where everything is static except for a single function which serves as a false constructor. In my experience as a developer this pattern has been useful for generating large monolithic objects that manage entire segments of your software. An example of this is the renderer in a game engine. 
	
## Conclusion
In the end Design patterns provide simple easy templates that can keep your project organized. Most of the time design patterns are viewed in the context of software engineering, although the fundamental concept stems from and applies to any complex system. It is helpful to increase understanding in a course at Uh Manoa. An example of a design pattern in a different context would be the design of an airplane. All airplanes have some sort of wing, a fuselage, an empennage, and landing gear. As an aircraft designer, you do not need to wonder whether to include wings or how to make the contraption fly. This frees engineers' minds to focus on decisions relevant to the specific implementation within these design patterns. There is much flexibility in how the wings are created and where the wings are attached, but an airplane has wings and engineers know it. Another design pattern for flying machines is the helicopter. As an airplane has wings a helicopter has rotors. To create your own flying machine, you must make several decisions. Design patterns help to organize these decisions. In software as in aviation the sky is the limit.

