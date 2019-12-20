# Tips for code challenges

In 2015 some folks (around 30, mostly women*) got together in Berlin to discuss coding challenges for lateral hires with no CS background. This repository includes the presentation as an html presentation and below are some of the main tips/outcomes. Feel free to fork and add your own :)

# How to open the presentation

Clone this repository on your local computer and run a simple http server, e.g.:
```
git clone git@github.com:laurawadden/codechallengetips.git
cd codechallengetips
python -m SimpleHTTPServer 8888
```

Navigate to your browser and go to `localhost:8888` (or whichever port you chose).

# Summary & results from the discussion

Some categories considered by people reviewing code assignments:
* Operational-ness
  * Does it work?
  * Are the outputs correct for the sample input?

* Readability
  * Was it easy to follow the code?
  * Are method sizes reasonable?
  * Does it have a README? If so, does it tell you anything useful?

* Ease of maintenance
  * How easy would it be for another programmer to maintain and extend this code?
  * Is there unused code or comments?
  * Is there any duplicated code?

* Testing
  * Does it have testing of any kind?
  * How much coverage is there?
  * Evidence of Test-Driven-Development?
  * Is there at least one test that tests the sample input?

* Artistic impression
  * Follows conventions of language used?
  * Stylistically consistent
  * Is there too much over-engineering?
  * Typos?

* Design
  * Naming - methods named according to what they do
  * Organization - e.g., tests in own folder
  * Error strategy?
  * Software Design Patterns - used correctly? do you need it?
  * Encapsulation? - e.g., not exposing class methods to other classes and using Object-Oriented Design
  * Domain modeling - does the program model model the problem domain?

Tips:
* Don’t over-engineer
* At least try to do what they ask you (e.g., testing? try it!)
* Write a readme - explains your assumptions, how to run the program, and how to run the tests
* Ask for help if you need it
* Review your code before your interview and get comfortable explaining how it works. Be prepared to explain decisions that you made.
* Have a friend or coach review the assignment
* Focus on readability
* Follow the instructions
* Call the recruiter (a conversation can be much easier than email)
* If in person - explain what you are doing and your thoughts; don’t stop talking
* Can ask interviewer questions, e.g., “how would you approach this problem?”
* remember: interviewers are people too
* Best interview feels like a conversation
* Be honest about what you can’t do and focus on what you can do / love to do
* Don’t panic
* Keep track of your projects - case study - what you did, technologies, how long it took
