# Simply Korean
The Simply Korean website acts to advertise a Korean restaurant by providing information and allowing customers to make a reservation at the restaurant. The website aims to attract lovers of Korean food, as well as encourage people who have never tried the cuisine before. 

Users on the website will be able to learn a little about Korean cuisine and see what meals are available at the restaurant. They are also able to see reviews, make reservations and find relevant contact information.

![Responsive view](/assets/images/responsive.jpg)

## Features
- Navigation
  - Functions to clearly display the restaurant name and allow access to all pages in the website.
  - Located at the top of the page in a fixed position so that it can easily be accessed even after scrolling down the page.
  - An easy to read 'Montserrat' font is used. The font and background colors provide sufficient contrast.
  - The bold logo is positioned to the left and acts as a link to easily return to the homepage.
  - Links to other pages are located on the right and include: Menu, Reservation and Contact.
  - The active page is underlined as a reference and links have a underline hover effect.
  - On smaller devices, a hamburger button is used to show the links when clicked. This was coded by placing the icon within a label element for a checkbox.

![Navigation Bar](/assets/images/navigation.jpg)

![Responsive Nav Bar](/assets/images/responsive-navigation.png)

![Responsive Nav Bar Clicked](/assets/images/responsive-nav-clicked.png)

- The Main Image Section
    - Background image of kimchi fried rice instantly shows the type and quality of food available at the restaurant.
    - The heading 'Your Local Authentic Korean Food' shows the function and aim of the restaurant to users.
    - The 'Make a Reservation' link is clear and consistent with the color theme and acts to advertise and allow users towards the reservation page.

![Main Image Section](/assets/images/main-section.jpg)

- The About Us Section
    - This section aims to give an insight into the different foods on offer at the restaurant, as well as prompt users to explore further via links to the menu page.
    - The heading reinforces the restaurant's aim in terms of food quality.
    - The alternating image and text layout creates a more interesting design.
    - Images are used to clearly represent the type and quality of food available.
    - Text is used to explain more detail about the food, culture and experience at the restaurant.

![Abous Us Section](/assets/images/about-section.png)

- Reviews Section
    - Title is consistent with the theme and functions to explain that the section contains customer reviews.
    - Background image is used to illustrate a sense of enjoyment at the restaurant.
    - Reviews either side create a more interesting design.
    - Reviews chosen are from different types of customers with varying experience eating Korean food to show customers that the restaurant can be enjoyed by everyone.

![Reviews Section](/assets/images/review-section.jpg)

- Footer Section
    - Contains contact information and opening times so they can be easily found by users whilst on any page.
    - Social media links encourage users to find out more about the restaurant.
    - Links open in new tabs to provide a good user experience.

![Footer Section](/assets/images/footer.jpg)

- Menu Page
    - The menu page aims to advertise a selection of dishes at the restaurant and raise interest.
    - The heading explains that a full menu with more dishes is available at the restaurant.
    - Images were used along with a description to illustrate the quality of food available at its price.
    - Different sections containing three dishes were used to create an organised display.
    - Using flexbox, the dishes are arranged in a single column to provide a better user experience on smaller devices.

![Menu Page](/assets/images/menu.png)

- Reservation Page
    - This page allows users to book a table at the restaurant by completing a form.
    - Users are required to provide their contact details and select the date, time and number of people attending.
    - A text area was created so users can send a message or make a special request.
    - This page is useful as it provides another method to make a reservation, instead of relying on making a telephone booking.

![Reservation Page](/assets/images/form.png)

- Contact Page
    - This page provides the restaurant's address, phone number and email address for customers to contact.
    - Opening times are also provided so users know when the restaurant can be contacted.
    - An iframe showing the address was also used to assure customers of the restaurant's location.

![Contact Page](/assets/images/contact.png)

## Testing

- The website has been tested and works on different browsers: Chrome, Safari, Microsoft Edge.
- All text can be seen clearly and isn't disrupted by another element.
- All form inputs are required, except the 'leave message' as intended and the form submit button works.
- The home page is responsive on all standard screen sizes and functions correctly.
![Responsive Home Page](/assets/images/responsive.jpg)
- The menu page is responsive on all standard screen sizes and functions correctly.
![Responsive Menu Page](/assets/images/responsive-menu.jpg)
- The reservation page is responsive on all standard screen sizes and functions correctly.
![Responsive Reservation Page](/assets/images/responsive-reservation.jpg)
- The contact page is responsive on all standard screen sizes and functions correctly.
![Responsive Contact Page](/assets/images/responsive-contact.jpg)

## Solved Bugs

- When making the main image section on the home page, the 'Make Reservation' link would center slightly to the left when using "margin 0 auto". This led me to learning flexbox to center and arrange this element, as well as the rest of the website.

![Reservation Link Error](/assets/images/reservation-error.png)

- After fixing the link error, it caused a white area to appear under the navigation bar. This space got bigger on smaller screens and was fixed using overflow:hidden.

![Navigation White Space Error](/assets/images/nav-error.png)

![Navigation White Space Error Mobile](/assets/images/nav-error-mob.png)

- When dividing the review section into three equal columns using floats and margin 0 auto, the right section was being positioned below the others. Again I solved this error by using flexbox.

![Review Error](/assets/images/review-error.png)

- On some pages when viewing on smaller devices, a horizontal scroll bar would appear. I solved this problem by a combination of setting overflow-x:hidden and making sure that no elements had an absolute width exceeding the width of the screen.

## Unfixed Bugs

- There are no remaining found bugs.

## Validator Testing

- HTML
    - Official W3C validator returned no errors.
- CSS
    - Official W3C validator returned no errors.

## Lighthouse Testing

![Lighthouse Test](/assets/images/lighthouse.png)

## Deployment

- The site was deployed to GitHub pages by:
    - Selecting 'Settings' in the GitHub repository.
    - From the source section drop-down menu, select the Master Branch.
    - This will then indicate that the project has been deployed successfully.

The link for this project: https://jamesmartin1998.github.io/HTML-CSS-Project/

## Credits

- Navigation bar html and css was created following a Youtube tutorial and adapted as necessary 
(https://www.youtube.com/watch?v=oLgtucwjVII)

- Review section HTML and CSS was based on code used in Code Institute's Love Running Project but was adapted on using flexbox

- Social links code was used from Code Institutes Love Running Project

- Icons used for social links are from Font Awesome

- Images used were taken from Pexels.com and Pixabay.com