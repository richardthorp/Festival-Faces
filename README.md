# Festival-Faces
[Click here to see live website](https://richardthorp.github.io/Festival-Faces/index.html)

This is a website for the face painting company 'Festival Faces'. The company provide face painting, eco glitter and body art services at children's parties, corporate events,
festivals and many other events. 
The primary users of the website are parents and carers, business owners and event organisers.

The business goals of the website are:
* Increase bookings
* Provide a central place to direct business leads via online or in person marketing
* Reassure potential customers of quality and legitimacy through a well made website with great UX 

## UX

As a first time user of this website, I want to:
* Immediately understand how to navigate the website.
* Understand the purpose of the website.
* See examples of previous work.
* Understand what services are offered.
* Gain an understanding of costs.
* Gain an undertanding of the company to attain whether they are right for my needs. 
* Find links to social network channels to find reviews and updates.
* Quickly find contact details.

As a returning user of this website, I want to:
* Quickly find contact details.
* Check for updated examples of work.
* Check for updated costs.

## Design
[Click here to view wireframes](https://github.com/richardthorp/Festival-Faces/blob/master/Festival%20Faces%20Wireframes.pdf)

### Colour Scheme
The colours found throughout the website have been taken from the company logo. The main body of the website is a lighter shade of the blue found in the logo and navigation bar. The outcomes of using the lighter shade chosen are:
* Clearer contrast between the background colour and font colour.
* More contrast between the images and background colour.
* A light and non oppressive user experience when compared to a heavy, darker colour.

An even lighter shade of the logo blue can be found in the 'Services' area of the home page, as well as in the Gallery page and the Contact page. This was used in the Gallery page to further accentuate the contrast between images and the background colour. The lighter shade was used in the 'Services' section and on the Contact page to break up the content and to draw the eye of the user to the key information on the page. 

The 'Send' button at the bottom of the contact form is the same blue from the logo, ensuring the element is consistent with the rest of the website.

### Fonts
The font used for all of the headings throughout the website is 'Londrina Solid' from Google Fonts. This font was used in part as it is similar in style to the font found on the company logo. It works well for the website and therefore the business, as it connotes feelings of fun and of being hand made. As a back-up font, 'Impact' has been chosen as it is a very 'web-safe' font, as well as being striking and stencil like, which is appropriate for a website pertaining to art. The company logo font was not chosen for headings as the shadow effect detracted from the clarity of the headers.

The font used for all other text on the website is 'Raleway' from Google Fonts. This font was chosen as it is very legible, even at small font sizes as well as being generally pleasing to the eye. As a back up font, 'Arial' has been selected as it is very 'web-safe' and is also very clear and easily legible.

### Features
#### Implemented Features
Each page features a responsive navigation bar with the navigational links clearly listed to the right of the page, or being found in a dropdown list by clicking a 'hamburger' button which appears on screens 575 pixels wide or less. The page the user is currently on is made clear by the navigational link for that page being brighter than the other links in the navigation bar. The logo on the left of the navigation bar also serves as a link to the home page - a feature which is widely used in web design and therefore expected by the user. 

Each page also features the same footer which contains a link to the business' email address, links to the business' social network pages and the copyright infomation for the website. All clickable links are clearly indicated with a subtle change in colour when the curser is hovered over them. The footer also implements responsive design by reordering the footer content to push the copyright information to the bottom of the screen and the more important social network and email links above on small screen sizes.

##### Home
The home page features a short welcome message to the user, followed by a tag line which quickly tells the user the purpose of the business. Immediately below are 3 circular images on screen sizes 768 pixels wide and above, or 1 circular image on smaller screen sizes. The purpose of the 3 images on larger screens is to immediately display a selection of examples of work to the user. On smaller screens where only 1 image is displayed, the image acts as a more standard hero image, giving the user an immediate and stricking example of what the website is about.

Beneath this, the user finds the 'About' section, comprised of a small picture of some of the Festival Faces team along with 3 short sentences that summarise the ethos of the business, provide examples of previous clients and offer a link to 'get in touch'. The picture, with the three women all smiling establishes a human connection between business and the user, as well as providing reasurrance that this business is operated by friendly and happy people. The copy contained in the 'About' section is kept short and to the point so as not to overwhelm the user with information, and provide a call to action in the form of the 'get in touch' link which is clearly styled as a clickable link.

The third and final section of the page goes on to highlight very briefly the most common types of events for which the business is booked regularly. This serves as to further reassure the user that 'Festival Faces' is a suitable company to hire for their event. This section also where possible, clearly provides prices for hiring the business and where prices can't be immediately given, another link and invitation to 'get in touch' is provided.

##### Gallery
The gallery page is virtually kept entirely free of text, except to explain to the user that they can 'Click on image to enlarge'. The gallery features an even number of thumbnails horzontally centered, thus ensuring the page is always symmetrical and visually pleasing. The images offer a wide selection of examples of previous work, including face painting, eco glitter and body art. The images also display clientelle of all age groups and genders, so as to reassure the user that this business is approprate for as wide a target market as possible. 
When clicked, the thumbnails open a modal which enlarges the image making it much easier for the user to see. Whist a 'Close' button is offered, the user can click anywhere outside of the modal to close it. This is a commonly used feature throughout web design and therefore expected by the user and good UX.


##### Contact
The contact page is kept very simple, with an invitation to email the business or if prefered use the contact form to send an enquiry. The contact form uses form validation to ensure appropriate responses have been entered, such as the use of an @ charactor in the email address field. On screens 768 pixels or wider, and attractive image of a facepainter testing paint on her arm whilst surrounded by paints and brushes is displayed. This is a nice way to fill the space and further reinforce the authentic and creative nature of the business.

#### Potential Future Features
* A hero video in place of the three images found on the home page. This would be an improved method of quickly establishing the business' purpose and ethos.
* An alternative to the modal code found in the Gallery page. Using Javascript, the code could be much more readable and maintainable.
* A thank you message in the form of a modal when the user sends an enquiry through the contact form. 
* A form that can give an immediate quote for potential customers by taking in variables such as location, number of guests and length of event and outputting an estimated price.

### Languages and Technologies  Used
The website has been built using HTML5 and CSS, as well as some Javascript via plugins as detailed below.

1. [Gitpod](https://www.gitpod.io/)
   * The IDE used to write the code for the website.
   
3. [Git](https://git-scm.com)
   * Used for version control during the website build via the command terminal in Gitpod
   
3. [GitHub](https://pages.github.com/)
   * Used to store the code after being 'commited' and 'pushed' using Git. 
   
3. [Bootstrap](https://www.getbootstrap.com/)
   * Used to create structure and some styling, as well as responsive aspects of the website.
   
4. [jQuery](https://www.jquery.com/)
   * Used to provide the Javascript found in the navigation bar.
   
5. [Google Fonts](https://www.fonts.google.com/)
   * Used to provide the 'Raleway' and 'Londrina Solid' fonts used throughout the website.
   
6. [Font Awesome](https://www.fontawesome.com/)
   * Used to provide the icons in the 'Services' section of the home page, as well as the social media icons in the footer.
   
7. [TinyJPG](https://www.tinyjpg.com/)
   * Used to compress image files used on the website to speed up loading times.
   
8. [Balsamiq](https://www.balsamiq.com/)
   * Software used to create wireframes.
   
9. [Autoprefixer](https://www.autoprefixer.github.io/)
   * Used to ensure cross browser validity for CSS.
   
### Testing
The HTML code has been checked against the [W3C Markup Validator](https://www.validator.w3.org/) and the CSS against the [W3C CSS Validator](https://www.validator.w3.org/) with any issues highlighted by the validators fixed. The code contains no validity issues.

#### Testing against user requirements (as listed in UX section)
As a first time user of this website, I want to:
* Immediately understand how to navigate the website.
  * The website follows common design features found throughout most websites. The navigation bar can be found at the top of every page, and clearly lists the areas of the website that the user can navigate to and what those areas are for.
  
* Understand the purpose of the website.
  * Upon arriving at the home page, the user is presented with a list of services offered ('FACE PAINTING - ECO GLITTER - BODY ART') by the business as well as examples of work in the form of the 3 images (1 on mobile). Directly below this is a short summation of what the business does in the 'About' section.

* See examples of previous work.
  * This requirement is met immediately upon arriving at the home page with the three images acting as a hero image (or 1 large image on mobile). This is further met by the gallery page which contains 18 images exhibiting a wide range of previous work.

* Understand what services are offered.
  The home page consists of very little in the way of copy, except for short consise paragraphs regarding the business' services and types of events catered for.

* Gain an understanding of costs.
  Prices for childrens parties are clearly detailed in the 'Services' section - seperate to the rest of the text and in bold. The other types of event listed in the services section are not possible to give prices for without further clarifications from the potential client. Where this is the case, a clear link to the 'Contact' page is offered.

* Gain an undertanding of the company to attain whether they are right for my needs. 
  * Again, the 'Home' page offers short and clear copy that summarises the business' ethos and services.

* Find links to social network channels to find reviews and updates.
  * As is common in web design, the footer contains links to the business' social network pages.

* Quickly find contact details.
  * The contact details are quickly found through the navigation bar link for 'Contact' as well as several links to the contact page throughout the copy on the 'Home' page. As well as this, the email address for the business can be found along with social network links in the footer.

As a returning user of this website, I want to:
* Quickly find contact details.
  * The contact details are quickly found through the navigation bar link for 'Contact' as well as several links to the contact page throughout the copy on the 'Home' page. As well as this, the email address for the business can be found along with social network links in the footer.

* Check for updated examples of work.
  * This is easily achieved by visiting the 'Gallery' page via the navigation bar.

* Check for updated costs.
  * Prices for childrens parties are clearly detailed in the 'Services' section - seperate to the rest of the text and in bold. The other types of event listed in the services section are not possible to give prices for without further clarifications from the potential client. Where this is the case, a clear link to the 'Contact' page is offered.

#### Manual testing of all elements thoughout the website
The following tests were all completed using the following web browsers and hardware:

Web Browsers:

* Google Chrome - Tested on Macbook Pro 2016 (13"), Microsoft Surface 3 (15"), Huawei P Smart 2019, Samsung Galaxy A6
* Microsoft Edge 
* Mozilla Firefox 
* Apple Safari -tested on iPad 7th generation 2019 (10.2") and Macbook Pro 2016 (13")

web browsers. As well as this, the website has been tested using a

thank you modal bug

### Deployment

### Credits
