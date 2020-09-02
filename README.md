# The Mancunian Cafe Website

## User Experience (UX)

### User Stories

- Key requirements of the website's users include:

  1. To be able to navigate the website easily to find the content I am looking for
  2. To understand what makes the cafe unique and why I should want to eat there.
  3. To view the offers the cafe currently has on.
  4. To view the cafe's menu and each item's nutritional information.
  5. To find out where the cafe is located 
  6. To find out the cafe's opening hours.
  7. To find out what other customers who have visited the cafe thought of it.
  8. To be able to contact the cafe to get answers to any questions I may have.

### Design

#### Colour Scheme

- The three main colours used in the website are turquoise, white and grey.

#### Typography

- The Pacifico font is the font used for the brand logo. Roboto is used throughout the website for main headings and Lato is used for subheadings and paragraphs. Sans Serif is the fallback font which is used in the event that the specified font fails to import into the website correctly.

### Wireframes

## Features

### Existing Features

1. Navigation links
    - The navigation links on the right of the navigation bar provide the user with links to the different pages of the website.
    - The cafe logo on the left of the navigation bar is also a link which can be accessed from any page to take the user back to the home page.

2. Hero image
    - The hero image provides the user with and idea of the atmosphere in the cafe, provides them with details of the current offer and invites them to come to the cafe to take advantage of the offer.

3. Customer Testimonials Carousel 
    - The carousel displays three customer testimonials to provide users with an insight into what other customers who have visited the cafe thought of it.

4. Menu Cards 
    - The menu cards provide users with information about each item on the menu including an image, the price and whether the item is gluten-free or vegan.

5. Nutritional Information Modal
    - The modal provides users with nutritional information about the menu item. 

6. Google Map and Address 
    - This displays the cafe's location on a map so that customers can see where it is located and plan how to get to it.

7. Contact us form 
    - The contact us form enables users to contact the cafe about any questions they may have.

### Features Left to Implement

1. Link the contact us form up to a database 
    - Set up a database and add the method and post attributes to the contact us form so that the cafe's employees can view the enquiries submitted by customers.

2. Placing of orders for collection through the website
    - Add an order form which makes it possible for customers to place orders which they are collecting from the cafe through the website.

3. Email sign-up 
    - Add an email sign-up form so users can sign up to a newsletter if they want to be kept informed about new products, services, offers and any other news about the organisation.

## Technologies Used

### Languages Used

1. [HTML5:](https://en.wikipedia.org/wiki/HTML5)
   - HTML5 was used for the sturcture of the webpages.
2. [CSS3:](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
   - CSS3 was used for the styling of the webpages.

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/)
   - Bootstrap was used for the jumbotron containing the hero image text, testimonials carousel, menu items cards, nutritional information modals. The website's styling and resposniveness is also based on Bootstrap.
2. [Hover.css:](https://ianlunn.github.io/Hover/)
   - Hover.css was used on the navbar links for the underline transition hover effects.
3. [Google Fonts:](https://fonts.google.com/)
   - Google fonts was used to import the 'Lato', 'Pacifico' and 'Roboto" fonts into the style.css file which is used on all pages throughout the project.
4. [Font Awesome:](https://fontawesome.com/)
   - Font Awesome was used on the home and location pages to enhance the UX of these pages by adding icons to the relevant content.
5. [jQuery](https://jquery.com/) and [Popper.js:](https://popper.js.org/)
   - Bootstrap uses jQuery and Popper.js to make the navbar responsive.
6. [Git](https://git-scm.com/)
   - Git was the version control system used whilst working on the project. Gitpod terminal was used to commit files to Git and Push them to GitHub.
7. [GitHub:](https://github.com/)
   - GitHub is used to store the project's code and any other required files.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure that the code used in the project was in compliance with the HTML5 and CSS3 standards and that there were no syntax errors.

- [W3C Markup Validator](https://validator.w3.org/) - Results
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - Results

### Testing User Stories from User Experience (UX) Section

1. To be able to navigate the website easily to find the content I am looking for.

    - In the header of each page there is a navigation bar which is clean and easy to read, and includes links to the other pages.  
    - In the footer of each page there are social media links and copyright information. 
    - The website is structured in a logical way with the offer information, reasons to eat at the cafe and testimonials being displayed on the home page, and the menu, location information and contact form each having their own page.

2. To understand what makes the cafe unique and why I should want to eat there.

    - When the user scrolls down to the "why eat with us" section in the middle of the home page, they can read the four reasons why they should come and eat at the cafe.

3. To view the offers the cafe currently has on.

    - When the user loads up the webpage, the hero image is displayed which informs the user about the offer currently on and invites them to come to the cafe and take advantage of it.

4. To view the cafe's menu and each item's nutritional information.

    - When the user clicks on the "menu" link in the navigation bar, they are presented with a card for each menu item containing an image, the item's price and and icons to show whether the item is gluten-free and vegan.
    - When the user clicks on the image of each menu item, they are presented with a modal containing information about the item's nutritional information.

5. To find out where the cafe is located.

    - When the user clicks on the "location" link in the navigation bar, they are presented with a google map displaying the location of the cafe and the cafe's address.

6. To find out the cafe's opening hours.

    - When the user clicks on the "location" link in the navigation bar, they are presented with information about the cafe's opening hours.

7. To find out what other customers who have visited the cafe thought of it.

    - When the user scrolls down to the testimonials section at the bottom of the home page, they are presented with a carousel containing three testimonials which have been written by customers reviewing their experience at the cafe.

8. To be able to contact the cafe to get answers to any questions I may have.

    - When the user clicks on the "contact us" link in the navigation bar, they are presented with a contact us form which they can complete to get in touch with the cafe.
    - When the user clicks on the "location" link in the navigation bar, the cafe's telephone number is presented to them.

### Further Testing

- The Website was tested on a variety of different web browsers including Google Chrome, Internet Explorer, Microsoft Edge and Safari.
- The Website was also viewed on a number of different devices with a range of screen widths including an iMac, MacBook, iPad and iPhone.
- All links and hover effects were tested thoroughly to ensure that they were functioning correctly.
- Family and friends were asked to review the site and documentation and identify any bugs or other issues that were affecting the user experience.

### Fixed Bugs

1. Navbar links were wrapping onto a second line on medium sized screens.
    - Changed size at which collapsed navbar displays to medium sized screens and below.

2. Hover effects were displaying in collapsed navbar.
    - This was fixed by making the background colour of the relevant css class to transparent and setting it to white only for large screens and above.

3. Carousel height changes if the number of lines of text in each testimonial changes.
    - Set minimum height for carousel paragraphs using media queries.

4. Items not centrally aligning in parent columns
    - Fixed error in code.

5. Type of enquiry dropdown text was appearing in a different color to the rest of the form.
    Added a css class to apply custom styling to whole form.

### Known Bugs

- Carousel height changes on devices below 288px if the number of lines of text in each testimonial changes.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps:

1.  Log in to GitHub and click on the relelavant [GitHub Repository](https://github.com/jonathan-odonnell/milestone-project-1).
2.  Click on the "Settings" button at the top of the repository.
3.  Scroll down to the "GitHub Pages" section.
4.  In the source section, click the branch dropdown and select "master".
5.  Wait for the page to refresh.
6.  Scroll back down to the "Github Pages" section and locate the link to the published site.

### Forking the Github Repository

The GitHub Repository can be forked using the following steps:

1.  Log in to GitHub and locate the project's [GitHub Repository](https://github.com/jonathan-odonnell/milestone-project-1).
2.  At the top-right of the repository, click the "Fork" Button.
3.  You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

A local clone of the project can be created using the following steps:

1.  Log in to GitHub and locate the project's [GitHub Repository](https://github.com/jonathan-odonnell/milestone-project-1).
2.  Under the repository name, click the "Code" button.
3.  To clone the repository using HTTPS, under "Clone with HTTPS", click the clipboard button to copy the repository URL. To clone using SSH click "Use SSH" and then click the clipboard button.
4.  Open Git Bash
5.  Change the current working directory to the location where you want to store the cloned repository.
6.  Type git clone, and then paste the URL you copied in Step 3.
7.  Press enter to create your clone

## Credits

### Code

- Code for the navbar came from [bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/).
- Code for the navbar toggler icon colour (.navbar-dark .navbar-toggler-icon class) came from viewing the css for the toggler and adapting it to appear in the desired colour.
- Code for navigation link underline colour (.hvr-underline-from-left:after class) came from viewing the css for the underline from left effect and adapting it to appear in the desired colour.
- Code for active navigation link underline (.active class) came from viewing the css for the underline from left effect and adapting it to appear permanently rather than when the link is hovered over.
- Code for the testimonials caurosel came from [Bootstrap](https://getbootstrap.com/docs/4.5/components/carousel/).
- Code for the line after the testimonial reviewer's name (.blockquote-footer::after class) came from viewing the css for the line before the name and adapting it to appear after the name. 
- Code for the menu item cards came from [Bootstrap](https://getbootstrap.com/docs/4.5/components/card/).
- Code for the nutritional information modals came from [Bootstrap](https://getbootstrap.com/docs/4.5/components/modal/).
- Code for vertically aligning items in the center of a column came from this Stack Overflow [post](https://stackoverflow.com/questions/26941443/how-to-center-vertically-and-horizontally-a-div-using-bootstrap/26941597).

### Content

- Fair Trade Coffee section of the home page was adapted from this [page](https://www.fairtrade.org.uk/buying-fairtrade/coffee/#:~:text=When%20you%20choose%20Fairtrade%20coffee,in%20improving%20productivity%20and%20quality) on the Fair Trade Foundation website.
- Lucy testimonial was adapted from this [Trustpilot post](https://uk.trustpilot.com/review/caffenero.com?languages=en&stars=5).
- Nutritional information was from Cafe Nero's [coffee menu](https://caffenero.com/uk/menu/coffee/), [all-day breakfast menu](https://caffenero.com/uk/menu/food/all-day-breakfast/), [panini and sandwich menu](https://caffenero.com/uk/menu/food/panini-sandwiches/), [cakes and muffins menu](https://caffenero.com/uk/menu/food/cakes-muffins/) and [snacks menu](https://caffenero.com/uk/menu/food/snacks/), and [Costa Coffee's menu](https://www.costa.co.uk/menu/).
- Contact us text was adapted from the Avanti West Coast Contact Us [page](https://www.avantiwestcoast.co.uk/help-and-support/contact-us).
- The information in the Github Pages section of the readme was adapted from the GitHub configuring a publishing source for your GitHub Pages site [documentation](https://docs.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
- The information in the Forking a Github Repository section of the readme was adapted from the GitHub forking a repository [documentation](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).
- The information in the Making a Clone section of the readme was adapted from the GitHub cloning a repository [documentation](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop).
- All other content was written by the developer.

### Media

- The hero image was from [Unsplash](https://unsplash.com/photos/I79Pgmhmy5M).
- The gluten-free was from [Needpix](https://www.needpix.com/photo/1208222/gluten-wheat-barley-food-diet-nutrition-gluten-free-eating-grain).
- The vegan icon was from [Wikipedia](https://upload.wikimedia.org/wikipedia/commons/7/79/Vegan_symbol.png).
- The cappuccino menu image was from [Unsplash](https://unsplash.com/photos/tPHZoqLkVw8).
- The latte menu image was from [Unsplash](https://unsplash.com/photos/s1-VmA26BIc).
- The caramel latte menu image was from [Unsplash](https://unsplash.com/photos/bbNssNJlsrk).
- The flat white menu image was from [Unsplash](https://unsplash.com/photos/ud_dMEf6M6k).
- The mocha menu image was from [Unsplash](https://unsplash.com/photos/72qDM1TA5p8).
- The americano menu image was from [Unsplash](https://unsplash.com/photos/N3bo4mkQEKM).
- The breakfast tea menu image was from [Unsplash](https://unsplash.com/photos/WgvTj1l6wps).
- The herbal tea menu image was from [Unsplash](https://unsplash.com/photos/7hohUWqBqU4).
- The croissant menu image was from [Unsplash](https://unsplash.com/photos/eUHKg4minfY).
- The pain au chocolat was from [Pixabay](https://cdn.pixabay.com/photo/2020/02/05/17/47/sweets-4821862_960_720.jpg).
- The bacon roll menu image was from [Unsplash](https://unsplash.com/photos/uhJfaJ6c9fY).
- The egg, bacon and sauage panini menu image was from [Unsplash](https://unsplash.com/photos/WcN0BupzoVg).
- The chicken and pesto menu image was from [Unsplash](https://unsplash.com/photos/z5UMFvTVXZg).
- The vegan meatball panini menu image was from [AnyRgb](https://c0.anyrgb.com/images/587/750/grilled-cheese-sandwich-food-kollam-india-school-lunch-school-canteen-bread-panini-table-paint-thumbnail.jpg).
- The chicken and salad sandwich menu image was from [Unsplash](https://unsplash.com/photos/IZ0LRt1khgM).
- The tuna and salad sandwich menu image was from [Unsplash](https://unsplash.com/photos/sBKLiRiunK0).
- The caramel shortbread menu image was from [Pikist](https://www.pikist.com/free-photo-vgadx).
- The chocolate brownie menu image was from [Piqsels](https://p0.piqsels.com/preview/480/697/97/dessert-food-chocolate-brownie.jpg).
- The flapjack menu image was from [Unsplash](https://unsplash.com/photos/-FyA5fhIPGI).
- The chocolate chip cookie menu image was from [Unsplash](https://unsplash.com/photos/7P-wc2Z2Ujs).

### Acknowledgements

- I received inspiration for this project from [Avanti West Coast](https://www.avantiwestcoast.co.uk), [Tim Hortons](https://timhortons.co.uk), [Cafe Nero](https://caffenero.com/uk/), [Costa Coffee](https://www.costa.co.uk) and [Axe and Cleaver](https://www.chefandbrewer.com/pubs/cheshire/axe-cleaver/).
