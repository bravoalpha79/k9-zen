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

Resulting from the above requirements, and bearing in mind the three-click philosophy, the following basic structure has been established:

 - Home page, containing the School's stylised name (in place of a logo), philosophy and motto, complemented by a small picture gallery (static),
 - Training page, containing the information about types of training, location and class timetable,
 - Contact page, containing the available contact options, and
 - About page, containing the trainers' biographies and photos.

This basic structure is mirrored by a top-fixed navigation bar in the header.

The footer contains the links to the school's social media pages, as well as copyright information.

Four wireframes were created (using wireframe.cc) during the initial UI design phase:

[Home page](https://wireframe.cc/iC7yCU)   
[Training](https://wireframe.cc/dQPuJ0)  
[Contact](https://wireframe.cc/QKaQTL)  
[Dropdown Menu](https://wireframe.cc/SgXwmQ)

_Note: the final design departs from the initial wireframes in several aspects, in particular:_   
_- the training types information has been moved from Home to Training,_   
_- the trainers' bios and photos have been moved from Training to a separate new About page; the navigation bar has been updated accordingly, and_   
_- the Contact page has been completely redesigned for a simpler and cleaner user experience._

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
