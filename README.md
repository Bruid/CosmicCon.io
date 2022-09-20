# CosmicCon

**MileStone project 1: HTML/CSS Essentials.**

This product/ website project was designed around space, comics, books and instellar activities. Its designed to be a free content delivering website to each of its users, when you sign up you will recieve content each of books, comics and movies.

A live version of my website CosmicCon can be found [here](https://bruid.github.io/CosmicCon.io/)






![Design](/images/)




# Contents
* [**User Experience UX**](<#user-experiences-user-design>)
    * [User Stories](<#ux-user-design>)
    * [Wireframes](<#wireframes>)
    * [Site Structure](<#site-structure>)
    * [Design Choices](<#design-choices>)
    * [Typography](<#typography>)
    * [Colour Scheme](<#color-scheme>)

* [**Features**](<#features>)
    * [**Home**](<#navigation-menu>)
    * [Navigation menu](<#navigation-menu>)
    * [About-us](<#about-us>)
    * [Footer](<#footer>)
* [**Contact Us**](<#contact-us>)
* [**Future Features**](<#future-features-to-implement-to-the-website>)
* [**Technologies Used**](<#technologies>)
* [**Testing**](<#testing-of-the-website>)
* [**Deployment**](<#deployment>)
* [**Credits**](<#credits>)
    * [**Content**](<#content>)
    * [**Media**](<#media>)
    * [**Code Acknowledgement**](<#code>)






# User Experiences (User Design)

## UX (User Design)

* As a user of this website I would like to have easy navigation to other pages
* As a user of this website access to the social media would be beneficial
* As a user of this website ability to know what the company does and what its about
* As a user of this website Id like to see nice layout and styles thats easy to the eye
* As a user of this website I would like to be able to see the website in resposive design

## Wireframes

The wireframes for this project ComicCon here [Figma](https://www.figma.com/)

## Site Structure

CosmicCon project has 3 pages in total, the first being [Home-Page](index.html), which showcases the hero image section and also the card section highlighting the services or features the website promotes as its service. The second page [About-Us](about.html) highlights the company information with a image of a comic and social media icons mentioning what the company does etc it also highlights that there is maintenance undergoing that a portion of the site is not active just yet(due to be added in during progression through the course with JS). The third page [Contact](contact.html) is the contact us page where the user will fill out their details and any questions or queries relating to services or content.

## Design Choices

* ### Typography 

- For this project the font that was used was sans-serif, as this is a standard font and if other fonts would not load this font will load as a fallback font.

* ### Color Scheme

- The colors chosen for this project were chosen so the images and hover psuedo attributes etc would stand out to the eye not causing the reader or visitor to have to focus on key areas to render the information on the screen.

## Features

- CosmicCons a site that is pretty easy to use and navigate through with links and pages connecting to each other, it contains features that the user would typically be familiar with, such as a nav bar, footer element, social media links and a contact form.


## Existing Features 

* ### Navigation Menu

  - The navbar is loacted at the top of the page where it contains a logo or shows the name of the company "CosmicCon" this navbar structure contains 3 links which navigate to the other two pages and the home linking back to the index page. When rendered on a small device the navbar collapses and and hides the logo icon using media queries, and also forms a burger icon so that the links/tabs of the navbar are structured well and not clustered all over the screen.

* ### About-Us

  - The about us page/ section contains information of the company and its purpose. In this about us section there is an image contained to the right side of the paragraph, with social media icons linking actively to the social media platforms of each icon. The header in the about us section is a h1 element and also shares a font awesome icon to make the website look more inviting/ designed better.

* ### Footer

- The footer is located at the bottom of the page where it stays fixed and does not move with the user when scrolled.
- The footer did have a word-spacing effect in css but in mobile design the icons were overflowing so the spacing was reduced/ removed and now they render well all the way down to 230px screen width.

* ### Contact Us

- This section was created for the user to contact the team directly at CosmicCon, by inputting their details and queries into the form element on the contact page.


* ### Future Features to Implement to the website

Future plans for this website would be to add a download feature where users can download copies or sample editions of books, comics or even watch movie reviews linked from other websites like youtube or IMBD where it is all present in the one place and searchable by a search function.


* ## Technologies Used

-  HTML - *Used to create a basic standard webpage*
-  CSS - *Used to design and add styles to the webpage and help it standout better*

* ## Testing of the Website

When designing the website all the links in the navbar were set up and then tested after creating them, the buttoms  also carry the same style design and element attributes as each other also all were tested before designing and after designing with css to ensure they are all working correctly, and ensuring that they all also open with a _blank attribute and go to the desired address also. The contact page form has been tested with being filled out with the required information and also pressing submit and everthing works as originally planned. 

when the screen resolution changes to a smaller smaller screen the navigation bar collapses into a burger dropdown icon menu. The footer adjusts to smaller screens by aligning the footer elements along the left hand side of the page for mobile friendly devices creating a cleaner less condensed, more tidier appearance by removing the word spacing around each social icon stopping them from overlapping.


## Bugs Found

During this project I had issues running the hero section on a responsive design where the cards were pushed up and the hero image was pished into the navbar, this was fixed by adding margin-top and bottom with padding to the hero section and card section. The about page had a similar issue where the height of the about us section was overflowing the screen so chnaged the margin and also the VH dropped from 100 down to 85-90 and fixed the issue.


# Deployment

This assignment/ Project was Deployed on guthub pages directly from the master branch and along with the theme jekyll as a standard theme provided by github.
The main page/landing page for github pages to load was named index.html as this is needed for the browser to read and deploy the website correctly.


### **To deploy the project to Github**

The site was deployed to GitHub pages. The steps to deploy a site/ repository are:
  - In the GitHub repository, navigate to the **Settings** tab on the created repository.
  - When in Settings, navigate to the **Pages** tab on the left hand side.
  - Under **Source**, select the branch to **master**, then click **save**.
  - Once this has been done it will take some time to deploy, once done the repository url link will appear allowing to view the website in a browser as if it is a published website with a domain etc.


### **To create a local clone of this project**

The process of cloning a project from GitHub is:

- Under the repo’s title, click on the **code** drop down tab.
- In the **Clone with HTTPS** section, click on the clipboard icon to copy the given URL.
- In your IDE of choice, open **Git Bash**.
- Change the current working directory to the location where you want the cloned repositorys directory to be made.
- Type **git clone**, and then paste the URL copied from GitHub.
- Press **enter** and the local clone will be created.

### To view this page from the github terminal:

- `python3 -m http.server`
- A blue button should appear to click: _Open Browser_.
- A new browser window should appear
- Dont Forget to clear cache if having issues loading CSS and HTML.

to remove or cut ties with github and its repositories in the terminal inside github write:
- `git remote rm origin`

* ## Validator Tools Used:

1. [W3C-HTML-Validator](https://validator.w3.org/) :This was used to validate my html code and test for errors and update the code to fix any errors, this is used by copying and pasting the code in to use the validator to check and then paste back in.
![Design](/images/html-validation.png)
2. [Jigsaw-W3-CSS-Validator](https://jigsaw.w3.org/css-validator/validator): This was used to validate my css code and test for errors and update the code to fix any errors, this is used by copying and pasting the code in to use the validator to check and then paste back in.
![Design](/images/css-validation.png)
3. [Web-formatter-tool](https://webformatter.com/css) : This was used to format my code to make the indentations correct to clean and position my code correctly and neatly by copying into the editor running it and then pasting it back into the gitpod.
![Design](/images/code-formatting.png)


# Credits

## Content

During this project I had used resources from different sites for html assistance in markup and also css styles:

- [W3Schools](https://www.w3schools.com/)
- [Stack-Overflow](https://stackoverflow.com/)
- [Youtube](https://www.youtube.com/)
- [Reddit](https://www.reddit.com/)
- [Font-Awesome-Icon](https://fontawesome.com/icons)
- [Google-Fonts](https://fonts.google.com/about)
- [Geek-for-Geeks](https://www.geeksforgeeks.org/)
- []()

## Media

Pexels was used for the free image gathering [Pexels](https://www.pexels.com/)

## Code

### Acknowledgements of assistance of work used in this project

- For the navbar I gained assistance from [Code-Pen](https://codepen.io/MinzCode/pen/bGexzXw): I found it hard creating a navbar using just css and html so I used assistance of the navbar form code pen in the lsited listed above link, and changed the styles according to the website needs.

- For the card section I tried muyltiple ways to complete this but when trying different methods it was disrupting my other stylea and elements. I used assistance from [Code-Info-Web](https://www.codeinfoweb.com/2021/03/Responsive%20Cards.html) for the cards I changed the images, added styles and colors and font sizes, I also added hover psuedo attributes and also links to sources and also border radiuses etc.

- For the about section I used assistance and changed styles to fit my website needs and added css and html to improve it different for my site [GitHub])(https://github.com/dhakallena/Responsive-About-Us-section-Using-Html-And-Css)
