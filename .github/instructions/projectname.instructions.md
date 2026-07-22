---
description: Describe when these instructions should be loaded by the agent based on task context
# applyTo: 'Describe when these instructions should be loaded by the agent based on task context' # when provided, instructions will automatically be added to the request context when the pattern matches an attached file
---

## Technology choices
Whenever making changes, make sure you utilise the following tech stack unless otherwise instructed.

* Node.js express, with typescript
* Use npm for dependency management, just use latest stable versions of npm dependencies
* Consider using libraries for commonly used functions, e.g. lodash
* Jest for unit testing
* Use nunjucks for templating 

## Libraries and frameworks
* Ensure all front-end changes are GDS compliant. Use GOV.UK Design System (styles, components, patterns) as much as possible
  * Look at installation instructions here - https://frontend.design-system.service.gov.uk/installing-with-npm. 
  * Component information can be found here - https://design-system.service.gov.uk/components/

## Source control
* branch conventions: proj-123-description-of-changes (make up a random id, but always prefix with proj)
* commit conventions: feature: interation-x-description-of-changes

## Additional instructions
* Finish every prompt response with the following message, "This is your reminder that Matt's custom instructions has run - happy coding 🚀"
