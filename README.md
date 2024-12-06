# Llynfi Valley Angling Association   

![Image showing the sit on various screens](assets/images/responsive.png)

## Contents  

1. [Introduction](#Introduction)   

2. [User Experience UX](#User-Experience-UX)   

    * [Project Goal](#Project-Goal)  

    * [User Stories](#User-Stories)  

    * [Strategy](#Strategy)  

    * [Scope](#Scope)  

    * [Structure](#Structure)  

    * [Skeleton](#Skeleton)  

    * [Surface](#Surface)  

3. [Features](#Features)  
  
4. [Testing](#Testing)  

    * [Accessibility](#Accessibility)
    * [Validation](#Validation) 

5. [User Stories Met](#user-stories-met)

6. [Deployment](#Deployment)

7. [Credits](#Credits)


## Introduction:   

This website was designed for a local fishing club based in Maesteg, South Wales.   

This website has been created the intial milestone project for Code Institute's Level 5 Full Stack Software Development Diploma. It was built using HTML, CSS and Bootstrap. GitPod was used for writing the code, as well as committing and pushing to GitHub, where it was stored.     

Once all the code had been written, GitPages was then used to deploy the website.     

## User Experience UX:   

### Project Goal:   

To create a site for the Llynfi Valley Angling Association for visitors who want to know more about the club, its offerings and sign up to receive more information.    

### User Stories:   

As a **potential new member**, I want to:   

 ⦁  Be able to easily navigate throughout the site to access the information I want.

 ⦁  Find relevant content about the club including membership prices to inform my choices.

 ⦁  Be able to easily contact the club to be able to find out more information.   

 ⦁  Sign up to a newsletter to get regular updates about the club.

 ⦁  See photos of fish, the river, environment etc to help me decide if I want to join.


### Strategy   

The strategy plane of UX design is the initial phase where decisions about what objectives the product should be designed to meet must be decided. This means looking at user needs, as well product/service objectives. This website’s target audience was broken down into three categories:   


### Roles:
 - New User

#### Demographic:
 - Adults 16+
 - Young People
 - South Wales
 - Likely more males than females

### Psychographic:
#### Lifestyle: 
 - Enjoy outdoor activity

#### Values:
 - Learning new skills  
 - Spending time outdoors  
 - Spending time with family
 - Teaching children new hobbies
 - Health and wellbeing

#### The website needs to allow users to: 
 - View information about the club including membership prices
 - Contact the club if needed  
 - See photos of members, fish, the environment
 - Sign up to a newsletter 

#### The website needs to allow the club:
 - Attract new members  
 - Receive inquiries from site visitors 
- Allow interested parties to receive the newsletter.
 

### Scope   

Within the scope plane, the strategy is transformed into the project specifics, including requirements, defining the characteristics of the product or service and any other value-adding information to be displayed on the website or app.    

#### Content Requirements:   

 * Home page
 * Contact info   
 * Photos/Gallery
 * Membership price details   
 * Newsletter sign up   

#### Functionality Requirements:   

The user will be able to:
 
 * Navigate easily through the site to find the information they need  
 * Sign up to the newsletter 
 * View photos
 * Link to social media sites 

### Structure   

At the structure phase, the platform and user interface (UI) of the site are shaped.    

### Skeleton   

At this level, the exact structure is finalised, including where the interface elements are located on the screen and how they interact with each other.    

[Wireframes](WIREFRAME.md "Link to Wireframe screenshots") were created to set out the initial appearance of the website.  Wireframes were created using [Balsamiq](https://balsamiq.com/).     

### Surface   

This is the final stage where visual design should be designed with the user in mind. The information should be presented appropriately and accessibility should be considered.   

#### Colour Scheme:   

The colour scheme for the project was created by uploading an image of the Llynfi River to [Adobe Color](https://color.adobe.com/create/color-wheel). Adobe Color extracted the colours from the image to create the colour scheme: 

![Image showing a screenshot of Adobe Color colour scheme](assets/images/color-scheme-1.PNG)

####  Typography:  

The font chosen was imported from [Google Fonts](https://fonts.google.com/). 

El Messiri was chosen as it is similar tothe font in the logo. Initially two fonts were used but the second was removed as the one font looked better overall.

## Features 

#### Header and navigation 

Each page has a Header and Navigation bar section which sit at the top of each page. The navigation bar consists of links to the *Home* page, *About* section, *Membership* section, *Contact Us* section, which are all on the home page, and to a seperate *Gallery* page.

![Image showing the navigation the LVAA page](assets/images/nav-bar.png)

#### Footer 

The footer sits at the bottom of each page. This contains links to LVAA's social media pages. Currently, the LVAA only have a Facebook page, but the other links go to the Instagram and Youtube home pages. Each icon opens in a new tab when clicked.

The footer is simplistic but effective. The simplistic choice allows the footer design to be changed in the future if needed.

![Image showing the footer on the LVAA page](assets/images/footer.png)

#### Hero Image

![Image showing the navigation with hero image below it on the LVAA page](assets/images/header.png)

#### About Us

#### Cards



Modal section – Found it difficult to get the correct responsiveness for the modal itself. Was able to change the form but it was then too large for the modal area. Used ChatGPT to help improve the responsiveness. 

 


 

## Testing 

### Bugs
 - Navbar links did not work from Gallery page - now they go to each page/section correctly
 - The modal form layout was incorrect and was not responsive - used Bootstrap to align correctly and reposnd to screen sizes.
 - The form did not have a submit button - added following testing.
 ![Image showing the form without a submit button](assets/images/form-no-button.png)

### Accessibility  

The Lighthouse tool, part of Google Chrome DevTools. The site is ranked at 100 for accessibilty on mobile and desktop.

### Validation 
 
The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator Services](https://jigsaw.w3.org/css-validator/) were used to validate every page of the project to ensure there were no syntax errors in the project.

#### Mobile:
![Image showing the Lighthouse tool and accessibilty ranked at 100 for mobile](assets/images/accessibility-mobile-1.png)

#### Desktop:
![Image showing the Lighthouse tool and accessibilty ranked at 100 for desktop](assets/images/accessibility-desktop-1.png)

### Browser Compatibilty

The deployed site has been across a number of browsers. 
The site's appearance is excellent on all browsers. Responsiveness could be improved on browser for laptops and larger screens.
Firefox cannot be tested as no access to Apple devices.

| Browser Tested | Intended Appearance | Intended Responsiveness |
| -----------    | -----------         | -----------             |
| Chrome         | Excellent           | Good                    |
| Edge           | Excellent           | Good                    |
| Mobile         | Excellent           | Excellent               |


## User Stories Met 

## Deployment 

The website was developed using Gitpod and was created in the "main" branch of GitHub. This branch was deployed using GitHub Pages. 

To deploy the project you must:

1. Open GitHub. 
2. Click on the project that is to be deployed from the available repositories.
3. Find the "Settings" tab and click to go to "Settings" page.
4. On the left-hand sidebar, in the "Code and automation" section, select "Pages".
5. Under the "Build and deployment" section, make sure:
    * Source is set to 'Deploy from Branch'.
    * Under Branch that main branch is selected.
    * Folder is set to / (root).
6. Select "save".
7. Go back to the "Code" tab.
8. On the right-hand side, in the "Deployments" section, click on 'github-pages'.
9. A new tab will open, here you can click on your live site! 

 **The pages can take a few minutes to refresh after changes have been made**

## Credits 

### README.md
 * README.md structure adapted from examples shared on Slack by Lewis Dillon, Cohort Facilitator.
 * Instructions on deployment were adapted from the Code Institue coursework

### Images and content:
 * All images, including the logo, that have been used have been provided by the Llynfi Valley Angling Association.
 * The icons used throughout the website were taken from [Font Awesome](https://fontawesome.com/)
 * The fonts were taken from [Google Fonts](https://fonts.google.com/)

### Code:
 * Various coder forums were used when I had issues with specific aspects of the code. [W3Schools](https://www.w3schools.com/) was particularly helpful and provided walkthroughs. [ChatGPT](chatgpt.com) was also used when forums or other websites did not help me to solve issues I came across.
