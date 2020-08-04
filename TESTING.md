# **Xclusive Suits - Testing Details**

[Main README.md file](https://github.com/Barronk99/milestone1-exclusivesuits/blob/master/README.md) 

[View website in GitHub Pages](https://github.com/Barronk99/milestone1-exclusivesuits)

## **Testing**

[W3C CSS Validation](https://jigsaw.w3.org/css-validator/)

[W3C Markup Validation](https://validator.w3.org/)

W3C CSS Validation service and W3C Markup Validation service was used to check the validity of the code.

### **Client Stories Testing:**

Websites most common path:
* Home >> The Xclusive Experience >> Xclusive Materials >> About Us
* Each page has the contact us section at the bottom of its page so at any time when a visitor feels comfortable they can send an enquiry easily regardless of which page they are currently on.

### **Testing the client stories from the UX section in README.md file** ###

1. As a new visitor I want to be able to easily navigate around the site and find relevant information
    * a) Every page has the navbar at the top and a footer at the bottom with links to all pages on the site.
    * b) The logo in the navbar is linked to the home page so clicking it will always take a user back to the home page.

2. As a potential client I want to be presented with proof of a good service through positive testimonials
    * a) The Xclusive Experience page provides detailed testimonials from reputable people. This makes sure the potential client feels reassured.

3. As a new visitor I want to be presented with an aesthetically pleasing website
    * a) The website is made with a consistent colour scheme.
    * b) The wbesites typography is consistent with it's fonts, text alignment and headings.
    * c) The website adjusts on different screen sizes to maintain it's clean, professional and aesthetically pleasing look.

4. As a potential client I want to be able to contact the company and see where they are located
    * a) The website has a contact us section on every page which features the location and telephone number of the company along with a contact form so users can send enquiries and check the location of the company at any time.

5. As a potential client I want to be able to send an enquiry form.
    * a) The websites 'Contact Us' section features an equiry form where users can also include a message for any specific information they would like answered.

6. As a potential client I want to know more about the company and what their goal is 
    * a) The about us page features a section about the company history and their goals.
    * b) The about us page also features a section about the CEO and an insight into his work which is a reflection on the company.

7. As a potential client I want to see the process I will go through to have my suit tailored
    * a) The Xclusive Experience page has a short, concise and informative video demonstrating the process of having a suit tailored with Xclusive Suits.

8. As a potential client in the future I want to keep up to date with the business via social media 
    * a) The footer includes links to the most popular social media pages the business uses.

9. As a visitor I want links to social media to open in a new tab so I do not lose where I was on the site
    * a) All social media links have an attribute set so they open in a new tab.

### **Manual (Logical) Testing of all the elements and functionality on each page**

#### **Home Page:**

1. Navigation Bar:
    * I opened the page on a desktop and used dev tools to switch the view to a ipad to test if the navigation bar is responsive. The test was successful and the navigation items collapse into a hamburger menu icon.
    * I checked for any overflow in the navbar causing a change in sizing for the navigation items. Test was succussful and there is no overflow.
    * I have hovered over the logo on desktop view and checked if the alt text appears especially for screen readers. The alt text did not appear however I have since added this feature and it now appears.
    * I have clicked on the logo in the navigation bar to ensure it links back to the home page from all pages. Test was successful.
    * I have clicked on each navigation item to ensure it links to the correct page. Test was successful.
    * I have clicked on the 'Contact Us' item and checked that it scrolls down to the bottom of each page where the contact us section is located. Test was successful.
    * I have changed the screen size to mobile and verified that the menu icon drops down and shows each item without any spacial or sizing problems. Test was successful.
    * *Repeated each of these steps on a mobile and a tablet.*

2. Full screen image carousel: 
    * Opened the home page on a desktop and verified the carousel takes up the full width and height of the screen. Test was successful.
    * Switched the view to tablet and then mobile to validate the responsiveness. Test was successful the images maintain their quality and resizes in proportion to the screen.
    * Opened the home page and waited for a few seconds to see if the images automatically scroll to the next one. Test was successful.

3. Short sales pitch section:
    * Opened the home page on a desktop and reduced and expanded the screen resolution to verify that the text is responsive across all devices and screen sizes. Test was successful.

4. Navigation Cards:
    * Opened the home page on desktop to ensure each card shared equal spacing in one column. Test was successful.
    * Reduced the screen size to mobile and tablet to verify that the cards take up their own column and appear one after the other. Test was successful.
    * Clicked on each card's button that directs to it's designated page to test that their links were working and directed users to the right page. Test was successful.

5. Contact Us: 
    * Opened the page and scrolled to the contact us section to verify it was there after the content of the page. Test was successful.
    * Reduced and expanded the window to verify the contact us section is fully respnsive. Test was successful.
    * Attempted to submit the contact form without filling in each required field to verify it would pop up with an error message. Test was successful.
    * Attempted to submit the contact form without entering a correct email format to ensure that it would pop up with an error message. Test was successful.

5. Footer:
    * Clicked on each social icon to ensure that they link to the correct site and are working. Test was successful.
    * Clicked on each social icon to ensure that they open in a new tab. Test was successful.
    * Clicked on each page link to ensure that they link to the correct page and do not open in a new tab. Test was successful.
    * Reduced and expanded the screen to ensure that the footer was fully responsive and did not cause any content to be commpressed and overlap. Test was successful.

6. *Double checked all responsiveness and functionality on mobile and tablets.*

#### **The Xclusive Experience page:**

1. Navigation bar:
    * Navigation bar is identical across all pages on the site. Test was already successful.

2. Page Heading & Small print text:
    * Opened the page on desktop and reduced and expanded the window to ensure the text was fully responsive. Test was successful.

3. Demo video:
    * Opened the page and resized the window to ensure the video took the full width of the screen on different sized screens. Test was successful the video is fully responsive.
    * Opened the page and waited a few seconds to make sure the video does not auto-play and use my data. Test was successful.
    * Opened the page and played the video until the end to ensure the video would not automatically restart to make sure my data wasn't over used. Test was successful.

4. Video Caption:
    * Opened the page on a desktop and reduced and expanded the screen resolution to verify that the text is responsive across all devices and screen sizes. Test was successful.

5. Full width image of the steps:
    * Opened the page and verified the image spans across the full width of the screen without any extra white space. Test was successful.
    * Resized the view to tablet size to verify that the image remains the full width of the screen without any extra white space at either side. Test was successful.
    * Resized the window to mobile to verify that the image splits into two images on these screen sizes and each take up their own column so they appear one after the other. Test was successful.

6. Testimonials section:
    * Opened the page on desktop to verify that the testiomnials share the column width equally by a third and do not overlap on desktop. Test was successful.
    * Resized the view to a tablet to verify that the testimonials remain in a shared column equally taking a third of the space without any of their contet overlapping. Test was successful.
    * Resized the view to a mobile screen to verify the testiomnials changed so they each take up a full width column and appear one after the other without any content overlap. Test was successful.
    * Verified that the text remained center aligned across all screen sizes. Test was successful.

7. Contact Us:
    * Contact Us is identical on all pages across the site. Testing already successful.

8. Footer: 
    * Footer is identical on all pages across the site. Testing already successful.

#### **Xclusive Materials page:**

1. Navigation bar:
    * Navigation bar is identical across all pages on the site. Test was already successful.

2. Page Heading:
    * Opened the page on desktop and reduced and expanded the window to ensure the text was fully responsive. Test was successful.

3. Modals: 
    * Opened the page on desktop and verified the 4 modals shared 2 columns with 2 modals in each column equally taking half width of the screen. Test was successful.
    * Resized the view to tablet and mobile to verify each modal takes up it's own column so they appear one after the other. Test was successful however the only exception was the iPad Pro as it has a screen size over 892px so it is classed a large screen and can handle the 4 models appearing as they do on desktop.
    * Reduced and expanded the screen to test that the headings over the images were respnsive and did not fall outside the image. The headings were not respnsive but on screens between 339px and 400px the headings began to fall out of the image. Although this is insignificant as these screen sizes do not match with tablet and mobile screens, the issue will be resolved by adding a new media query.
    * Clicked on each modal to ensure it displayed the right information and content. Test was successful.
    * Reduced and expanded the window after clicking on a modal to verify it was fully responsive. Test was successful.

5. Contact Us:
    *Contact Us is identical on all pages across the site. Testing already successful.

4. Footer: 
    * Footer is identical on all pages across the site. Testing already successful.

#### **About Us page:** 

1. Navigation bar:
    * Navigation bar is identical across all pages on the site. Test was already successful.

2. Page Heading:
    * Opened the page on desktop and reduced and expanded the window to ensure the text was fully responsive. Test was successful.

3. Page content:
    * Opened the page on desktop to make sure the margin left and right was correctly set and centered the content with equal white space either side. Test was successful.
    * Reduced and expaded the window to verify that the margins left and right only appeard on large screens and dissapeared on medium and small screen so the content contained the entire screen. Test was successful.

4. Contact Us:
    *Contact Us is identical on all pages across the site. Testing already successful.

5. Footer: 
    * Footer is identical on all pages across the site. Testing already successful.





