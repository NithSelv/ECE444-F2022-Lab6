## ECE444 Lab6

Made by Nithushan Selvanesan

All content involved steps followed from https://github.com/mjhea0/flaskr-tdd

## Heroku Deployment

https://warm-retreat-48934.herokuapp.com/

## Test Cases Written For the Group Project


## Pros and Cons of Test Driven Development

# Pros
Test driven development provides many benefits such as better code quality and flexibility. For example, it is easier to write code that can fufill one function as opposed to fufilling multiple objectives simultaneously. This allows programmers to focus on writing a particular piece of code to complete one task well before moving to the next. Therefore, a logical sequence of task completion can be made which allows prohrammers to finish their work succinctly. In addition, feature creep can be avoided until after the basic features have been written and their quality has been ensured. Thus, a minimum functionality has been achieved before additional features can be introduced which may cause issues and may need to be rolled back.

Furthermore, test driven development allows programmers to interchange parts of the code as needed. For example, tests may need to be revised to account for new information from stakeholders and thus, certain parts of the code may need to be updated. With test driven development, those tests can be updated and then the code can be checked to see which components actually need to be changed to get the code functioning again. This allows programmers to avoid wasteful effort on updating code that may have little to no impact. 

Finally, test driven development often has better documentation because each component and feature is tested individually and thus the documentation of each function is very clear. There is no need for large amounts of complex code that is only tested at the end which may disguise the effects of bug propagation between features. Therefore, test driven development helps with error checking because programmers can isolate system errors down to whichever unit test is failing.

# Cons

On the other hand, test driven development is very difficult to maintain. There may be many features that need to be tested which could result in extremely long test run times. This makes code production take a very long time since programmers may have to wait hours before knowing if their changes are fine. Sometimes, programmers may even skip running the tests because it takes too long and they may submit erroneous code to the repository. Test suites taking an extremely long time to run is due to the fact that they may be testing very trivial code or they may be testing very complex features. 

Another issue is that test driven development requires someone to keep track of the tests and ensure that they are up to date. For example, if a team changes or gets replaced, then often what happens is that no one keeps track of the tests anymore and then those tests become outdated as new code is introduced to the project. As a result, someone has to go and then update the tests but at that point, some tests may not even be applicable anymore. Therefore, test maintenance and upkeep is a very important task, but many often ignore it in other to get production code completed on time.

Finally, test driven development may not account for the actual usability of the final product. For example, the code may not run on different machines or operating systems, but the test may run perfectly. Or the code may pass the tests but be extremely slow and/or perform poorely in an actual usecase environment (i.e web page formatting for different browsers). Thus, one should not become too reliant on unit tests as a measure of success and they should ensure that the final product is manually tested for functionality as well.
