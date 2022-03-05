# Testing

## User Stories

Current User Goals

* As a current user, I want to be able to easily navigate through the site and access the information I need.
    - The nav bar is responsive and allows the user to select the page they want to access. Page titles are descriptive of their content.
* As a current user, I want to easily find out when I might receive a reply to my inquiry.
    - The response times table under the contact us form provides the user with the information
* As a current user, I want to be able to get to know the dogs and learn about the service.
    - The home page clearly displays information about the service's history, mission and values on the 'About us' page, and details and pictures of the dogs on the 'Meet the Dogs' page.
* As a current user, I want to be able to access the service's social media platforms.
    - The footer contains clear links to Facebook, Twitter, Instagram and Youtube which open in new tabs. Each icon has an associated aria-label for screen-readers and accessibility.

New User Goals

* As a new user, I want to easily navigate the whole site.
    - The nav bar is responsive and allows the user to select the page they want to access. Page titles are descriptive of their content.
* As a new user, I want to see clearly what the site is about.
    - The tagline tells the user what the website is about, and is present on every page to reinforce the aim of the website.
* As a new user, I want to learn more about the benefits of caring for a dog.
    - The home page contains a clear section about the health benefits of caring for a dog. 

Animal Lover Goals

* As an animal lover, I want to be able to easily see all the dogs available, see how I can get in touch and submit an inquiry.
    - The meet the dogs page allows the user to see all the dogs available, and the contact us page clearly shows how to get in touch with the service. There is also a clear location provided on the About Us page in case the user wishes to visit the service in person.
* As an animal lover, I want to be able to see the history of the service, and what their mission/values are.
    - The About us page clearly shows the history, mission and values of the service.

## Browser compatibility

Initial testing was done using Google Developer Tools while coding the project. Links, images, presentation and different screen sizes were all checked using this tool.

When the website was deployed, I was able to check the site on mobile devices, and identified some bugs.

* Meet the dogs page- Images and bios were squashed together
* About us page- Mission contents weren't aligned
* Home page- Pictures lacked margin

These were all fixed with the small screen media queries.

Google Chrome, Microsoft Edge, Mozilla Firefox and Safari all display content and images correctly and all links work and open in new windows.

The form correctly sends the user to the thankyou page once the data is submitted, and the form data validation works correctly.
I attempted to submit without filling out each field, and was presented with a message to fill out the required data (First name, Last name, Email).
When attempting to use a non-valid email address in the email field, the relevant error message appeared asking to use the correct format.

This was tested on a laptop, PC, iPad, Iphone SE, Galaxy S8 and a Motorola G9. 

## Accessibility

The site has been checked using Google Lighthouse, with a score of 100 for accessibility.

![Lighthouse Screenshot](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/lighthouse.PNG "Screenshot of lighthouse check")

# Validator Testing

## HTML
No errors were returned when passing through the official W3C validator

![Home page HTML check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/html-check-home.PNG "Screenshot of Home page HTML check")
![About us page HTML check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/html-check-about-us.PNG "Screenshot of About Us page HTML check")
![Meet the dogs page HTML check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/html-check-meet-the-dogs.PNG "Screenshot of Meet the Dogs page HTML check")
![Contact us page HTML check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/html-check-contact-us.PNG "Screenshot of Contact Us page HTML check")
![Thankyou page HTML check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/html-check-thankyou.PNG "Screenshot of Thankyou page HTML check")

## CSS
No errors were found when passing through the official (Jigsaw) validator

![Home page CSS check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/css-check-home.PNG "Screenshot of Home page CSS check")
![About us page CSS check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/css-check-about-us.PNG "Screenshot of About Us page CSS check")
![Meet the dogs page CSS check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/css-check-meet-the-dogs.PNG "Screenshot of Meet the Dogs page CSS check")
![Contact us page CSS check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/css-check-contact-us.PNG "Screenshot of Contact Us page CSS check")
![Thankyou page CSS check](https://github.com/BenD2525/the-rescuers-p1/blob/main/documentation/css-check-thankyou.PNG "Screenshot of Thankyou page CSS check")

