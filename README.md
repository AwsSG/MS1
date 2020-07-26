# Aws online WEB CV

MS1 GitHub project page [here](https://awssg.github.io/MS1/index.html)

This is the main website used to show my CV for the targeted audience (in user stories). It was designed to be simple and clear on wide range of devices, making it easy to follow and navigate.

## User Experience (UX)

-   ### User stories

    -   #### Recruiters

        1. As a recruiter, I want to easily get an understanding of this developer’s background and experience so I can decide if I want to contact him or not.
        2. As a recruiter, I want to be able to easily navigate throughout the site to find content.
        3. As a recruiter, I want to find what projects this developer had done so far.
        4. As a recruiter, I want to easily contact the developer about a project.


-   ### Design
    -   #### Color Scheme
        -   There is a total of 5 colors used. Of those colors, two were the main; a degree of white and dark gray. Dark red was used to show the hover effect on the clickable links.
        -   The background image used was dark pattern taken from subtlepatterns  (https://www.toptal.com/designers/subtlepatterns/)  

    -   #### Typography
        -   The Roboto font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Montserrat is a clean font used frequently in programming, so it is both attractive and appropriate. A secondary font was used in the subheadings, which was Exo 2. Another font that is clear and attractive for subheadings and it looks good when combined with uppercase letters.
    -   #### Imagery
        -   The only image used was the personal image, just so that the user would have a face with the contents of the CV website.

*   ### Wireframes

    -   Home (Aws) Page Wireframe - [View](wireframe/index.png)

    -   Work History (Aws Work History) page Wireframe - [View](wireframe/workhistory.png)

    -   Contact (Contact Aws) Page Wireframe - [View](wireframe/contact.png)

## Features

-   Responsive on all device sizes.
-   Leyout of the skills in the index page change from meduim screen sizes and below.

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.5:](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
    - Latest Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the Roboto and Exo 2 fonts into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages’ footer in the social links throughout the website to add icons for aesthetic and UX purposes.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   W3C Markup Validator: No errors were found.
-   W3C CSS Validator: No errors were found.

### Testing User Stories from User Experience (UX) Section

-   #### Recruiters

    1. As a recruiter, I want to easily get an understanding of this developer’s background and experience so I can decide if I want to contact him or not.

        1. Upon entering the site, recruiters are presented with a clean and easily readable dar background layout with bright text on all pages. Navigation is simple at the top of the page, wiith self explinatory text.
        2. The profile of the developer is presented in two stages. First, the name and keywords that developer describes himself as. second, a shot bio outlining the developers profile and personality.
        3. Recruter is then able to see the skills on the main two areas, with a layout that is best presented on tablets and computer screens.
        4. Finally, the recruiter will be presented with the latest projects that the developer did, with links to go to each project page.

    2. As a recruiter, I want to be able to easily navigate throughout the site to find content.

        1. The home page was desinged to lead the users' eyes down on logical flow from top to bottom. Starting with navigation and ending with social links at the footer.
        2. The navigation buttons are self explinatory, and the contents of each page corrospond to its navigation button text.

    3. As a recruiter, I want to find what projects this developer had done so far.

        1. Presented at the home page, after the recruiter has skimmed through the developer's profile, the most recent projects are presented in a clear card layout with links to each of the project.

    4. As a recruiter, I want to easily contact the developer about a project.

        1. As logically expected, the contact navigation botton leads to a contact form where the recruiter can write to the developer about any type of project.


### Further Testing

-   The Website was tested on browsers (Google Chrome, Internet Explorer, Microsoft Edge browsers) and it worked properly.
-   The website was viewed on a variety of devices (Desktop, Laptop, Big LG screen, iPhone 8 & iPhone5/SE) and the responsiveness was woring properly.
-   Testing was done to ensure that all pages were linking correctly. As well as the download and social links.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues. non were found.

### Known Bugs

-   On some screen sizes, the keywords fade in animation shows a little glitch that makes the text move slightly upwards after the animation ends.
-   The rounded edges of the cards and the footer shows a bit of distorsion on not standard screen sizes.
-   On some very small screen sizes (Galaxy Fold), the tags under the main name header wraps to a second line. Which is not intended.
-   On some not standard screen sizes, some items in the personal info card overflows outside its box to the right. Which is not intended.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the steps in the CI video (GitHub Pages) as follows...

1. Log in to GitHub and locate the [GitHub MS1 Repository](https://github.com/AwsSG/MS1)
2. Go to the "Settings" tab and scroll down to GitHub Pages.
3. Under the "source" Select the "master branch" and click "save".
4. Scrol down on the next page to GitHub Pages and find the live link to the project.

## Credits

### Code

-   The dark background image file came from [subtlepatterns](https://www.toptal.com/designers/subtlepatterns/)

-   [Bootstrap4](https://getbootstrap.com/docs/4.5/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System and to use some dafualt styling.

-   The fade in animation on the tags under the main name header came from [Stackoverflow post](https://stackoverflow.com/questions/29846224/css-animation-with-delay-and-opacity)

### Content

-   All content was written by the developer.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.
