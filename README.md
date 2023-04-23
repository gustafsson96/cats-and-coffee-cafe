# Cats and Coffee Café

**Link to live website: [Cats and Coffee Café](https://gustafsson96.github.io/cats-and-coffee-cafe/)**

Cats and Coffee Café is the ultimate hybrid of a café and a cat rescue organization, located in Stockholm, Sweden. The website is targeted towards people who like cats, both those looking for a unique and fun café experience and those looking to adopt a rescue cat. This website contains the most important information for a potential visitor/cat adopter: address and opening hours, contact information, images of the cats, an adoption form, and text content guiding the user depending on their purpose of visiting the site (such as encouragement to fill out adoption form or where contact information can be found).

![screenshot showing website on different devices to show its reponsiveness](/documentation/amiresponsive.2.png)

## Features

+ ### Navigation bar
    * The navigation bar consists of a Logo (linking to the website) and About Us, Our Cats, and Adoption (all linking to their correlating section of the page, seeing that this is a website with a single scrolling page).
    * To faciliate the user's navigation of the website, the navigation bar stays on top of the screen while scrolling the page on bigger screens. This function has been intentionally removed on smaller screens to allow more space for the other content. 

![screenshot of navigation bar](/documentation/navigation_bar.png)

+ ### Landing page image
    * The landing page shows a photograph next to a block of informative text, both clearly on the cats and coffee theme. This introduces the user to the café and tells them where and when to visit. 
    * The photograph will be displayed above the text on smaller screens.

![screenshot of landing page image](/documentation/landing_page_image.png)   

+ ### About Us Section
    * The About Us section tells the user more about what to expect from a visit at Cats and Coffee Café. It also contains information that guides the user to other sections of the page depending on what they are looking for.

    ![screenshot of about us section](/documentation/about_us_section.png)

+ ### Our Cats Section (gallery)
    *  In the Our Cats section, the user is presented with photographs and information about the adoptable cats living at the café.
    * The photographs are presented using two rows of images (only one is shown in the screenshot below).
    * The rows can be scrolled on screens too small to show all photographs next to each other. 

    ![screenshot of our cats section](/documentation/our_cats_section.png)

+ ### Adoption Form
    * The Adoption Form allows the user to show interest in adopting a cat. Name, email, phone number and a short introduction are required for the form to be submitted. 

![screenshot of adoption form](/documentation/adoption_form.png)

+ ### Footer
    * The footer consists of social media links that will open in a new tab when clicked, in addition to the café's email address and phone number.
    * The content in the footer is important for users who have a question or want to know more about the café.

![screenshot of footer](/documentation/footer.png)

## Testing

+ ### Browsers

+ ### Responsive design

+ ### Form



## Validator Testing

+ ### HTML
    * The HTML code was validated using the [W3C HTML Validator](https://validator.w3.org/#validate_by_input). 
    Two paragraph elements were missing end tags. Added the needed tags and then validated the code a second time with no errors found.
+ ### CSS
    * The CSS code was validated using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). No errors found.
+ ### Accessibility (Lighthouse Report)
![screenshot of the scores from the first lighthouse report](/documentation/lighthouse-testing.1.png)

The screenshot above shows the results from my first lighthouse report. I decided I wanted to see if I could improve the accessibility score and therefore added aria-label attributes to the social media links (as alternative text for the social media link was suggested in the first lighhouse report). This resulted in an accessibility score of 100 after running a second lighthouse report, results presented below:

![Screenshot of the scores from the second lighthouse report with improved accessibility](/documentation/lighthouse-testing.2.png)


## Bugs

+ #### Solved bugs
    + Problem: After I first deployed my project, none of the image files in my HTML code would load on the page. 
    + Solution: Removing the first / for the absolute file paths in my code (**CREDIT to the Code Institute video "PP1 Sample READMEmd" for this solution**).

+ #### Unfixed bugs
    + No unfixed bugs to present.





## Deployment

## Credits

### Content

### Media

Used https://heyreliable.com/ultimate-google-font-pairings/ and https://typ.io/fonts/roboto?utm_content=cmp-true to choose what fonts to pair. 

https://www.w3schools.com/cssref/sel_hover.php To view options for a:hover for nav-bar. 

Used google "colour picker" to find the right hex color. 

Header image and contact from https://unsplash.com/

cat images and about image from https://www.pexels.com/

code from love running for responsive elements header and footer


## Content

Followed along the "love running" walkthrough by Code Institute and adapted the content to add core strucutre to the home page html file.

## Media


Don't forget to add screenshots!!

# Cats and Coffee Café

**Link to live website: [Cats and Coffee Café](https://gustafsson96.github.io/cats-and-coffee-cafe/)**

Cats and Coffee Café is the ultimate hybrid of a café and a cat rescue organization, located in Stockholm, Sweden. The website is targeted towards people who like cats, both those looking for a unique and fun café experience and those looking to adopt a rescue cat. This website contains the most important information for a potential visitor/cat adopter: address and opening hours, contact information, images of the cats, an adoption form, and text content guiding the user depending on their purpose of visiting the site (such as encouragement to fill out adoption form or where contact information can be found).

![screenshot showing website on different devices to show its reponsiveness](/documentation/amiresponsive.2.png)

## Features

+ ### Navigation bar
    * The navigation bar consists of a Logo (linking to the website) and About Us, Our Cats, and Adoption (all linking to their correlating section of the page, seeing that this is a website with a single scrolling page).
    * To faciliate the user's navigation of the website, the navigation bar stays on top of the screen while scrolling the page on bigger screens. This function has been intentionally removed on smaller screens to allow more space for the other content. 

![screenshot of navigation bar](/documentation/navigation_bar.png)

+ ### Landing page image
    * The landing page shows a photograph next to a block of informative text, both clearly on the cats and coffee theme. This introduces the user to the café and tells them where and when to visit. 
    * The photograph will be displayed over the text on smaller screens.

![screenshot of landing page image](/documentation/landing_page_image.png)   

+ ### About Us Section
    * The About Us Section tells the user more about the café and the organization.

-Our cats (with images) table? 

-Adoption (form)

-Contact 

-Footer with social media links


Features left to implement (other feature ideas)

## Bugs

## Validator Testing

### Lighthouse report

![screenshot of the scores from the first lighthouse report](/documentation/lighthouse-testing.1.png)

The screenshot above shows the results from my first lighthouse report. I decided I wanted to see if I could improve the accessibility score and therefore added aria-label attributes to the social media links (as suggested in the lighhouse report). This resulted in an accessibility score of 100 after running a second lighthouse report, results below: 

![Screenshot of the scores from the second lighthouse report with improved accessibility](/documentation/lighthouse-testing.2.png)

### Bugs

#### Solved Bugs

+ Problem: After I first deployed my project, none of the image files in my HTML code would load on the page. 
+ Solution: Removing the first / for all images in my code (**CREDIT** to the Code Institute video "PP1 Sample README.md" for this solution).

## Unsolved bugs

## Deployment

## Credits

### Content

### Media

Used https://heyreliable.com/ultimate-google-font-pairings/ and https://typ.io/fonts/roboto?utm_content=cmp-true to choose what fonts to pair. 

https://www.w3schools.com/cssref/sel_hover.php To view options for a:hover for nav-bar. 

Used google "colour picker" to find the right hex color. 

Header image and contact from https://unsplash.com/

cat images and about image from https://www.pexels.com/

code from love running for responsive elements header and footer


## Content

Followed along the "love running" walkthrough by Code Institute and adapted the content to add core strucutre to the home page html file.

## Media


Don't forget to add screenshots!!

