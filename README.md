### 1: What is the Event loop ?
Event loop isa built in mechanism that enables asynchronous programing. It handles the execution of multiple chunks of codes

### 2: Explain the 6 phases of the event loop
- timers : This executes timers like setTimeout(), setIntermediate() depending on the time set.  when the time set has elapsed except if they are set to 0 or
- pending - this is an internal phase in the event loop
- idle/prepare - Also an internal phase of the event loop
- poll(ing) - processes inpot/outpt callbacks
- check - executes setIntermediate() timers added in the poll phase
- close - Event loop closes and the process ends if there are no more timers or input/output calls, otherwise the loop continues


3: List some best practices in server-side code development

4: What is NPM5: How do you initialize a package in npm

6: How do you run a script in the package.json ?

7: Initialize a package if your choice, give it a name and install the following npm packages to it, express, mongoose, joi.

NB: Create a github repo and submit your answers in the readMe of this repo, 

Also, add your initialized npm package to this repo, then submit a link to the repo as your submission. 