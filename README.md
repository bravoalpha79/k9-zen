# K9Zen

K9Zen (a wordplay on "canine zen") is a website for a fictional dog training school of the same name. What makes the K9Zen Training School special is its use of the Positive Reinforcement Training (PRT) method.

Traditional dog training usually relies on "carrot-and-stick" methods i.e. the combined use of rewards and punishments (or "corrections") to induce desirable and prevent/correct unwanted dog behaviour. However, while appearing effective on the short term, punishment and the use of force have a negative impact on the dog-owner relationship and may also produce unwanted side effects, such as development of anxiety or reactiveness in the dog. 

On the other hand, K9Zen (appyling PRT) relies solely on positive motivation to steer the dog towards desired behavioural patterns.

*_"K9Zen Training school - because your favourite snout deserves the best."_*


 
## UX
 
The website is intended primarily for dog owners who are looking to train their dog, especially those looking to provide the dog with a different-than-mainstream training approach. It is tailored to provide them with all the essential information they might need to decide if K9Zen is the right school for their dog and for them.

A second potential user group are visitors (dog owners or not) who have heard about K9Zen and are looking for more detailed information about the school, its location, trainers etc.

A third hypothetical group would be users who are simply looking for more information on PRT. For this group, the information found on the website itself will be relatively limited as the PRT philosophy is not discussed in detail on the pages. Howewer, they can make use of the Contact functionalities on the website to obtain the information they require.

As a result, the following requirements were set for the website:

### User Requirements

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


 ### Owner requirements

5.  A user shall be provided with the information about what makes K9Zen training different than "mainstream" training.

6.  A user shall be provided with the following contact details:
    - a phone number (with established contact times), and
    - a contact form for email communication.

7. A user shall be provided with the additional contact option of visiting (auditing) any class training session.
    - A user shall be provided with an additional caveat when visiting with their dog.


### UI structure

Taking into consideration the above requirements, and bearing in mind the three-click philosophy, the following basic structure has been established:

 - Home page, containing the School's stylised name (in place of a logo), training principles and ethos, complemented by a small picture gallery (static),
 - Training page, containing the information about types of training, location and class timetable,
 - Contact page, containing the available contact options, and
 - About page, containing the trainers' biographies and photos.

This basic structure is mirrored by a top-fixed navigation bar in the header.

The footer contains the links to the school's social media pages, as well as copyright information.

Four wireframes were created (using [wireframe.cc](wireframe.cc)) during the initial UI design phase:

[Home page](https://wireframe.cc/iC7yCU)   
[Training](https://wireframe.cc/dQPuJ0)  
[Contact](https://wireframe.cc/QKaQTL)  
[Dropdown Menu](https://wireframe.cc/SgXwmQ)

_Note: the final design departs from the initial wireframes in several aspects, in particular:_   
_- the trainers' bios and photos have been moved to a separate page (About), while the existing About page has been renamed "Training" and now contains only training information,_   
_- the navigation bar has been updated accordingly (four links),_
_- the training types information has been moved from Home to Training,_   
_- the Contact page has been completely redesigned for a simpler and cleaner user experience._

## Features

 
### Existing Features

#### Navbar
- The top-fixed navbar provides the user with links to navigate to any of the four available pages; the colour coding in the navbar (darker text colour for the active page link) provides the user with a visual indication of the current page;

- The Training link opens a dropdown menu which enables the user to navigate directly to individual sections containing specific information about training;

#### Footer links
- The footer contains links to social networks (Facebook, Twitter, Instagram, YouTube).    

  _Note: since K9Zen is an entirely_ fictional _training school, the footer links will merely open the homepage of the respective social network, not an actual user page._   

#### Home page
- The button "Discover us!" below the Homepage main heading enables the user to jump directly to the gallery/ethos section without scrolling. 

- The button "What we offer" at the end of the gallery/ethos section enables the user to jump directly to the Training page without having to use the navbar.

#### Training page
- The "Read more" anchor below each training type description opens a pop-up (modal) containing details about the selected training type.

  _Note: All pop-ups can be closed by clicking anywhere outside the pop-up area, clicking on the Close icon ("x") in the top right corner of the pop-up, or clicking on the Close button (Cancel button for the Message form) in the bottom right corner of the pop-up._ 

- The map in the "Where we train" section is fully interactive (embedded Google Maps iframe). 

#### Contact page
- Each of the three button-like anchors for contact options opens a pop-up (modal) containing the necessary details for the selected contact option:
   - the Visit modal provides the user with links to the Location and Timetable sections on the Training page,
   - the Call modal provides the user with the contact hours and the phone number,
   - the Message modal provides the user with a message submission form with marked required fields, with the options to Send message or to Cancel.

      _Note: Upon clicking "Send message", the message form will perform semantic and completeness checks of the fields labelled as required. However, since no back-end processing takes place (as it is outside the scope of this project), the "Send message" button will simply close the pop-up without actually sending the entered information._

### Features Left to Implement
- Add the smooth scrolling funtion to links which lead to different sections of the same (current) page (Home and Training).
- Add interactivity to the Home gallery (the option to open full-size images).
- Enable the "Read more" anchors in Training to open the additional information as "inline" dropdown text rather than in pop-ups.   

## Technologies Used

The languages, frameworks, libraries, and other tools used during this project: 

- HTML5 for page basic structure and content;
- CSS3 for content styling;
- [Bootstrap](https://getbootstrap.com/) was used for grid layout, responsive design, Navbar and modal implementation, and some additional styling (Jumbotron, buttons);
- Fonts were obtained from [Google Fonts](https://fonts.google.com/);
- Icons were obtained from [Font Awesome](https://fontawesome.com/);
- The "perfect background image" CSS code snippet was obtained from [CSS-tricks](https://css-tricks.com/).


## Testing

Testing has a threefold objective:
- verify that the intended page structure is in place (text and fonts, images, frames);
- verify that the interactive elements are fully functional as intended (menus, links, buttons, maps, forms);
- verify that the implemented design is responsive as intended.

The test procedures and results are detailed in a separate document.


## Deployment

   #TBA


   

## Credits

### Media

- The photos used in this site were obtained from [Pexels](https://www.pexels.com/) (Gallery and About) and [Peakpx](http://www.peakpx.com/) (Contact); the remaining photos are from a personal collection.
- The Location map was obtained from [Google Maps](https://www.google.com/maps)

### Acknowledgements

- I received inspiration for this project from my dogs Dona and Fiftie (pictured on the Home and Training pages), from our trainer Ana, and from my friend Doris who first introduced me to Positive Reinforcement Training.
