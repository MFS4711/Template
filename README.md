# Add Title Here
<!-- Maybe create a header with html and css and use screenshot  -->

Single line description of project

Source code can be found [here](Add link)

The live project can be viewed [here](Add link)

## Purpose of Project
The aim of the project is to ...
The website consists of ...

<!-- Photo from responsiveness website - check file path -->
![responsivenes_screenshot](/static/doc_images/responsiveness_screenshot.png)

---

## Links to content

[**Purpose of Project**](#purpose-of-project)

[**Features**](#Features)

[**User Experience**](#User-Experience)
- [Design](#design)
    - [Fonts](#fonts)
    - [Colour](#colour)
    - [Wireframes](#wireframes)

[**Development Process**](#Development-Process)
- [Project Planning](#project-planning-and-documentation-in-github)
- [Search Engine Optimization](#search-engine-optimization)
- [Data Model](#data-model)

[**Testing**](#Testing)
- [Manual Testing](#manual-testing)
    - [Feature Testing](#feature-testing)
    - [Responsiveness](#responsiveness)
    - [Lighthouse](#lighthouse)
    - [Code Validation](#code-validation)
        - [Python](#python-code)
        - [JavaScript](#javascript-code)
        - [HTML](#html-validation)
        - [CSS](#css-validation)
    - [User Stories](#user-stories)
- [Automated Testing](#automated-testing)
    - [Django testing](#testing-django-views-models-and-forms)

[**Bugs**](#Bugs)

[**Libraries and Programs Used**](#libraries-and-programs-used)

[**Deployment**](#Deployment)
- [Deploying the app on Heroku](#deploying-the-app-on-heroku)
- [Making a local clone](#making-a-local-clone)
- [Running the app in your local environment](#running-the-app-in-your-local-environment)

[**Credits**](#Credits)

[**Acknowledgements**](#acknowledgements)

---

## Features
The following pages are visible to all users, logged in or not.

<!-- Create dropdowns for different sections following below format -->
<details>
<summary>Welcome Page (landing page)</summary>

- The landing page presents the user with a choice of ... actions:
    <!-- List actions -->
- The page has a header which has the following elements, from left to right:
    - Site icon, clickable, which links from any page back to this one.
    <!-- Add further elements in nav/header -->
    <!-- give element name and type - description of action when clicked -->
    <!-- Bullet point of any features to note from homepage and describe significance -->
    - The page footer, common to all pages, consists of ...

<!-- Add screenshot of welcome page - maybe different screenshots for different devices -->
![Welcome Page](static/doc_images/feature_screenshots/feature_welcome.png)

</details>

<!-- Any other pages that are visible to all users using same format -->
<details>
<summary>... Page</summary>
<!-- List features and describe significance -->

![... Page](static/doc_images/feature_screenshots/SOME_IMAGE)

</details>

<!-- Repeat for all Pages visible to all users -->

<!-- Below for login and register pages -->
<details>
<summary>Login Page</summary>

![Login Page](static/doc_images/feature_screenshots/feature_login.png)

- This is the standard allauth login page, styled with the site styling, and including social login links for Google and Facebook.

</details>

<details>
<summary>Register Page</summary>

![Register Page](static/doc_images/feature_screenshots/feature_register.png)

- This is the standard allauth signup page, with fields for email, username, and password + password confirmation. All fields are required.

</details>

---

The following pages are only available to logged in users.

<details>
<summary>... Page</summary>
<!-- List features and describe significance -->

![... Page](static/doc_images/feature_screenshots/SOME_IMAGE)

</details>

<!-- Similar to previous just repeat for each page unique to this user -->

---

The remaining pages are only accessible to staff
<details>
<summary>... Page</summary>
<!-- List features and describe significance -->

![... Page](static/doc_images/feature_screenshots/SOME_IMAGE)

</details>

<!-- Similar to previous just repeat for each page unique to this staff -->
<!-- Add any other sections for other roles -->

---

## Future Features
<!-- Bullet point any features that could be added and describe benefit -->
- It would be useful for (user type) to be able to ... This will ... etc
- A feature with added benefit for (user type) would be ...
- Another future feature, which I coonsidered implementing, is ...

---

[Return to top](#Add_Title_Here)

# User Experience

## Design

### Fonts
<!-- description in style below -->
The ... font was used throughout the project. It's a simple, very ligible sans-serif font, with a rounded appearance, particularly on headings and larger fonts

### Colour
The following colour palette was used in the project

![colour_palette](/static/doc_images/colour_palette.png)

<!-- Add short descriptions of why colours were used -->
<!-- Maybe add colour contrast images for accessibility? -->

### Wireframes
These wireframes outline how each page was intended to be displayed on Mobile, Tablet, Desktops and Larger Screens.
#### _Welcome Page (Landing Page)_

![welcome_page wireframe](/static/doc_images/SOME_FILE_PATH)

<!-- Repeat for each page as above/below -->
#### _Another Page_

![another_page wireframe](/static/doc_images/SOME_FILE_PATH)

---

[Return to top](#Add_Title_Here)

# Development Process

## Project planning and documentation in GitHub
GitHub Issues were used to document the development steps undertaken in the project. 
Two issue templates were created: one for [User Epics]() and another for [User Stories]().
A variety of labels were applied to categorise issue types, such as Bugs, User Epics, User Stories, and Style.
MoSCoW prioritisation was applied using the labels must-have, should-have, and could-have.
<!-- change labels listed as required -->

The project was broken down into manageable sprints using GitHub Projects, which provided a Kanban board. Issues were posted to the board and moved from "Todo" to "In Progress" to "Done" as they were completed.

The iterations are documented here :
    - [Iteration 1]()
    - [Iteration 2]()
    - ...

The User Epics and their related User Stories are as follows:
- Epic : [Epic Name](add_link_to_issue_in_github)
    - Story : [User Story title/description](add_link_to_issue_in_github)
    - Story : [User Story title/description](add_link_to_issue_in_github)
    - etc
- Epic : [Epic Name](add_link_to_issue_in_github)
    - Story : [User Story title/description](add_link_to_issue_in_github)
    - Story : [User Story title/description](add_link_to_issue_in_github)
    - etc
- etc.
<!-- repeat based on number of epics and stories - maybe display MoSCoW here - although will show in GitHub -->

<!-- Include this section and add depth if time at the end -->
## Search Engine Optimization
A set of long and short tail keywords was developed. 
The initial set was generated from a combination of brainstorming and examining the related searches returned by Google for these terms. This was then culled back to a smaller set of more targeted short- and long-tail keywords, which were each trialled on [wordtracker.com](https://wordtracker.com). 
This resulted in the following list of terms, ordered by volume:

|Term|Short/long-tail|Volume|Competition|
|---|---|---|---|
|'Word'|Short|226000|55.44|

After completing this research, I returned to the project's templates, and made the following changes:

- &lt;title> tag in base.html:
    - Set to '....'. This is one of the most important SEO locations ...
<!-- Add any tags in same form and bullet point impact of change -->

## Data Model
This section provides an overview of the data models used in the project, represented through Entity-Relationship Diagrams (ERDs) for each application. Each sub-heading corresponds to a specific app, detailing its database schema and the relationships between key entities. These ERDs were drawn using [Lucidchart](https://www.lucidchart.com/pages/) and offer a clear visualization of how data is structured and flows within the application.

<!-- Add Apps and ERD Diagram for App -->

### ... App

![Entity-relationship diagram for ... App](docs/SOME_FILE_PATH)

### ... App

![Entity-relationship diagram for ... App](docs/SOME_FILE_PATH)

<!-- Repeat for each App -->

## Data Validation
<!-- List places where validators were used in model - i.e.price -->
<!-- If someone tries a negative number, error will occur and some action will happen - describe  -->
The following decimal fields, representing currency amounts, are protected by Django's MinValueValidator, with the minimum value being set at 0.

<!-- Also add any JS checks on form fields etc. to ensure desired action/errors are caught -->

---

