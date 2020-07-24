# User Story Testing

_1. As a first-time listener, I want to listen to the band's music._
 - **Option One**
   - Select the [Music](https://kiehozero.github.io/weightbearer/music.html) button on the navigation bar on any page;
   - On this page, each song is represented individually, and users can listen by click on the icon of their preferred streaming service.

 - **Option Two**
   - Users can access the band's latest record by scrolling to the 'New Record Out Now!' post on the [home page](https://kiehozero.github.io/weightbearer/index.html);
   - Click on the icon of preferring streaming service.

_2. As a music writer, I want to learn about the band and expose them to a wider audience._
 - Select the [About](https://kiehozero.github.io/weightbearer/about.html) from the navigation bar of any page;
 - Scroll to view a brief history of the band and an short profile of each band member.

_3. As a promoter, I want to check the band's availability for shows that I am booking._
 - Select the [Shows](https://kiehozero.github.io/weightbearer/shows.html) button on the navigation bar of any page;
 - Scroll to view the band's current itinerary;
 - Select the [Contact](https://kiehozero.github.io/weightbearer/contact.html) button on the navigation bar on any page;
 - Scroll to the 'Got a Question for Us?' heading and complete the contact form;
 - Select the 'promoter' query button and click the 'Submit' button.

_4. As a long-time fan, I want to support the band by purchasing merchandise._
 - Click the [Shop](https://kiehozero.github.io/weightbearer/shop.html) button on the navigation bar of any page;
 - This page contains a range of merchandise.
 
_5. As an event-goer, I want to buy tickets to a show and find out where the venue is._
 - Select the [Shows](https://kiehozero.github.io/weightbearer/shows.html) button on the navigation bar of any page;
 - Scroll to view the band's current itinerary;
 - Click the ticket icon beneath each show to be re-directed to the relevant ticketing partner;
 - Click the map icon beneath each show to be re-directed to a Google Maps link for the venue.
 
_6. As a musician, I want to find out what instruments the band are using._
 - Click the [About](https://kiehozero.github.io/weightbearer/about.html) button on the navigation bar of any page;
 - Each member profile contains a brief overview of theirs instruments and/or amplification.
 
_7. As a long-time fan, I want to keep in touch with the band by following them on social media._
 - **Option One**
   - Users can scroll to the bottom of any page to view links to the band's social media pages.

 - **Option Two**
   - Click the [Contact](https://kiehozero.github.io/weightbearer/about.html) button on the navigation bar of any page;
   - Scroll down to the 'Want to Stay in Touch?' heading to view links to each of the band's social media pages.
 
_8. As a long-time fan, I want to keep in touch with the band by subscribing to their mailing list._
 - **Option One**
   - Scroll to the bottom-right of any page and enter an e-mail address in the form provided.

 - **Option Two**
   - Click the [Contact](https://kiehozero.github.io/weightbearer/about.html) button on the navigation bar of any page;
   - Scroll down to the 'Subscribe to our newsletter!' heading;
   - Enter an e-mail address in the form provided.
 
_9. As a music writer, I want to contact the band regarding reviews or interviews._
 - Select the [Contact](https://kiehozero.github.io/weightbearer/contact.html) button on the navigation bar on any page;
 - Scroll to the 'Got a Question for Us?' heading and complete the contact form;
 - Select the 'press' query button and click the 'Submit' button.
 
_10. As a label owner, I want to contact the band regarding releasing some of their material._
 - Select the [Contact](https://kiehozero.github.io/weightbearer/contact.html) button on the navigation bar on any page;
 - Scroll to the 'Got a Question for Us?' heading and complete the contact form;
 - Select the 'label' query button and click the 'Submit' button.

# Bug Fixes

Given that this is the first website I've built without the use of guidance, there were inevitably going to be plenty of bugs for me to wrestle with. I was surprised at how many I was able to fix simply by editing code on the fly and re-loading, but a few proved more frustrating and required a visit to W3Schools, Bootstrap Shuffle or Stack Overflow, links to which can be found in the credits section below.

- One early problem I noticed was that photography and banners were loading when running inside the Gitpod 8080 server, but then were showing the alt tag once I loaded from Github pages. I found that this was an navigation issue, namely adding one point instead of two to the internal address that locates the storage location. My mentor pointed this out when he loaded remotely from GitHub Pages, thus teaching me a valuable lesson about testing across devices and browsers!
- I spent an awfully long time trying to incorporate banners onto each page. The banners I initially used contained lots of text (i.e. the band name) or photography, and I had toyed around with making multiple size versions of images to account for different screensizes. Ultimately I gave up and figured it was hopeless until I realised that the band had sent me plenty of very hi-res (3000px wide!) variations of their logo, so I cropped these using Pixlr and they made the perfect banners. In hindsight I probably wasted more time on this issue than pretty much any other, but I will have to look at it as a very useful, but painful, lesson. 
- In the CSS stylesheet there is a long comment regarding navbar font colouring issues, whereby I spent far too much time trying to unpick the interactions and specificity between my own CSS and the code used to create Bootstrap classes. Ultimately I learnt that if in doubt, simply default to the Bootstrap class styling, and be mindful of adding your own styling to override Bootstrap elements without adding comments as it can become very confusing to try and work backwards without it.
- I had a lot of trouble working out how to override the default colour of the drop-down menu button, but [Stack Overflow](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color#42587673) provided a solution in the way of replacing the Bootstrap class with a Font Awesome icon and styling this separately, which enabled me to sidestep another round of unpicking Bootstrap class parameters.
- On a related note, I had included the jQuery code for the drop-down meneus at the bottom of each html script as per the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) page, but Chrome's developer tools flagged this as technically incorrect, and that I should include it before the Bootstrap script at in the head of each page.
- A visit to [W3Schools](https://www.w3schools.com/cssref/css_units.asp) allowed me to fix the problem of img elements overflowing on smaller devices. I changed img widths from px to % values, allowing these elements to be sized based on their parent elements, which were ultimately determined by the Bootstrap grid system.
- A similar sizing issue affected the background images on each page's container stretching to the length of the page's content, which becomes a significant issue once you are on a mobile view with 13 col-sm-12 divs. Luckily this problem had a much quicker solution; I simply looked back at the code for the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) project and changed the background to fixed.
- All social media links and music links are functioning. I've also tested links from the events page, which are set to the specific location of each venue, although the event and ticket pages are currently linking only to the Ticketmaster and Facebook homepages as all gigs are cancelled until further notice due to Covid-19 restrictions.
- I tested this site primarily on Firefox but also Chrome and Edge, taking advantage of the screen size options to test using iPad, Samsung Galaxy and Kindle Fire. I also tested the site on my own Huawei device. Once I start a new project I'll be working in Chrome as it seems to flag up errors (see jsQuery issue above) and is a bit stricter in enforcing code than Firefox. 
- W3Schools' guide on Bootstrap's [media class](https://www.w3schools.com/Bootstrap/bootstrap_media_objects.asp) allowed me to get out of a CSS hole of my own making in horizontally aligning pictures and text in the press section. I then had an issue of not being able to get the h2 above them to stay above it, but [Bootstrap Shuffle](https://bootstrapshuffle.com/classes/sizing/w-100) provided the class I needed to solve that
- In terms of look and feel, the site is similar across all browsers. The tablet and desktop views are almost identical, while mobile devices always drop into col-12 formatting. There were a couple of fixes that were required to get this up and running across multiple devices and browsers, most notably the jsQuery issue above. There were also some issues around how the mailing list form in the footers was floating. The social media links in the footer also started to crunch around the 930px mark so I just upped the max-width on my tablet-specific CSS. 

    [Bootstrap Creative](https://bootstrapcreative.com/how-to-center-a-div-horizontally-in-bootstrap-4/) provided the mx-auto Bootstrap class as a quick fix to center-align divs
    /* .nav-link.active appears to be a Bootstrap class that was causing me an immense amount of distress in getting
    this navbar to style correctly. I realised there was no whitespace in the middle of the tag, then realised it is 
    coloured using rgb, which is how I knew I hadn't written it (I've used hex for font colouring all the way 
    through). I write this lengthy comment only to express my joy at finally solving this! */

    In tablet view there is some whitespace beneath the footer of the contact page that I can't seem to get rid of.


# Outstanding Issues

- I've been unable to get around the Bootstrap grid system to have my five boxes perfectly aligned on the index page, the result being that on a desktop the welcome banner and the press banner are slightly wider than the three middle boxes. I suspect this is because I've used a combination of custom percentage column widths and custom padding and margin widths;
- The h2 elements on shows.html begin to overlap around 1000px if the word is too long (namely 'Manchester'), but is working fine once in tablet or mobile view.


# Validation

Each page was directly inputted into the [W3C HTML Validator](https://validator.w3.org/#validate_by_input) to check that the markup used passed W3C standards. The CSS style sheet was directly inputted into the [W3C CSS Validator](http://jigsaw.w3.org/css-validator/#validate_by_input). The results can be seen below.

## Issues raised

- In validator testing it was found that I had combined multiple meta properties into a single tag, and that the name property had to come first in any tag it was used in. This has now been rectified on all pages.
- In the header, the img in the navbar-brand anchor tag did not contain an alt property. This has now been rectified on all pages to read "Weight Bearer logo".
- In the footer, I had used a paragraph element to sit around the mailing list form. This has now been replaced with a div element.

## Validation Proof

- about.html validation

![Contact page validation](/assets/images/validation/about-valid.PNG)

- contact.html validation

![Contact page validation](/assets/images/validation/contact-valid.PNG)

- index.html validation

![Contact page validation](/assets/images/validation/index-valid.PNG)

- music.html validation

![Contact page validation](/assets/images/validation/music-valid.PNG)

- shop.html validation

![Contact page validation](/assets/images/validation/shop-valid.PNG)

- shows.html validation

![Shows page validation](/assets/images/validation/shows-valid.PNG)

- style.css validation

![CSS page validation](/assets/images/validation/css-valid.PNG)

![CSS page validation](/assets/images/validation/css-valid-2.PNG)