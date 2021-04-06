# K9Zen

K9Zen (shorthand for "canine zen") is a website for a fictional dog training school of the same name. What makes the K9Zen Dog Training school special is its use of the Positive Reinforcement Training (PRT) method.

Traditional dog training usually relies on "carrot-and-stick" methods i.e. the combined use of rewards and punishments (or "corrections") to induce desirable and prevent/correct unwanted dog behaviour. However, while appearing effective on the short term, punishment and the use of force have a negative impact on the dog-owner relationship and may also produce unwanted side effects, such as development of anxiety or reactiveness in the dog. 

On the other hand, K9Zen (applying PRT) relies solely on positive motivation to steer the dog towards desired behavioural patterns.

**_"K9Zen Dog Training - because your favourite snout deserves the best."_**


 
## UX
 
### User stories

The website is intended primarily for dog owners who are looking to train their dog, especially those looking to provide the dog with a different-than-mainstream training approach. 

A second potential user group are visitors (dog owners or not) who have heard about K9Zen and are looking for more information about the school, its location, trainers etc.

A third hypothetical group would be users who are simply looking for more information on PRT. 

The following relevant user stories have been identified:

- As a user, I want to find out about the school's training methods in order to decide whether they are right for my dog.
- As a user, I want to find out about the training options/courses provided in order to choose the most appropriate one for me and my dog.
- As a user, I want to find out about the price of training options in order to compare with other schools and to decide whether I can afford it.
- As a user, I want to find out about the school's location in order to decide whether it is convenient for my routine.
- As a user, I want to find out about the training schedule in order to decide whether it can fit into my schedule. 
- As a user, I want to find out about the trainers and their references.
- As a user, I want to be able to contact the school via telephone or email, in order to obtain additional information or to arrange start of training.  
- As a user, I want to find out more about PRT.


- As owner, I want to attract dog owners to choose my school and my services to train their dog.
- As owner, I want to present PRT as a more positive training method compared to mainstream training.
- As owner, I want to let the user know that they are welcome to contact me on any school- or PRT-related topic.
- As owner, I want to present the user with the option to visit/audit any training class in person.
- As owner, I want to request the user to notify me if advance if visiting/auditing with their dog.
- As owner, I want to provide the user with a message form rather than my email address.

### Requirements

As a result of the above considerations, the following requirements were set for the website:

1. A user shall be able to obtain relevant and up-to-date information about the school, namely:
    - training method and philosophy,
    - school location,
    - contact information: contact means and contact times (where applicable), and
    - social media links.

2. A user shall be able to obtain information about the trainers and their references.
3. A user shall be able to obtain information about the different types of training available, specifically:
    - description of each training type and its purpose,
    - duration of training type,
    - price of training type,
    - training location(s),
    - training time(s), if fixed, and
    - training prerequisite(s), if any.

4. A user shall be able to contact the school personnel in order to obtain additional information on any school-relevant topic.

5.  A user shall be provided with the information about what makes K9Zen training different than "mainstream" training.

6.  A user shall be provided with the following contact details:
    - a phone number (with established contact times), and
    - a contact form for email communication.

7. A user shall be provided with the additional contact option of visiting (auditing) any class training session.
    - A user shall be provided with an additional caveat when visiting with their dog.


### UI structure

Taking into consideration the above requirements, and bearing in mind the three-click philosophy, the following basic structure has been established:

 - Home page, containing the School's stylised name (instead of a logo), training principles and ethos, complemented by a small picture gallery (static),
 - Training page, containing the information about types of training, location and class timetable,
 - Contact page, containing the available contact options, and
 - About page, containing the trainers' biographies and photos.

This basic structure is mirrored by a top-fixed navigation bar in the header.

The footer contains the links to the School's social media pages, as well as copyright information.

Four wireframes were created (using [wireframe.cc](https://wireframe.cc/)) during the initial UI design phase:

[Home page](https://wireframe.cc/iC7yCU)   
[Training](https://wireframe.cc/dQPuJ0)  
[Contact](https://wireframe.cc/QKaQTL)  
[Dropdown Menu](https://wireframe.cc/SgXwmQ)

_Note: the final design departs from the initial wireframes in several aspects, in particular:_   
_- the trainers' bios and photos have been moved to a separate page (About), while the existing About page has been renamed "Training" and now contains only training information;_   
_- the navigation bar and its dropdown menu have been updated accordingly;_   
_- the training types information has been moved from Home to Training;_  
_- the Contact page has been completely redesigned for a simpler and cleaner user experience._

## Features

 
### Existing Features

#### Navigation bar
- The top-fixed navigation bar provides the user with links to navigate to any of the four available pages; the colour coding in the navbar (darker text colour for the active page link) provides the user with a visual indication of the current page.

- The Training link opens a dropdown menu which enables the user to navigate directly to individual sections containing specific information about training.

#### Footer links
- The footer contains links to social networks (Facebook, Twitter, Instagram and YouTube).    

  _Note: since K9Zen is an entirely_ fictional _training school, the footer links will merely open the homepage of the respective social network, not an actual user page._   

#### Home page
- The button "Discover us!" below the Home page main heading enables the user to jump directly to the gallery/ethos section without scrolling. 

- The button "Let's train!" at the end of the gallery/ethos section enables the user to jump directly to the Training page without having to use the navbar.

#### Training page
- The "Read more" anchor below each training type description opens a pop-up (modal) containing details about the selected training type.

  _Note: All pop-ups can be closed by clicking anywhere outside the pop-up area, by clicking on the Close icon ("x") in the top right corner of the pop-up, or by clicking on the Close button (Cancel button for the Message form) in the bottom right corner of the pop-up._ 

- The map in the "Where we train" section is fully interactive (embedded Google Maps iframe). 

#### Contact page
- Each of the three button-like anchors for contact options opens a pop-up (modal) containing the necessary details for the selected contact option:
   - the Visit modal provides the user with links to the Location and Timetable sections on the Training page,
   - the Call modal provides the user with the contact hours and the phone number,
   - the Message modal provides the user with a message submission form with marked required fields, with the options to Send message or to Cancel.

      _Note: Upon clicking "Send message", the message form will perform semantic and completeness checks of the fields labelled as required. However, since no back-end processing takes place (as it is outside the scope of this project), the "Send message" button will simply close the pop-up without actually sending the entered information._

### Features Left to Implement
- On the About page, add a separate section about PRT history, philosophy and methods in detail.
- Add the smooth scrolling function to links which lead to different sections of the same (current) page (Home and Training).
- Add interactivity to the Home gallery (the option to open full-size images).
- Enable the "Read more" anchors in Training to open the additional information as "inline" dropdown text rather than pop-ups.
- Make the site bilingual (add identical content in Croatian and a link/button to switch between languages).   

## Technologies Used

The languages, frameworks, libraries, and other tools used during this project: 

- HTML5 for page basic structure and content;
- CSS3 for content styling;
- [Bootstrap](https://getbootstrap.com/) was used for grid layout, responsive design, navigation bar and modal implementation, and some additional styling (Jumbotron, buttons);
- Fonts were obtained from [Google Fonts](https://fonts.google.com/);
- Icons were obtained from [Font Awesome](https://fontawesome.com/);
- [W3C Markup Validation Service](https://validator.w3.org/) was used to validate HTML and CSS code;
- [W3schools.com Color Converter](https://www.w3schools.com/colors/colors_converter.asp) was used to convert colours between default, HEX and RGB for CSS coding purposes;
- [Autoprefixer CSS online](https://autoprefixer.github.io/) was used for correct vendor prefixing of CSS styles where required;
- [Compress JPEG](https://compressjpeg.com/) for image file size reduction;
- Google Chrome Developer Tools were used for debugging and as a styling aid;
- [Gitpod](https://www.gitpod.io/) was used as the IDE for development and Git version control;
- [GitHub](https://github.com/) was used for source code storage and site deployment (GitHub Pages).



## Testing

Testing has a fourfold objective:
- verify that all user/owner requirements have been met; 
- verify that the intended page structure is in place (text and fonts, images, frames);
- verify that the interactive elements are fully functional as intended (menus, links, buttons, maps, forms);
- verify that the implemented design is responsive as intended.

The test procedures and results are detailed in a [separate document](test-procedure.md).

Summary:

1. All planned tests have been performed successfully.
2. All User Requirements have been fulfilled.
3. Three issues have been identified:

    **_Issue #1_**: On all pages, the background image jerks/twitches when the page is scrolled in MS Internet Explorer 11.  
    **_Issue #2_**: On About page, the trainer photos are not displayed and the structural integrity of the page body is corrupted in MS Internet Explorer 11.  
    **_Issue #3_**: The modal just appears (pops up) instead of fading in as expected.

4. Issue #3 has been analysed and corrected. The implemented correction has been verified successfully. Issue #3 is considered resolved.
5. Issue #1 and Issue #2 are documented. No fix will be attempted at this time because
    - known workarounds bear the risk of creating unwanted side issues, and  
    - the issues are absent from _all_ other tested browsers, including MS Edge.

6. One observation has been raised:

    **Observation #1**: On small and extra small screens (screen width below 768px) the background images on all pages become too zoomed in (i.e. the screen range is too small) to be recognisable.

    The observation is not considered to be an issue. A potential future improvement/solution could be either a choice of higher resolution images, or of abstract images, for page backgrounds.

7. The webpage is **considered ready for official deployment**.  


## Deployment

   The deployment version of the source code is stored on [GitHub](https://github.com/), in the master branch of [bravoalpha79/k9-zen](https://github.com/bravoalpha79/k9-zen).

   From the master branch, the site has been published using [GitHub Pages](https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site). The deployed site code is identical to the code stored on the master branch on GitHub.

   **The live version of the site is located at:**   
   **https://bravoalpha79.github.io/k9-zen/index.html** 



## Credits

### Code
- The "perfect background image" CSS code snippet (used for styling of background images on all pages) was obtained from [CSS-tricks](https://css-tricks.com/).

### Media

- The photos used in this site were obtained from [Pexels](https://www.pexels.com/) (for the gallery and About) and [Peakpx](http://www.peakpx.com/) (for Contact); the remaining photos are from a personal collection.
- The Location map was obtained from [Google Maps](https://www.google.com/maps).

### Acknowledgements

- I received inspiration for this project from my dogs Dona and Fiftie (pictured on the Home and Training page backgrounds), from our trainer Ana, and from my friend Doris who first introduced me to Positive Reinforcement Training.
