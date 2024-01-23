# Kiki codes -  Testing

![Kiki codes shown on a variety of screen sizes](documentation/kiki_codes_mockup.webp)

Visit the deployed site: [Kiki codes](https://kikiberg.github.io/Kikicodes/)

Return back to the [README.md](README.md) file.

- - -

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
  * [Browser Compatibility](#browser-compatibility)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)
* [BUGS](#bugs-fixing)

Testing was ongoing throughout the entire build. I utilised Chrome developer tools whilst building to pinpoint and troubleshoot any issues as I went along.
During development I made use of google developer tools to ensure everything was working correctly and to assist with troubleshooting when things were not working as expected.
I have gone through each page using google chrome developer tools to ensure that each page is responsive on a variety of different screen sizes and devices.

- - -

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML and CSS on all pages of the website.

#### W3C HTML Validator

Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkikiberg.github.io%2FKikicodes%2F) | ![screenshot](testing/Kiki_codes_Testing_w3_html_Home.png) | Passed. No warnings or errors |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkikiberg.github.io%2FKikicodes%2Fabout.html) | ![screenshot](testing/Kiki_codes_Testing_w3_html_About.png) | Passed. No warnings or errors|
| Photos | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkikiberg.github.io%2FKikicodes%2Fphotos.html) | ![screenshot](testing/Kiki_codes_Testing_w3_html_Photos.png) | Passed. No errors. 1 warning for section lacking heading. I added this in CSS and turned it to hidden. |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkikiberg.github.io%2FKikicodes%2Fcontact.html) | ![screenshot](testing/Kiki_codes_Testing_w3_html_Contact.png) | Passed. No warnings or errors|

#### W3C CSS Validator

File | Screenshot | Notes |
| --- | --- | --- |
| style.css | ![screenshot](testing/Kiki_codes_Testing_w3_css.png) | Passed. No errors. 1 warning for google font import style. |

- - -

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

#### Desktop Results

![index.html](testing/Kiki_codes_Testing_lh_desktop_Home.png)

![about.html](testing/Kiki_codes_Testing_lh_desktop_About.png)

![photos.html](testing/Kiki_codes_Testing_lh_desktop_Photos.png)

![contact.html](testing/Kiki_codes_Testing_lh_desktop_Contact.png)

#### Mobile Results

![index.html](testing/Kiki_codes_Testing_lh_mobile_Home.png)

![about.html](testing/Kiki_codes_Testing_lh_mobile_About.png)

![photos.html](testing/Kiki_codes_Testing_lh_mobile_Photos.png)

![contact.html](testing/Kiki_codes_Testing_lh_mobile_Contact.png)

- - -

### Browser Compatibility

I have tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Photos | Contact | 
| --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browser-chrome-home.jpg) | ![screenshot](documentation/browser-chrome-about.jpg) | ![screenshot](documentation/browser-chrome-contact.jpg) | ![screenshot](documentation/browser-chrome-birthday-cakes.jpg)| ![screenshot](documentation/browser-chrome-speciallty-cakes.jpg) | ![screenshot](documentation/browser-chrome-sweet-treats.jpg) | Works as expected |
| Edge | ![screenshot](documentation/browser-edge-home.jpg) | ![screenshot](documentation/browser-edge-about.jpg) | ![screenshot](documentation/browser-edge-contact.jpg) | ![screenshot](documentation/browser-edge-birthday-cakes.jpg) | ![screenshot](documentation/browser-edge-speciallty-cakes.jpg) | ![screenshot](documentation/browser-edge-sweet-treats.jpg) | Works as expected |

- - -

## MANUAL TESTING

### Testing User Stories

`First Time Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to make it interesting enough for possible future employers to see. | There is a "say hi on Linkedin" link on the Home page leading to my profile on Linkedin. |
| I want the site to be responsive for different device sizes. | I have developed the site with responsiveness in mind. |
| I want the site to be easy to navigate. | Clean buttons are used throughout the site for navigation, much like a mobile app. The navbar is collapsing when being used on mobile. |

`Returning and Frequent Visitors`

|  Goals | How are they achieved? |
| :--- | :--- |
| I want to be able to see updates (news page) about Kiki's fulfillments. | Users will be able to follow my engagement and achievements as a fullstack software developer. |

- - -

### Full Testing

Full testing was performed on the following devices:

* Laptop:
  * Macbook Pro 2021 14 inch screen
* Mobile Devices:
  * iPhone 13 pro.
  * iPhone 11 pro.
  * Phone X.

Additional testing was taken by friends and family on a variety of devices and screen sizes. They reported no issues when using the website.

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |


`About Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |


`Photos Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |

`Contact Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |

- - -

## BUGS

