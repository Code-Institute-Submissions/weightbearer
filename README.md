# Weight Bearer

![Weight Bearer Logo](/assets/images/icons/text-stack.png)

Welcome to my user-centric front-end development milestone project. For this project I chose to create a [website](https://kiehozero.github.io/weightbearer/) for a friend's band, Weight Bearer, a metal band based in Lancashire, England. Luckily for me the band actually wish to use this as their online home, so this project might technically count as my first (unpaid) commission!
 

## UX

I have created a website which centralises resources that would otherwise be spread across a number of social media websites. The band currently uses Bandcamp for hosting and selling music, Spotify and YouTube for streaming and Facebook for publicity and events.

### Styling

A wireframe for this project is included in the repository, with [desktop](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Desktop%20Wireframes.pdf), [tablet](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Tablet%20Wireframes.pdf) and [mobile](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Mobile%20Wireframes.pdf) versions.

I used the following hex colours, selecting using [Pixlr](https://www.pixlr.com):

- #f2f2f2 is an off-white colour that is used in the band's monochrome diamond icon;

- #693288 is a shade of purple that is used in the band's colour diamond icon. I also created a version of the band's font logo to match this colour using Pixlr.

- For the lead font I chose Merriweather Sans as it most closely matched the font that the graphic designer commissioned by the band had used. This font only really worked in upper case, so I chose Poppins as a secondary font just for h3, p and span elements.

### User Stories

1. As a first-time listener, I simply want to hear the band's music.
2. I write a music blog and want to interview the band and give them some exposure to a wider audience.
3. I'm a promoter booking shows for later this year, I want to check the band's availability.
4. I love this band's music and I want to support the band by purchasing CD and a t-shirt.
5. I want to buy tickets to a show and find out where the venue is.
6. I really like the guitar sound this band uses, can I find out what gear they are using?


## Features

### Existing Features

- Index - The landing page includes a short biography of the band, as well as prominent links to music, a shop and a diary of live events, in line with the main user stories;
- Music - Contains links to each of the band's releases so far. I've included the album artwork for each as a thumbnail, which is inspired by the presentation style used by Spotify and Bandcamp, focusing primarily on individual songs;
- Shop - Contains the band's merchandise. These are currently in production so I've used dummy images for these;
- Shows - Contains a diary of upcoming shows, with a dummy link to Facebook events as shows are obviously cancelled given current circumstances;
- About - A short history of the band, its members, and their instruments;
- Contact - A basic form that allows people to send a message to the band, as well as selecting the reason for enquiry.

### Features Left to Implement

- I've included a dummy contact form and shop that will be live once I've completed the JavaScript module. I have no doubt that completing that module will throw up a million ideas for this project, but I'll be using this README as a guide of what to get started on.
- A really frustrating part of this project was in the effect of borders and margins on Bootstrap grids. I actually took a few days off because I was making zero progress towards my goal, I had just lost all perspective and was in danger of stalling. Bootstrap is obviously a powerful and complex tool so I'd like to re-visit the main structure of the index page once I'm more comfortable with how things work.
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

### User Story Testing

1. As a first-time listener, I simply want to hear the band's music.
 - The Music page contains Spotify, YouTube and Bandcamp links to all of the band's releases.
2. I write a music blog and want to interview the band and give them some exposure to a wider audience.
 - Journalists and editors who wish to interview the band can complete the form on the Contact page.
3. I'm a promoter booking shows for later this year, I want to check the band's availability.
 - The Shows page contains all of the band's upcoming live events, to contact the band fill out the form on the Contact page.
4. I love this band's music and I want to support the band by purchasing CD and a t-shirt.
 - The Shop page contains a range of merchandise containing the band's logo and artwork.
5. I want to buy tickets to a show and find out where the venue is.
 - The Shows page contains links to Facebook events, ticketing websites and a Google Maps location pin for each venue.
6. I really like the guitar sound this band uses, can I find out what gear they are using?
 - The About section contains a short biography of each member plus any instruments and amplification that they are currently using.

### Bug Fixes

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

### Outstanding Issues

- I've been unable to get around the Bootstrap grid system to have my five boxes perfectly aligned on the index page, the result being that on a desktop the welcome banner and the press banner are slightly wider than the three middle boxes. I suspect this is because I've used a combination of custom percentage column widths and custom padding and margin widths;
- In tablet view there is some whitespace beneath the footer of the contact page that I can't seem to get rid of;
- The h2 elements on shows.html begin to overlap around 1000px if the word is too long (namely 'Manchester'), but is working fine once in tablet or mobile view.

### Cloning

Assuming you already have Git [installed](https://git-scm.com/download/), anybody can clone this repository by opening Windows command prompt and using the command 'cd' followed by the directory you wish to store the repository in.

Go to the top of the [repository](https://github.com/kiehozero/weightbearer) and click the green Code drop-down button. Copy the [link](https://github.com/kiehozero/weightbearer.git) provided, then return to Command Prompt and type 'git clone' followed by the copied address.

For an in-depth guide to cloning repositories, click [here](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/).

## Deployment

I used GitHub as the host for this project, and Gitpod to write it, using just one branch. I took part in the Code Institute hackathon while completing this project, learning a lot about the benefit of branches from the more experienced students in our team. In hindsight I would have used branches from the start of this project but I already had the major structure and feel of the site completed at that point.

All of the images used on the website except for the logos for the external press links are hosted within the Gitpod repository. I had initially included mp3s on the music page so users could listen to the band directly within their browser, but my mentor advised me that this adds a large amount of content to the page for not much benefit, especially because I've linked to Spotify, YouTube and Bandcamp.


## Credits

### Content
- The header and footer formats were borrowed from existing CI course content, namely the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) and [resume](https://github.com/kiehozero/resume) projects. The links are my own versions of each project but are more or less identical to the walkthrough.
- Social media icons are provided by [Font Awesome](https://fontawesome.com/), while the fonts themselves come from [Google Fonts](https://fonts.google.com/).
- Bootstrap's [navbar documentation](https://getbootstrap.com/docs/4.0/components/navbar/) helped me break down and customise the navigation classes they have;
- As mentioned about, W3Schools' guide on Bootstrap's [media class](https://www.w3schools.com/Bootstrap/bootstrap_media_objects.asp) and [Bootstrap Shuffle](https://bootstrapshuffle.com/classes/sizing/w-100) helped me better understand element positioning;
- [MakeAReadMe](https://www.makeareadme.com/) is an excellent resource for putting together a readme, although I largely used the [Code Institute readme template](https://github.com/Code-Institute-Solutions/readme-template);
- The [Stormotion guide](https://www.stormotion.io/blog/how-to-write-a-good-user-story-with-examples-templates/) helped me put together the user stories I used for this project in a consistent format.

### Media
- Photography and graphic designs were provided directly by the band, with the graphics being designed by [Secret Industries](https://www.instagram.com/secretindustries/).

### Acknowledgements

- The band themselves had mentioned needing a website previously so I'm happy they let me use them as a guinea pig in putting this together.
- My mentor [Precious](https://github.com/precious-ijege) helped this project seem a bit more manageable after I'd come up with my initial ideas. He pointed out what he'd expect using his experience of similar previous projects, and it was good to get that professional perspective after I'd researched other band websites of varying qualities.