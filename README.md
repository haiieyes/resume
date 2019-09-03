# Hairi Ali Portfolio
Stream One Project: User-Centric Frontend Development - Code Institute 

This website was coded to showcase certain levels of skills to future employers. 
It contains four different sections: About Me, Portfolio, Skills and Contact Me.


## Demo
![Desktop Demo](https://raw.githubusercontent.com/hschafer2017/HSCHAFER-Portfolio/master/assets/images/portfolioview.gif "Desktop Demo")


## UX
I believe that most people will only stay on the website for about 2-3 seconds. 
My goal is to encourage my future employers to stay on and continue looking through what I can do.
Although my social media buttons and my 'Contact Me' section is positioned below, the 'call-to-action' to connect with me should be one of the first few things they see.
The colour scheme that I chose should represent my age. If bright colours show energy and monochrome colours show professionalism, 
I have chose to balance both.

I wanted to showcase that I am open to follow any formalities or think outside of the box.
Thus, 85% of the website will showcase my knowledge to utilize bootstrap's grid system 
and 15% of the website will showcase the 'out-of-grid' thinking only for the portfolio section.
This way, they would understand that whatever their company represents, I can show that I can fit in their business style. 

I placed a strong focus on the present and on the future, thus I don't feel that it is important for me to showcase my irrelevant past experiences and education. 
I believe it's important that I showcase the personality of being humble, knowing that I do not have any experiences in the relevant field.
With that in mind, I have added quotes to show humility.


## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.1)


## Features
This site uses the scrollSpy feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. The navbar also stays collapsed regardless of the screen size to promote a minimalist design.


### Features Left to Implement
In the future, I would like to add further projects that I've worked on to create a more comprehensive 'work/travail' section. I would like to also add animations to the progress circles in the "skills/compétences" section to animate on a hover. 


## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer. 

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar. 

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that ```background-attachment: fixed``` was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the ```background-attachment: scroll``` property value was added in a media query.


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/hschafer2017/HSCHAFER-Portfolio.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
All content in the "About Me" section in this site were written by me. 

### Media
All photos were taken from: 
[Pexels](https://www.pexels.com/),
[Burst](https://www.burst.shopify.com/),
[Unsplash](https://www.unsplash.com).

### Acknowledgements
The Bootstrap components that I've used can be found [here](https://www.getbootstrap.com/docs/4.0/components/).

Fonts used are from [Google Fonts](https://www.fonts.google.com).

**This is for educational use.** 