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

### Features Left to Implement

* Include link to location of the café on Google Maps. Perhaps this would also require a separate contact section where all contact information could be collected. 

## Testing

+ ### Browsers
    * I opened the website in Chrome, Safari, and Firefox to ensure that it works in different browsers.

+ ### Responsive design
    * To make sure that this project is responsive, I have continuously used the device toolbar in devtools when adding and making changes in the code. After finishing the code, I checked one last time and to confirm that the page looks good and is functioning on diffent screen sizes. 

    * I have opened the project on my own devices (MacBook Air and iPhone 13) to confirm that the page looks good and is functioning on diffent screen sizes. 

    * For a greater variety to further ensure that the project is responsive, I have asked friends and family with devices other than mine to open the project and got confirmations that it looks good and is functioning.

     * I have used the [amiresponsive website](https://ui.dev/amiresponsive) to display the website on different devices and can confirm that it (after the problem and solution presented under "bugs") looks good. 

+ ### Form
    * I have personally and by the help of family confirmed that the form and submit button work. The form cannot be submitted without the fields filled in (emphasizing that an email is required for the email field).

    ![screenshot of form required](/documentation/form_required.png)

## Validator Testing

+ ### HTML
    * The HTML code was validated using the [W3C HTML Validator](https://validator.w3.org/#validate_by_input). 
    Two paragraph elements were missing end tags. Added the needed tags and then validated the code a second time with no errors found.
+ ### CSS
    * The CSS code was validated using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). No errors found.
+ ### Accessibility (Devtool Lighthouse Report)
![screenshot of the scores from the first lighthouse report](/documentation/lighthouse-testing.1.png)

The screenshot above shows the results from my first lighthouse report. I decided I wanted to see if I could improve the accessibility score and therefore added aria-label attributes to the social media links (as alternative text for the social media link was suggested in the first lighhouse report). This resulted in an accessibility score of 100 after running a second lighthouse report, results presented below:

![Screenshot of the scores from the second lighthouse report with improved accessibility](/documentation/lighthouse-testing.2.png)


## Bugs

+ #### Solved bugs
    + 1st problem: After I first deployed my project, none of the image files in my HTML code would load on the page. 
    + Solution: Removing the first / for the absolute file paths in my code (**CREDIT to the Code Institute video "PP1 Sample READMEmd" for this solution**).

    + 2nd problem: When I first used the [amiresponsive website](https://ui.dev/amiresponsive) to check my website on different devices, I could see that the links in the navigation bar were not aligned on the smallest screen.

     ![screenshot from first time showing website on different devices](/documentation/amiresponsive.png)
    + Solution: Adding a media query for smaller screen sizes solved the problem and placed the links next to each other on smaller screens (the screenshot presented below is identical to the one at the top of this README file).

    ![screenshot showing website on different devices to show its reponsiveness](/documentation/amiresponsive.2.png)

+ #### Unfixed bugs
    + No unfixed bugs to present.

## Deployment
+ I deployed this site to GitHub pages through the following process: 
    1. Open up the GitHub repositry for the project. 
    2. Click the Settings tab and navigate to Pages in the menu to the left of the screen.
    3. Under Branch, select "main" in the dropdown menu and clich Save. 
    4. Refresh page to find the link to the live website at the top of the GitHub Pages section. 

## Credits

### Content

Followed along the "love running" walkthrough by Code Institute and adapted the content to add core strucutre to the home page html file.

### Media

Used https://heyreliable.com/ultimate-google-font-pairings/ and https://typ.io/fonts/roboto?utm_content=cmp-true to choose what fonts to pair. 

https://www.w3schools.com/cssref/sel_hover.php To view options for a:hover for nav-bar. 

Used google "colour picker" to find the right hex color. 

Header image and contact from https://unsplash.com/

cat images and about image from https://www.pexels.com/

code from love running for responsive elements header and footer