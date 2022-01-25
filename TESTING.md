# Testing

## Code Validator 
The 'I'd Rather Be At Pemberley' website was tested thoroughly. All code was ran though [W3C html Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate it. Minor bugs were found and fixed so that no errors were returned.

#### HTML Validator Results
* Home Page
![Home Validation](assets/readme-images/homevalidation.png)
* Events Page
![Events Validation](assets/readme-images/eventsvalidation.png)
* Join Page
![Join Validation](assets/readme-images/joinvalidation.png)
* Thank you Page
![Thank You Validation](assets/readme-images/thankyouvalidation.png)

#### CSS Validator Results
![CSS Validation](assets/readme-images/cssvalidation.png)

---

# User Stories Testing 

#### First Time Visitor Goals

* As a first time visitor, I want to easily navigate the site.

  1. On entering the site users are met with a clear navigation bar.
  2. The user can easily know which page of the website they are one with as the background color change of the title on the navigation title highlights which page the user is visiting.
  3. Above the navigation bar the site logo is clicked to easily return to the home page.
  4. Both the navigation titles and logo have a a hover effect to let users know they can be clicked.

* As a first time visitor, I want To find information on the book club, what type of books are read and where it takes place. 

  1. The About The Club section below the hero image provides all imformation on the book club and is in four sections of information with title questions for users to easily find answers about the book club.

* As a first time visitor, I want to easily find their social media links .

  1. The site contains social media links through easy to find icons located at the bottom of the webpage in the footer.
  2. There is a hover effect on the icons to let users know they can be clicked.

#### Returning Visitor Goals

* As a returning visitor, I want to find out how I can join the book club.

  1. The Join page provides an easy to fill join form with four input fields including first and last name, email and an input to fill about the users reasons for joining the book club.
  2. A 'Join Us' button sits at the bottom of the form that is easily distinguishable from the other input fields.

* As a returning visitor, I want to easily find contact information if I have queries before joining the book club.

  1. Contact informaton for the book club is located in the footer of the website above the social media links.
  2. It is laid out to be easily read and provides a phone number and email to reach the book club.

#### Frequent User Goals
* As a frequent user, I want to be able to check for any upcoming book club events.

  1. The sites Events page has easy to read sections detailing upcoming events including time, date and the place of the event as well as information on which book is being read.
  2. The event sections also contain a link to the Goodreads website which provides more informatiom on the books being read.

* As a frequent user, I want to be able to check what the book club is currently reading before attending the meet up.

  1. Frequent users can find the book that is currently being read at the bottom of the webpage above the footer.
  2. It highlights the book being currently read by the book club.
  3. There is also a link to the events page that changes to a pink font color when a mouse hovers on it showing it can be clicked, so that the user can find information on when the book will be reviewed.


  # Responsive Desgin Testing

  * Responsive design testing for the website was carried out using [Google Chrome Dev Tools](https://www.google.com/chrome/dev/), [Website Planet](https://www.websiteplanet.com/) and [Responsive Design Checker](https://responsivedesignchecker.com/)

  * The website was checked on various devices such as Iphone 5/SE, Iphone X, Samsung Galay S8+, Nokia N9, Ipad, Galaxy Tab, Laptop and Desktop.
  * The website was checked on all devices to see that the website flowed and nothing was too large or out of the screen view.
  * Any issues that were shown such as the website logo being to large on mobile screens and the events page needing adjusting to fit on mobile screens were fixed using media queires.

  # Browser Compatibility Testing 
  
  * This Website was tested on the browsers Google Chrome, Safari, Microsoft Edge and Mozilla Firefox.
  * Links where checked in each browser to make sure they worked correctly and were not broken.
  * The functionality of each page of the website was checked to make sure they worked.
  * The appearance of the website was checked on each browser to make sure nothing was out of place.


  # Known Bugs
  ### Validatin bugs
  ---
  ### During Validation a few bugs were shown including:

  ### The first bug was an error which meant the link to the website pages was not working properly.

   ![Links Error](assets/readme-images/linkserror.png)

  * ### This was resolvd by containg the link within the list item elements.

  ### The second bug was an error with the font awesome script.

  ![Script Error](assets/readme-images/scripterror.png)

  * ### This was resolved by removing the duplicate boby tag that had accidently been placed in the code.

  ### The third bug was an error with the hero images on both the Home and Events page.

  ![Hero Image Error](assets/readme-images/heroimageerror.png)

  * ### This was resolved by removing the section tag that surrounded the div tag.

  ### Responsive Bugs
  ---
  Whiles testing the responsive design of the website some bugs were encountered.

  * The Logo was too large on mobile screen sizes and need to be made smaller with media queries.
  ![Logo Bug](assets/readme-images/logobug.png)

  * The Navigation bar look askew on mobile screen sizes and needed to be made vertical with media queries.
  ![Nav Bug](assets/readme-images/navbug.png)

  * The About The club section needed to be changed from a row into a column when on tablet and mobile screen sizes.
  ![About Bug](assets/readme-images/aboutbug.png)
  ![About The Club Book](assets/readme-images/aboutclubbug.png)

  * the Events section had too large of a margin and was unreadable on mobile and small tablet screen sizes.
  ![Events Bug](assets/readme-images/eventbug.png)



  # Lighthouse 
  This website was tested using the [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) feature. The scores for the home and events page went from to 60% to over 90% performance once image files were compressed.

  ## * Home Page
  ![Home Lighthouse](assets/readme-images/homelighthouse.png)
  ## * Events Page 
  ![Events Lighthouse](assets/readme-images/eventslighthouse.png)
  ## * Join Page 
  ![Join Lighthouse](assets/readme-images/joinlighthouse.png)
