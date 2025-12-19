# Electronic-product-showcase
Electronic Market is a responsive front-end website designed to showcase and sell electronic products such as mobiles and laptops. 

The website allows users to browse products view items using a carousel and contact the market through the contact form/section or the social media links so the customer is able to click on icons.

I built the project as part of a milestone assessment to demonstrate skills in HTML, CSS and using Bootstrap as optional library, i focused on clean UI, responsiveness, and user experience. 

# User Experience (UX)
## User Story 1: View electronic products 
- As a user i want to clearly view the products 
features so that i can understand what the product offers.
# Acceptance Criteria
- I need a clear and concise description of the electronic products.
- I'd like to list the most important features as bullet points, not as a long text.
- I don't need to scroll much to find out the basic information.

## User Story 2: View Images 
- As a user i want to see high-quality images of the product so that I can know how it looks from different angles.
# Acceptance Criteria
- I see a clear main image of the product.
- I see more than one image (from different angles).
- Images are of appropriate quality.


## User Story 3: Easy to navigate 
- As a user i want simple and clear navigation  so that I can move easily between the website pages.
# Acceptance Criteria
- Text and images change according to screen size.
- The navigation menu becomes a drop-down menu on the phone.
- There is no horizontal scrolling


## User Story 4: devise compatibility 
- As a user i want the website to be responsive that I can view it comfortably on mobile, tablet, and desktop.
# Acceptance Criteria
- Having a table or detailed list of specification.
- The information is organized, such as: weight battery and connection.
- The format is easy to read.



## User Story 5: Price details
-  As a user i want to see pricing so that I can decide whether to buy the product.
# Acceptance Criteria
- The price is obvious and needs no further explanation.
- Appears on the product page.
- It appears in an attractive visual style (card or box shape).


## User Story 6: Contact
- As a user i want to access a contact form so that I can ask questions or request more information about the product. 
# Acceptance Criteria
- The Contact page is working.
- It has a simple form: Name-Email-Message.
- I can send a message 

## Live Link of the Project
[Electronic Market](https://darksyntax99.github.io/Electronic-product-showcase/)

## Responsiveness 
I Tested on:
- Desktop (  ≥ 1024px)
- Mobile (≤ 375px)
- Tablet ( 768px)

## Browsers 
Tested on:
- Crhome 
- Firefox
- safari 

## HTML Validators 
All HTML passed without errors 
[The test](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdarksyntax99.github.io%2FElectronic-product-showcase%2F)

## CSS Validators
All CSS passed with no errors but some warnings
[The test](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdarksyntax99.github.io%2FElectronic-product-showcase%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Lighthouse (Chrome DevTools)
- Best Practices **100**
- Accessibility **90**
- SEO **91**
- performance **74**

## About the Lighthouse Performance Note 
The performance score is affected by the use of high-resolution images and probably external libraries such as bootstrap and font awesome. Maybe the images optimization and lazy loading could improve performance in iterations.

## Built by
- HTML5
- CSS3
## Library
- Bootstrap v5.3.8
## Fonts
- Google Fonts 
## Icons 
- Fonts Awesome
## Manual testing 
Test: navbar links.
Action: click on home,products,contact.
Result: Navigate to index.html, prodcut.html, contact.html.
Test: image slide.
Action: for auto slide.
result: images rotate automatically.
Test: controls.
Action: click next/prev buttons.
Result: images change correclty.
Test: image display.
Action: resize screen.
Result: images remain centred and scaled.
Test: Name, Email, Message input .
Action: enter text,email, message.
result: text appears correctly, email accepted, message displayed correctly.
Test: submit button.
Action: click submit.
result: form submits without errors.
Test: facebook, instagram icons.
Action: click icons.
result: opens in new tab.

## Bugs and Fixes
Bug: navbar overlapping content. 
Cause: fixed navbar height.
Fix: added padding-top to body.
Bug: icons hover inconsistency.
Cause: CSS specificity.
Fix: used targeted selectors.
Bug: layout spacing issues.
Cause: bootstrap defaults
Fix: custom CSS adjustments
all known issues were resolved before final submission.
## Wireframes 
Wireframes were created during the planning stage to define the basic structure and layout of the website across different screen sizes. Each page was designed with a mobile-first approach and adapted for desktop and tablet screens.

### Homepage Wireframes
![Homepage Desktop Wireframe](wireframes/AD3B9C45-32B9-4104-BC05-F4922DBB55D4_1_201_a.jpeg)
*Desktop Homepage Layout*

![Homepage Mobile Wireframe](wireframes/799286BD-15D6-4F4B-8E35-2BE253B3523F_1_201_a.jpeg)
*Mobile Homepage Layout*

![Homepage Additional View](wireframes/A6CE0B62-1F70-4568-89F0-414678477A0C_1_201_a.jpeg)
*Homepage Alternative Layout*

### Products Page Wireframes
![Products Desktop Wireframe](wireframes/60814CBD-8393-4C75-AF1A-F9AE6E825E0A_1_201_a.jpeg)


![Products Mobile View](wireframes/9479A4AC-4EE7-4C7C-A38D-804FAE1CD5E5_1_201_a.jpeg)


![Products Additional View](wireframes/8ABD65B1-F88A-4CF4-96ED-F807DD1E339F_1_201_a.jpeg)


### Contact Page Wireframes
![Contact Desktop Wireframe](wireframes/328DA751-F51E-4F4A-9C6C-2AA24AC26BFA_1_201_a.jpeg)


![Contact Mobile View](wireframes/C4F8DB3D-1CFE-414D-BAC2-68274CCF6896_1_201_a.jpeg)


### Additional Design Wireframes
![Design Concept 1](wireframes/2693AC0D-D0C4-43F7-9565-5C7E01276FFD_1_201_a.jpeg)


![Design Concept 2](wireframes/D4323868-92EC-4A8A-B654-5C0EDEAFDE19_1_201_a.jpeg)


![Overall Site Structure](wireframes/AFE26C30-EF17-4380-9140-38F59108F80D_4_5005_c.jpeg)


## Home page 
- mobile view 
navigation menu
Carousel 
product show and contact buttons
products 
footer with information and social icons
- desktop 
full navigation bar
large hero section
products displayed clearly with more space
footer with information and social icons
- tablet
navigation menu expanded
product carousel displayed wider
improved spacing between sections
## product page
- mobile 
navigation menu
Carousel with images 
contact us buttons 
product cards with price and buy button.
footer with information and social icons
- desktop
multi-column product grid
clear pricing and feature visibility
- Tablet View
multi column product layout
## Contact Page
- Mobile View
stacked contact form
easy-to-tap input fields
- Tablet View
centered form with improved spacing
- Desktop View
wide contact form layout
social media icons displayed clearly


## ABOUT THE AI (github copilot)
I used AI during the development of this 
project strictly as a learning tools.
- Understanding responsiveness issues and layout behavior.
- improve understanding of lighthouse.
All code in this project was written, adapted, and fully understood by me.
No AI-generated code was copied directly into the project.
AI was only consulted in specific situations to help identify issues (for example understanding when and why !important might be necessary) after which I implemented the solutions myself
I remain fully responsible for the project’s structure code decisions and final implementation.

