<!-- Logo Image here -->
# A Vanlifers Must See

## A website dedicated to sharing the best places to visit in the UK and more!

<!-- general description -->
A Vanlifers Must See (and more, in the UK) is dedicated to bringing the top MUST SEE places in the UK. Not only that, but it also brings a few benefits to taking on Vanlife full time or even part time (its your choice!) and more!

## Deployment
[Click here to view site](https://camcove-crichton.github.io/avanlifersmustsee/)

1. From the repository in Github I went to 'Settings'
2. In 'Settings' I went to the 'Pages' tab on the left side of the page under 'Code and Automation'
3. On the 'Pages' tab, I then selected the **main** branch under the 'Branch' heading of the 'Build and Deployment' section of the page
4. I then selected the 'Save' button to deploy

<!-- Amiresponsive image here -->
### Am I Responsive

![webpage displayed on multiple devices](/README%20images/amiresponsive.png)
[Am I Responsive](https://amiresponsive.co.uk/)

<!-- Website Features here -->
- Benefits to vanlife
- Vanlife hacks
- Top 5 Must See places in the UK
- Weekly blogs
- Blog sign up

## Development
<!-- Wireframes here -->

### Wireframes
![Wireframe homepage one](/README%20images/wireframe1.jpg)

![Wireframe homepage two](/README%20images/Wireframe2.png)

![Wireframe homepage three](/README%20images/Wireframe3.png)

![Wireframe vlogs page](/README%20images/Wireframe4.png)

![Wireframe sign-up page](/README%20images/Wireframe5.png)

<!-- Development Steps -->
- Started with the index.html file basic sturcture along with placeholder text for reference
- Added an assets folder with a CSS folder and images folder
- Created a style.css file, and linked it to the index.html file
- Created the general layout for the README.md file
- Added the general layout to the header section in the index.html file along with adding font awesome script link to the bottom of my index.html file
- Continued updating the README.md file as i went on through the project
- Started with the header content and then started the general styling of the header
- Added a background image to the assets folder and styled it
- Styled the logo fonts, and updated the font color in the body
- Continued tweaking header h* elements and then more styling on the nav
- Started adding content to the Benefits section with some placeholder text in the index.html file
- Updated the style.css file to target more than one section in the index.html file
- Added placeholder content in the Lifehacks section and added an image to go with it
- Replaced the placeholder content with actual content for the Vanlife Hacks section
- Created basic structure and content for the Top 5 Must See Places section
- Added Icons to the Top 5 Must See Places section
- Added styling to the Top 5 Must See Places section
- Added images to the Top 5 Must See Places section
- Created footer structure and added content and style
- Created new html files for the Vlogs and Sign Up pages
- Added embeded vlogs for the Community Vlog page
- Started creating media queries for responsive design
- Added a new file for when sign-up form is submitted, and began working on the sign-up form design
- Added style to the sign-up form
- Continued working on the media queries for medium and small screens
- Added in the content for the signed-up message in the signed-up.html file
- Started to use the dev tools for responsive design, and to tweak code for a better UX
- Added comments for sections in each html file
- After checking code in the W3 Nu html validator and the W3C CSS validator, the errors were corrected until all html files and the CSS file passed with no errors
- Added in screen grabs from the wireframe
- Checked site using Lighthouse
- Added in a screen grab from the Lighthouse check
- Checked the responsive design using Am I Responsive
- Added in a screen grab from the Am I Responsive site
- Added in screen grabs of the final site and explanations of each feature
- Began testing the site over three browsers, Google Chrome, Mozilla Firefox and Mircosoft Edge
- Continuously updated the README.md file

<!-- Site Screen grabs -->
### Finished Website Screen grabs
![Finished project homepage](/README%20images/Finished%20site%20home%20title%20and%20nav.jpg)
- Home page for A Vanelifers Must See (And More in the UK) showing the site title and the sites navigation

![Finished project vanlife benefits](/README%20images/Finished%20site%20vanlife%20benefits.jpg)
- The vanlife benefits section presenting some insight into why living in a van part time or full time can be beneficial

![Finished project vanlife hacks](/README%20images/Finished%20site%20vanlife%20hacks.jpg)
- The vanlife hacks section presenting a few good to know hacks for aspiring van lifers

![Finished project top five must see places](/README%20images/Top%205%20must%20see%20places.png)
- The Top 5 Must See places in the UK, each with its location, GPS coordinates and a few things to do while there

![Finished project footer](/README%20images/Finished%20site%20footer.jpg)
- The social links which can take the user to the social media platforms

![Finished project vlogs page](/README%20images/Finished%20site%20vlogs%20title%20and%20nav.jpg)
- The vlogs page has some embeded videos from other vanlifers to show and inspire other vanlifers from their experiences

![Finished project sign-up page](/README%20images/Finished%20site%20signup%20title%20and%20nav.jpg)
- A sign-up page where users can submit their details to receive emails about the newly added vlogs

![Finished project signed-up message](/README%20images/Finished%20site%20signedup%20message.jpg)
- A message to inform the user the sign-up has been successful

<!-- Sections/Pages functions & screen shots here -->

## Testing
<!-- Website tests here -->
- Below tests performed on Chrome, Firefox, Edge

| Test | Expected Result | Pass/Fail |
| ----------- | ----------- | ----------- |
| Open site from URL | The Home page to open and display | Pass |
| Hover Nav buttons | Highlight each button with a border bottom line and border top line when user hovers over | Pass |
| Select Nav Buttons | Open selected page when clicked and highlight the active page with a border top line and border bottom line | Pass |
| Title logo | Return to home page when clicked | Pass |
| Check 'Things to do' list items hover for Top 5 Must See Places section | Highlight each list item when mouse hovers over | Pass |
| Check 'Things to do' list links | Open each list link item in a new tab when clicked | Pass |
| Check my Footer hover on social links work on all four html files | Highlight each social link when mouse hovers over | Pass |
| Check my Footer social links work on all four html files | Opens each social link in a blank tab when clicked on | Pass |
| Check all the vlog videos | Each video plays when clicked and controls work to pause play and adjust volume | Pass |
| Check the hover over the input fields in the form of the sign-up.html file | Each input field changes border color when mouse hovers over | Pass |
| Check the required attribute for the input fields in the form of the sign-up.html file | Each input field must be filled in before you can submit | Pass |
| Check the signed-up message displays once form has been submitted | The signed-up.html file is displayed to show a thank you message to inform the user the form has been submitted successfully | Pass |

### Bugs
<!-- Any bugs found here -->
- Links to credits not working, fixed with looking up the correct URL
- Ordered list items not displaying number values, fixed using the "list-style-position: inside;" property
- Used dev tools to figure out why the footer was appearing in the the middle of the index.html file when media queries came into play

### Validator Testing
<!-- Validator testing results here -->
[W3 Nu html checker](https://validator.w3.org) - index.html, vlogs.html, sign-up.html, and signed-up.html files check with no errors found

[Jigsaw validator](https://jigsaw.w3.org/css-validator/) - style.css file check with no errors found

<!-- Lighthouse test here -->
![Lighthouse performce scores](/README%20images/Lighthouse.png)

### Unfixed Bugs
<!-- Any unfixed bug details here -->
- As far as I am aware there are not unfixed bugs

## Credits

### Content
<!-- Content credits here -->
[Beyond the Bucketlist](https://beyondthebucketlist.co/10-benefits-of-van-life-why-its-so-popular/#10_Benefits_of_Van_Life_Why_You_Should_Consider_Joining_the_Movement) - Benefits content ideas

[Republic of Durable Goods](https://republicofdurablegoods.com/blogs/field-guide/van-camping-hacks-best-van-life-tips) - Vanlife Hacks ideas

[National Parks UK](https://www.nationalparks.uk/parks/) - Must see places ideas

[Trip Advisor](https://www.tripadvisor.co.uk) - Ideas for things to do in the Top 5 Must See Places

[Google](https://google.com) - General info searches

[Dalwhinnie Distillery](https://www.malts.com/en-gb/distilleries/dalwhinnie) - Things to do idea

[Love Cairngorms](https://www.lovecairngorms.com/wild-swimming-loch-pityoulish) - Things to do idea

[Kinging-It](https://www.kinging-it.com/) - Youtube video of How to convert a van to a campervan in 6 weeks

[Kinging-It Youtube Channel](https://www.youtube.com/@kingingit)

[Wandering Home](https://www.wanderinghome.co.uk/) - Youtube video of How we built our dream home

[Wanering Home Youtube Channel](https://www.youtube.com/@WanderingHome)

[Jits into the Sunset](https://www.jitsintothesunset.com/) - Youtube video of Scotland road trip in our tiny van

[Jits into the Sunset Youtube Channel](https://www.youtube.com/@JitsIntoTheSunset)

### Media
<!-- Media credits here -->
[Pexels](https://pexels.com) - Images

[Pixabay](https://pixabay.com/) - Header background image

[PNW Production](https://instagram.com/pnw.production/) - Image in the benefits section

[Clément Proust](http://clementp.fr/) - Image in the lifehacks section

[Nathan J Hilton](https://www.pexels.com/@radmondo/) - No.5 Must See Place

[Soe Thiha Oo](https://www.instagram.com/soethihaoo/) - No.4 Must See Place

[Facebook](https://facebook.com) - Facebook link for Social Media purpose

[Instagram](https://instagram.com) - Instagram link for Social Media purpose

[Youtube](https://youtube.com) - Youtube link for Social Media purpose

[Twitter](https://twitter.com) - Twitter link for Social Media purpose

[Gabriela Palai](https://www.instagram.com/gabrielapalai/) - Sign-up and signed-up background image

[Till Daling](https://www.tilldaling.com/) - Media query image change for the form on the sign-up page

[Hakeem James Hausley](https://www.instagram.com/jameshausley/) - Media query image change for the heading image on all pages

### Code
<!-- Code credits here -->
[Code Institue](https://codeinstitute.net) - Love Running Project (Layout ideas and troubleshooting)
-Nav layout idea in the index.html, vlogs.html, sign-up.html & signed-up.html files

```         
            <ul>
                <li class="block">
                    <a href="index.html" class="active">Home</a>
                </li>
                <li class="block">
                    <a href="vlogs.html">Community Vlogs</a>
                </li>
                <li class="block">
                    <a href="sign-up.html">Vlog Sign Up</a>
                </li>
            </ul>
 ```

- Top 5 Must See Places in the UK div layout in the index.html file for No.5, No.4, No.3, No.2 and No.1

```
                <div class="must-see">
                    <h3>No. 5</h3>
                    <h4><i class="fa-solid fa-map-location-dot"></i> Location: Llandudno, Wales</h4>
                    <h4><i class="fa-solid fa-earth-europe"></i> GPS Coordinates: 53.3241° N, 3.8276° W</h4>
                    <h4><i class="fa-solid fa-binoculars"></i> Things to do:</h4>   
                </div>
```

- The Footer social links layout in the index.html, vlogs.html, sign-up.html & signed-up.html files

```
<ul>
                <li class="block">
                    <a href="https://www.facebook.com/" target="_blank" class="social"><i
                            class="fa-brands fa-facebook"></i> facebook
                    </a>
                </li>

                <li class="block">
                    <a href="https://www.instagram.com/" target="_blank" class="social"><i
                            class="fa-brands fa-instagram"></i> instagram
                    </a>
                </li>

                <li class="block">
                    <a href="https://www.youtube.com/" target="_blank" class="social"><i
                            class="fa-brands fa-youtube"></i> youtube
                    </a>
                </li>

                <li class="block">
                    <a href="https://twitter.com/" target="_blank" class="social"><i class="fa-brands fa-twitter"></i>
                        twitter
                    </a>
                </li>
            </ul>
```

- The form layout in the sign-up.html file

```
                <form method="GET" action="signed-up.html">
                    <label for="first-name">First Name</label>
                    <input class="entry" type="text" id="first-name" name="first-name" required>

                    <label for="last-name">Last Name</label>
                    <input class="entry" type="text" id="last-name" name="last-name" required>

                    <label for="email">Email</label>
                    <input class="entry" type="email" id="email" name="email" required>

                    <input class="send" type="submit" value="Submit">
                </form>
```

- CSS General Page setup from the Code Institute - Love Running Project

```
* {
    margin: 0;
    padding: 0;
    border: none;

    list-style-position: inside;
}
```

- The CSS general body style from the Code Institute - Love Running Project

```
body {
    font-family: 'Unna', sans-serif;
    font-weight: 400;
    font-size: 1.3rem;
    color: #023020;
}
```

- Idea for the h* styling from the Code Institute - Love Running Project

```
h1,
h2,
h3 {
    font-family: 'Dancing Script', sans-serif;
    font-weight: 600;
    color: #a45a52;
}
```

- Idea for the .heading style code from the Code Institute - Love Running Project

```
.heading {
    margin: auto;

    width: 90%;
    height: 300px;

    background-image: url(../images/pexels-pixabay-39003-small.WebP);
    background-position: 0 0;
    background-size: 100% auto;
    background-repeat: no-repeat;
}
```

- Idea for the #logo size and alignment from the Code Institue - Love Running project

```
    text-transform: capitalize;
    text-align: center;
    font-size: 200%;
    color: white;

    width: 100%;
    height: 300px;
```

- Nav style idea from Code Institute - Love Running Project

```
ul {
    text-align: center;
    padding-top: 15px;
}

#menu li {
    list-style-type: none;
}

ul>li {
    display: inline-block;
    padding: 0 15px;
}
```

- The Hover style idea from the Code Institute - Love Running project (Used a few time with multiple links and buttons in the style.css file)

```
#menu a:hover {
    border-top: 1px solid #023020;
    border-bottom: 1px solid #023020;
    padding: 5px 0;
}
```

- The active page idea from the Code Institute - Love Running Project to display the currently active page

```
.active {
    border-top: 1px solid #023020;
    border-bottom: 1px solid #023020;
    padding: 5px 0;
}
```

- The .must-see layout style idea from the Code Institute - Love Running project

```
.must-see {
    line-height: 1.5;

    margin: 0;
    padding: 15px;
    box-sizing: border-box;

    width: 100%;
    height: 300px;

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

    background-color: rgba(00, 00, 00, 0.7);
}
```

- The footer style idea from the Code Institute - Love Running project

```
.social {
    list-style-type: none;

    display: inline-block;
    padding: 10px 30px;
    margin-bottom: 30px;

    color: #023020;
}
```

- The sign-up form style code from the Code Institute - Love Running project

```
#sign-up {
    background-image: url(../images/pexels-gabriela-palai-420233-small.WebP);
    background-position: 0 0;
    background-size: 100% auto;
    background-repeat: no-repeat;
    width: 90%;
    height: 600px;
    margin-left: 5%;
}
```

```
.form {
    margin-top: 60px;
    margin-left: 5%;
    color: #D3D3D3;
    background-color: rgba(00, 00, 00, 0.6);
    max-width: 300px;
    position: absolute;
    padding: 30px;
    border-radius: 5px;
}
```

```
.send {
    margin-top: 30px;
    padding: 5px 15px;
    font-size: 90%;
    font-family: inherit;
    background-color: #D3D3D3;
    color: #023020;
    border-radius: 5px;
    display: block;
}
```

- The media querey size ideas for the widths from the Code Institute - Love Running project

```
@media screen and (max-width: 1200px)
```

```
@media screen and (max-width: 1025px)
```

```
@media screen and (max-width: 850px)
```

```
@media screen and (max-width: 600px)
```

```
@media screen and (max-width: 400px)
```

```
@media screen and (max-width: 360px)
```

[stackoverflow](https://stackoverflow.com) - Resolving issues/troublshooting

[Code Institute Tutor Support](https://codeinstitute.net) - Tutor Support

- Assistance with centering content in a div with a background image from Code Institute - Tutor Support (Went on to use it again with the .must-see)

```
display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
```

[W3 Schools](https://w3schools.com) - Troubleshooting

[Font Awesome](https://fontawesome.com/) - Icons on the website

- Found Font Awesome from the tutorial in the Code Institute Full Stack Software Development course, used in the index.html, vlogs.html, sign-up.html & signed-up.html files

```
<script src="https://kit.fontawesome.com/c1b12b8cf9.js" crossorigin="anonymous"></script>
```

[Google](https://google.com) - Troubleshooting searches

[Google Fonts](https://fonts.google.com/) - Fonts for site

- Found Google Fonts during the Love Running Project in the Code Institute Full Stack Development course

```
@import url('https://fonts.googleapis.com/css2?family=Anek+Malayalam:wght@300&family=Dancing+Script&family=Unna:ital@1&display=swap');
```

[TinyPNG](https://tinypng.com/) - Compressing images