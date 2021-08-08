# Debugging 
![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing-1200x720.png)

## What Does Debugging Mean?
Debugging is the routine process of locating and removing computer program bugs, errors or abnormalities, which is methodically handled by software programmers via debugging tools. Debugging checks, detects and corrects errors (or "bugs") to allow proper program operation, according to set specifications.

- Debugging is also known as debug.

- ## Experts often talk about debugging as involving “people, processes and systems” that will help to iron out any issues with an existing code base. So how this works is different in different eras: for example, the debugging that took place in the early days of the PC, in bare-metal environments on linear, non-object-oriented code, is going to be different than the debugging that happens today.

## An excellent example of this is the rise of modern practices called “reverse debugging.”

1. In the age of devOps and agile software development, reverse debugging involves monitoring programs and delivering data in particular ways, in order to automate the process of debugging. This used to be done by individual computer scientists in a process that often resembled a kind of technical detective work.

2. In the old days, programmers filed individual tickets after observing some functional bug while testing, and then went back and scoured the code using now-primitive debuggers to figure out what was going on. It wasn’t unusual for even a seasoned team to be “stumped” for a while, either because of the sophistication of the code that created the bug, or the elusiveness of the bug in testing, or both.

> By contrast, reverse debugging systems that resemble the design of flight recorders in airplanes track programs in runtime, or otherwise monitor programs, in order to deliver the right information to make debugging more of an automated process.

> By doing more kinds of sophisticated monitoring in real-time or as programs are used, reverse debugging tools will catch more of the details that computer scientists would have traditionally had to investigate on their end.

### Testing has also changed, where with CICD and related processes, some of the testing may be done by engineers, and other kinds of testing might be done by end-users in a production environment or in beta, or elsewhere in the pipeline.

##  How to minimize the occurrence of bugs? Let’s discuss that in detail.




### 
1. Run Your Code More Often: This one is the most important advice, especially for the beginners. A lot of beginners do this mistake and they run their code first time after writing a bunch of code in a file. Please avoid this mistake else you will become more confused checking your own code and you will waste your time finding little errors in your code. When you run your code every time and test it, you get the feedback and you check that whether you are going in the right direction or not.

2. Use Print Statement Effectively: One of the simplest and favorite tool for every programmer especially for beginners to debug the code. Most of the debugging issues can be solved by inserting the print statements in your code. Print the variable and check your console that if the value stored in it is correct or not. Print the array, object, variables wherever you get a sense to inspect your data values.

3. Google, Google, and Google: Yes…we can’t deny that Google has solutions for most of our problems and this one is the easiest advice, especially for beginners. You might encounter a problem when you don’t understand the error message on your screen for the code you have written. The simplest thing you can do is to copy the error message and google it. Once you will try to search it there is a big chance that you get your answer on StackOverflow (the largest community for developers) or on other forums or community (fewer chances to switch from StackOverflow).




4. Try Alternate Solution: Try different solutions when you don’t understand the cause and don’t know how to fix the problem. If still, it’s not working try another one. Possibilities are also that you get the solution but you encounter a new error. Don’t be panic in this case and accept that every developer has to go through this phase. If you are a junior developer or a beginner you should definitely try alternate solutions to get into the root cause of the problem before asking for help from senior developers or from someone else. If you won’t try the alternate solutions and ask for help directly the first question they will throw at yourself “Did you try a different solution?“. So make sure that you don’t need to come back to your seat again and try a different solution after asking for help.

5. Use Comments Effectively: In any language comments are not just to leave a note in the code or to explain the code. You can also use it smartly to debug your code. A lot of beginners don’t understand how to use comments effectively to debug the code. You can temporarily comment out a piece of code that you don’t need to run at that time and you can check another piece of code to identify which one is causing the problem. It becomes easy to check the remainder code and identify the mistake. A lot of beginners remove the code to check the error instead of commenting it out, please don’t do that.























and make a practice to comment out the code.

6. Reproduce the Bug: Many times it happens that when you upload your website in a production environment (Godaddy, Heroku, etc) it doesn’t work. It works fine in your local environment but you get the issue in a production environment and the reason might be a change in an environment variable or few things like API keys which you store directly in your local environment, you do the same thing in your production environment which you aren’t supposed to do there for security reasons.
To resolve this kind of problem the best solution is to reproduce the same bug in your local environment but make sure that you don’t play with your code in the production environment because it can take time to communicate with the server.

7. Use Binary Search: Finding a complex error in a buggy file is really difficult especially when it has thousands of lines of code. In those cases, you need to check more and more places and to avoid this case the best thing you can do is to apply binary search. In this process, you need to cut the whole bunch of code into two parts. Comment out one part and run another part. Whatever part is responsible for the error, repeat the same process with that part and keep repeating it until or unless you don’t find the exact lines of code which causes an error.


9. Automated Tests: This technique is used in a lot of companies to detect the error. Automated tests and some other unit tests are performed to check if the actual output is matched with expected output or not and this is done by using some tool or writing some test scripts where we execute the software with specific input. If you are making any hypothesis or assumption write a unit test(checking the functionality of a single function or class) and check the outcome. Writing these test cases are traversing your code and checking their behavior which helps in finding the error.


10. Discuss and Ask for Help: If you have tried everything to find out the bug and to resolve it but nothing is working then it might be a complex issue like Race Condition and in such kind of scenarios, you need to ask someone for help. Explain everything about the issue, your assumption, solutions that you have tried, show the code that’s giving an error. Pairing up with someone else or if you ask for the help you might get a solution or you might have to consider some other scenarios which you haven’t considered before can resolve your issues.
![](https://media.geeksforgeeks.org/wp-content/uploads/20190902105053/Debugging-Tips-To-Get-Better-At-It.png)
> ## Learn more about  [Debugging in visualstudio ](https://code.visualstudio.com/docs/editor/debugging)




