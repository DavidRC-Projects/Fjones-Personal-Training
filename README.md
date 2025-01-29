# FJones Personal training

## Introduction

The primary goal of this webpage is to serve as a platform for my friend's business. Currently, my friend does not have a website and relies on word-of-mouth to build his client base. This site aims to offer an engaging and informative introduction to his experience, training philosophy and what he can offer. It will also provide details about one-on-one training sessions, group training, nutritional guidance and customised workout plans. Additionally, the webpage will feature a booking system and accessible contact options, making it easier for the potential clients to reach out, ask questions, and schedule consultations. This will hopefully bring in new business and target people from any training level that want to improve their strength or fitness.

## CONTENTS

[User Experience]
[User Stories]

[Features]

[Design]

- Colour scheme
- Typography
- Wireframes

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

- I want to be able to learn about the personal trainers experience and what they offer so that i can assess their expertise and find the right trainer for me.
- I want to view testimonials to gauge the effectiveness of the personal trainer.
- I want to see a list of availiable services and pricing to work out my budget.
- I want to be able to view the trainers social media links to learn more about their sessions and training philosophy.
- I want a user-friendly layout so i can find information quickly and is responsive to different screen sizes.

#### Returning Visitor Goals

- Upon returning to the site i would like access to workout and nutrition plans.
- I would like to be able to book a session and contact the trainer.

#### Frequent Visitor Goals

- I would like to be able to rechedule my bookings online and be able to do this quickly without having to navigate through many pages.
- I want to access a schedule overview to check upcoming sessions at a glace.
- I would like to have access to personalised feedback from sessions.

#### Owner Goals

- To increase the number of new clients and retension of existing clients by offering online services that are accessable and easy to use from any device.
- To increase awareness of his brand by establishing a strong online presence by increasing visibility on search engines that will highlight his experience.
- The webpage will make administrive tasks easier by using an automated system that will organise time slots from his clients and make it easier to track payments as currently uses a paper diary to record this.

## Design

### Colour Scheme

I used a colour image picker to select colours from the logo, ensuring consistent colour usage across the webpage. To create visually appealing design, i chose a dark background, accented with purple to highlight specific elements. The use of purple can help reinforce brand identity and can make key components stand out to engage users. Initially i created a logo for the website, however i made a conscious descision that actual images of the trainer would be more engaging and add familiarity for the users. Therefore, despite this the colours stayed consistent throughout the webpages with CSS variables used to make it easier to change in the future.

![imagecolorpickerlogo](assets/img-readme/imagecolorpickerlogo.png)

I have used the following Hex colours:

#ffffff;
#000000;
#380b72;
#7A0BEA;
#bcbcbc;

![wireframehomepage](assets/img-readme/colourpalette.png)

### Typography

I have used google fonts to import fonts.

The primary font that was used for the h1 headings was Marvel font. From my research of fonts i felt this looked sharp and had modern feel to it and preferred this to other fonts. An advantage to using this font is that is a sans serif typeface making it more legible.

I used Montserrat as my secondary font. I researched on google good fonts for readability and consciously decided this was the most appealing font to go along side the marvel font.

### Wireframes

Wireframes were created for desktops, tablet and mobile using figma.

### Home page (index.html)

![wireframehomepage](assets/img-readme/wireframehomepage.png)

### Aboutme page (aboutme.html)

![wireframehomepage](assets/img-readme/aboutme1.png)
![wireframehomepage](assets/img-readme/aboutme2.png)

### Booking page (booking.html)

![wireframehomepage](assets/img-readme/booking.png)

### Testimonials page (testimonial.html)

![wireframehomepage](assets/img-readme/testimonials.png)

### Contact page (contact.html)

![wireframehomepage](assets/img-readme/contact.png)

## Features

The website is designed to offer a seamless experience through the following pages:

- Home Page: This is the starting point where new clients or existing clients can have an overview of what the trainer offers and availiability.

- About Me Page: This page gives a deeper dive into the trainers expereince and why the user should choose his services.

- Booking Page: This page has been developed for enquires and to send a date and time the user would like to book an appointment.

- Contact Page: This page was developed for the user to reach out for any enquiries.

- Booking confirmation pages: This was developed for the booking form and feedback form to indicate to the user that their request has been submitted.

- Error 404 page: This was added incase the page is not able to load or has been deleted and sends the user back to the homepage.

All pages have a favicon item, title of 'Francis Jones Personal Training' and a h1 element of 'Francis Jones Fitness' that links every page with an anchor element back to the home page. There is a navigation bar and footer on each page that includes anchor elements to navigate the website and access his social media links respectively.

- Favicon and title

![wireframehomepage](assets/img-readme/faviconandtitle.png)

- Header and navigation bar

![wireframehomepage](assets/img-readme/header.png)
The header includes a h1 element that links back to the homepage.
The navigation bar stays in a fixed position on the screen and has the text underlined when your on a particular page. The navigation bar will also change colour as you hover over each option. This is also responsive to different screen sizes and will turn into an icon on mobile devices, in which the options will drop down in a list.

Navbar icon for mobile device

![wireframehomepage](assets/img-readme/navdropdownicon.png)

Navbar dropdown for mobile device

![wireframehomepage](assets/img-readme/navdropdown.png)

- Footer

![wireframehomepage](assets/img-readme/footer.png)

The footer maintains a consistent colour with icons that enlarge when you hover over them. Each footer icon has a link to the corresponding social media site. It is responsive to all device sizes.

- Home page

![wireframehomepage](assets/img-readme/homepage.png)

Link to [responsive Mockup](https://ui.dev/amiresponsive?url=https://davidrc-projects.github.io/Fjones-Personal-Training/)

The home page is divided into two responsive containers that adapt to all screen sizes. I used a Bootstrap carousel with 2 images and a table of his availiability that adjusts dynamically, displaying as a single column on mobile devices and two columns on desktop screens and larger. The second container features cards with images showcasing the trainer's offerings. Additionally, an h2 heading presents a welcome message, accompanied by text in a paragraph designed to inspire and highlight the site's purpose. Under the table there is a "Book Now" button that has a link for the user to go to booking page.

- About me page

![wireframehomepage](assets/img-readme/aboutmepage.png)

The About Me page follows a similar format to the homepage, featuring a container that splits into two columns. One column displays a picture of Francis, the trainer, while the other highlights reasons to choose Francis, using spans to emphasize key words. Below this, buttons are styled in CSS to match those on the homepage. The "Book Now" button links to the booking page, while the "Get in Touch" button directs users to the contact page.

The second container includes three cards that is the same as the homepage. The layout is fully responsive, adjusting to a single column on mobile devices and three columns on larger screens for optimal readability.

span elements
image

- Booking and testimonial pages
  forms
  container for testimonials page
  background image
  date picker (copied from geeksforgeeks.org)
  star rating (W3schools)
  booking success pages - Opacity (W3schools)
  booking validation for white space validator (stackoverflow.com)

- Contact
  embedded Google maps (researched on google and found option to embed code into my work as the url link was blocked)
  container for contact details

- Buttons (Bootstrap 5)

scroll bar (copied from W3schools)

- Hover (CSS Pseudo-classes on W3schools)

CSS variables (Boardwalk games and W3schools)

- Error 404 page (udacity.com)
