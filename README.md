# Code Refactoring for Horiseon website.

## Main objectives
To streamline the HTML and CSS files, avoiding redundancy (DRY principle applied), as well as making it more accessible.

### Challenges 

Avoid changing the look and feel of the website.

### Key points
We have made sure the HTML follows a semantic logic (header, footer, etc instead of general divs). We also have added different screen size compatibility by adding the <meta name="viewport" content="width=device-width, initial-scale=1.0" /> . We have also added alt descriptions for images (for added accessibility) as well as given description of each element. Lastly, we have added notes both in CSS and HTML with modifications apported (<!-- ACTIONS TAKEN --> and /* Descriptions */ )
 

> **HINTS*: Make sure to explore the .css and .html file to see all actions taken during the refactory of the original code.

Lastly, we have called the Repo (in GitHub) "first-challenge" , so that it can easily be recognized down the track during our Coding Bootcamp.

## Original Criteria 
Below we have included the original User Story and the Acceptance Criteria, for visibility.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
