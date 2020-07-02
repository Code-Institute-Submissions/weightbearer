# Weight Bearer

Welcome to my user-centric front-end development milestone project (MS1 for short). For this project I chose to create a website for a friend's band. The band is called Weight Bearer, a metal band based in Lancashire, England.
 
## UX

I've created a website which centralises resources that would otherwise be spread across a number of social media websites. The band currently uses Bandcamp for hosting and selling music, Spotify and YouTube for streaming and Facebook for publicity and events. I've retained full links to these pages but included the ability to listen and download music direct from the website.

### User Stories

- LISTEN: Users who want to listen to the band's music can either listen using the mp3s on the Music page or re-direct to Spotify, Bandcamp or YouTube.

- PURCHASE: Users who wish to purchase band merchandise can visit the Shop page. This page is a dummy until I have completed the Javascript module.

- CONTACT: Users who need to contact the band can complete the form contact form and specify their request.

A wireframe for this project is included in the repository, with [desktop](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Desktop%20Wireframes.pdf), [tablet](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Tablet%20Wireframes.pdf) and [mobile](https://github.com/kiehozero/weightbearer/blob/master/wireframes/Weight%20Bearer%20Mobile%20Wireframes.pdf) versions.

## Features

###Existing Features

- Index - The landing page includes a short biography of the band, as well as prominent links to music, a shop and a diary of live events, in line with the main user stories;
- Music - Contains links to each of the band's releases so far. I've included the album artwork for each as a thumbnail, which is inspired by the presentation style used by Spotify and Bandcamp, focusing primarily on individual songs;
- Shop - Contains the band's merchandise, namely their first record, a t-shirt and a sticker pack. These are currently in production so I've used dummy images for these;
- Shows - Contains a diary of upcoming shows, with a dummy link to Facebook events as shows are obviously cancelled given current circumstances;
- About - A short history of the band, its members, their influences and instruments;
- Contact - A basic form that allows people to send a message to the band, as well as selecting the reason for enquiry.

### Features Left to Implement
- I've included a dummy contact form and shop that will be fleshed out once I've completed the JavaScript module.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

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

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- Header and footer formats borrowed from CI course content

### Media
- Photography and graphic designs were provided directly by the band, with the graphics being designed by [Secret Industries](https://www.instagram.com/secretindustries/).

### Acknowledgements

- The band themselves had mentioned needing a website previously so I'm happy they let me use them as a guinea pig in putting this together.
- My mentor [Precious](https://github.com/precious-ijege) helped this project seem a bit more manageable after I'd come up with my initial ideas. He pointed out what he'd expect using his experience of similar previous projects, and it was good to get that professional perspective after I'd researched other band websites of varying quality.
