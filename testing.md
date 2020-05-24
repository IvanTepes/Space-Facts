# Sp@ce F@cts - Testing details

[Main README.md file](README.md)

## Table of Contents

- [Browser used in testing](#browser-used-in-testing)
    * [Microsoft Edge Bug](#microsoft-edge-bug)
- [Testing functionality of site on varied browsers and devices.](#testing-functionality-of-site-on-varied-browsers-and-devices)
- [Responsiveness Test](#responsiveness-test)
- [Lighthouse](#lighthouse)
- [Validators](#validators)
- [Users Testing](#users-testing)
  * [Meeting the needs of the user stories](#meeting-the-needs-of-the-user-stories--as-described-in-the-ux-section-of-this-readme-file-)

During the development of this project, I had the experience of facing some problems. Browser used for testing application during development was **[Google Chrome](https://www.google.com/chrome/)** and **[Dev Tools](https://developers.google.com/web/tools/chrome-devtools)** from same browser. For audit the site i have used **[Lighthouse](https://developers.google.com/web/tools/lighthouse/)** from **Chrome DevTools**. Exhaustively testing the functionality of each part of the application and managed to solve most of the problems that i have came across before writing this document. However how process of testing is being expanding on different browsers and different devices some problems are found and noticed. Some of them I have solved and corrected, some remained uncorrected until the end of the test, and as my skills and knowledge develop, hopefully i will be able to eliminate them.

I received help from some family members and friends to do the tests on application.

Testing is conduct by sharing application to them and have conversation about application.

This was the primary method of testing the application. People were asked to visit the website on a variety of devices. This feedback was very uselful to determine any bugs that may have been present. I also tested the app manually myself on a varietly of browsers and tools. 

## Browser used in testing 

* **[Google Chrome 81.0.4044.138](https://www.google.com/chrome/)**
    - Used for testing site through all developing process and DevTools for responsiveness and scaling issues on different screen sizes.
* **[Mozilla Firefox 76.0.1](https://www.mozilla.org/en-US/exp/)**
    - Used for testing site and responsiveness and scaling.
* **[Opera Web Browser 68.0.3618.104](https://www.opera.com)**
    - Used for testing site and responsiveness and scaling.
* **[Microsoft Edge 44.18362.449.0](https://www.windowscentral.com/microsoft-edge)**
    - Used for testing site and responsiveness and scaling.


* Testing was conducted on the browsers above on the first three browsers such as **Google Crome**, **Mozilla Firefox** and **Opera Web Browser** no problems or bugs were noticed. 
### **Microsoft Edge bug** 
- On Microsoft Edge we encounter a bug at the beginning of the site and that is the only bug noticed on that browser.

    - ~~Bug on **Microsoft Edge** web browser `before update`. ( bug was attempted to be corrected through the **Autoprefixer** but bug is still remained visible.)~~ Picture 1
    - `After the update, the first bug was removed but a new one appeared on navigation bar. Picture 2`
    - `**Bug Fix** Bug was fixed by overrides Bootstrap default !important display attribute from ** display: -ms-flexbox!important; ** to ** display: -ms-inline-grid !important; ** in css.style calling element by ID and giving element important rule. Picture 3`
    - Snip code from css.style
    ```
    #navbarNavDropdown {
    display: -ms-inline-grid !important;
    }
    ```

<div align="center">
<img src="/assets/images/readme/testing/bug/edge_bug.png" target="_blank" rel="noopener" width="200" alt="microsoft edge bug">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/bug/bug_edge_new.png" target="_blank" rel="noopener" width="200" alt="microsoft edge bug">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/bug/edge_bug_fix_display.png" target="_blank" rel="noopener" width="200" alt="microsoft edge bug fix">
</div>

- `Also ** Smooth Scroll ** feature does not work on Microsoft Edge.`

* `Smooth Scroll feature on **Microsoft Edge**, **Google Chrome**, **Mozilla Firefox** and **Opera**`
<div align="center">

<img src="/assets/images/readme/testing/scroll/scroll_bug_edge.gif" alt="microsoft edge scroll bug" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_crome.gif" alt="Chrome scroll feature" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_firefox.gif" alt="Firefox scroll feature" width="200" height="250"/>&nbsp;&nbsp;&nbsp;<img src="/assets/images/readme/testing/scroll/scroll_opera.gif" alt="Opera scroll feature" width="200" height="250"/>
</div>

## Testing functionality of the site on varied browsers and devices.

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
    - forms on **Contact Us** page are not in function due to the lack of skills and current position in the course.
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

|   Brand / Tipe	|   Screen Size	|   Screen Resolution	|   Css Pixel Ratio	|   Notable display Issues	|   `Notable display Issues after update`	|
|:-:	|:-:	|:-:	|:-:	|:-:	|:-:	|
|   **Samsung**	|   	|   	|   	|   	|
|   Galaxy S8, S8+, Note 8	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|	
|   Galaxy S6, S7 	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|
|   Note 4, Note 5	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|
|   Galaxy S5, Note3	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|   NONE	|
|   Galaxy S3, Note2	|   360 x 640	|   720 x 1280	|   2	|   NONE	|   NONE	|
|   Galaxy Note1	|   400 x 640	|   800 x 1280	|   2	|   NONE	|   NONE	|
|   Galaxy S2, S1	|   320 x 533	|   480 x 800	|   1.5	|   <img src="/assets/images/readme/testing/display_issues/s2s1.png" target="_blank" rel="noopener" width="150" alt="Samsung Galaxy s2, s1 display issues">	|   NONE	|
|   Galaxy Tab S	|   800 x 1280	|  1600 x 2560 	|   2	|   NONE	|   NONE	|
|   **Apple**	|   	|   	|   	|   	|
|   iPhone 6 (s), 7, 8,	|   375 x 667	|   750 x 1334	|   2	|   NONE	|   NONE	|
|   iPhone 6 (s)+, 7+, 8+	|   414 x 736	|   1242 x 2208	|   3	|  NONE 	|   NONE	|
|   iPhone 5, SE	|   320 x 568	|   640 x 1136	|   2	|   NONE	|   NONE	|
|   iPhone 4	|   320 x 480	|   640 x 960	|   2	|   <img src="/assets/images/readme/testing/display_issues/iphone4.png" target="_blank" rel="noopener" width="150" alt="iphone 4 display issues">	|   <img src="/assets/images/readme/testing/display_issues/iphone4_display_issues.jpg" target="_blank" rel="noopener" width="150" alt="iphone 4 display issues">	|
|   iPhone 3GS	|   320 x 480	|   320 x 480	|   1	|   <img src="/assets/images/readme/testing/display_issues/iphone3gs.png" target="_blank" rel="noopener" width="150" alt="iphone 3GS display issues">	|   <img src="/assets/images/readme/testing/display_issues/iphone_3gs_display_issues.jpg" target="_blank" rel="noopener" width="150" alt="iphone 4 display issues">	|
|   iPad Retina 	|   768 x 1024	|   1536 x 2048	|   2	|   NONE	|   NONE	|
|   **LG**	|   	|   	|   	|   	|
|   G5	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|
|   G4	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|
|   G3	|   360 x 640	|   1440 x 2560	|   4	|   NONE	|   NONE	|
|   G2	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|   NONE	|
|   Optimus G Pro	|   360 x 640	|   1080 x 1920	|   3	|   NONE	|   NONE	|
|   Optimus G 	|   384 x 640	|   768 x 1280	|   2	|   NONE	|   NONE	|
|   Optimus View	|   384 x 512	|   768 x 1024	|   2	|   NONE	|   NONE	|
|   G Pad 8.3	|   600 x 960	|   1200 x 1920	|   2	|   <img src="/assets/images/readme/testing/display_issues/g_pad8.3.png" target="_blank" rel="noopener" width="150" alt="G pad 8.3 display issues">	|   NONE	|
|   **Google**	|   	|   	|   	|   	|
|   Nexus 5	|  360 x 640 	|   1080 x 1920	|   3	|   NONE	|   NONE	|
|   Nexus 4	|   384 x 640	|   768 x 1280	|   2	|   NONE	|   NONE	|
|   Galaxy Nexus	|   360 x 640 	|   768 x 1280	|   2	|   NONE	|   NONE	|
|   Nexus S	|   320 x 533	|   480 x 800	|    1.5	|  <img src="/assets/images/readme/testing/display_issues/nexus_s.png" target="_blank" rel="noopener" width="150" alt="Nexus S display issues">	|   NONE	|
|   Nexus 10	|   800 x 1280	|  1600 x 2560	|   2	|   NONE	|   NONE	|
|   Nexus 7 (2013)|  600 x 960 	|   1200 x 1920	|   2	|   <img src="/assets/images/readme/testing/display_issues/nexus7.png" target="_blank" rel="noopener" width="150" alt="Nexus 7 display issues">	|   NONE	|
|   **Pc Screens**	|   	|   	|   	|   	|
|   800 px	|   800 x 600	|   800 x 600	|   1	|   NONE	|   NONE	|
|   970 px	|   970 x 600	|   970 x 600	|   1	|   NONE	|   NONE	|
|   1024 px	|   1024 x 768	|   1024 x 768	|   1	|   NONE	|   NONE	|
|   1280 px	|   1280 x 800	|   1280 x 800	|   1	|   NONE	|   NONE	|
|   1366 px	|   1366 x 768	|   1366 x 768	|   1	|   NONE	|   NONE	|
|   1440 px	|   1440 x 900	|   1440 x 900	|   1	|   NONE	|   NONE	|
|   1600 px	|   1600 x 900	|   1600 x 900	|   1	|   NONE	|   NONE	|
|   1920 px	|   1920 x 1080	|   1920 x 1080	|   1	|   NONE	|   NONE	|

    - I found some display issues with some smaller screens and some medium screens.
    - After update all notible display issues for medium screens where resolved when on small mobile screens still some where visible.
    
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
    - all the pages from the site where tested and all the results came back with no error.
<div align="center">
<img src="/assets/images/readme/testing/html_validator.png" target="_blank" rel="noopener" width="800" alt="html validator results">
</div>

* **[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)** 
    * This is online CSS code validator
    - CSS was tested and came back with no error and 34 warnings. All the warnings where **an unknown vendor extension**. The reason i recived the warnings was because i have tryed to achive  that the site supports various browsers.
<div align="center">
<img src="/assets/images/readme/testing/css_validator.png" target="_blank" rel="noopener" width="800" alt="css validator results">
</div>
<div align="center">
<img src="/assets/images/readme/testing/css_validator1.png" target="_blank" rel="noopener" width="800" alt="css validator results">
</div>

## Users Testing 

* Users who tested this site mostly came back with the same comments that were addressed to the design of the site. 
* All links were rated to work and met their expectations as confirmed by my testing which can be viewed in tables above.

* Some useful feedbacks from mobile testers.
    - When you enter the planet and scroll all the way, the back button is missing.
    - On the carousel the icons for the next picture are not seen enough especially lost on some planets that are lighter in color.
    - There are three indicators and four pictures on the carousel.
    - Carousel indicators are not visible enough.
    - The Call-to-action button with two arrows does not tell me what should do so I pressed explore.
    - The images on the explore sections are not clickable. I had to click on read more.
    - When I click Explore "Jump" "is too strong. It would be better to scroll it slightly.

    Feedbacks was very useful and it pointed to some things that i missed during development or just forget to change.

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
