# CGphotography

CGphotography is a couple photography website.

It presents the previous works of the photographer in order to attract new clients. The portfolios present:
* Couples photographs
* Wedding photographs
* More than two photographs

## Demo

A live demo can be found [here](https://itamichan.github.io/CG_photography/)

![Desktop Demo](assets/images/webpage_response.jpg)


## UX

### Goals

#### CGphotography goal

The goal of this web page is to present previous works of the photographer and as such, attract new clients.

**Target audience is:**
* Couples with the age between 20-45 years.
* Couples interested in photo services.
* Couples interested in wedding photo services. 
* Couples interested in pregnancy photo services. 

#### Business goals

* Reach the new, potential customers.
* Have a high conversion rate.
* Have a fully proficient web page.
* Have an intuitive design.

#### Visitor goals

* Find a photographer for their photo session.
* Find previous works made by the photographer.
* Find contact information of the photographer.

Both business and visitor goals are addressed through user stories.

### User Stories

#### The Photographer

* As a photographer, I want to show my previous works so that people hire me.
* As a Photographer, I want my page to load fast so that the user is engaged.
* As a Photographer, I want the potential customers to have an easy way to find my contact details so that they can order a photo session.
* As a photographer, I want to show positive reviews so that I convince people to book my services.
* As a photographer, I want them to know my current location so that I can  avoid orders that are too far away for me to come.
* As a Photographer I want that the user remember me so that they come back.

#### The UX designer

* As a UX designer, I want to track the user behaviour so that I can improve the user experience.
    * As a UX designer, I want to track the user behaviour so that I can identify the possible user confusion.
    * As a UX designer, I want to find which parts are not accessed by the user so that I can improve the website’s structure.

#### The potential customer

* As a customer, I want to know the prices of the services so that I can decide if I want to pay the price.
* As a customer, I want to see the  previous work so that I can decide if I would like to have something similar or not.
* As a customer, I want to have an easy way to contact the photographer so that I can book a session.
* As a customer, I want an easy way to contact the photographer so that I can clarify some information.
* As a customer, I want to know if the photographer is willing to come to remote/distant locations so that I can have a photo session there.
* As a customer, I want to know what is the duration of the photo session so that I know how much time it will take.
* As a customer, I want to know how many photos I will get so that I can assess if this is enough for me or not.
* As a customer, I want to know if the photos will be edited so that I have a professional editing of my photographs.
* As a customer, I want to know what are the photographer’s values and vision so that I can know if they align with mine.
* As a customer, I want to know if I can change the clothing during the photo session so that I can have different looks.

#### The future married couple

* As a couple, we want to be able to see when the photographer is available so that we can book his services on our wedding day.
* As a couple, we want to divide our photo session in two different days so that we can have a wedding and pre-wedding photo session.
* As a couple, we want to know if any discount system exists so that we can  take benefit of it.
* As a couple, we want to have a physical photo album so that we can have a paper version of our photographs.
* As a couple, we want to choose how our photo album looks so that it is personalized.

All User Stories were added as [issues](https://github.com/Itamichan/CG_photography/issues?q=is%3Aopen+is%3Aissue) on GitHub in order to keep track and address them in the project's [dashboard](https://github.com/Itamichan/CG_photography/projects/1).

### Minimum Viable Product

All the User Stories have been assessed against value/complexity chart. Considering the relative short time of implementation of the web page only the MVPs will be addressed in the first release of the web page.

[User Stories evaluation](MVP/user-stories)

![chart](MVP/value-chart.jpg)

#### Explanation of the chart

* The top right corner have been given the higher priority of implementation because it represents the most important functionality features. Such as:
    * The Contact Form.
    * The Portfolios.
    * The Gallery.
* Features with a medium value and with a low complexity have been addressed in second place since most of them can be easily resolved through creation of the FAQ Page.
* Features with low complexity and low value where addressed in the third place. It didn't represent a must feature for the first release but was very easy to be done.
* Features with medium to low value and high complexity have been postponed for future releases.

User Stories identified as important for MVP were attributed the respective label in the [issues](https://github.com/Itamichan/CG_photography/issues?q=is%3Aopen+is%3Aissue) section on GitHUb.

### Design

#### Colors

Following colors have been used:
* `#932244` - dark pink
* `#7e1f3f` - darker version of the initial pink
* `#000000` - black
* `#ffffff` - white

The stand out color for this web page is dark pink which is associated with romance, love, feminine qualities and friendship. Considering that this color is very strong and easily attract attention I decided to not use any other bright colors. Therefore, the other used colors are the classic white and black.

#### Font

Used Font Family for this project is **Montserrat** with the font weight: 
* 400 - for most of the text.
* 500 - for logo, button and headers on the hero images.
* 600 - for heavy headers.

The Montserrat font was chosen for its easy readability and common use.

## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)


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
All content in the "About Me/À Propos" and "Work/Travail" sections in this portfolio site were written by me. 

### Media
All photos were taken from [Pexels](https://www.pexels.com/), a stock image library, with the exception of the photo of myself in the background of the 'about me/À Propos' section in the desktop view. A greyscale filter was applied to each one prior to upload to preserve the greyscale theme. 

### Acknowledgements
The scrollSpy delay JavaScript function was found through this tutorial [here](https://www.abeautifulsite.net/smoothly-scroll-to-an-element-without-a-jquery-plugin-2).

The progress circles from the skills section are modeled after the following Stack Overflow [example](https://stackoverflow.com/questions/14222138/css-progress-circle). They were significantly modified to fit the styling, sizing, and progress for each skill.

The media query for the collapsed navbar regardless of viewport width was taken from this [site](https://www.codeply.com/go/iaM1zcNsQB/bootstrap-navbar-always-collapsed).

**This is for educational use.** 