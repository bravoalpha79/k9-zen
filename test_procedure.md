# "K9Zen" Pre-Deployment Testing Write-Up

This document details the test procedure and results of the official deployment of the _K9Zen Dog Training_ web page.

## Introduction

Based upon the fourfold objective of the testing process, the test steps have been divided into four groups:

1. User Requirement tests, labelled **UR-[test number]**;
2. Structural Integrity tests, labelled **SI-[test number]**;
3. Interactive Components tests, labelled **IC-[test number]**;
4. Responsive Design tests, labelled **RD-[test number]**.

## Test Procedure

### User Requirements

**UR-1a**:  
On the **_Home_** page, check that information on the School's training method and philosophy is available.

**UR-1b**:  
On the **_Training_** page, check that information on the School's location is available.

**UR-1c**:  
On the **_Contact_** page: 
1. check that contact means/methods are listed;
2. for each contact method, check that the corresponding contact information is available;
3. where applicable, check that contact time(s) information is listed.

**UR-1d**:  
In the footer (of any page), check that links to the School's social media pages are available. 

**UR-2**:   
On the **_About_** page: 
1. check that information about the School's trainers is available;
2. check that the information contains details about the trainers' references.

**UR-3a**:  
On the **_Training_** page, check that available training types are listed.

**UR-3b**:  
For each of the four training types - _Obedience_, _Tricks_, _Individual_ and _Consultation_ - check that:   
1. training description and purpose are listed;
2. training duration is listed;
3. training price is listed;
4. training location is listed;
5. training time(s), where applicable, is listed;
6. training prerequisites, if applicable, are listed.

**UR-4**:  
Check that the website provides the user with the option to contact the school personnel in order to obtain additional information on any school-relevant topic.

**UR-5**:   
On the **_Home_** page, check that information is provided about what makes the School's training different than mainstream training.

**UR-6a**:  
On the **_Contact_** page, check that the School's phone number and available contact times are provided.

**UR-6b**:  
Check that a contact form for email/message submission is provided to the user.

_Note: the full functionality/interactivity of the Message Submission Form is checked in Interactive Components tests._

**UR-7a**:   
Check that the option to visit/audit any training class is presented to the user.

**UR-7b**:  
On the **_Training_** page, check that the user is informed about the requirement to contact the School in advance if visiting/auditing a class with her/his dog.



### Structural Integrity

**SI-1**:   
Check that fonts are rendered properly:
- on the **_Home_** page, the School title font is displayed correctly;
- on all pages, the section headings' sizes are homogenous;
- on all pages, body text size is homogenous.

**SI-2**:  
Check that the Header/Navigation section is rendered properly on all pages:
- the Navbar "brand" ("_K9Zen_") is displayed with the correct font;
- the Navbar items _Home_, _Training_, _Contact_ and _About_ are displayed correctly.

_Note: the full functionality of the Navbar is tested in Interactive Components tests._ 

**SI-3**:  
Check that the Footer section is rendered properly on all pages:
- the social media link icons - Facebook, Twitter, Instagram, YouTube - are displayed properly;
- copyright information is displayed.

_Note: the full functionality of the social media links is tested in Interactive Components tests._

**SI-4**:  
Check that section frames, margins/paddings and borders are homogenous on all pages.

**SI-5**:  
Check that the display of images, icons and embedded objects on all pages is complete and correct within the overall page structure.  

**SI-6**:  
Check that the textual parts contain no typos.

**SI-7**:  
Using a different web browser, repeat tests SI-1 through SI-5.


### Interactive Components

#### Navigation

**IC-1**:  
From **_Home_** page:
1. In the Navbar, click on the Navbar "brand" (_"K9Zen"_). Check that the Home page opens.
2. In the Navbar, click on the _Home_ field. Check that the Home page opens.
3. In the Navbar, click on the _Training_ field. Check that a dropdown menu opens, containing four options:
       
    3a. In the dropdown menu, click on _Why K9Zen?_. Check that the browser navigates to the corresponding section on the Home page.  
    3b. In the dropdown menu, click on _What we offer_. Check that the browser navigates to the corresponding section on the Training page.  
    3c. In the dropdown menu, click on _Where we train_. Check that the browser navigates to the corresponding section on the Training page.  
    3d. In the dropdown menu, click on _Class timetable_. Check that the browser navigates to the corresponding section on the Training page.
4. In the Navbar, click on the _Contact_ field. Check that the Contact page opens.
5. In the Navbar, click on the _About_ field. Check that the About page opens.

**IC-1a**:  
From **_Training_** page, repeat actions 1 through 5 of **IC-1**.

**IC-1b**:  
From **_Contact_** page, repeat actions 1 through 5 of **IC-1**.

**IC-1c**:  
From **_About__** page, repeat actions 1 through 5 of **IC-1**.



#### Footer links

**IC-2**:  
From **_Home_** page:
1. In the footer, click on the Facebook icon. Check that the Facebook homepage opens in a new browser window.
2. In the footer, click on the Twitter icon. Check that the Twitter homepage opens in a new browser window.
3. In the footer, click on the Instagram icon. Check that the Instagram homepage opens in a new browser window.
4. In the footer, click on the YouTube icon. Check that the YouTube homepage opens in a new browser window.

**IC-2a**:   
From **_Training_** page, repeat actions 1 through 4 of **IC-2**.

**IC-2b**:  
From **_Contact_** page, repeat actions 1 through 4 of **IC-2**.

**IC-2c**:  
From **_About__** page, repeat actions 1 through 4 of **IC-2**.



#### Buttons and modals

**IC-3**:  
On **_Home_** page:
1. Click on the _Discover us!_ button. Check that the browser navigates to the section titled _"Why K9Zen?"_.
2. Click on the _Let's train!_ button. Check that Training page opens.

**IC-4**:  
On **_Contact_** page:
1. Click on the _Visit_ button. Check that a modal opens, containing information about visiting.  
Check that the modal can be closed by clicking on the Close button in the bottom right corner of the modal.
2. Click on the _Call_ button. Check that a modal opens, containing call times information and a phone number.  
Check that the modal can be closed by clicking on the "x" icon in the top right corner of the modal.
3. Click on the _Message_ button. Check that a modal opens, containing a message submission form.  
Check that the modal can be closed by clicking outside the modal area.

#### Anchors

**IC-5**:  
On **_Training_** page:
1. At the bottom of the "Obedience Class" column/section, click on _Read more_. Check that a modal opens with details on Obedience training.  
2. At the bottom of the "Tricks Class" column/section, click on _Read more_. Check that a modal opens with details on Tricks training. 
3. At the bottom of the "Individual Training" column/section, click on _Read more_. Check that a modal opens with details on Individual training.
4. At the bottom of the "Consultation" column/section, click on _Read more_. Check that a modal opens with details on Consultation.

**IC-6**:  
On **_Training_** page:
1. In the "What we offer" section, click on the _location_ anchor. Check that the browser navigates to the appropriate section on the page.
2. In the "What we offer" section, click on the _timetable_ anchor. Check that the browser navigates to the appropriate section on the page.
3. In the "What we offer" section, click on the _contact us_ anchor. Check that Contact page opens.
3. In the "Class Timetable" section, click on the _call us_ anchor. Check that Contact page opens.

**IC-7**:  
On **_Contact_** page, click on the _Visit_ button to open the "Visit us" modal. In the modal:
1. Click on the _training location_ anchor. Check that the browser navigates to the appropriate section on Training page.
2. Click on the _class timetable_ anchor. Check that the browser navigates to the appropriate section on Training page.

**IC-8**:  
At the bottom of **_About_** page, click on the _contact us_ anchor. Check that Contact page opens.


#### Map

**IC-9**:  
On **_Training_** page, check that the embedded map is fully interactive:
1. Map zoom in/out is available.
2. Map panning is available.
3. Toggle satellite/map view is available.
4. Clicking on "Directions" or "View larger map" opens Google Maps in a new browser window.

#### Form

**IC-10**:  
On **_Contact_** page, click on the _Message_ button. Check that a modal opens, containing the "Message us" submission form.

**IC-10a**:  
Check that the message form contains the following items:
- a Name field (labelled as required),
- an Email field (labelled as required),
- a Phone field (with placeholder "optional"),
- a Message text area/field (labelled as required), 
- a Cancel button, and
- a Send message button.

**IC-10b**:  
With Name field empty, click _Send message_. Check that a valid warning is raised about the Name field and the form remains open.

**IC-10c**:  
With Name field filled, input an incomplete email address into the Email field:
- no address,
- an address without "@", and
- an address without any characters following "@"

and click _Send message_. Check that for each of the above scenarios, a valid warning is raised about the Email field and the form remains open.

**IC-10d**:  
With Name and Email fields correctly filled and Message field empty, try to click _Send message_. Check that:
1. no warning is raised about the Phone field (as the field is optional), and
2. a valid warning is raised about the Message field and the form remains open. 

**IC-10e**:  
With all required fields correctly filled, click on _Send message_. Check that no warning is raised and the modal closes.

_Note: as no back-end processing takes place (this is outside the scope of the project), the only effect of clicking_ Send message _will be the closure of the modal. No data is transmitted and no message is sent._

**IC-10f**:  
Click on the _Message_ button to reopen the "Message us" modal.   
In the bottom right corner of the modal, click on the _Cancel_ button. Check that the modal closes.



### Responsive Design

**RD-1**:  
Using Google Chrome Development Tools in Responsive view, check the rendering and layout of each of the four pages in the following width ranges:
1. below 576px;
2. at and above 576px but below 768px;
3. at and above 768px but below 992px;
4. at and above 992px but below 1200px;
5. at and above 1200px.

**RD-2**:  
Using Google Chrome Development Tools in Emulated Device view, check the rendering and layout of each of the four pages on the following emulated devices:
1. iPad Pro (large screen),
2. Kindle Fire HDX (medium screen),
3. Galaxy S5 (extra small screen).

**RD-3**:  
Check the rendering and layout of each of the four pages on a physical device of your choice.

----------



## Test Results

Google Chrome was used as the primary test browser.

### Code  
All HTML and CSS code was validated using the [W3C Markup Validation Service](https://validator.w3.org/). No error was found.

### User requirements


### Structural integrity  
All structural integrity tests (SI-1 through SI-7) were performed successfully. 

1. Tests SI-1 through SI-6 were performed using Google Chrome. No issue was found.
2. Test SI-7, which requires the use of an alternate browser, was performed using the following browsers:
    - Mozilla Firefox,
    - Safari,
    - MS Edge, and
    - MS Internet Explorer 11.

   

