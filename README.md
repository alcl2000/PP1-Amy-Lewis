# Frost's Bakery
## Introduction
This project is a bakery's website, alowing users to find out opening and closing times, the bakery's location and menu. As well as place an order for delivery or collection. The site is targeted towards customers of all ages in the local area, it will provide users with ways to find and contact the bakery; as well as be able to see and order the food from the site

The live website can be found [here](https://alcl2000.github.io/PP1-Amy-Lewis/index.html)

![A website showing the completed website on several different devices including phones, tablets and laptops](assets/content/readme/responsive.jpg)
## UserExperience
### User stories
1. As a local of the area I would like to be able to find new and exciting options for food and to support the local ecoonomy by avoiding commercial coffee shops and bakeries. 
2. I am looking to buy a cake for an upcoming event, I would like to find and order this online
3. I am new to the area and looking for new bakeries and cafes to try out
4. I would like to visit Canterbury for the day and buy food while I'm there, I am looking for an option in the city center
### User Expectations
1. I expect Information to be laid out in an easy to read manner
2. I expect to be able to find an address and a menu for this buisness
3. I expect to be able to use the website easily, and for it to have a responsive interface
4. I expect to be able to place an order, and for this process to be simple

## Wireframes
### Inital Wireframes used for this project
The inital wireframes do not exactly match the end project, but still show the user a base idea of how the website will look on different pages and devices.
![A sitemap created in wireframe for to show the stucture of pages within this project](assets/content/readme/wireframe-sitemap.jpg)
![A wireframe created for the home page, on larger screens](assets/content/readme/wireframe-homepage-large.jpg) 
![A wireframe created for the home page, on smaller screens](assets/content/readme/wireframe-homepage-small.jpg) 
![A wireframe created for the menu page, on large screens](assets/content/readme/wireframe-menu.jpg) 
![A wireframe created for the order page, on large screens](assets/content/readme/wireframe-order.jpg) 
## Features
### Header & Navigation Bar 
![The Finished Header and navigation bar](assets/content/readme/finished-header.jpg)
The header provides a welcome to the site, with a bold title on top and a friendly tagline to welcome users in. The fonts used a both credited below, and both have alternate tags for users who's browsers may not support the linked fonts.

The navigation bar is placed directly below the header for ease of access by users, it contains 3 evenly spaced links to the other pages of the site, making it easy to navigate through. The navigation anchor tags contain the 'id="open"' so that the open links display at a different colour, making the site easier to navigate.

### Footer
![The finished footer and links](assets/content/readme/finished-footer.jpg)

At the bottom of each page there is a footer, which provides links to several social media pages. All of these links have aria-labels for accessibility and open in a new page to make navigation easier. The footer also contains a small copy right to demonstrate the ownership of the website.

### Landing Page
![The finished index page showing a video and the USP of the company](assets/content/readme/finished-video.jpg)
![The finished index page showing the map address and contact details for the bakery](assets/content/readme/finished-contact.jpg)

The landing/Index page acts as a home page to the Bakery Website; it has a short about section and a section with the Frost's unique selling point as a way to encourage new customers. There is also a video, demonstrating common baking techniques as a way of inticing customers, the video plays on mute and allows users to pause or play it with the use of controls. The landing page also has a map and address section, which fulfills user expectation 2. 
### Menu 
![The finished menu page showing the three menu cards with different options available through the bakery](assets/content/readme/finished-menu.jpg)

The menu page contains three boxes which display Unordered lists, these contain different menu items which customers may want to order, fulfilling both expectations 1 and 2.

### Ordering page 
![The finished order page showing the hero image at the top of the order page](assets/content/readme/finished-hero.jpg)
![The finished order page showing the order form at the bottom of the page, where users can place an order](assets/content/readme/finished-form.jpg)

The order page contains information about the ordering process and how it works, which fulfills expectation 1, it also contains an easy to use form to order food and decide whether to have it delivered or collect it, fulfilling expecation 4. 

### Thank you page
![The finished thank you page, with a back button to allow users to navigate without using the browser](assets/content/readme/finished-thank-you.jpg)

The thank you page acts as an order confirmation page, letting customers know that their order from the form has gone through and that their order will be processed. This page also has a back button, allowing users to navigate without needing to use the browser. 

## Features to implement   

In future, the scope of this project is set to expand, to increase functionality for both site owners and users. The 'Thank you' page will have an additional section telling the customer their order number and providing email confirmation of their order to help with deliveries and collection. The order page will feature a rolling total to display the price of the order for added ease of use by the customer.

## Testing
### Validation
All pages pass HTML validtion with no errors. [HTML Validation from](https://validator.w3.org/nu/#textarea)
Both CSS files pass validation with no errors. [CSS Validation from](https://validator.w3.org/nu/#l88c26)
### Manual Testing

All pages load quickly, and on devices with smaller screen sizes load with a different layout to increase loading times and to make the website look more modern. 

All links in the header work, and all links to external sites open in a different tab.

The video content on the index page loads quickly and on mute and pause, with controls available for the user to be able to play the video at will.

This website was developed using Google chrome, but the website still performs well on other browsers, such as Firefox and Edge
## Accessibility

All images and video content have alt-text provided, all links have attached aria-labels, helping users who need screen readers. The video and image content also has alternate text for people who's browsers does not support the content, as to support the web-content for user's who's browsers don't support HTML5.

The font sizes change with media queries in the CSS file, so the text remains legible at all screen sizes.

Some of the colours used in this project did not score highly enough in acessibility testers for contratst, so different colours were used instead.
![acessibility tester showing a warning over text saying 'order' the text is a light pink, with a brown background](assets/content/readme/acess-testing.jpg)
### Lighthouse scores 
- Desktop
![Lighthouse scores for desktop showing green in all categories](assets/content/readme/lighthouse-desktop.jpg)
- Mobile
![Light house scores for mobile showing green in all categories](assets/content/readme/lighthouse-mobile.jpg)
## Bug fixes
- The footer on pages with less content (ie the Thank You page) does not always stick to the bottom of the screen, often creating quite a large gap between content and the footer. This was resolved by adding the property of 'fixed' to the footer, and in the appropriate media queries.
- While not a bug, intially the hero image for the order page was too large a file size and was causing lags when opening the page on mobile, this was solved by compressing the image to decrease loading times and to make the site more responsive.

- Html validation showed several errors in the HTML code of various pages, these inlcuded:
    - The menu page containing a mixed up closing div tag and closing ul tag
    - The index page contained 2 elemments with the same id tag, this tage was changed to solve any discrepancies 
    - The order page's date input was rectified to remove an invalid attribute tag
## Deployment
Deployment of this project is done through GitHub pages, a cloud-based web hosting service, which will allow for changes to be made to the website post-deployment, in order to update menus and other details. The code is hosted through Github, allowing people to clone the project if desired.

The live website can be found [here](https://alcl2000.github.io/PP1-Amy-Lewis/index.html)

## Credits
### Technology used

This projected was developed using HTML and CSS code only.

### Media 
- Royalty free baking video By Taryn Elliot [Sourced from Pexels](https://www.pexels.com/video/stirring-flour-and-condensed-milk-in-a-mixing-bowl-3325984/)
- Royalty free pastry picture By Skyler Ewing [Sourced from Pexels](https://www.pexels.com/photo/freshly-baked-bread-with-cinnamon-9513725/)
### Other content
[Social media icons from Font Awesome](https://fontawesome.com/search?s=solid%2Cbrands)
#### Fonts through out the website 
- ['Arsenal' By Andrij Shevchenko](https://fonts.google.com/specimen/Arsenal?query=arsenal)
- ['Nothing you can do' by Kimberly Geswein](https://fonts.google.com/specimen/Nothing+You+Could+Do?query=nothing+)