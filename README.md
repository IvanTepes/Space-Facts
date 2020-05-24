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

![buttons](/assets/images/readme/features/button/buttons.gif)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![buttons](/assets/images/readme/features/button/buttons_new2.gif)
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
    - `On small and medium screens, after the facts and the read text, the user is offered quick navigation with three buttons. Return to the **Explore** section on the **Home** page which would happen by pressing the **Planets** button positioned in the middle or selecting the next / previous planet displayed through the planet name. The first and last planets have an activated page where we are letting us know that we are at the beginning or the end.`

* `Quick navigation when we are on planet ** Mercury **, planet ** Earth ** and planet ** Neptune **`

<div align="center">
<img src="/assets/images/readme/features/navbar/quick_nav_first_active.jpg" target="_blank" rel="noopener" width="300" alt="Quick navigation with first page actived">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/features/navbar/quick_nav.jpg" target="_blank" rel="noopener" width="300" alt="Quick navigation with three button">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/features/navbar/quick_nav_last_active.jpg" target="_blank" rel="noopener" width="300" alt="Quick navigation with last page actived">
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
<details>
    <summary>Click to expand!</summary>

During the development of this project, I had the experience of facing some problems. Browser used for testing application during development was **[Google Chrome](https://www.google.com/chrome/)** and **[Dev Tools](https://developers.google.com/web/tools/chrome-devtools)** from same browser. For audit the site i use **[Lighthouse](https://developers.google.com/web/tools/lighthouse/)** from **Chrome DevTools**. Exhaustively testing the functionality of each part of the application and managed to solve most of the problems that across before writing this document. However how process of testing is being expanding on different browsers and different devices some problems are found and noticed. Some I solved and corrected, some remained uncorrected until the end of the test, and as my skills and knowledge develop, so they will be eliminated.

I received help from some family members and friends to do the tests on application.

Testing is conduct by sharing application to them and have conversation about application.

This was the primary method of testing the application. People were asked to visit the website on a variety of devices. This feedback was very uselful to determine any bugs that may have been present. I also tested the app manually myself on a varietly of browsers and tools. 

## Browser used in testing 

* **[Google Chrome 81.0.4044.138](https://www.google.com/chrome/)**
    - Is uses for testing site through all developing process and DevTools for responsiveness and scaling issues on different screen sizes.
* **[Mozilla Firefox 76.0.1](https://www.mozilla.org/en-US/exp/)**
    - Is uses for testing site and responsiveness and scaling.
* **[Opera Web Browser 68.0.3618.104](https://www.opera.com)**
    - Is uses for testing site and responsiveness and scaling.
* **[Microsoft Edge 44.18362.449.0](https://www.windowscentral.com/microsoft-edge)**
    - Is uses for testing site and responsiveness and scaling.


* Testing was conducted on the browsers above on the first three browsers such as **Google Crome**, **Mozilla Firefox** and **Opera Web Browser** no problems or bugs were noticed. 
* But on the **Microsoft Edge** we encounter a bug at the beginning of the site and that is the only bug noticed on that browser.

    - Bug on **Microsoft Edge** web browser `before update`. ( bug was attempted to be corrected through the **Autoprefixer** but bug is still remained visible.)
    - `After the update, the first bug was removed, but a new one appeared on navigation bar`
    
<div align="center">
<img src="/assets/images/readme/testing/bug/edge_bug.png" target="_blank" rel="noopener" width="300" alt="microsoft edge bug">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/bug/bug_edge_new.png" target="_blank" rel="noopener" width="300" alt="microsoft edge bug">
</div>

- `Also ** Smooth Scroll ** feature does not work on Microsoft Edge.`

* `Smooth Scroll feature on **Microsoft Edge**, **Google Chrome**, **Mozilla Firefox** and **Opera**`
<div align="center">

<img src="/assets/images/readme/testing/scroll/scroll_bug_edge.gif" alt="microsoft edge scroll bug" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_crome.gif" alt="Chrome scroll feature" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_firefox.gif" alt="Firefox scroll feature" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_opera.gif" alt="Opera scroll feature" width="200" height="250"/>
</div>

## Testing functionality of site on varied browsers and devices.**

* **Navigation Bar functionality testing**
<center>

|   Action	|   Expetation	|   Chrome	|   Firefox	|   Opera	|   Edge	|   Mobile 	|   Tablets 	|
|---	|:-:	|:-:	|:-:	|:-:	|:-:	|:-:	|:-:	|
|   Clicked **Logo** on Home page	|   Refresh **Home** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Logo** on any other page on site	|   Return to **Home** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Hamburger button** on any page on site	|   Open **Menu** 	|   -	|   -	|  - 	|   -	|   PASS	|   PASS	|
|   Clicked **Home** on Home page 	|   Refresh **Home** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Home** on any other page on site	|   Return to **Home** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **About** on any page on site	|   Open **About** page	|   PASS	|   PASS	|  PASS 	|   PASS	|   PASS	|   PASS	|
|   Clicked **Planets** on any page on site	|   Open drop-down menu	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Mercury** from drop-down menu on any page on site	|   Open page with planet **Mercury**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Venus** from drop-down menu on any page on site	|   Open page with planet **Venus**	|   PASS	|   PASS	|   PASS	|  PASS 	|   PASS	|   PASS	|
|   Clicked Planet **Earth** from drop-down menu on any page on site	|   Open page with planet **Earth**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Mars** from drop-down menu on any page on site	|   Open page with planet **Mars**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Jupiter** from drop-down menu on any page on site	|   Open page with planet **Jupiter**	|   PASS	|  PASS 	|  PASS 	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Saturn** from drop-down menu on any page on site	|   Open page with planet **Saturn**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Uranus** from drop-down menu on any page on site	|   Open page with planet **Uranus**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked Planet **Neptune** from drop-down menu on any page on site	|   Open page with planet **Neptune**	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
    -if user clicked on same page where he is page will be refreshed
    -Example: If user is on planet **Earth** and choose from drop-down menu planet **Earth** again page **Earth** will be refreshed.
</center>

* Testing functionality of **Call-to-action** button, **Explore section** and **Footer** 

<center>

|   Action	|   Expetation	|   Chrome	|   Firefox	|   Opera	|   Edge	|   Mobile 	|   Tablets 	|
|---	|:-:	|:-:	|:-:	|:-:	|:-:	|:-:	|:-:	|
|   Clicked **Explore** on Home page	|   Smooth Scroll to **Explore** section	|   PASS	|   PASS	|   PASS	|   FAIL	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Mercury**	|   Open planet **Mercury** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Venus** 	|   Open planet **Venus** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Earth**	|   Open planet **Earth** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Mars**	|   Open planet **Mars** page	|   PASS	|   PASS	|  PASS 	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Jupiter**	|   Open planet **Jupiter** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Saturn**	|   Open planet **Saturn** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Uranus**	|   Open planet **Uranus** page	|   PASS	|   PASS	|   PASS	|  PASS 	|   PASS	|   PASS	|
|   Clicked **Read More** button under planet **Neptune**	|   Open planet **Neptune** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **About** in footer on any page on site	|   Open **About** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked **Contact Us** in footer on any page on site	|   Open **Contact Us** page	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
|   Clicked any **Social** network icon in footer on any page on site	|   Open desired social network platform	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|   PASS	|
    - forms on **Contact Us** page are not in function due to lack of skills and current position in the course.
    - on **About** page there are three links that lead to **Contact Us** page, **Google Fonts** and **NASA** page all three links have been tested and are operational.
</center>

* Testing functionality of **Quick navigation** buttons for small (mobile) and medium screens (tablets).

<center>

|   Action	|   Expetation	|   Mobile 	|   Tablets 	|
|---	|:-:	|:-:	|:-:	|
|   Pressed **Active** page button (Marcury / Neptune)	|   Scroll to top of page	|   PASS	|   PASS	|
|   Pressed **Planets** button on any page on site	|   Go to **Explore** section on **Home** page	|   PASS	|   PASS	|
|   Pressed any **Next / Previous** button	|   Go to **Next / Previous** page	|   PASS	|   PASS	|
</center>


## Responsiveness Test
I also tested the responsiveness site through **[Troy](http://troy.labs.daum.net/)** web page that has different devices in its database as well as different screen sizes.

<center>

|   Brand / Tipe	|   Screen Size	|   Screen Resolution	|   Css Pixel Ratio	|   Notable display Issues	|
|:-:	|:-:	|:-:	|:-:	|:-:	|
|   **Samsung**	|   	|   	|   	|   	|
|   Galaxy S8, S8+, Note 8	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   Galaxy S6, S7 	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   Note 4, Note 5	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   Galaxy S5, Note3	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|
|   Galaxy S3, Note2	|   360 x 640	|   720 x 1280	|   2	|   NONE	|
|   Galaxy Note1	|   400 x 640	|   800 x 1280	|   2	|   NONE	|
|   Galaxy S2, S1	|   320 x 533	|   480 x 800	|   1.5	|   <img src="/assets/images/readme/testing/display_issues/s2s1.png" target="_blank" rel="noopener" width="200" alt="Samsung Galaxy s2, s1 display issues">	|
|   Galaxy Tab S	|   800 x 1280	|  1600 x 2560 	|   2	|   NONE	|
|   **Apple**	|   	|   	|   	|   	|
|   iPhone 6 (s), 7, 8,	|   375 x 667	|   750 x 1334	|   2	|   NONE	|
|   iPhone 6 (s)+, 7+, 8+	|   414 x 736	|   1242 x 2208	|   3	|  NONE 	|
|   iPhone 5, SE	|   320 x 568	|   640 x 1136	|   2	|   NONE	|
|   iPhone 4	|   320 x 480	|   640 x 960	|   2	|   <img src="/assets/images/readme/testing/display_issues/iphone4.png" target="_blank" rel="noopener" width="200" alt="iphone 4 display issues">	|
|   iPhone 3GS	|   320 x 480	|   320 x 480	|   1	|   <img src="/assets/images/readme/testing/display_issues/iphone3gs.png" target="_blank" rel="noopener" width="200" alt="iphone 3GS display issues">	|
|   iPad Retina 	|   768 x 1024	|   1536 x 2048	|   2	|   NONE	|
|   **LG**	|   	|   	|   	|   	|
|   G5	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   G4	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   G3	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|
|   G2	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|
|   Optimus G Pro	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|
|   Optimus G 	|   384 x 640	|   768 x 1280	|   2	|   NONE	|
|   Optimus View	|   384 x 512	|   768 x 1024	|   2	|   NONE	|
|   G Pad 8.3	|   600 x 960	|   1200 x 1920	|   2	|   <img src="/assets/images/readme/testing/display_issues/g_pad8.3.png" target="_blank" rel="noopener" width="200" alt="G pad 8.3 display issues">	|
|   **Google**	|   	|   	|   	|   	|
|   Nexus 5	|  360 x 640 	|   1080 x 1920	|   3	|   NONE	|
|   Nexus 4	|   384 x 640	|   768 x 1280	|   2	|   NONE	|
|   Galaxy Nexus	|   360 x 640 	|   768 x 1280	|   2	|   NONE	|
|   Nexus S	|   320 x 533	|   480 x 800	|    1.5	|  <img src="/assets/images/readme/testing/display_issues/nexus_s.png" target="_blank" rel="noopener" width="200" alt="Nexus S display issues">	|
|   Nexus 10	|   800 x 1280	|  1600 x 2560	|   2	|   NONE	|
|   Nexus 7 (2013)|  600 x 960 	|   1200 x 1920	|   2	|   <img src="/assets/images/readme/testing/display_issues/nexus7.png" target="_blank" rel="noopener" width="200" alt="Nexus 7 display issues">	|
|   **Pc Screens**	|   	|   	|   	|   	|
|   800 px	|   800 x 600	|   800 x 600	|   1	|   NONE	|
|   970 px	|   970 x 600	|   970 x 600	|   1	|   NONE	|
|   1024 px	|   1024 x 768	|   1024 x 768	|   1	|   NONE	|
|   1280 px	|   1280 x 800	|   1280 x 800	|   1	|   NONE	|
|   1366 px	|   1366 x 768	|   1366 x 768	|   1	|   NONE	|
|   1440 px	|   1440 x 900	|   1440 x 900	|   1	|   NONE	|
|   1600 px	|   1600 x 900	|   1600 x 900	|   1	|   NONE	|
|   1920 px	|   1920 x 1080	|   1920 x 1080	|   1	|   NONE	|

    - I found some display issues with some smaller screens and some medium screens.
</center>


## Lighthouse

* **[Lighthouse](https://developers.google.com/web/tools/lighthouse/)** from **Chrome DevTools** is used to audit site for performance, accessibility, progressivnes and SEO.

* Results varied from trial to trial.
    - Here are some of the results.  

<div align="center">
<img src="/assets/images/readme/testing/try1.png" target="_blank" rel="noopener" width="800" alt="crome lighthouse try 1">
</div>
<div align="center">
<img src="/assets/images/readme/testing/try2.png" target="_blank" rel="noopener" width="800" alt="crome lighthouse try 2">
</div>
<div align="center">
<img src="/assets/images/readme/testing/try3.png" target="_blank" rel="noopener" width="800" alt="crome lighthouse try 3">
</div>

## Validators

* **[W3C HTML Validator](https://validator.w3.org/)** 
    * This is online HTML code validator
    - all pages from site was tested and all ressults was come back with no error.
<div align="center">
<img src="/assets/images/readme/testing/html_validator.png" target="_blank" rel="noopener" width="800" alt="html validator results">
</div>

* **[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)** 
    * This is online CSS code validator
    - CSS was tested and come back with no error and 34 warnings all warnings was **an unknown vendor extension** as i try to site be compatibility and support various browser.
<div align="center">
<img src="/assets/images/readme/testing/css_validator.png" target="_blank" rel="noopener" width="800" alt="css validator results">
</div>
<div align="center">
<img src="/assets/images/readme/testing/css_validator1.png" target="_blank" rel="noopener" width="800" alt="css validator results">
</div>

## Users Testing 

* Users who tested this site mostly came back with the same comments that were addressed to the design of the site. 
* All links were rated to work and met their expectations as confirmed by my testing which can be viewed in table above.

* Some useful feedbacks from mobile testers.
    - When you enter the planet and scroll all the way, the back button is missing.
    - On the carousel the icons for the next picture are not seen enough especially lost on some planets that are lighter in color.
    - There are three indicators and four pictures on the carousel.
    - Carousel indicators are not visible enough.
    - The Call-to-action button with two arrows does not tell me what I should do I pressed explore.
    - The images on the explore sections are not clickable I had to click on read more.
    - When I click Explore "Jump" "is too strong it would be better to scroll it slightly.

    Feedbacks was very useful and point to some things that i missed during development or just forget to change.

### Meeting the needs of the user stories (as described in the UX section of this README file)

* **Access the application from your favourite equipment, such as smartphones, tablets, laptops or PCs, without loss of content.**
    - The site has been tested through a variety of devices from mobile devices, tablets and desktops as well as laptops. The site has gone through and met the user's needs as well as ressposivnes through different screen sizes.

* **Easily navigate the site across all pages.**
    - The site met the expectations of users and the test of navigation through the page was rated as simple and easy.

* **Enjoy viewing high quality pictures of space and objects.**
    - The images on the page met the expectations of the users and were rated as pleasant and of high quality.

* **To see simple, clear design, which cleary shows what the user can do.**
    - In general, the design of the site met all the expectations of users, although there were some comments and suggestions on how to improve certain parts.

* **Want to see what different category are included in content.**
    - The content of the site was assessed as satisfactory for now and the current phase of project development.

* **Expect to know from where the content of the site came from.**
    - User expectations were met and users were able to find information about the content they were interested in.

* **Be able to contact somebody about content,prise,critics,mistakes or any other topic.**
    - User expectations have been met although contact forms are not operational for now. All testers were familiar with the fact that contact forms are not working.

* **User testing devices**
 * **Mobile devices**
    - Samsung Note 8
    - Huawei P10
    - Sony Xperia x2
    - Sony Xperia xA2
    - Samsung A30s
    - Samsung S7
 * **Tablets** 
    - Lenovo Tab2 A10-30
 * **Laptops**
    - Hp Pavilion
    - Hp Ultrabook

 </details>

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