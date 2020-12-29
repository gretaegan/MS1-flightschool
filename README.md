# Flight School

This website is my first Milestone Project on the Code Institute Full Stack Web Developer Course.

My project is a website for a flight school that trains people to become commercial airline pilots. 
I chose this idea based on my own experience of becoming a commercial
pilot and my knowledge of aviation. 
 In 2019 there was a huge worldwide demand for commercial pilots and while the pandemic has paused this, it is expected that when aviation recovers the demand will be even
 greater. Pilots will need to be trained and flight schools will become valuable once again.
 This flight school provides the Integrated style of training, which is favored by most airlines around the world. 

The link to the live site can be found here https://gretaegan.github.io/MS1-flightschool/

(will insert picture of mock ups here)

# UX
## User Stories 

*Who is this website targeting?*
This website is for people who want to train to become a commercial pilot. 
They might have no previous flying experience or they might already have some level of training done. Either way, the site must provide information on what
Integrated flight training is and how it is delivered.

*As a user of this website, I want*
1. To understand the brand at a first glance.
1. To understand what the product being sold is.
1. To see information about the training provided clearly and without having to go searching for it.
1. To understand the entry requirements and any barriers that may prevent me from applying to the course.
1. To be able to contact the school easily.

# Design

### Images Used
All images used in this project are my own pictures that I took throughout my time in Flight school. The pictures were specifically chosen as I wanted 
to show a range of different aircraft that the school would offer. They are a Boeing 737-800, a Salisbury Firefly and a Cessna 172RG.
The hero image was chosen because aspiring pilots will see the image of cadets flying a jet and it will provide inspiration that it could be them if they go
through the training.
![Salisbury Firefly](/assets/firefly.jpeg)
![Cessna172RG](assets/fii.jpeg)
![Boeing737](assets/hero.jpeg)

### Typography
* 'Poppins' is the font used for this website, with sans-serif as the fall back. It is a clean and simple font that gives a sense of professionalism and
readability.
* All headings are in Uppercase with letter spacing to make them stand out and grab attention. 
I used a custom horizontal rule under the headings to add attention
and draw the eye.

### Layout
The website is a simple, single scrolling page design that contains links to the different sections of the page.
My intention was to keep the website as simple and clear as possible. 
I used to Bootstrap grid system to provide the layout of the website and to ensure responsiveness.
The navigation bar at the top of the page is fixed and, on smaller screen sizes, becomes a data toggler button to prevent cluttering the screen. 

### Colors 
I kept to a cool palatte of blues: a dark navy (#071337) and a teal(00cccc).
My hero-text was kept to a simple off-white color(#fafafa) so that it was still readable and grabbed attention, without distracting from the hero image of the 
two pilots flying the Boeing737-800. 


### Overall Feel
The most important thing was that the website conveyed professionalism as it is what you would want and expect from a company that trains pilots.
I am satisfied that this has been achieved with the color scheme, layout of the website and images I have chosen to use.

# Wireframes

will add these later.

# Features
*Flight School is a mobile first design that is fully responsive on a variety of different screen sizes.
*The Navigation bar list items become hidden in a data-toggler on smaller screen sizes.
*The social media icons link to their respective websites.
*The logo in the Navbar is a link back to the beginning of the page.

## Future Features
Currently, the form system does not function. However once I have learned Javascript this can be made fully functional.

## Technologies Used

* HTML5
* CSS3
* Javascript

## Frameworks Used

* Bootstrap was used to provide the website layout, features including the Navbar and data toggler, and to make the site responsive.
* Font Awesome was used to provide the icons in the training section and the testamonial section.
* Google Fonts was used to provide the font used across the entire webpage.
* Figma was used to provide the wireframes for the project.
* GitHub was used to host the repository.
* GitPod was used to develop the project.
* GitHub pages was used to deploy the project.
* Lighthouse was used to check performance.

# Testing

I used the code validators :

* HTML - https://validator.w3.org/
* CSS - https://jigsaw.w3.org/css-validator/

Each validator was used at the end of my project and throughout, whenever I had done a large amount of coding in one sitting.

## Testing User Stories

From the UX Section: 

*To understand the brand at a first glance*
* I have achieved this by using a hero image that shows two commercial pilots flying an airliner. This is the goal of the potential customers so they are 
seeing it immediatly on using the site. 
*The logo shows an aircraft and the color scheme exudes professionalism.
 
*To understand what the product being sold is*
* The user is immediatly greeted with the hero text 'Wings Flight Training Academy, Training Future Airline Captains Since 1967'
This provides immediate information to the user what the website is all about.

*To see information about the school provided clearly and facilities*
* The About section is clearly displayed in a way that is easy to read and to the point. The facilities that the school offers are clearly listed.
The icons and text underneath provide extra clarity what this course offers in an easy to read way.

*To understand the entry requirements and any barriers that may prevent me from applying to the course*
* The Training and Entry Requirements section is clearly defined by using images and headings to draw attention. Requirements to the course are listed clearly in a list
to prevent any confusion to the user.

*To be able to contact the school easily*
* A contact form is provided on the page, and the schools details such as address, phone number and email are clearly listed in the footer.

*Has this website succeeded in providing clear information on Integrated Flight training to potential customers?*
Yes it has, by displaying the information in concise, easy to read formatting and by using colors and images that are not distracting. I have not used any
complicated jargon or abbreviations that will confuse users who have no experience in aviation. 


## Further Testing

### Devices I Tested on
*Smart Phones*
* iPhone SE 2020
* iPhone 8
* iPhone X

*Tablets*
* iPad Pro 
* Samusung Galaxy Tab S7
* Samsung Galaxy Tab About

*Laptops*
* Macbook Air 13"
* Dell G7 17.3"

## Third Party Testing

It was important to me to get feedback from potential users of this site. I asked four different people, two qualified commercial pilots, one current student
cadet pilot and one who plans on applying to a flight school after the pandemic.
The following people below acted as testers for my site:

Name  | Age | Pilot    | Tech BG
------|-----|----------|--------
Marius| 32  | Yes      | High
Eoin  | 39  | Yes      | Medium
Sarah | 22  | Student  | None
Dean  | 18  | No       | High


## Lighthouse

will add here on next commit 

# Bugs and Fixes

* There was an issue with the Navbar. It was displaying the data toggler on all screen sizes and not the links. 
I resolved the issue by updated my Bootstrap CDN and adding the Javascript files to the bottom of my project, ahead of the closing body tag.

* There was an issue where, on smaller screen sizes, the entire body of my content was only showing on half of the screen size, with white space everywhere else.
The problem was caused by my Bootstrap form which I had given a width to. This was resolved by removing the width I had given. 


# Deployment 

This site was deployed through GitHub Pages. The steps I took to deploy were as follows.
1. Log into GitHub.
1. Locate the repository.
1. Locate the settings option along the options bar.
1. Locate GitHub Pages options towards the bottom of the page.
1. In 'Source' dropdown, select 'Master' from the branch options.
1. Click the save button.
1. The site is now published and it was accessable after a few minutes.
1. The site URL was visable on the green bar under the section header. This will remain there permanently and it can be referred back to at any time.

## Cloning

1. Log into GitHub.
1. Locate the repository.
1. Click the 'Code' dropdown above the file list.
1. Copy the URL for the repository.
1. Open Git Bash on your device.
1. Change the current working directory to the location where you want the cloned directory.
1. Type git clone in the CLI and then paste the URL you copied earlier. This is what it should look like:
$ git clone https://github.com/gretaegan/MS1-flightschool.git
1. Press Enter to create your local clone.

# Credits 

## Content 
* The code was mostly written by myself.
* The images used were taken by me during my time as a student pilot in Flight School. 
* I used Bootstrap Documentation for the code on my contact form
 https://getbootstrap.com/docs/4.0/components/forms/ was the form provided and slightly modified by me.
* My logo was a generic flight school logo taken from https://depositphotos.com/stock-photos/flight-school.html?filter=all and heavily edited. 
 I used the outline of the aircraft as a stencil to create my own logo in Paint3D.
 * 'Academind' on Youtube for his Bootstrap Navbar tutorial https://www.youtube.com/watch?v=23bpce-5s8I that I watched many times when my Navbar was 
 not working!
 * I referenced https://www.w3schools.com/howto/howto_css_parallax.asp for information on how to create a parallax scrolling effect with my hero image.
 * 

# Acknowledgements 

* A huge thank you to my mentor, Oluwafemi Medale for all of his help, patience and wisdom throughout this project.
* To the Slack Community for being endlessly helpful and supportive, and never laughing at my many questions!
* To Tutor Support, who were always on hand to offer advise and help me to solve problems myself.
* To the whole team at Code Institute for being so helpful, friendly and professional. 
* To my friends and fellow pilots who provided valuable feedback to me on the website.
* To my family for always supporting my goals, and listening to my endless talking about my project!
