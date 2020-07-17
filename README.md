# Weight Bearer

Welcome to my user-centric front-end development milestone project. For this project I chose to create a [website](https://kiehozero.github.io/weightbearer/)] for a friend's band. The band is called Weight Bearer, a metal band based in Lancashire, England. Luckily for me the band actually wish to use this as their online home, so this project might technically count as my first (unpaid) commission!
 

## UX

I've created a website which centralises resources that would otherwise be spread across a number of social media websites. The band currently uses Bandcamp for hosting and selling music, Spotify and YouTube for streaming and Facebook for publicity and events.

### Styling Decisions

I used the following hex colours, selecting using [Pixlr](https://www.pixlr.com):

- #f2f2f2 is an off-white colour that is used in the band's monochrome diamond icon;

- #693288 is a shade of purple that is used in the band's colour diamond icon. I also created a version of the band's font logo to match this colour using Pixlr.

- For the lead font I chose Merriweather Sans as it most closely matched the font that the graphic designer commissioned by the band had used. This font only really worked in upper case, so I chose Poppins as a secondary font just for h3, p and span elements.

### User Stories

- LISTEN: Users who want to listen to the band's music can either listen using the mp3s on the Music page or re-direct to Spotify, Bandcamp or YouTube.

- WATCH: User who want to see the band live can view the Shows page, which takes users to a Facebook event, ticket page and venue location for each show. The shows currently listed are dummies as shows are currently prohibited due to Covid-19 regulations.

- PURCHASE: Users who wish to purchase band merchandise can visit the Shop page. This page is a dummy until I have completed the Javascript module.

- CONTACT: Users who need to contact the band can complete the form contact form and specify their request, as well as their .

A wireframe for this project is included in the repository, with [desktop](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Desktop%20Wireframes.pdf), [tablet](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Tablet%20Wireframes.pdf) and [mobile](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Mobile%20Wireframes.pdf) versions.


## Features

### Existing Features

- Index - The landing page includes a short biography of the band, as well as prominent links to music, a shop and a diary of live events, in line with the main user stories;
- Music - Contains links to each of the band's releases so far. I've included the album artwork for each as a thumbnail, which is inspired by the presentation style used by Spotify and Bandcamp, focusing primarily on individual songs;
- Shop - Contains the band's merchandise, namely their first record, a t-shirt and a sticker pack. These are currently in production so I've used dummy images for these;
- Shows - Contains a diary of upcoming shows, with a dummy link to Facebook events as shows are obviously cancelled given current circumstances;
- About - A short history of the band, its members, their influences and instruments;
- Contact - A basic form that allows people to send a message to the band, as well as selecting the reason for enquiry.

### Features Left to Implement
- I've included a dummy contact form and shop that will be live once I've completed the JavaScript module. I have no doubt that completing that module will throw up a million ideas for this project, but I'll be using this README as a guide of what to get started on.
- A really frustrating part of this project was in the effect of borders and margins on Bootstrap grids. I actually took a few days off because I was making zero progress towards my goal, I had just lost all perspective and was in danger of stalling. Bootstrap is obviously a powerful and complex tool so I'd like to re-visit the main content of the index page once I'm more comfortable with how things work.
- My initial wireframe included a slightly more advanced grid system than I ultimately implemented, a grid of four windows and a separate side-column. I'd like to bring this in to save other content being hidden at the bottom of the page; ideally there would be no scrolling required on the home page unless being viewed on a mobile device.
- I'd like to include a live Instagram feed at the side of the home page just to break up the content.
- After lots of pain and suffering causing by overwriting Bootstrap classes with my own CSS and the myriad issues this brings up (see testing section!), I'd like to conduct a review of my CSS styling to see if there are further efficiencies I can make with a better understanding of Bootstrap.


## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS3](https://en.wikipedia.org/wiki/CSS3)

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap's grid framework helped me bring my initial wireframe ideas to life, while [Font Awesome](https://fontawesome.com/)'s icons and [Merriweather Sans](https://fonts.google.com/specimen/Merriweather+Sans) made things look that bit more professional.

- [Gitpod](https://www.gitpod.io)
    - I'm not cocky enough to start using another editor so I've stuck with the trusty Gitpod!

- [Balsamiq](https://www.balsamiq.com)
    - Balsamiq was recommended to me by my mentor Precious Ijege as a good drafting tool, and it took me very little time to get to grips with it. I will definitely be using this again in the future.

- [Pixlr](https://www.pixlr.com)
    - Pixlr is a great free software package that enabled me to quickly pick out hex colors and edit existing material that the band provided me with.


## Testing

>>> In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

>>> Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

>>> 1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

>>> In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

>>> You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

>>> If this section grows too long, you may want to split it off into a separate file and link to it from here.

- one early problem I noticed was that photography and banners were loading when running inside the Gitpod 8080 server, but then were showing the alt tag once I loaded from Github pages. I found that this was an navigation issue, namely adding one point instead of two to the internal address that locates the storage location.
- I spent an awfully long time trying to incorporate banners onto each page. The banners I was using contained lots of text (i.e. the band name) or photography, and I had toyed around with making multiple size versions of images to account for different screensizes. Ultimately I gave up and figured it was hopeless until I realised that the band had sent my plenty of very hi-res (3000px wide!) variations of their logo, so I cropped these using Pixlr and they made the perfect banners. In hindsight I probably wasted more time on this issue than pretty much any other, but I will have to look at it as a very useful, but painful, lesson. 
- I had a lot of trouble working out how to override the default colour of the drop-down menu button, but [Stack Overflow](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color#42587673) provided a solution in the way of replacing the Bootstrap class with a Font Awesome icon and styling this seperately, which enabled me to sidestep another round of unpicking Bootstrap class parameters.
- testing of all external links, social media, mp3s, etc.
- integrity of all images (https://www.w3schools.com/cssref/css_units.asp), I changed img widths from px to % values to prevent images from overflowing on smaller screensizes
- testing on multiple devices and browsers, footers are still not working properly on Kindles but this is because they have a slightly wider screen (800px) than what Bootstrap classes are subdivided to
- footers did not initially align properly, this was due to the mailing list column being set to col-sm-12 col-lg-4 and the other two columns being col-sm-12 col-md-4
- go through github commit history to find issues
- mention big comment that helped solve navbar font colouring issue
Clone: click green ‘Code’ button at the top of the repo and copy link, google the rest
- test whole site (wider screen, use work monitors as well) without developer tools and on different browsers (Chrome, Huawei Mobile, Edge)

- To do:
--- about: footer on tablet view still unaligned
--- contact: whitespace underneath footer on ipad view
--- index: border match issues, needs more uniform picture styling?
--- music: 
--- shop: 
--- shows: text overflow on tablet text;
--- site: navbar-dropdown


## Deployment

I used GitHub as the host for this project, and Gitpod to write it, using just one branch. I took part in the Code Institute hackathon while completing this project, learning a lot about the benefit of branches from the more experienced students in our time. In hindsight I would have used branches from the start of this project but I already had the major structure and feel of the site completed at that point.

All of the images used on the website except for the logos for the external press links are hosted within the Gitpod repository. I had initially included mp3s on the music page so users could listen to the band directly within their browser, but my mentor advised me that this adds a large amount of content to the page for not much benefit, especially because I've linked to Spotify, YouTube and Bandcamp.

>>> In addition, if it is not obvious, you should also describe how to run your code locally. ADDING CLONING INFORMATION HERE


## Credits

### Content
- The header and footer formats were borrowed from existing CI course content, namely the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) and [resume](https://github.com/kiehozero/resume) projects. The links are my own versions of each project but are more or less identical to the walkthrough.
- Social media icons are provided by [Font Awesome](https://fontawesome.com/), while the fonts themselves come from [Google Fonts](https://fonts.google.com/).
- Bootstrap's [navbar documentation](https://getbootstrap.com/docs/4.0/components/navbar/) helped me break down and customise the navigation classes they have;
- W3Schools' guide on [Bootstrap's media class](https://www.w3schools.com/Bootstrap/bootstrap_media_objects.asp) allowed me to get out of a CSS hole of my own making in horizontally aligning pictures and text in the press section. I then had an issue of not being able to get the h2 above them to stay above it, but [Bootstrap Shuffle](https://bootstrapshuffle.com/classes/sizing/w-100) provided the class I needed to solve that;
- [MakeAReadMe](https://www.makeareadme.com/) is an excellent resource for putting together a readme, although I largely used the [Code Institute readme template](https://github.com/Code-Institute-Solutions/readme-template).

### Media
- Photography and graphic designs were provided directly by the band, with the graphics being designed by [Secret Industries](https://www.instagram.com/secretindustries/).

### Acknowledgements

- The band themselves had mentioned needing a website previously so I'm happy they let me use them as a guinea pig in putting this together.
- My mentor [Precious](https://github.com/precious-ijege) helped this project seem a bit more manageable after I'd come up with my initial ideas. He pointed out what he'd expect using his experience of similar previous projects, and it was good to get that professional perspective after I'd researched other band websites of varying qualities.