<div align="center">
<img src="/assets/images/readme/all_devices.png" target="_blank" rel="noopener" alt="Space Facts">
<h1>Sp@ce F@cts</h1>
    - First version can be see here
</div>


  Hello everyone welcome to Sp@ce F@cts your new favorite space app.
 
  Sp@ce F@cts was started in April 2020 as educational school project.
 
  The site itself is educational and was created out of love and hobbies. Its purpose is to share information about the universe. Site will be updated over time and i would like to keep the design as much as possible as it is right now. Nice simple black background with high resolution pictures to highlight all the beauty, intrigue and incredible appearance of some objects in space.

  I am thrilled that I can turn my passion and hobby into my own website. I hope you enjoy my web page as much as I enjoy presenting space facts to you all.

#### You can access the application [here.](https://ivantepes.github.io/Space-Facts/)
# Table of Content
- [UX](#ux)
  * [User Stories](#user-stories)
  * [Design](#design)
    + [Typography](#typography)
    + [Colours](#colours)
    + [Icons](#icons)
  * [Wireframes](#wireframes)
- [Features](#features)
    + [Layout](#layout)
    + [Buttons](#buttons)
    + [Font](#font)
  * [Existing Features](#existing-features)
    + [Responsiveness](#responsiveness)
    + [Navigation Bar](#navigation-bar)
    + [Landing page and jumbotron](#landing-page-and-jumbotron)
    + [Explore section and Buttons](#explore-section-and-buttons)
    + [Multi-page layout](#multi-page-layout)
    + [Planets](#planets)
    + [About](#about)
    + [Contact Us](#contact-us)
    + [Footer](#footer)
    + [Features Left to Implement](#features-left-to-implement)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Tools Used](#tools-used)
  * [Libraries](#libraries)
- [Testing](#testing)
  * [Browser used in testing](#browser-used-in-testing)
  * [Responsiveness](#responsiveness-test)
  * [Lighthouse](#lighthouse)
  * [Validators](#validators)
  * [Users Testing](#users-testing)
    + [Meeting the needs of the user stories (as described in the UX section of this README file)](#meeting-the-needs-of-the-user-stories--as-described-in-the-ux-section-of-this-readme-file-)
- [Deployment](#deployment)
- [Credits](#credits)
  * [Content](#content)
  * [Media](#media)
  * [Inspiration](#inspiration)
  * [Acknowledgements](#acknowledgements)

```diff
- After first testing and testers feedback i changed and added some features to page and explanation of changes will be highlight futher in text.
``` 

# UX

## User Stories

### As a user of this application, I will be able to:

- Access the application from your favourite equipment, such as smartphones, tablets, laptops or PCs, without loss of content.

- Easily navigate the site across all pages.

- Enjoy viewing high quality pictures of space and objects.

- To see simple, clear design, which cleary shows what the user can do.

- Want to see what different category are included in content.

- Expect to know from where the content of the site came from.

- Be able to contact somebody about content, prise, critics, mistakes or any other topic.

## Design
This project was developed with a focus on a mobile approach first. However, with full responsiveness on other screen sizes.
I used the jumbotron, grids, nav, cards, forms, table, carousel and bootstrap in this project.
The main idea for the design of this project was to have a serious and professional appearance, transparent navbar, black background to highlight images of space objects, which convey sophistication and provide a pleasant user experience.
~~I used the two icons on the home page to clarify what the user should do when they first come to the page, I made them clicable so that the user is taken to the content by pressing~~.

`For better clarifycation bouncing icons are replaced with **Scroll Down** text and three **Arrows** on bottom of landing page, **Explore** message/button is changed in color from white to orange. At the same time by hover over text **Explore** explore message transform to button, text and background changes color letting the user know that the action can achieve something.`

### Typography
The main font used in this project is **Robotto**. I think that's a well designed and easy to read font. An extra reason for using this font is the excellent display on small screens.
In the main titles of the site and logo the font **Girassol** was used, which also has a good design and combines nicely with the main font.

### Colours

- In the colour scheme, i used black, orange and white which combined together give me favoured the easy visualization of the information.

- Transparent rounded navbar with orange border and same style is used for footer to greater contrast and to get pleasant ux.

- Transparent callout section with white text and orange seperators for text and that style is constantly used through all pages.

- In the background, I used an black-blue image of the galaxy for callout section and black universe image for planet section which provide me great ground for planets to "float".

- The orange buttons continue and blend in with the black-and-orange design, changing the color on hover.


#### Colors used on site can see [here.](/assets/images/readme/colors.png)

### Icons

The icons used in this project are provided by [Font Awesome](https://fontawesome.com/).
They were used as social media icons in the footer and on contact page as address, comment and map.

## Wireframes

Wireframes were designed with [Balsamiq Wireframes](https://balsamiq.com/wireframes/). These were the first version of scope and some things have changed, removed or leave for later development.
* Mobile  [here](/assets/images/readme/wireframes/mobile.png)
* Detskop home [here](/assets/images/readme/wireframes/index.png)
* Detskop planets [here](/assets/images/readme/wireframes/planets.png)
* Detskop contact [here](/assets/images/readme/wireframes/contact.png)
* Detskop login [here](/assets/images/readme/wireframes/login.png)
* Call to action button [here](/assets/images/readme/wireframes/call_to_action.png)
* Site map [here](/assets/images/readme/wireframes/site_map.png)

# Features

### Layout
This is a multi-page layout, but designed with simplicity in mind. The home page displays the navbar with dropdown menu and jumbotron in middle, below the header text is Explore message/button which allows the user to find information very quickly without the need to have to search for it.

### Buttons
Buttons on this application are made with **Bootstrap**. Big, and easy to use.

### Font
Two fonts used are a google fonts, called **Robotto** and **Girassol**.

`**Smooth Scroll**`

`On whole site is added **Smooth Scroll**. One of testers say that scroll is too strong when **Explore** message/button is pressed.`

## Existing Features

### Responsiveness
  The biggest feature of this site is the responsiveness across devices and screen sizes that we have achieved using [Bootstrap](https://getbootstrap.com/docs/4.4/layout/overview/) layout. 
  So with small screens or mobile phones we have one planet per row, on medium screens as tablets we have two planets per row, while on desktop and larger screens we have four planets per row which led to better visibility, organization, readability and better visual presentation.

* **Small screen, medium screen,large screen.**
<div align="center">
  <img src = "/assets/images/readme/features/responsiveness/small.jpg" width ="200" alt="small screens"/>                                   <img src = "/assets/images/readme/features/responsiveness/medium.jpg" width ="200" alt="medium screens"/> 
  <img src = "/assets/images/readme/features/responsiveness/large.jpg" width ="200" alt="large screens"/>
</div>

### Navigation Bar 
  Is on the top of all the pages on the site and is fixed, with rounded on edge and transparent to give user sense where is when scroll. The left hand side has the logo of the page being **Sp@ce F@cts**, and when clicked, will return the user to the home page. The rest of the navigation items are centred to middle of the Navigation bar and they are: **Home**, **About us** and **Planets** which is also a drop down menu and change shape to three lines called "Burger" for mobile screens `and tablets screens`. 
    
`Navigation bar is now centered middle on mobile screens too, before was lined to left side when is in drop down shape.`

  Navigation item **Planets** have orange down indicator and is drop down menu on larger screens.
  Navigation bar have thick orange border on bottom side to separate navigation bar from rest of page because is rounded and only on bottom side give pleasant and interesant ux.
  The Navigation bar gives the user information about where he is on the site by changing the color of the active page also change color on hover provide user information what action he can make.

* **Navigation bar with active home page**

<div align="center">
<img src="/assets/images/readme/features/navbar/navbar.jpg" target="_blank" rel="noopener" width="800" alt="Nav bar home">
</div>

* **Navigation bar with active about**

<div align="center">
<img src="/assets/images/readme/features/navbar/navbar_about.jpg" target="_blank" rel="noopener" width="800" alt="Nav bar about">
</div>

* **Navigation bar items on hover**

<div align="center">

![nav](/assets/images/readme/features/navbar/nav.gif)
</div>

* **Navigation bar with active planet mars and dropdown menu before and after update**
* `Navigation bar was changed with last update. The functionality remained the same only the style was changed to fit into whole design.`

<div align="center">

![nav](/assets/images/readme/features/navbar/dropdown_old.gif)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![nav](/assets/images/readme/features/navbar/new_dropdown.gif)
</div>

* **Navigation bar with active planet mars on small and medium screens before and after update**

<div align="center">
<img src="/assets/images/readme/features/navbar/nav_mobile.jpg" target="_blank" rel="noopener" width="300" alt="Nav bar mobile">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="/assets/images/readme/features/navbar/nav_mobile_new.png" target="_blank" rel="noopener" width="300" alt="Nav bar mobile">
</div>

### Landing page and jumbotron

* Background for landing page i chosen dark black-blue image with orange center of galaxy and slightly transparent jumboton in middle give nice sight in that image.

* **Jumbotron** contains a question that immediately catches the eye and prompts the user to ask for a second what the universe is, the second thing is ~~that distracts him are two bouncing icons around the message~~**Explore** message/button in orange colour to interest him and encourage him to explore the site the third thing is the `**Scroll Down** text and the three **Arrows** that point down and have an animation of disappearing and reappearing over a period of time.`

* **Explore** is designed as call-to-action button and are clickable and on desktop screens when hover over it with mouse change colours giving user information that he can make action whit it.

* ~~**Bouncing icon** are designed to let the user know that he should scroll the page, but if he did not understand the first idea and clicks on the icon or on **Explore** the page will automatically move to the section with planets.~~

* **Scroll down and Arrows** ``are one of changes that i make after first testing of application. They try to clarify what user need to do when land for first time on page. With first design **Bouncing icon** around text **Explore** testers had the impression that it was not clear enough what to do on the first visit to the site.`` 

* **Jumbotron, Bouncing icons and Explore before update.**
* `Jumbotron, Scroll Down Text and Explore after update.`

<div align="center">

![jumbotron](/assets/images/readme/features/jumbotron/jumbotron.gif)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![jumbotron](/assets/images/readme/features/jumbotron/jumbotron_new.gif)
</div>

###  Explore section and Buttons

* **The Explore** section contains pictures of all the planets offered on the site and one fact about each planet, it also contains a button with the message **Read more** that changes color when hover over it and clicking on it leads the user to a page about the planet he is interested in.

* **Buttons**
with the **Read more** message are designed using a **[Bootstrap](https://getbootstrap.com/)**, are orange in color ~~and change slightly to a lighter shade of orange~~  when hover over it on detskop screens changes color providing user information that he can make action whit it.

* `The buttons are styled with an update for a better visual impression and to follow the design of the site.`

* **Explore section with one facts and button Read More before and after update.**

<div align="center">

![Read More buttons](/assets/images/readme/features/button/buttons.gif)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![ Read More buttons](/assets/images/readme/features/button/buttons_new2.gif)
</div>

### Multi-page layout

* This site has several separate pages in total 11 at the moment. The **Home** page we went through in the text above, **About us**, **Contact** and 8 **Planets** from our solar system.
  Multi-page layout, but designed with simplicity in mind.

* Each **Planet** has a separate page with more information about the same.

* **Home page and planets together**

<div align="center">
<img src="/assets/images/readme/layout.png" target="_blank" rel="noopener" width="700" alt="Nav bar about">
</div>

### Planets 

* **Planet** page is designed with dark background image, carousal that rotate the images of the planet, table with information about the planet and a couple of interesting facts.

* **Responsiveness** of all planet pages can be seen on different screen sizes. **Table** and **Facts** sections on small and medium screen sizes will be stack verticly and on larger size screens will be next to each other. With this we get better readability of facts and tables.

<div align="center">
<img src="/assets/images/readme/features/responsiveness/planet_ress.png" target="_blank" rel="noopener" width="700" alt="Planet page ressposivnes">
</div>

* **Background** image is a dark photograph of the universe. Which serves as a space for the carousel and images of planets to "float" in that universe.

* `** Buttons for small and medium screens ** are added with update because feedback from testers.`
    - `On small and medium screens, after the facts and the read text, the user is offered quick navigation with three buttons. Return to the **Explore** section on the **Home** page which would happen by pressing the **Planets** button positioned in the middle or selecting the next / previous planet displayed through the planet name. The first and last planets have an activated page where we are letting us know that we are at the beginning or the end. When button with active planet is pressed page will scroll to te top of selected page.`

* `Quick navigation when we are on planet ** Mercury **, planet ** Earth ** and planet ** Neptune **`

<div align="center">
<img src="/assets/images/readme/features/navbar/quick_nav_first_active.jpg" target="_blank" rel="noopener" width="200" alt="Quick navigation with first page actived">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/features/navbar/quick_nav.jpg" target="_blank" rel="noopener" width="200" alt="Quick navigation with three button">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/features/navbar/quick_nav_last_active.jpg" target="_blank" rel="noopener" width="200" alt="Quick navigation with last page actived">
</div>

* **Images of the planets** have a transparent background leaving only the planet visible to the user as the image of the universe is behind the planets we get the floating effect I mentioned earlier.

* **[Carousel](https://getbootstrap.com/docs/4.5/components/carousel/)** is taken from **[Bootstrap](https://getbootstrap.com/)** and contain 4 image of each planet all images have transparent background for float effect.
* `Carousel indicators are changed with update. Styled and positioned on bottom of carousel for easier navigation and visability`

* **[Table](https://getbootstrap.com/docs/4.5/content/tables/)** used in page are same from **[Bootstrap](https://getbootstrap.com/)** and they contain information about each **Planet** in some column comparing it to earth to be able to imagine their size, if that is even possible.. They are orange color to separate them from facts and to get pleasant visual effect.

* **Facts** are on each **Planet** page. Contain couple interesting facts about planet and they are in white color.

* **Carousel with planet Uranus and float effect with indicators before and after**

<div align="center">

![carousel](/assets/images/readme/features/carousel/float_effect.gif)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![carousel](/assets/images/readme/features/carousel/float_new.gif)
</div>
    

### About

* About page contains a short motivation message, information about the author, the page and information about the content. Each of the   sectors contains a link for further action. Such as the contact of the author, the font used on the page and the source of the information.

### Contact Us

* **Contact us** is divided into two items. The first item gives the user contact information such as address, phone number and email address.
While the second item allows the user to have direct contact with the author and requests from the user: name, email address and comment.

* **Contact us** page can be reached through the **About** page and through the **Footer**.
* An **[Font Awesome](https://fontawesome.com/)** was used to mark the information given to the user.
**[Bootstrap](https://getbootstrap.com/docs/4.5/components/forms/)** was used to create the contact form.

* **Address** and **Form** 

<div align="center">
<img src="/assets/images/readme/features/contact.jpg" target="_blank" rel="noopener" width="800" alt="contact page whit form and contact information">
</div>

### Footer

* **Footer** is located at the bottom of each page on this site.
* It is the same on each page and uses the orange rounded edge that we also saw on the navigation bar only this time from the top to    separate it from the rest of the content.

* **Footer** is divided into **About** i **Social**.
* **About** contains links for **About** page and **Contact** page which at the hover on detskop screens get a horizontal orange line below the link. 
* While **Social** contains social network icons that animate icons by zooming. Social icons used here are from **[Font Awesome](https://fontawesome.com/)**

* Animated Zoom used here are from **[w3schools.com](https://www.w3schools.com/howto/howto_css_zoom_hover.asp)**.

* Footer with **About** and **Social**

<div align="center">
<img src="/assets/images/readme/features/footer/footer.jpg" target="_blank" rel="noopener" width="800" alt="footer with about and social network icons">
</div>

* **About** links and **Social** icons on hover

<div align="center">
  
  ![about](/assets/images/readme/features/footer/about.gif)![social](/assets/images/readme/features/footer/social_zoom.gif)
</div>

### Note

* The form on the **Contact** page as well as the submit button are currently not in function due to lack of skills to embed them in the code.

* Footer **Social** network icons when clicked will take the user to the home page of the target platform Sp@ce F@cts does not currently have any profiles on the social network and they are there for visual appearance.

### Features Left to Implement

 * More content to site such as Galaxys, Solar System, Comets etc. Can se some projections from scope [here](/assets/images/readme/wireframes/site_map.png).

 * Login feature to site with addition ideas such as disscusions about space.

 * News banner with latest news research or news about space general.

 * Subscribe feature.

 * Share button to share site or particular parts of site.  

 * Comparation chart, diagrams or images to compare other objects in space with something more familiar to human.

 * Animation of planets, galaxies, comets etc.

 # Technologies Used

 ## Languages

 ### Hyper Text Markup Language or HTML 
* **[HTML](https://www.w3.org/TR/html52/)** is the standard markup language for creating Web pages.
* I used this programming language to provide structure and presenting content of site.

### Cascading Style Sheets or CSS 
* **[CSS](https://www.w3.org/Style/CSS/Overview.en.html)** is a style sheet language used for describing the presentation of a document written in a markup language like **HTML**.
* In this project i used **CSS** to describes and style **HTML** document such as layout, colors, font and animation.

## Tools Used

* **[Balsamiq Wireframes](https://balsamiq.com/wireframes/)** 
    - Used to create the wireframes and planning this project.
* **[Gitpod](https://www.gitpod.io/)**
    - Used as development environment for building the application.
* **[GitHub](https://github.com/)**
    - Used to store and share all project code remotely.
* **[Photoshop](https://www.adobe.com/ie/products/photoshop.html)**
    - Used to edit all pictures on site and creating some presentation images for README.
* **[Dev Tools](https://developers.google.com/web/tools/chrome-devtools)**
    - Used to keep track and test the code during the development.
* **[Tinypng](https://tinypng.com/)**
    - Used to compress the size of images.
* **[HTML Formatter](https://www.freeformatter.com/html-formatter.html)**
    - Used to formating code.
* **[Autoprefixer](https://autoprefixer.github.io/)**
    - Used to valid code for all browsers.
* **[Trello](https://trello.com/)**
    - Used for organize user stories and determination of sprints.
* **[Favicon & App Icon Generator](https://www.favicon-generator.org/)**
    - Used for creating favicon for site.
* **[HTML Color Codes](https://htmlcolorcodes.com/)**
    - Used for creating color.
* **[Adobe Color](https://color.adobe.com)**
    - Used for creating color.
* **[ScreenToGif](https://www.screentogif.com/)**
    - Used for creating gif for README.
* **[Paint 3D](https://www.microsoft.com/en-us/p/paint-3d/9nblggh5fv99?activetab=pivot:overviewtab)**
    - Used for creating color patters presentation.

## Libraries

* **[Bootstrap](https://www.bootstrapcdn.com/)**
    - Is uses for better responsiveness and organization.
* **[FontAwesome](https://fontawesome.com/)**
    - Is uses to provide icons.
* **[Google Fonts](https://fonts.google.com/)**
    - Is uses to provide 'Roboto' ans 'Girassol' font.
* **[JQuery](https://jquery.com)** 
    - Is used to simplify DOM manipulation.

# Testing

* Testing information can be found in separate [testing.md](testing.md) file.

# Deployment
This project was developed using the **[Gitpod](https://www.gitpod.io/)** Integrated development environment, version controlled by committing to git and pushing to **[GitHub](https://github.com/)** via the **GitPod** IDE.

To deploy this page to **GitHub** pages from its specific **GitHub** repository the steps followed were;

* Scroll to the top of this **GitHub** page or press **[here](https://github.com/IvanTepes/Space-Facts)**.

* From the horizontal menu select **Settings**
    
* The page should be open on **Options** if is not select **Options** from left menu.
    
* Scroll down to the **GitHub Pages section**
    
* Under **Source** select **Master branch**
    
* On selecting **Master branch** the page is automatically refreshed, the website is now delployed.

* The link to the webpage can be found at the top of the **GitHub Pages section**

How to run this project locally?

To clone this project from GitHub:

* Follow this link to the Project GitHub repository.

* Under the repository name, click **Clone or download**

* In the Clone with HTTPs section, copy the clone URL for the repository

* In your local IDE open the terminal

* Change the current working directory to the location where you want the cloned directory to be made.

* Type **git clone**, and then paste the URL you copied from repository.

* Press Enter. Your local clone will be created

# Credits

## Content
* All content on site is copied from **[Wikipedia](https://en.wikipedia.org/wiki/Solar_System)**.
## Media
* All images on site are copied from **[Wikipedia](https://en.wikipedia.org/wiki/Solar_System)** and **[NASA](https://www.nasa.gov/)**.

## Inspiration 

* Color Patterns from **[Adobe Color](https://color.adobe.com/search?q=earth%20space)**.

* Font Inspiration from **[Reliable](https://www.reliablepsd.com/ultimate-google-font-pairings/)**.

* Inspiration, ideas , problems solutions from **[Free Front End](https://freefrontend.com/)**, **[Codepen](https://codepen.io/)**, **[w3schools.com](https://www.w3schools.com/)**, **[Stack Overflow](https://stackoverflow.com/)**, **[Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)**, **[Behance](https://www.behance.net/onboarding/adobe)**

* And some more but i lost track of all articles readed and web pages visited.

## Acknowledgements

* I'd like to thank my mentor in Code Institute **Precious Ijege** who had all the patience to explain and make me understand certain concepts and peculiarities of the project. And also for useful and constructive feedback through this project.

* To my girlfriend who was my biggest helper, the biggest critic, the voice of common sense in some difficult moments during the making of this project.

* All people, including family, friends, and colleagues who have tested the application on their real devices, reporting to me about any usability issues and giving improvement tips to improve the usability.

* To all of the Code Institute Slack community for the help in my issues and review to my project.

### The content of this website is for educational purposes only. 
### Thank you.