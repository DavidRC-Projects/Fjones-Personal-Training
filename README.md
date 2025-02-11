# FJones Personal training

## Introduction

The primary goal of this webpage is to serve as a platform for my friend's business. Currently, my friend does not have a website and relies on word-of-mouth to build his client base. This site aims to offer an engaging and informative introduction to his experience, training philosophy and what he can offer. It will also provide details about one-on-one training sessions, group training, nutritional guidance and customised workout plans. Additionally, the webpage will feature a booking system and accessible contact options, making it easier for the potential clients to reach out, ask questions, and schedule consultations. This will hopefully bring in new business and target people from any training level that want to improve their strength or fitness.

![wireframehomepage](assets/img-readme/homepage.png)

Link to [responsive Mockup](https://ui.dev/amiresponsive?url=https://davidrc-projects.github.io/Fjones-Personal-Training/)

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

## Existing Features

The website is designed to offer a seamless experience through the following pages:

- Home Page: This is the starting point where new clients or existing clients can have an overview of what the trainer offers and availiability.

- About Me Page: This page gives a deeper dive into the trainers expereince and why the user should choose his services.

- Booking Page: This page has been developed for enquires and to send a date and time the user would like to book an appointment.

- Contact Page: This page was developed for the user to reach out for any enquiries.

- Booking confirmation pages: This was developed for the booking form and feedback form to indicate to the user that their request has been submitted.

- Error 404 page: This was added incase the page is not able to load or has been deleted and sends the user back to the homepage.

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

![wireframehomepage](assets/img-readme/homepage2.png)![wireframehomepage](assets/img-readme/homepage2bottom.png)

The home page is divided into two responsive containers that adapt to all screen sizes. I used a Bootstrap carousel with 2 images and a table of his availiability that adjusts dynamically, displaying as a single column on mobile devices and two columns on desktop screens and larger. The second container features cards with images showcasing the trainer's offerings. Additionally, an h2 heading presents a welcome message, accompanied by text in a paragraph designed to inspire and highlight the site's purpose. Under the table there is a "Book Now" button that has a link for the user to go to booking page.

- About me page

![wireframehomepage](assets/img-readme/aboutmepage.png)

The About Me page follows a similar format to the homepage, featuring a container that splits into two columns. One column displays a picture of Francis, the trainer, while the other highlights reasons to choose Francis, using spans to emphasize key words. Below this, buttons are styled in CSS to match those on the homepage. The "Book Now" button links to the booking page, while the "Get in Touch" button directs users to the contact page.

The second container includes three cards that is the same as the homepage. The layout is fully responsive, adjusting to a single column on mobile devices and three columns on larger screens for optimal readability.

- Booking and testimonial pages

Booking page

![wireframehomepage](assets/img-readme/bookingpage.png)

The booking inquiry page will allow the user to submit their details and request a specific date and time for their first session. This page includes a textarea for the user to leave a message and a submit button that takes the user to another page upon submission. I have used bootstrap 5 to provide a responsive layout and an image in the background to make the page more engaging and enhance the user experience.

 Please see the booking success page below:

Booking success page

![wireframehomepage](assets/img-readme/bookingsuccess.png)

Testimonials page

![wireframehomepage](assets/img-readme/testimonialspage.png)

This page has been developed using bootstrap 5 and will help the user provide feedback on their training sessions with a textarea and a star rating. On desktop and larger the screen splits into 2 columns. The left section of the page has a feedback form and a drop down menu down menu to provide the star rating. There is a submit button below that takes the user to a feedback success page to let the user know their feedback has been submitted. Please see an example below. The right side of the page displays testimonials provided from his clients with his star ratings. On smaller screens like mobile devices the screen adjusts to one column with the input fields at the top of the page and testimonials at the bottom.

- Contact page

This page will provide the user the necessary information to locate the gym and multiple options for getting in touch with the trainer. The page has been developed with a responsive bootstrap 5 layout. I have placed headings to guide the user and embedded a google map that includes the location of the gym and is resposive to different screen sizes. Below the google map i have used icons from font awesome to give the user 3 options to contact the trainer. This makes it visually easier and more accessable for the user the identify how they want to contact the trainer. The 'Contact Me' section is split into 3 columns on desktop and larger screens and stack ontop of eachother when in smaller screens. 

![wireframehomepage](assets/img-readme/contactpage.png)

  embedded Google maps (researched on google and found option to embed code into my work as the url link was blocked)

## Accessibility

### General Site Strucutre

All pages have a favicon item, title of 'Francis Jones Personal Training' and a h1 element of 'Francis Jones Fitness' that links every page with an anchor element back to the home page. There is a navigation bar and footer on each page that includes anchor elements to navigate the website and access his social media links respectively. Each page of the website has an accessibility rating of 94-100.

### Buttons

All buttons throughout the site maintain a consistent design and hover effect to improve the user experience. The buttons are styled using CSS and bootstrap 5. The buttons all have a hover effect using variables to change the colour from purple to white, indicating to the user they are hovering over the button.

### Custom scroll bar

I have added a customised scroll bar that changes colour from purple to dark purple when the user hovers over to interact with the bar. This bar stays consistent with he colours used through the sites design.

### Hover effects

To improve user interaction the icons across the site i have implemented a hover effect that increases in size when hovered over. Also to maintain a consistent style, all buttons across the site have the same background colour that changes as you hover over.

### Error 404 page

The site includes a custom 404 error page to enhance user experience when a page doesn't exist anymore or is broken. This contains a message telling the user that the page cannot be loaded or doesn't exist with a button to give them the option to return to the homepage. This uses a background image used in the booking page and consistent colours with the other webpages. Bootstrap has been used to create a card that has been used in both the booking success and feedback success pages.

![wireframehomepage](assets/img-readme/error404page.png)

### Colour contrast improvements

A contrast checker was used to ensure the text was readable on the background. The original hex code #7A0BEA (purple) used in the spoan elements on the About Me page had a low contrast rating (3.06) and was replaced with #FFFFFF (white) to improve its readbility.

![wireframehomepage](assets/img-readme/colour-contrast-fail.png) ![wireframehomepage](assets/img-readme/colour-contrast-pass.png)



## Future implementations

1. Booking form
- Add a caldendar feature that allows users to select and save availiable training session dates.
- Ensure live calendar visibility for both the user and trainer, providing a better user experience.
- Add a payment option for booking sessions directly through the website.
- Include a pricing list below the booking form to display availiable services and their costs. 

2. Core training area cards and blog page
 - Make the core training area cards in the home and about me pages clickable with a hyperlink.
 - Each card will like to blog pages providing detailed advice on kettlebell training, strength training and nutritional coaching. This will help give the user more understanding of the level of coaching and advice they will receive and to improve their own knowledge and options aviliable from the trainer.

3. Star rating and testimonials update
- Autumatically update the testimonials page with client-submitted feedback and their star ratings.
- Add a testimonial carousel for better readability and a smoother user experience.
- Place the testimonial carousel on the homepage below the core training sections and add a "leave feedback" button below the carousel. This will hopefully improve user engagement for returning users.

## Testing

### Manual testing

#### Responsiveness testing

- Used the inspect element tool in Google Chrone to check different screen sizes (mobile, tablet, desktop and larger screens).
- Ensured all webpages adapt properly to different screen widths.

#### Navigation and link testing

- Verified that all navigation links direct users to the correct pages.
- Tested the h1 element, navigation bar, buttons, and social media icons to confirm they link to there respective pages.

#### Hover effects and User interaction
- Checked hover effects on:
- h1 element
- Navigation bar
- Tables
- Icons
- Buttons
- Social media links

#### Form Validation and Redirection
- Tested the booking enquiry and feedback forms to confirm they:
- Redirect users to the correct successpage after submission.
- Display validation messages when required fields (marked with an asterisk) are left empty.
- Prevent submission of inputs containing only whitespace.

Validation check

![wireframehomepage](assets/img-readme/validationcheck.png)

#### Layout and UI fixes
- Identified and resolved an issue where the h1 element had a line break on every page expect the index page.

![wireframehomepage](assets/img-readme/h1layoutissue.png)![wireframehomepage](assets/img-readme/h1layoutfix.png)


## Deployment

## Credits

Transition hover effects https://stackoverflow.com/questions/19469495/css-slow-hover-effect

### Content

### Media

### Other General Project Advice

CSS variables (Boardwalk games and W3schools)

 date picker (copied from geeksforgeeks.org)
  star rating (W3schools)
  booking success pages - Opacity (W3schools)
  booking validation for white space validator (stackoverflow.com)
  scroll bar (copied from W3schools)
  Hover (CSS Pseudo-classes on W3schools)
  Error 404 page (udacity.com)