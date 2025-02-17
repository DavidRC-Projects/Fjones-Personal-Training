# F Jones Personal Training - Testing

![wireframehomepage](assets/img-readme/homepage.png)

## Contents

### Automated testing
- Lighthouse

### Results from Lighthouse testing

#### Homepage
![lighthousetesting](assets/img-readme/lighthouse-homepage.png)

#### About me page
![lighthousetesting](assets/img-readme/lighthouse-aboutme.png)

#### Booking page

![lighthousetesting](assets/img-readme/lighthouse-booking.png)

#### Testimonials page

![lighthousetesting](assets/img-readme/lighthouse-testimonials.png)

#### Contact us page

![lighthousetesting](assets/img-readme/lighthouse-contactus.png)

#### Error 404 page

![lighthousetesting](assets/img-readme/lighthouse-404.png)

#### Booking success page

![lighthousetesting](assets/img-readme/lighthouse-bookingsuccess.png)

#### Feedback success page

![lighthousetesting](assets/img-readme/lighthouse-feedbacksuccess.png)

### Results W3C HTML validator

##### Homepage - W3C Validation Check
There were 22 errors identified, which were corrected as follows:
1. Added div to container due to the container tag not being closed.
2. Changed duplicate id attributes to class.
3. Removed multiple <tr> without any cells.

After the above changes the validation passed. Please see homepage validation errors below:

![wc3checkindex](assets/img-readme/wc3checkindex1.png)
![wc3checkindex](assets/img-readme/wc3checkindex2.png)
![wc3checkindex](assets/img-readme/wc3checkindex3.png)
![wc3checkindex](assets/img-readme/wc3checkindex4.png)
![wc3checkindex](assets/img-readme/wc3checkindex5.png)

##### About me page - W3C Validation Check
There were 2 errors identified, which were corrected as follows:
1. Added div element to container as the tag was not closed.

After the above changes the validation passed. Please see about me validation errors below:

![wc3checkindex](assets/img-readme/wc3checkaboutme.png)

##### Booking page - W3C Validation Check
There were 7 errors identified, which were corrected as follows:
1. Added missing div element that needed a closing tag.

After the above changes the validation passed. Please see booking page validation errors below:

![wc3checkindex](assets/img-readme/wc3checkbooking1.png)
![wc3checkindex](assets/img-readme/wc3checkbooking2.png)

##### Testimonials page - W3C Validation Check
There were 4 errors identified, which were corrected as follows:
1. Added missing div element that needed a closing tag.
2. Removed white space validator from text area.

After the above changes the validation passed. Please see testimonial page validation errors below:

![wc3checkindex](assets/img-readme/wc3checktestimonials1.png)

##### Contact page - W3C Validation Check
There were 2 errors identified, which were corrected as follows:
1. Previous syntax of 'width="100%' was invalid. Changed width to 600 and added style width: 100%.
2. Height of iframe changed from auto to 450 as invalid due to expecting a digit value.

After the above changes the validation passed. Please see contact page validation errors below:

![wc3checkindex](assets/img-readme/wc3checktestcontact.png)

##### booking and feedback success page - W3C Validation Check
Both pages passed validation.

##### 404 page - W3C Validation Check
There were 2 errors identified, which were corrected as follows:
1. There was a main element inside another main element. Removed additional main element.

After the above changes the validation passed. Please see 404 page validation errors below:

![wc3checkindex](assets/img-readme/wc3check404.png)

