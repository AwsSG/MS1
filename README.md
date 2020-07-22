#Aws online WEB CV

MS1 GitHub project page [here](http:)

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

    -   Home (Aws) Page Wireframe - [View](https://github.com/)

    -   Work History (Aws Work History) page Wireframe - [View](https://github.com/)

    -   Contact (Contact Aws) Page Wireframe - [View](https://github.com/)

## Features

-   Responsive on all device sizes.

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
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
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   W3C Markup Validator
-   W3C CSS Validator

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

-   The Website was tested on Google Chrome, Internet Explorer, and Microsoft Edge browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, Big LG screen, iPhone 8 & iPhone5/SE.
-   Testing was done to ensure that all pages were linking correctly. As well as the download and social links.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On some screen sizes, the keywords fade in animation shows a little glitch that makes the text move slightly upwards after the animation ends.
-   The rounded edges of the cards and the footer shows a bit of distorsion on not standard screen sizes.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.
