## Flashback

Hearing about "coding standards" in this course brings me back to the first time I heard about them in my ICS 212 class. Off the top of my head, our instructor at the time had us follow these rules: indentations must be made using 4 spaces instead of a single tab, curly braces were to be placed on the line below the function declaration, and break statements and recursion were forbidden from ever being used. It was a bit difficult to adjust to these rules at first but it became much easier with repetition. I even grew to like the way the code looked. In fact, rather than writing out a convoluted solution, I feel as if restricting us from using recursion or break statements made our code much simpler and easier to follow. Now that I'm taking ICS 314, it suddenly became much easier to tell whether I'm following the coding standard or not thanks to ESLint. However, there are times when ESLint can get pretty annoying, especially when the pressure's on due to time constraints. Other than that, I really don't mind it at all. With that being said, I will be sharing with you my personal view points on coding standards and ESLint as of so far.


## No Coding Standards?

Imagine you're working on a huge coding project with a few other team members, the work is evenly divided between everyone, and you guys are not required to comply with a coding standard. Someone reports that they've been getting errors and asks you and the other members to peer review in order to check for bugs. You take a look at it and to your surprise, everything is cluttered and painful to look at. The curly braces for if statements and loops aren't always formatted the same (e.g. the opening curly brace may either be below or next to the loop/if statement condition), parameters of a function have no spaces between them, variables that are never used anywhere in the code were declared, indentations might have two tabs worth of spacing while others only have one, and so on. Not only might this be extremely visually unappealing, but poor formatting practices could affect the overall readability of the code you produce. As an example, compare the way both the function headers below are formatted.

```
// Option 1

function func(arr,str,num,obj) {}

// Option 2

function func(arr, str, num, obj) {}


// Examples of functions with a missing parameter comma

// function fun(arr,str,numobj) {}
// function fun(arr, str, num obj) {}
```

Which one would you say is the better formatted one? In my opinion, the second option is the better version because the spaces make it more visually appealing to look at and it's slightly easier to tell that there are four distinct parameters that are required to pass into the function. I could imagine a scenario where someone intended to create a function with a set number of parameters but accidentally declared one less due to missing a comma as seen in the examples above. If everything is so close together in the parameter field, I believe that it would make it a bit harder to tell that you were missing a comma in the first place. However, by adding a space after every comma, you should know that each space should be a clear indicator that a comma should also belong before it, especially when variable names cannot contain spaces in them. As trivial as this example sounds, I've seen people make mistakes even though the solution to fixing their problem actually should've been painfully obvious to begin with. As humans, we're prone to missing these small details. 

## Wrap Up

The only general problem I see with having to comply with a coding standard is the learning curve. Getting used to how it wants you to write code when it's different than what you're used to can take a while to get accustomed with. From my own experience, getting one ESLint error after another gets really irritating when you have limited to work with during the WOD assignments. However, it's made much easier with tools like ESLint because it tells you exactly what you need to change and it gives you the option of automatically making the changes for you. That definitely beats intently checking lines and lines of code to look for potential deviations.

Otherwise, coding standards are actually a great way to make code more readable by formatting it in such a way that makes it clear and organized. Making some mistakes here and there is inevitable and coding standards could potentially make it easier to see where it is. Overall, I see more good than bad for this kind of practice.

