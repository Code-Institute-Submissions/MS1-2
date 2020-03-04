# Injectable Inc
This website is created for a small business who offer non-surgical aesthetic procedures to enhance, or gain desirable features. The business offers Botox fillers to accentuate, define, or even smooth the appearance of facial features (Nose, Cheekbones, Jawline, and Lips). The fillers are injected by Injectable Inc’s own aesthetic professionals. My task at hand was to create a Front-End responsive website using HTML and CSS as basics, based on the principles of the user experience, accessibility, and responsivity. 
The framework I have used is based on bootstrap 4, there was an array of different concepts and design templates which made constructing the website simple. However, manipulating the basic structure, using CSS and some HTML got a bit tricky. I used inline styling, and also CSS styling to target specific elements of the website. I used the tutorials from Code Institute, I referred to Stack Overflow, W3schools a lot during the construction of Injectable Inc. 

## UX
As a user I would want to feel an attraction and a buzz about the website, as changing any facial features you need to be confident that the person holding the needle understands your vision of you; having a website which appeals to you is the first representation of the business. 
### The colour scheme
Considering the general aesthetic industries colour scheme 9/10 is clinical. As Injectable Inc is a non-surgical cosmetic business, I felt it was appropriate to move away from that ‘white’ theme and dress the site with a theme that would appeal to our target audience (18-40yr olds). The fluid background I used from ‘shutterstock’, had a mix of hologram colours, which I considered to be modern, and edgy, I felt that this mix of colours opened up many options od a block colour I can pair with it. Originally i decided to use an opaque pink, but this caused issues with the mobile view drop down menu, as the writing wasn’t user friendly. I eventually chose a lilacy-pinky shade: “rgba(243, 157, 240, 0.96);”, I darkened the dept of the shade but still felt it was appropriate to give a marginal accent of opacity, to keep with the ‘fluid’ theme.
The pages following on from ‘Procedures’ also display a splash of colour from the same icecream palette. I also used some black styling to add to the modern, edge of the appearance, these black hyperlinked headings have a ‘hover’ property which reverts to pink upon selection.
The home page has a picture of a lady licking a lollypop, the features the business offers services for are visible, and hold a visual message for the user. There is a short inviting paragraph which pose questions to the user about their thoughts on themselves, by this point the users who know what they want would click ‘enquire’ and register their interest on a pop-up form. 
The business logo sits on the left of the navbar which reminds the customer of what business they are looking at, and adds to the professional look of the site. On the right of the navbar there are 3 visible links ‘home’, ‘procedures’, and ‘contact us’. Procedures drop down into a further 3 links for the areas the business specialises in (Lips, Nose, Cheekbone & Jawline Fillers).
As the user scrolls down the home page they are presented with 3 images, which are each headed with the procedures and represent the regions of application Lip, Nose, Jaw & Cheek Filler). A small footer gives a vague description of what each procedure does.
As the user scrolls further down they are met with an interactive gallery, which can be enlarged once clicked on. This showcases work of previous clients, and reinforces trust in the business as their portfolio of previous customers, and their procedures of ‘before and after’ images score quiet highly especially if the user is planning on using a procedure to alter their face. 
Further down there are reviews from customers who have had procedures, and what they have to say about their experience. This reassures the user that the business has been trialled and tested, and is an opportunity for the business to show their customer service side of things, as having people skills goes a long way. The nature of the business is such that it may attract people who are self-conscious but are scared of needles; people who have a very low pain threshold, and people who just can’t visualise the results and need someone to share their concerns with. Knowing that you are being valued as a customer could be the tipping point of the customer making and enquiry.
There’s banner of 0% finance, which speaks to the customer directly, this opens up an option of buying into the product and paying later or in instalments, which eases the financial pressures of our target audience. students who want to look good, but cannot afford to; a special occasion the user wants to look good and have the confidence for.
By this point, questions such as ‘how do I do this? What will happen after my enquiry? Will arise. The final paragraph is based on the customers journey from the moment they get in contact with the business, and the steps that follow. 
The final step on this page is the-call-to-action button, which would dial into the business.
And beneath this, for ongoing marketing purposes, and further information for our user, there are social media icons which are hyperlinked to each site. The user has the option to visit these and potentially follow, as a business this would also earn exposure and the users followers would see regular updates from Injectable Inc, and would be curious enough to visit their sites and also follow, eventually having a ripple effect.
Wireframes were created using ‘Balsamiq Mockups 3’- this allowed me to create a computer and a mobile based design. The mobile design doesn’t differ much from the computer-based design, apart from reduced content which gives the user the important content, in a simple and easy to read manner.
## Features
For consistency I have kept the footer and the header the same across the pages, the index page requires scrolling down to, but the other pages contain just the right amount of information for both the header and footer to be visible. Hover elements have been added to the hyperlinked aspects, I have chosen to use the ‘buzz’ of buttons to create an element of excitement, and to go with the theme of being ‘fun’. The larger button at the bottom was too big to set to buzz, as it made the page look messy and that there was too much going on, I countered this with a vertical wobble; so its not too different from the buzz but a discreet wobble made the page look neater and in control.
### Index.html
The use of a modal with a form, which is linked to the enquiry button as the first visual page, along with another call-to-action modal activated with a button above the footer. Both modals were taken from Bootstrap4 templates, and customised to suit the website needs. The modal links with the button by embedding the ‘data-target=“enquiryModalCenter”’ into the <button></button> tag, and linking this to the modal using a ‘id=“enquiryModalCenter”’, tags are also used to .
I have used fancyBox.com to allow my gallery images to opens up to a whole page, when clicked. I neatened the appearance of the fancybox gallery using bootstrap grid styling. Where I followed the rule of thumb ‘container>row>column’.

### Lip-filler.html, Cheekjaw-filler.html, Nose-filler.html, contact-us.html

This page was created to hold further information on a procedure. For ease of use, and to maximise the UX I wrapped the button and the footer and gave it a element of ‘fixed-bottom’, so the footer and the button would hold their position on the screen. If the user decided that the procedure is for them, they are able to get in contact immediately with just one click Call Now (call-to-action) button.
For the mobile version of this page I used @media query (display: none) to hide the image, I found that this gave the mobile version a stream-lined and a neater finish. Leaving the page to give the information it needs to.

## Technologies used
Languages:
HTML- hypertext markup language- used to build basic structure of a website.
CSS- cascading style sheets- used to style HTML
Bootstrap4- HTML CSS JS library 
JQuery- implemented in the templates used from fancy box
Font Awesome- used for the social media icons
Google Fonts- used to apply the style of font choice (Raleway)

## Testing:
HTML validator check- complete- https://validator.w3.org/#validate_by_input
<script type=”text/javascript”>
 
 this appeared as a unnecessary JS resource- however this was interlinked with Fancybox’s JS script.
Aria label also flagged up in the modal template used for the ‘Call Now’ button.
Font Awesome cdn link attribute was also flagged up as bad practice. 
CSS validator check complete- https://jigsaw.w3.org/css-validator/validator
-webkit-background-size, -moz-background-size, -o-background-size all appeared as ‘unknown vendor extensions’.
Device	Images	Links	Navbar
Desktop	yes	yes	yes
Laptop	yes	yes	yes
Ipad	yes	yes	yes
Iphone x	yes	yes	yes
Iphone 5	yes	yes	Yes- but some links fail
Chrome	yes	yes	yes
Safari	yes	yes	yes
Explorer	yes	yes	yes

I have found the website appears to be smaller, so it appears to be zoomed out income, opposed to Explorer, where the text and the image formatting is much larger in size.

## Deployment,
This website was deployed on GitHub Pages. 
The link: https://fudge88.github.io/MS1/index.html

## Credits:
###Content
The contents were created by myself. Some parts of the descriptions used were collected from Wikipedia.

###Media
Images for background and theme taken from Shutterstock:
Background.JPG Lipscandy.JPG Lips-candy.JPG
Productlp.JPG productnf.JPG productcf.JPG productcontact.JPG

Images to create the gallery were taken from Pinterest:
Jaw1.JPG Jaw2.JPG Jaw3.JPG Jaw4.JPG 
Lips1.JPG Lips2.JPG Lips3.JPG Lips4.JPG
Nose1.JPG Nose2.JPG Nose3.JPG Nose4.JPG

###Acknowledgments
Mentor Ignatius for giving me a better understanding of what the UX would mean (in lay man’s terms the less the clicks the better), also advised me to use ‘Fancybox’ for my gallery. 
Thank you for your support.
The tutor me staff at code institute who spent a lot of time, trying to guide me without giving me the answers!
I also referred into using some of the following resources available online, to help me with the content and customisation of Injectable Inc.
W3schools.com
Stackoverflow.com
Fancyapps.com (Fancybox)
Youtube.com 
Css-tricks.com
Quora.com
Codepen.io
Freecodecamp.org
Getbootstrap.com
I received inspiration for this project through the current market and demand for such products, as its readily available to anyone. I used mya.co.uk for inspiration when it came to some styling aspects.







