# My very first Project!

It is a User Centric Frontend Development Milestone Project, where a personal resume site is built.
It is a full stack developer resume website for the users such as employers, recruiters considering to hire the IT employee. 
It can be also used by potential partners for future projects.

## UX
All users who are looking for full stack developer, can find information about experience, education, professional skills and interests of the person. They can see photo, personal and social contacts.
### User Stories:
- As a recruiter, I want to know work experience, skills and educational history of employee, so that I can find experienced employee.
- As a recruiter, I want to know more personal information about person, so that I can know more about personality.
- As a recruiter, I want to know how to contact the person, so that I can contact the person.
- As a recruiter, I want to download CV of employee, so that I can have copy of CV.

One of the part of the design process was creating a mockup of the website. Here is a link to the mockup in program "Balsamiq": https://balsamiq.cloud/s9gst4n/pdmxmfc.


## Features
The website srtucture is a single scrolling page, consisting of 4 separate page areas.
It consists of:
- Header 

  It has navigation menu that is fixed on top during scrolling. The menu consists of 5 items. 4 of them navigate to 4 different areas and 1 menu item opens my CV. 
- Main section that consists of 4 features:
  + Feature 1 - allows user to see the photo and personal contacts on top of the page.
  + Feature 2 - allows user to read short information about Darya and her interests by scrolling to the part "About Me" or choosing the item "About Me" in menu.
  + Feature 3 - allows user to read information about Darya's work experience, educational history and her skills, by choosing the items "Experience", "Skills" respectively in menu or scrolling down the page.
  + Feature 4 - allows user to see contact form by choosing item "Contact" in menu or scrolling down the page (it will be implemented in future to allow user to contact Darya by filling in contact form).
- Footer with social links. It allows user to find social networks such as Facebook, LinkedIn, Skype, Instagram (in the future user can find Darya in these social links).

## Technologies Used
For constructing this project technologies were used such as HTML and CSS.

The project uses libraries:
- Bootstrap's components (container, navbar, progress bar, collapse, scrollspy, contact form, buttons, media) and grid system for creating navigation menu, scrolling page, columns, location of content for mobile and desktop versions both - https://getbootstrap.com/;
- Awesome for using icons - https://fontawesome.com/;
- Hover.css for hovering effects- https://cdnjs.com/;
- JQuery for bootsrtap - https://code.jquery.com/;

## Testing
It has been conducted enough testing the website. It was tested from desktop and mobile devices such as Honor 8, iPhone 6, iPhone 11 Pro.

Testing was mainly focused on:
- How navigation menu works;
- How content and colors look like in every section in different screen sizes;
- How scrolling page works;
- How CV opens and is getting downloaded;
- How social links work;
Testing showed that the website works well for both desktops and mobile devices.
When the website is opened on mobile devices, menu is changed to a toggle-button and the photo disappears in the area "About Me".

In addition a strange bug was discovered during testing the website in desktop and mobile versions. 
There is a little space (several pixels) between the footer and the right side of screen. The same bug is found with personal contacts area (class "my-info").
For "my-info" and footer container-fluid (bootstrap library) is used for a full width container, that should cover the entire width of the screen.
This bug can not be reproduced every time. Thats why it's hard to identify the problem.
Moreover contact form doesn't work yet. 
Social links open just main pages of websites. They are planned to be implemented in the future. 
 
## Deployment
The website was deployed to a hosting platform GitHub Pages. GitHub Pages website is currently being built from the master branch.
The link is https://dynjashik.github.io/My-resume-website/.

## Credits
The text for all content and photo was obtained from Darya's words, from CV and from personal archive.

 Inspiration for this project was received from:
- www.toptal.com - website's background;
- visme.co -  website-color-schemes;
- www.cssmatic.com -  shadow effects;
- https://stackoverflow.com/ - finding answers for questions;