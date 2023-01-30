# MOMS WELLBEING CLUB

Moms Wellbeing Club website is a landing page for moms in Enniscorthy, St Aidans Primary School, who want to take a break from the day-to-day routine and get social. Joining the Club, they can enjoy relaxing and interesting activities, such us Yoga, Aerobics, Art and Crafts, reading books and discussing them together. In addition, they can bring their toddlers to the Toddler Group, where moms can enjoy a cup of coffee or tea, socializing with other moms, while toddlers play together and get involved in different activities. 
Visiting this website, users will be able to find all the information about the Club, all the activities they could join, schedule for each activity. There is the possibility to book a place for activities by submitting a sign up form. There is also a Gallery with Club’s activities photos and contact information.
The site is targeted towards moms whose children are St Aidans Primary School students. View the live site [here](https://t1i2n3a4.github.io/moms-wellbeing-club/)

![Mockup](docs/readme-images/website-mockup.png)

## Features

### Header

* The header contains website’s Logo and the Navigation Menu, with links to the About-us Activities, Gallery, Contact us and Sign up pages, which are responsive on all devices.
* The Header has fixed position to allow users to easily access different pages within the site on any size device.
* The links to pages have zoom effect when being mouse hovered and the link to the active page is underlined to show the user which page he accessed at that moment.

![Navigation Menu](docs/readme-images/header.png)

### About-us 

* About-us page contains a quote, the club’s ethos and an aside information about the purpose of the club and it’s foundation, all of them on a background picture. The page is responsive for any device screen.

![About-us](docs/readme-images/about-us-page.png)

* It also contains the Activities section, which can be accessed as a separate page from the navigation menu. The activities page contains 5 sections, one for each activity type. Each section is consists of:
    * Activity description;
    * A picture for that activity, including a link to Sign-up page;
    * Activity schedule.

![Activities section](docs/readme-images/activities-section.png)

* Contact-us page is also a part of the About us page, however it can be accessed from the navigation bar. Contact us page comprises:
    * The address;
    * Get in touch information (phone and email);
    * A map.

![Contact-us section](docs/readme-images/contact-us-section.png)

### Gallery page

* The gallery provides the users with photos from the club's activities.
* The page is fully responsive on all devices.

![Gallery page](docs/readme-images/gallery-page.png)

### Sign-up

* Sign-up page consists of a thank you heading and the suggestion to join the club.
* A submission form comprising 2 fieldsets and a submission button is also included on the page, all of them being fully responsive on any devices. 
* The first fieldset requires personal information as:
    * First name
    * Last name
    * Email address
* The second fieldset offers the users the possibility to check one or more activities to join.

![Sign-up page](docs/readme-images/sign-up-page.png)

### Footer

* The footer includes icons and links to social media networks.
* It is fixed positioned to ensure an easy and immediat access to the social networks.
* The text: FIND US ON is hidden for smaller viewports to make the footer responsive.

![Footer](docs/readme-images/footer.png)

### Features left to implement

* Pictures filter to be added to gallery page, to sort them by activity type.
* A sign-up form for mothers who would like to become volunteers by introducing and organising new activities.

## Design

### Wireframes

* Website's wireframe was created in Balsamiq.
* Desktop and Mobile versions are presented below.

    * About us page

    ![About-us wireframe](docs/readme-images/about-us-wireframe.png)

    * Activities section

    ![Activities section wireframe](docs/readme-images/activities-wireframe.png)

    * Contact-us section

    ![Contact-us section wireframe](docs/readme-images/contact-us-wireframe.png)

    * Gallery page

    ![Gallery page wireframe](docs/readme-images/gallery-wireframe.png)

    * Sign-up page

    ![Sign-up page wireframe](docs/readme-images/sign-up-wireframe.png)


### Color scheme

* The color scheme for the website was selected based on the purpose of the club to help mothers achieving a state of wellbeing.
* The color green represents new beginnings and growth. It contains calming attributes, but also incorporates energy.
* The color purple brings up a feeling of trust and reliability. It is also one of the mindfulness color.
* The backround image of the landing page incorporates both colors: green and purple. The picture represents a woman in a lavender field, touching the lavender flowers. 
* Lavender flower is a symbol of purity, silence, devotion, serenity, grace and calmness, which also reveals the club's purpose.
* The nuances of green and purple fro the website were extracted from the background picture using Adobe Color.

![Website's color-scheme](docs/readme-images/color-scheme.png)


## Technologies

* HTML
    * The website's structure was developed using HTML as the main language.
* CSS
    * The website was style using CSS.
* [GitHub](https://github.com/)
    * GitHub hosts the source code which is deployed using Git Pages.
* Git
    * Commit and pushing code using Git while creating the website.
* [Font Awesome](https://fontawesome.com/)
    * The icons used as Social Media links on the Footer were obtained from Font Awesome website.
* [Google Fonts](https://fonts.google.com/)
    * Used to select font families for website's body and headings.
* [Tinypng](https://tinypng.com/)
    * Used to reduce the pictures embeded on the website.
* Paint app 
    * Used to tailor the pictures embede on the website.
* [Adobe Color](https://color.adobe.com/)
    * Used to extract the color scheme from the background picture.
* [Balsamiq](https://balsamiq.com/wireframes/)
    * Used to create the wireframes for descktop, tablet and mobile.
* [Google maps](https://www.google.com/maps/)
    * Used to embed the map on Contact us section.


## Testing

### Validator Testing

* HTML 
    * [W3C Validator](https://validator.w3.org/) was used for HTML validation.
    * No errors or warnings were found.
    ![HTML validation result](docs/readme-images/HTML-checker.png)

* CSS
    * [W3C CSS validator (Jigsaw)](https://jigsaw.w3.org/css-validator/) was used for CSS validation.
    * No errors were found.
    ![CSS validation result](docs/readme-images/w3c-css-validator.png)

### Lighthouse Testing

* Performance, Accessibility, Best Practices and SEO for each page were tested by running them through Lighthouse in DevTools.
* The results for each page are presented below.

    * About-us page

    ![About us page Lighthouse](docs/readme-images/about-us-lighthouse.png)

    * Gallery page

    ![Gallery page Lighthouse](docs/readme-images/gallery-lighthouse.png)

    * Sign-up page

    ![Sign-up page Lighthouse](docs/readme-images/sign-up-lighthouse.png)

### Responsiveness

* All website's pages are responsive on any screen sizes from 320px and upwards on Chrome, Firefox, Edge and Opera browsers.
* The responsiveness was tested using Developer Tools set to responsive and decreasing width from maximum to 320px.
* The website was opened on the following devices and no issues were seen:
    * Samsung Galaxy S22
    * Iphone 12 Mini

### Form testing

* The form on the Sign-up page was tested for functionality.
* If one of the fields is empty a warning message "Please fill this field" appears when click to submit.
* If the email field is sumbitted with a non-email text, a warning message "Please include an '@' in the email address" appears.
* If correctc inputs are submitted, no warning or errors appear. 
![Form testing result](docs/readme-images/form-testing.png)


### Unfixed bugs



## Deployment

### Version Control

* The site was created on [Gitpod](https://www.gitpod.io/) platform.
* The code was added to the staging area using ```git add .``` command.
* Changes were commited using ```git commit -m “ ”``` command.
* Commited code was pushed to the GitHub repository using ```git push``` command.

### Deployment to Github Pages

* The website was deployed to GitHub Pages, following the steps:
    * GitHub Repository - Settings - General (left side menu) - Pages - Build a Deployment - Source - Branch: main - Save.
    * Go back to GitHub Pages were a live link is displayed when published successfully.
    * The live link can be found [here](https://t1i2n3a4.github.io/moms-wellbeing-club/).

## Credits

* Code
    * Most of the codes used troughout the project were taken from the [Code Institute Programme](https://learn.codeinstitute.net/), icluding the CI projects.
    * [W3Scools](https://www.w3schools.com/) and [freeCodeCamp](https://www.freecodecamp.org/) were used to solve the issues arised while developing the project.
* Content 
    * The website's content was written by the developer.
    * Gareth's McGir README was used as a sample for this project.
* Media
    * All the pictures for the website were taken from [Pexels](https://www.pexels.com/).
    * [Google Maps](https://www.google.com/maps/) was used for the map on the Contact us section.
    * [Code Institute Channel Lead Library](https://www.youtube.com/playlist?list=PL_7334VduOHvzZYlgy_0kZLcic2NINCUt) guided throughout the project developement, especially on the planning stage.
    
* Acknowledgements
    * Special thanks of gratitude to my project mentor Daisy McGir for her guidance at every stage of the project,continuos support, understanding, encouragement and supply with useful information .
    * Special thanks of gratitude to our cohort tutor Irene Neville for her continuos support, for informational material and for providing with all the facilities required during the project developement.
    * Code Institute Learning Programm.
     








