# The Solar System

The Solar System is an educational website based on the Planets that are orbiting our Sun (Pluto is also included). The website is easy to navigate and the demographic it would be aimed at would be pre - early teens. The information is provided in bullet points along with images and is not too technical. This will make the content easy to digest and engaging.

The site uses a main page with the images of the sun and planets on it for use of navigation. The colours, fonts are a simple bright white which contrast quite nicely with images that would naturally follow a night sky theme 

<img src="assets/images/am-i-responsive.png" alt="Screenshot of Am I Responsive webpage">

# Feautures

## Opening Section

* When you load the website, the title will display along with cover text over an image of our Solar System explaining what the Solar System is in very simple bullet points

* The user is prompted to click on the images below in order to navigate around the website

* The image is surrounded by a white border in order to avoid the two dark shades of the night sky and empty space clashing

<img src="assets/images/opening-section-head.png" alt="Image of opening section">




## Navigation

* In this section which is on the same page as the opening section - the user navigates the website through the use of the images and text displayed

* The user is again prompted with the text "Choose your Celestial Body"

* No Hover feature was used here as I found it wasn't displaying well with the colour and background images 

<img src="assets/images/planet-navigation-image.png" alt="Screenshot of planet-navigation section">


* When you click on one of the planets it will take you to that planet page

* If you want to choose another planet then all you have to do is click the nav link that reads "Choose Another Celestial Body". This has a burnt orange colour to it in order to contrast between the information text 

* This is also placed in a fixed position so it follows the user as they scroll through the content saving the user the effort of having to scroll back to the top in order to go back to the main navigation page

<img src="assets/images/planet-page-with-nav-feature.png" alt="Screenshot of Uranus page head">



## Content

* Within the individual Planet Pages we have a section with Four Heading - Overview, Composition, Size and Distances and Temperature and Atmosphere

* Within these Four Headings we have Four Bullet Points stating facts about the planet

* These are quick-fire points that are easy to take in and comprehend

* Between the divs of text we have images of the planets

<img src="assets/images/planet-content-image.png" alt="Screenshot of planet information section">


## Footer

* The footer has links to social media which open in new pages

* Like the majority of text on this website the colour is set to white

* Again, no Hover feature is used

<img src="assets/images/footer-image.png" alt="Screenshot of Footer">

# Tests

## Responsive Design

* For mobile and tablets I changed the layout of the Navigation Images on the Home Page so that they would stack up on top of eachother

* This was done by removing the display: inline block; and changing the width to 100% as opposed to 33% with the divs containing the images

* The difficulty with the responsive design over all was the size and placement of text which had to be re-sized and re-positioned in order to display in the correct manner

<img src="assets/images/responsive-design-example-1.png" alt="Responsive Design Screenshot for Home Page">

* I applied the same design idea to the individual planet pages - placing the each div with content in it on top of each other

* Again, it was the text that caused difficulty at various pixel widths

<img src="assets/images/responsive-design-example-2.png" alt="Responsive Design Screenshot for Individual Planet Pages">



* Here is an example below of the text used in the individual planet pages information section being altered for Responsive Design purposes

<img src="assets/images/css-media-queries-example.png" alt="Screenshot of CSS media queries">


## Validator

* The screenshot below shows a warning from the validator for the index.html (Home Page). However I don't think of this as an issue as the nature of the element does not require any further modifications

<img src="assets/images/index.html-validator-image.png" alt="Screenshot of HTML validator warning">

* As for the planet.htmls and the style.css - No errors were found

<img src="assets/images/planet-html-validator-image.png" alt="Screenshot of individual planet code validation">

<img src="assets/images/css-validator-image.png" alt="Screenshot of CSS code validation">

# File Paths

* On the live site nothing was displaying due to the use of absolute file paths as opposed to relative file paths

* I had a lot of trouble figuring out how to implement the relative file paths but eventually figured out "./assets...." in my html and "../images...." in my css.style solved the issue

* In this context, using relative file paths is a habit that I will be picking up from now on as I didn't realise its importance


## Lighthouse Testing

* The individual planets all scored above 90 in performance with Neptune being the highest at 95 and Mars the lowest at 91

* The Main Home Page scored at 89 but still runs very well on desktop and mobile

<img src="assets/images/neptune-lighthouse-image.png" alt="Screenshot of Neptune Lighthouse score">

<img src="assets/images/mars-lighthouse-image.png" alt="Screenshot of Mars Lighthouse score">

<img src="assets/images/homepage-lighthouse-image.png" alt="Screenshot of Home Page Lighthouse score">

## Unfixed Bugs

* In the individual planet.htmls - When the responsive design facilitates the switching over of divs to be stacked on top of one another the images don't naturally fill out in the div.

* In the future I will need to be carful in terms of image heights and how it fills a particular area out. However it is a trade-off I am willing to make as I don't want to sacrifice the intergrity of the images through stretching etc

* Another trade-off is the navigation - "Choose Another Celestial Body" and how it sits with the text in the section with the headings and bullet points

* I think it looks good on mobile but perhaps seems a little blurred on desktop. With the way I wanted the content to be layed out I simply didn't know a better way to design the nav in such a way that it wouldn't seem to "interfere" with the content as a whole

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

* In the GitHub repository, click on the Settings tab
* Scroll down to the pages section and click into it
* From the source section Drop-Down Menu, select the Main Branch
* A link is then generated and provided

Link to Live Website: https://willunger.github.io/the-solar-system/

# Credits

Sources

* The Fonts used can be sourced from https://fonts.google.com/
* The Icons used can be sourced from https://fontawesome.com
* The information used to make the content came mainly from the NASA https://www.nasa.gov/topics/solarsystem/index.htmlwebsite as well as my own knowledge on the subject
* Images also came from the NASA website above but mainly from https://commons.wikimedia.org/wiki/Main_Page
* 

Finally, I wish to thank my Mentor - Richard Wells - for the encouragement and help he gave me




