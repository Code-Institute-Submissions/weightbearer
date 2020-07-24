# Weight Bearer

![Weight Bearer Logo](/assets/images/icons/banner-text-line-900px.png)

Welcome to my user-centric front-end development milestone project. For this project I chose to create a [website](https://kiehozero.github.io/weightbearer/) for a friend's band, Weight Bearer, a metal band based in Lancashire, England. Luckily for me the band actually wish to use this as their online home, so this project might technically count as my first (unpaid) commission!
 

## User Experience

I have created a website that centralises resources that would otherwise be spread across a number of social media websites. The band currently uses Bandcamp for hosting and selling music, Spotify and YouTube for streaming and Facebook for publicity and events.

### Styling

A Balsamiq wireframe for this project is included in the repository, with [desktop](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Desktop%20Wireframes.pdf), [tablet](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Tablet%20Wireframes.pdf) and [mobile](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Mobile%20Wireframes.pdf) versions.

I used the following hex colours, selecting using [Pixlr](https://www.pixlr.com):

- #f2f2f2 is an off-white colour that is used in the band's monochrome diamond icon;

- #693288 is a shade of purple that is used in the band's colour diamond icon. I also created a version of the band's font logo to match this colour using Pixlr.

- For the lead font I chose Merriweather Sans as it most closely matched the font that the graphic designer commissioned by the band had used. This font only really worked in upper case, so I chose Poppins as a secondary font just for h3, p and span elements.

- I have tried to keep a uniform template through the site in order to create a sense of familiarity when new users are navigating. Each page, across all devices, contains a navigation bar and an image banner in the header, and a footer with links to social media channels and a subscription form for their mailing list. I have removed this information from the footer on the Contact page as it features more prominently in the main content of that page.

### User Stories

Testing for each of the below user stories is included within the [testing log](https://github.com/kiehozero/weightbearer/blob/master/TESTING.md).

1. As a first-time listener, I want to listen to the band's music;
2. As a music writer, I want to learn about the band and expose them to a wider audience;
3. As a promoter, I want to check the band's availability for shows that I am booking;
4. As a long-time fan, I want to support the band by purchasing merchandise;
5. As an event-goer, I want to buy tickets to a show and find out where the venue is;
6. As a musician, I want to find out what instruments the band are using;
7. As a long-time fan, I want to keep in touch with the band by following them on social media;
8. As a long-time fan, I want to keep in touch with the band by subscribing to their mailing list;
9. As a music writer, I want to contact the band regarding interviews;
10. As a label owner, I want to contact the band regarding releasing some of their material.


## Features

### Existing Features

- Index - The landing page contains a welcome message and a couple of news items;
- Music - Contains links and artwork for each of the band's releases so far. This is inspired by the presentation style used by Spotify and Bandcamp, focusing primarily on individual songs;
- Shop - Contains the band's merchandise. These are currently in production so I've used dummy images for these;
- Shows - Contains a diary of upcoming shows, with live links to Google Maps and dummy links to Facebook events and ticketing websites;
- About - A short history of the band, its members, and their instruments;
- Contact - A basic form that allows people to send a message to the band, as well as selecting the reason for enquiry, plus a form to sign up to the mailing list and links to all social media channels.

### Features Left to Implement

- I've included a dummy contact form and shop that will be live once I've completed the JavaScript module. Completing that module will throw up a million ideas for this project, but I'll be using this README as a guide of what to get started on.
- As the project has progressed I have become more comfortable exploring Bootstrap classes so I'd like to re-visit the main structure of the index page;
- I'd like to conduct a review of my CSS styling to see if there are further efficiencies I can make with a better understanding of Bootstrap.
- My initial wireframe included a slightly more advanced grid system than I ultimately implemented, a grid of four windows and a separate side-column. I'd like to bring this in to save other content being hidden at the bottom of the page; ideally there would be no scrolling required on the home page unless being viewed on a mobile device.
- I'd like to include a live Instagram feed at the side of the home page just to break up the content and push as much of the band's online presence into the website;
- The user story for promoters at the moment involves having to view the itinerary and the contact form in separate pages, I would like to rectify this with another contact from beneath the list of shows;


## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - HTML is the language used to display and structure information on any website.

- [CSS3](https://en.wikipedia.org/wiki/CSS3)
    - Cascading Style Sheets is the language used to style HTML content.

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap's grid framework helped me bring my initial wireframe ideas to life;
    
- [Font Awesome](https://fontawesome.com/)
    - Font Awesome's free package provides a comprehensive icon suite that is fully customisable in CSS;
    
- [Google Fonts](https://fonts.google.com/)
    - Google's free service provided countless fonts to help your project stand out;

- [Gitpod](https://www.gitpod.io/)
    - I'm not cocky enough to start using another editor so I've stuck with the trusty Gitpod!

- [Balsamiq](https://www.balsamiq.com/)
    - Balsamiq was recommended to me by my mentor Precious Ijege as a good drafting tool, and it took me very little time to get to grips with it. I will definitely be using this again in the future.

- [Pixlr](https://www.pixlr.com/)
    - Pixlr is a great free software package that enabled me to quickly pick out hex colors and edit existing material that the band provided me with;

- [Favicon.io](https://favicon.io/)
    - A quick and easy tool to create favicons for display in the address bar.

## Testing

I have included a [testing log](https://github.com/kiehozero/weightbearer/blob/master/TESTING.md) within the repository.

In terms of look and feel, the site is similar across all browsers. The tablet and desktop views are almost identical, while mobile 
devices always drop into col-12 formatting.

I tested this project primarily on Firefox but also Chrome and Edge, taking advantage of the screen size options to test using iPad, 
Samsung Galaxy and Kindle Fire. I also tested the site on my own Huawei device. In future I'll use Chrome as it flag up errors (see 
jsQuery in the [testing log](https://github.com/kiehozero/weightbearer/blob/master/TESTING.md). 

## Deployment

I used GitHub as the host for this project, and Gitpod to write it, using just one branch. I took part in the Code Institute hackathon while completing this project, learning a lot about the benefit of branches from the more experienced students in our team. In hindsight I would have used branches from the start of this project but I already had the major structure and feel of the site completed at that point.

I deployed this project to GitHub Pages using the following method:

 - Locate the desired repository in your repository list and open it;
 - Navigate to the Settings heading in the repository heading;
 - Locate the GitHub Pages heading at the bottom of the page;
 - Click the button beneath the Source sub-heading and change this from 'None' to 'Master Branch';
 - Once the page reloads, locate the GitHub Pages heading again;
 - If successful, a green box will appear beneath the heading with the link to your deployed page;
 - This page will only update with new content once that content has been pushed from your developer environment.


### Cloning

Assuming you already have Git [installed](https://git-scm.com/download/), anybody can clone this repository by following these steps:

- Open the Windows command prompt on your machine;
- Type the command 'cd' followed by the directory you wish to store the repository in;
- Go to the top of the [GitHub repository](https://github.com/kiehozero/weightbearer) and click the green 'Code' drop-down button;
- Copy the [link](https://github.com/kiehozero/weightbearer.git) provided;
- Return to the Command Prompt and type 'git clone' followed by the copied address.

For an in-depth guide to cloning repositories, click [here](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/), from which my steps above were taken.

## Credits

### Content
- The header and footer formats were borrowed from existing CI course content, namely the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) and [resume](https://github.com/kiehozero/resume) projects. The links are my own versions of each project but are more or less identical to the walkthrough;
- Social media icons are provided by [Font Awesome](https://fontawesome.com/), while the fonts themselves come from [Google Fonts](https://fonts.google.com/);
- Bootstrap's [navbar documentation](https://getbootstrap.com/docs/4.0/components/navbar/) helped me break down and customise the navigation classes they have;
- Bootstrap's [grid documentation](https://getbootstrap.com/docs/4.0/layout/grid/#offsetting-columns) helpeed more than once when I needed to refresh my thinking, while the [offsetting section](https://getbootstrap.com/docs/4.0/layout/grid/#offsetting-columns) gave me the explanation I needed to re-work the Contact page footer;
- W3Schools' guide on Bootstrap's [media class](https://www.w3schools.com/Bootstrap/bootstrap_media_objects.asp) and [Bootstrap Shuffle](https://bootstrapshuffle.com/classes/sizing/w-100) helped me better understand element positioning;
- [MakeAReadMe](https://www.makeareadme.com/) is an excellent resource for putting together a readme, although I largely used the [Code Institute readme template](https://github.com/Code-Institute-Solutions/readme-template);
- The [Stormotion guide](https://www.stormotion.io/blog/how-to-write-a-good-user-story-with-examples-templates/) helped me put together the user stories I used for this project in a consistent format.

### Media
- Photography and graphic designs were provided directly by the band, with the graphics being designed by [Secret Industries](https://www.instagram.com/secretindustries/).

### Acknowledgements

- The band themselves had mentioned needing a website previously so I'm happy they let me use them as a guinea pig in putting this together.
- My mentor [Precious](https://github.com/precious-ijege) helped this project seem a bit more manageable after I'd come up with my initial ideas. He pointed out what he'd expect using his experience of similar previous projects, and it was good to get that professional perspective after I'd researched other band websites of varying qualities.