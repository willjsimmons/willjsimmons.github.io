---
layout: essay
type: essay
title: "Coding Standard, why Lint is great for your code"
# All dates must be YYYY-MM-DD format!
date: 2023-09-21
published: true
labels:
  - Coding Standards
  - Javascript
  - Programming
---

<img width="100%" class="rounded float-start pe-4"  src="https://i0.wp.com/blog.knoldus.com/wp-content/uploads/2020/09/CleanCode.jpg?w=800&ssl=1">

# Standards, and The line between good And Legal

What would it be like to live in a world without standards? Standards are the fundamental underpinnings of the entire society. 
Before the standardization of measurements, people would often use, and reference measurements based on things that everyone had access to.
One example of these archaic measurement systems is the cubit. A cubit was defined as the length from the elbow to the tip of the middle finger. 
With centuries of experience under our collective belts, In 2023 it is abundantly apparent that this system is flawed, as your cubit is likely not the same as mine or your neighbor’s.
What standardization does is ensure that my inch is equal to yours, that my centimeter and kilogram etc. are also equal to yours.
It would be nearly impossible to build anything if everyone had differently marked tape measures.
Imagine a world where everyone invented their own grammar and there was no concept of correct punctuation, you could put extra spaces wherever you like, it would make reading an impractical nightmare.
A world without standards is a world full of Chaos. 

## The connection to code
The big question then is, if standards can maintain an orderly society, why wouldn't it be blatantly apparent that standards be applied to things so critical as code? In this sense, we are talking about the standardization of coding style.
The languages developers use to code are themselves codified in what is known as a Language Standard which provides the bare minimum as to what is valid code.
Although language standards outline what is legal, it does not mean that they always equate to what is good.
For example, according to the c language standard, it is perfectly legal to type your entire program as one long line of code without any carriage returns.
However, it would be awful to read one incredibly long line of code and how terrible to debug it! In essence, not implementing coding style standards is equivalent to operating off the technical difference between good code, and valid code.
Just because a compiler or interpreter does not complain does not make you a good programmer.

## Why Lint?
One example of a system that verifies and corrects JavaScript/ECMAScript code is ESlint.
More generally a commonly used term for the process of applying coding standards is known as linting.  other linting tools for different languages work as well.
In my opinion, the value of code style standardization is dependent in large part on the scope of a given project with two caveats.
Firstly, if one plans to write code that no one else will ever see there is a diminishing value to linting.
This, however, is not entirely true as the habit of linting is incredibly important to build.
It is also clear from history that many a massive project has started off as a side job that was never intended for anyone but the author's eyes.
Another advantage of using code standards is that it is easy.
Unless you write egregiously bad code, i.e., an entire program in a single line of c" linting programs can point out and often correct deviations from the standard.
Finally, to this end, Linting will also help the author themselves read their own code more clearly. 

## Conclusion
Thus, in conclusion, adhering to coding style standards is of paramount importance.
There are no valid excuses for neglecting the standardization of your code.
Embracing these standards will not only benefit you but also your entire team.
When collaborating on a project, it is crucial to establish either your own coding standards or, preferably, adopt the standards of a successful project with a proven track record.
By doing so, you'll ensure code readability, maintainability, and overall project success.
Your future self and your team will undoubtedly thank you for upholding these essential standards.





