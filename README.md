# Corvin Castle #
**This site is for those who like to explore historical places or are passionate about castles.** 

**Those who use this site will find information about Corvin Castle such as: contact details, buy tickets, prices, timetable, little history, legends, pictures about the castle and a contact form.** 

![Am I responsive screen-shot](/assets/images/am-i-responsive.png)

 ## Features
 * Navigation 
    * Featured at the top of the page, the navigation shows the castle name in the left corner: CORVIN CASTLE links to the top of the page.
    * In the middle you can find a button named TICKETS, if clicked it opens another site in new tab where you can buy tickets to visit the castle.
    * The other navigation are to the right: Home, About Castle, Gallery and Contact wich link to different pages from the same website.
    ![Navigation bar](/assets/images/navigation.png)
* Header
    * The header contains the city and country where the castle is located.
    * Here you can also see the front of the castle
    ![Header](/assets/images/header.png)
* Video
    * In the middle of the page you will find a slideshow with images of the castle.
    * Video contain a relaxing background music.
    * The video also contains action buttons such as play, pause, volume and full screen.
    * ![Video](/assets/images/video.png)
* Map
    * Below on the page you will find a map with the Corvin Castle located, by clicking on it you can get directions to visit the castle.
    * ![Map](/assets/images/map.png)
* Footer
    * Here is the opening time.
    * Social media icons, which opens in a new tab.
    * Contact details such as email, phone number and address where the castle is located.
    ![Footer](/assets/images/footer.png)
* About Castle 
    * Here you can also see the back side of the castle
    * Short history about castle, who build it and short history about John Hunyadi
    * ![Who build](/assets/images/who-build.png)
    * ![Who was John](/assets/images/who-was.png)
    * The map of the castle
    * ![Masterpiece section](/assets/images/masterpiece.png)
    * Three of famous legends of the castle      
    * ![The three legends section](/assets/images/legends.png)
* Gallery
    * Here you can find couple of pictures from the castle.
     ![Gallery](/assets/images/gallery.png)
* Contact
    * Contact form is not linked yet to the owners of the castle
    * Right next to the form you can find the real contact details, prices and a button to buy tickets.
    ![Contact details page](/assets/images/contact.png)

## Testing

* I tested that this site works in different browsers: Mozilla, Chrome, Opera.
* I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the devtools device toolbar
* I confirmed that the navigation Home, About Castle, Gallery and Contact text are all readable and easy to understand
* I confirmed that the form works: requires entries in every field, will only an email in email field, radio buttons work properly and submit button works.

## Bugs

* When I deployed my project to GitHub Pages I discovered that couple of images was broken, the links to the other images from About Castle page and from video from main page.
* I discovered this was because I had used absolute file paths such as this in my code
### ![Broken file after deployment](/assets/images/wrong-code.png)
* Removing the starting / fixed the problem
* Radio buttons from form section was not required when submiting, includin *required*  to input fixed problem
* When I write *width="100%"* to iframe, it fails to HTML validator because of *%* so I remove it until I will find how to fix it.

## Validator Testing
* HTML 
    * No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmitzusca.github.io%2Fcorvin-castle%2F)
* CSS 
    * No errors were returned when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmitzusca.github.io%2Fcorvin-castle%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
*<a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!">
    </a>*
* Accessibility 
    * I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools [Lighthouse Report Viewer](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fmitzusca.github.io%2Fcorvin-castle%2F&strategy=desktop&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)
### ![Lighthouse score](/assets/images/lighthouse-score.png) 

## Unfixed Bugs
* *width="100%"* on iframe it fails when validate, but it works as i wish only when I use *%*

## Deployment
* The site was deployed to GitHub Pages. The steps to deploy are as follows:
    * From Overview click on repository that need to be deployed
    * Than click on Settings button and on the left side you can find Pages button
    * From Source section drop-down menu, select *main* branch and  *root* from select folder than save
    * Once saved, the page provide the link to the completed website
* The live link can be found here [Corvin Castle](https://mitzusca.github.io/corvin-castle/)

## Credits
* Contents 
    * The code for making social media links was taken from CI [Love Running](https://mitzusca.github.io/love-running/gallery.html) Project
    * Pricing, opening time and contact details from official site in romanian [Castelul Corvinilor](http://www.castelulcorvinilor.ro/)
## Media
* Pictures and information about castle was taken from [Wikipedia](https://en.wikipedia.org/wiki/Corvin_Castle)