# SME Front-end homework

## Intro

Welcome! At SME, we aim for composable, testable and scalable front-end code. This homework is the opportunity for you to showcase your skills in FE Engineering as you're free to choose any tools you want to work with within the React stack.

If you have any questions about the task itself or the technical tools (libraries and such) you'd like to use, feel free to reach out to us at any time.

## Assignment

Make a simple form that consists of 2 fields:
1. Company code / ID
2. Company name

Make an integration with an API (or use fake Promise-based requests in FE), manage the form's state and form's field validation (in any way you want).

### Business requirements
1. Company code / ID field should have digits-only and 9 digits validation rules (according to Lithuania's company code pattern; example: `304254910`.
2. When user correctly fills `Company code / ID` field, a request to the API should be made to GET company data by company ID; response should be mocked with a 3rd party API or your own very basic Backend MOCK API (you can use anything).

### Technical Requirements
* Use a 3rd party tool to create a simple MOCK API (example of a 3rd party provider -> https://www.mockaroo.com/apis; or -> https://www.mocks-server.org/); or you can create a very basic Backend application that has 1 endpoint (example route: /api/company/all) that'd return hard-coded JSON response with random company data. (you can use any tech you want: NodeJS(Express) and so on.)
* Required packages: `react` and `react-dom`. The rest is up to your imagination.
* Typescript (optional).
* Unit tests (optional).
* Styling and UI component libraries: you're free to use anything you want (except plain CSS).
* Use any libraries you see fit (for API integration, form state management, form validation and so on). You have complete freedom to show off your skills here.
* Browser support: Chrome and Firefox (don't worry about Safari/Edge/Opera/others here).

### Time
Ideally, the task could be completed in several hours. You're free to suggest how much time is needed and spend your time however you want. You have complete freedom here.


### Bonus points

If you have additional time, feel free to implement any of the additional functionality. This is a great way to showcase more of your skills.

* Form data submit (fake request in front-end or an actual Network request to your MOCK API)
* Loading indicator for API requests
* Responsive design (with 3 primary breakpoints — Desktop, Tablet, Phone (as a guideline, breakpoint values can be borrowed from MUI breakpoints; see: https://mui.com/material-ui/customization/breakpoints/)).
* Saving user's form data somewhere in the Browser (feel free to use anything you see fit)

### Tips
* There's no design available for this task. The form should be very straighforward, don't think too much about it.
* Work on the fundamentals first (API integration, form validation, form state management and such) and polish additional functionality later.
* If you're short on time, consider using React app boilerplates that do the most usual tasks for you.
* Feel free to add `TODO`, `FIXME` and other commonly used notes in your code for various suggestions what could've been done better, but couldn't be done within the timeframe you have available.
* Make sure your project runs in `dev` mode and builds for distribution (usually to `dist` directory in simple builds).

### Submission
There are 2 ways:

1. Create an unlisted, private or public repository with your project (on Github, Gitlab or Bitbucket).
2. Clone this repo and, when you're done, make a Pull Request.

### Questions?

Got any questions? Feel free to ask.
