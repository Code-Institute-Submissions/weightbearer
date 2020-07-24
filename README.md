# Weight Bearer

![Weight Bearer Logo](/assets/images/icons/banner-text-line-900px.png)

Welcome to my user-centric front-end development milestone project. For this project I chose to create a [website](https://kiehozero.github.io/weightbearer/) for a friend's band, Weight Bearer, a metal band based in Lancashire, England. Luckily for me the band actually wish to use this as their online home, so this project might technically count as my first (unpaid) commission!
 

## UX

I have created a website which centralises resources that would otherwise be spread across a number of social media websites. The band currently uses Bandcamp for hosting and selling music, Spotify and YouTube for streaming and Facebook for publicity and events.

### Styling

A Balsamiq wireframe for this project is included in the repository, with [desktop](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Desktop%20Wireframes.pdf), [tablet](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Tablet%20Wireframes.pdf) and [mobile](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Mobile%20Wireframes.pdf) versions.

I used the following hex colours, selecting using [Pixlr](https://www.pixlr.com):

- #f2f2f2 is an off-white colour that is used in the band's monochrome diamond icon;

- #693288 is a shade of purple that is used in the band's colour diamond icon. I also created a version of the band's font logo to match this colour using Pixlr.

- For the lead font I chose Merriweather Sans as it most closely matched the font that the graphic designer commissioned by the band had used. This font only really worked in upper case, so I chose Poppins as a secondary font just for h3, p and span elements.

- I have tried to keep a uniform template through the site in order to create a sense of familiarity when new users are navigating. Each page, across all devices, contains a navigation bar and an image banner in the header, and a footer with links to social media channels and a subscription form for their mailing list. I have removed this information from the footer on the Contact page as it features more prominently in the main content of that page.

### User Stories

Testing for each of the below user stories is included within the [testing log](https://github.com/kiehozero/weightbearer/blob/master/TESTING.md).

1. As a first-time listener, I simply want to hear the band's music;
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
    - HTML is the language used to display and structure information on any website.

- [CSS3](https://en.wikipedia.org/wiki/CSS3)
    - Cascading Style Sheets is the language used to style HTML content.

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap's grid framework helped me bring my initial wireframe ideas to life, while [Font Awesome](https://fontawesome.com/)'s icons and [Merriweather Sans](https://fonts.google.com/specimen/Merriweather+Sans) made things look that bit more professional.

- [Gitpod](https://www.gitpod.io/)
    - I'm not cocky enough to start using another editor so I've stuck with the trusty Gitpod!

- [Balsamiq](https://www.balsamiq.com/)
    - Balsamiq was recommended to me by my mentor Precious Ijege as a good drafting tool, and it took me very little time to get to grips with it. I will definitely be using this again in the future.

- [Pixlr](https://www.pixlr.com/)
    - Pixlr is a great free software package that enabled me to quickly pick out hex colors and edit existing material that the band provided me with.


## Testing

I have included a [testing log](https://github.com/kiehozero/weightbearer/blob/master/TESTING.md) within the repository.


## Deployment

I used GitHub as the host for this project, and Gitpod to write it, using just one branch. I took part in the Code Institute hackathon while completing this project, learning a lot about the benefit of branches from the more experienced students in our team. In hindsight I would have used branches from the start of this project but I already had the major structure and feel of the site completed at that point.

All of the images used on the website except for the logos for the external press links are hosted within the Gitpod repository. I had initially included mp3s on the music page so users could listen to the band directly within their browser, but my mentor advised me that this adds a large amount of content to the page for not much benefit, especially because I've linked to Spotify, YouTube and Bandcamp.

### Cloning

Assuming you already have Git [installed](https://git-scm.com/download/), anybody can clone this repository by opening Windows command prompt and using the command 'cd' followed by the directory you wish to store the repository in.

Go to the top of the [repository](https://github.com/kiehozero/weightbearer) and click the green Code drop-down button. Copy the [link](https://github.com/kiehozero/weightbearer.git) provided, then return to Command Prompt and type 'git clone' followed by the copied address.

For an in-depth guide to cloning repositories, click [here](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/).

## Credits

### Content
- The header and footer formats were borrowed from existing CI course content, namely the [Whiskey Drop](https://github.com/kiehozero/WhiskeyDrop) and [resume](https://github.com/kiehozero/resume) projects. The links are my own versions of each project but are more or less identical to the walkthrough.
- Social media icons are provided by [Font Awesome](https://fontawesome.com/), while the fonts themselves come from [Google Fonts](https://fonts.google.com/).
- Bootstrap's [navbar documentation](https://getbootstrap.com/docs/4.0/components/navbar/) helped me break down and customise the navigation classes they have;
- Bootstrap's [grid documentation](https://getbootstrap.com/docs/4.0/layout/grid/#offsetting-columns) helpeed more than once when I needed to refresh my thinking, while the [offsetting section](https://getbootstrap.com/docs/4.0/layout/grid/#offsetting-columns) gave me the explanation I needed to re-work the Contact page footer.
- W3Schools' guide on Bootstrap's [media class](https://www.w3schools.com/Bootstrap/bootstrap_media_objects.asp) and [Bootstrap Shuffle](https://bootstrapshuffle.com/classes/sizing/w-100) helped me better understand element positioning;
- [MakeAReadMe](https://www.makeareadme.com/) is an excellent resource for putting together a readme, although I largely used the [Code Institute readme template](https://github.com/Code-Institute-Solutions/readme-template);
- The [Stormotion guide](https://www.stormotion.io/blog/how-to-write-a-good-user-story-with-examples-templates/) helped me put together the user stories I used for this project in a consistent format.

### Media
- Photography and graphic designs were provided directly by the band, with the graphics being designed by [Secret Industries](https://www.instagram.com/secretindustries/).

### Acknowledgements

- The band themselves had mentioned needing a website previously so I'm happy they let me use them as a guinea pig in putting this together.
- My mentor [Precious](https://github.com/precious-ijege) helped this project seem a bit more manageable after I'd come up with my initial ideas. He pointed out what he'd expect using his experience of similar previous projects, and it was good to get that professional perspective after I'd researched other band websites of varying qualities.