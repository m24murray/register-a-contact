---
name: brainstorm
---

## Project overview
I want to create a new Node.js front-end web app. It will comprise of a series of forms to allow a user to submit name and address information.

### Application overview
* Lets call the app, web-contact-registration
* It allows the user to register contact details of an individual attending an appointment
* 5 screens
  * Start page - some basic text explaining what the service does
  * Enter your contact details - form with name and contact fields for the user to input
  * Enter your address details - form with UK address fields
  * Summary - summary of the information from previous two screens (name and address)
  * Submitted - An screen confirming the form has been complete. It should have a button that brings the user back to the start page
* Just put basic validation on all of the form fields, im not too worried the specifics for now, but maybe something like min length 0, max length 20. I'll extend on this manually.

### Details
* Eventually we'll have a backend api that we can persist some data to. But for now we'll just stub this out and log the data instead.
* Don't worry about auth for now, we'll implement this later. As long as we've got basic security stuff like csrf.
* Headers need to be configured correctly, put the standard stuff. Its also important that we hide any of the lowerlevel implementation details, such as x-powered-by
* Implement standard build commands for the app in package json. build using tsc, hot reload, run tests

## Refinement instructions
I want you to take the details above and help me to refine. Ask me one question at a time so we can develop a detailed spec. 

Not too detailed though, this is just for MVP so im happy to accept some sensible defaults.

## Final output
Create a file in this project directory called `spec.md`. I want you to update that file to include the information provided to you in the details above, as well as the answers to your refinement questions.
