![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

**Student:**  John Gardner<br>
**Date:**  28/09/2024 <br>
**cohort:**  WECA- Full Stack Software Developer: Skills Bootcamp <br>
**Project:**   Individual Formative Assignment: HTML, CSS, Bootstrap <br>

- - - -
# Project Goals #
## 1. User goals
- The users goal is to gather information about diversity and inclusion in the workplace or educational environment.

- The users goal is to being able to navigate a visually appealing, easy-to-navigate webpage.

- The users goal is to use our information presented in diversity and inclusion in the workplace or educational environment. 

- The users goal is to better understand and implement positive diversity and inclusion change within the workplace and educational environment. 
    
## 2. Site Owner Goals
- The site owner goal is to provide unbiased information about diversity and inclusion in the workplace or educational environment.

- The site owner goal is to increase the knowledge, understanding and positve changes that enhance diversity and inclusion in the workplace and educational environment.

- The site owner goal is to take feedback from users and provide better information to the public
- - - -
# Features #

## Index Page
### Carousel
The site features a way to display information on gain a basic understanding of diversity and inclusion in the workplace or educational environment., it’s home page prominently features a carousel of hero images that can display a basic understanding of diversity and inclusion in the workplace or educational environment.
### Cards
Below that are 3 cards that feature guides available with a short snippet of information and you can quickly choose the guide you wish rather than browsing the entire guide page. Selecting the guide you want will send you to the correct section of the guides page via an ID.  The cards are responsive going into a single column on a small screen and showing as a row of 3 on medium and larger screens.
Below that is some information regarding Welsh rules on wild camping.

## Guides Page
The guides page is multiple pages in one and can be expanded downwards with further guides. It is responsive showing as a single column on smaller screens and two on medium and larger screens. The order on smaller screens is image > text > image > text however on medium and larger screens it will alternate to make the site more visually interesting and balanced. The guides have an accordion element from bootstrap that can be used to store extra information, a map iframe has been used as an example.

## Contact page
This page has used the min() function to fluidly size for many screen sizes at and between breakpoints to ensure a consistent view, the body is size to the viewport to ensure the footer remains at the bottom of the page without using a fixed position as fixed position cause issues with overlapping of the form and footer at smaller screen sizes

- - - -
# UX/UI #

   ## 1. Target Audience
   
  - People looking to gain a basic understanding of diversity and inclusion in the workplace or educational environment.
  - People specifically looking for gain a basic understanding of diversity and inclusion in the workplace or educational environment.
  - Users looking for gain a basic understanding of diversity and inclusion in the workplace or educational environment.

 ## 2. User Stories
  - As a first time user, I want a navbar to easily navigate to the content I want.
  - As a first time user, I want an introduction, blurb or image to easily understand the main purpose of the site.
  - As a first time user, I want a guide/article to get a general rundown on the location. (i.e Transport, accommodation, events, food/drink, local history)
  - As a  first time user, I need a map of the location.

  - As a returning user, I want to contact the organisation to provide feedback
  - As a returning user, I want to leave a review

  - As a site owner I want a logo in order to help identify the brand.
  - As a site owner, I want users to find the visually pleasing travel content easily.
  - As a site owner, I want users to be able to book or find out more on the respective websites mentioned in the content
  - As a site owner, I want to display an engaging carousel of hero images so that users are more likely to book tours
- - - -
 ## 2. Design Choice
 
 ##  Colour Scheme
 
 ##  Fonts
 
 ### Main Content 

 ### Home Title & Wild Camping  

 
 ## Wireframes
    
  - Main Page Wireframe:
 
 ## Logo

- CSS file is in the assets folder in the CSS sub-folder which were used to generate logo files are logo.css and logo.css
- Images used are in the assests folder in the logo sub-folder files are 
- - - -
# Testing #

## HTML Validation
- Initial HTML Validation was performed using the W3C Mark up service and the results can be found in this document.
- The missing P element & the duplicate attribute on class in the Guide.html has been resolved.
- Any issues with the index.html & contact.html page have remained as future fixes.
  
## CSS Validation
- Initial W3C CSS style sheet validation link 
- Test W3C Validation CSS style sheet validation 
- The style.css form passed with only one issue that was with a newer feature that some browsers do not support just yet. We have left this in as the browsers still work as intended.

## Accessibility
- We entered our website through AccessScan to check we were compliant with with ADA standards. Our website is ADA-compliant as shown below:


## Device Testing

We have tested the site with the following devices:

- Android Google Pixel 5
- Desktop
- Android Tablet
- Chrome Developer Tools (Simulating for all available device options)

The site functioned as expected except for the loading on the guide page with the map & Youth Hostel content on smaller devices.
  
## Browser Testing

Testing has been done on the following browsers:

- Chrome (& Developer tools)
- Opera
- Safari

## Testing Breakdown
- We completed the following tests on all mentioned devices and browsers including the steps & outcomes from said tests. Any noted bugs are explained below.


## Testing user stories

We tested our site vs the user stories: 

1. 
User Story:

--
4.
User Story:

## Known Bugs

## During development, we found these bugs and fixed them:

### Nav bar disapperance

- On smaller devices, the navbar burger logo to indicate the nav bar would disappear when switching to the guide page.
- To fix this issue, we chekced the Home & Contact nav bar, realised they had no issues and copied the code back into the guide HTML.

### Carousel Images poor quality on smaller devices

- The carousel originally loaded on all devices, however the images appeared pixelated & poorly rendered.
- To fix this issue, as a design choice, we decided to remove the carousel feature to mobile users to keep a high quality of user experience.

## During development and testing, these are the current bugs:

### Content on smaller devices

- The content when deployed on a smaller device reshuffles the image to the bottom of the container.
- The text in the last paragraph changes to the default font rather than our applied styling in the CSS folder. This is specific to Android.

- - - -
# Deployment #

How this site was deployed

- In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu 
- From the source section drop-down menu, select the Main Branch
- Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment
- Any changes pushed to the main branch will take effect on the live project

- The live link is here: 

- We used an agile methodology by using early deployment. We could see every change on a live site to aid our development process

- - - -
# Sources #

## Media
 

## HomePage Content. 
-  This site was used as the key reference for the home page content.
-  The Text for the Home Page Content can be found here 

## Content
- The colour scheme was helped with the use of: https://coolors.co
- The fonts were imported from Google Fonts.
- The Wales Sans Headline font was imported specifically from: https://www.onlinewebfonts.com/download/87c492db36d96bca8d9d769a21874b83
- Font awesome was used to add icons for UX purposes.
- Balsamiq was used to create the wireframes during the design process.
- The background texture is from: https://www.transparenttextures.com/

## Code
- The Logo CSS code orginated from here: https://www.w3schools.com/howto/howto_css_shapes.asp
- The HTML & CSS uses Bootstrap Version 5.3: https://getbootstrap.com/docs/5.3/getting-started/introduction/

# Future Features #

- I would like to implement a review system where users can leave reviews & feedback that would be shown on the site. This requires an API/database that is not currently within our scope.
- - - -
## Readme
