# Real-Time Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/emilydowdle/real-time)

### Link to the Deployed Application
[Your Application](http://real-time-feedback.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/emilydowdle/real-time/commits/master)

### Provide a Screenshot of your Application
![Real Time Feedback](https://github.com/emilydowdle/ruby-submissions/blob/master/1508/module_4_assignments/real-time/Emily_Dowdle/assets/Dowdle_App.png)

## Completion

### Were you able to complete what you feel is the base functionality?
#### If not, list what functionality you think may be missing missing.
* Yes, I completed all base functionality and fulfill the expectations of Steve and Tan in the Crowdsource project

### What features did you complete which you feel 'exceeded expectations'?
* Admins and voters can chat with each other in real time
* Chat messages are shared with the entire group and appended chronologically

### Attach a .gif, or images of any extensions work being used on the site.
![Live Chat](http://g.recordit.co/W8p8TAPf39.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
#### Why were you proud of this piece of code?
[Awesome code](https://github.com/emilydowdle/real-time/blob/master/server.js#L71-L83)

* This project wasn't easy for me. I had trouble conceptualizing how information gets passed back and forth between the sockets and how to set up routes in Node.
* Once I got the hang of it, I was able to create live chatting as an extra feature. I'm pleased with the refactoring of the code, it's functionality and my growth.

### Link to a specific block of your code on Github that you feel not great about
#### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
[Testing](https://github.com/emilydowdle/real-time/blob/master/test/server-test.js)

* I need to continue to work on my Javascript testing.
* There's room for more exhaustive server tests as well as integration tests.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Tests Running](https://github.com/emilydowdle/ruby-submissions/blob/master/1508/module_4_assignments/real-time/Emily_Dowdle/assets/Dowdle_Tests.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
[Returns 404 if POST body is empty](https://github.com/emilydowdle/real-time/blob/master/test/server-test.js#L61-L67)

-----

### Please feel free to ask any other questions or make any other statements below!

## Instructor Feedback

The chat messaging is so awesome! Good job implementing a feature that really enhances the UX for the project.

I think working on JavaScript testing for you is less about understanding testing, and more about refactoring and writing less coupled JS code. Having a 'poll' object and 'pollStorage' (which would be the layer over your 'database' that would allow you to create, fing, etc polls) and splitting logic out of the server would make unit testing much easier.

Total Score: 170

Concept and Features

Does it have the expected features?

100 points - Exceeded expectations. There are more features than we planned.

Code Quality (JavaScript and/or Ruby)

25 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

Client-Side Application

25 points - Your application is thoughtfully put together with some duplication and no major bugs.

Test-Driven Development

10 points - Many areas of the code are not covered by tests.

Interface

5 points - The application is pleasant, logical, and easy to use

Workflow

5 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
