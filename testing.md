# Random Old Books - Testing

## Functionality

### Links

#### Homepage links

|Feature|Expect|Action|Result|
|---|---|---|---|
|Navbar Logo link|When clicked, the page scrolls to the top|Clicked the logo when the page was scrolled to the bottom|The page scrolled to the top|
|Navbar "Shop & Events" link|When clicked, the page scrolls to the events header|Clicked the link  when the page was at the top|The page scrolled to the events header|
|Navbar "Subscription Box" link|When clicked, the page scrolls to the subscription box header|Clicked the link when the page was at the top|The page scrolled to the subscription box header|
|Navbar "Contact" link|When clicked, the page scrolls to the footer's contact details section|Clicked the link when the page was at the top|The page scrolled to the footer's contact details section|
|Events section "bookshop in Book Town" link|When clicked, the page scrolls to the footer's contact details section|Clicked the link|The page scrolled to the footer's contact details section|
|Footer social media icon: Bluesky|When clicked, the Bluesky homepage opens in a new tab|Clicked the icon|The Bluesky homepage opened in a new tab|
|Footer social media icon: TikTok|When clicked, the TikTok homepage opens in a new tab|Clicked the icon|The TikTok homepage opened in a new tab|
|Footer social media icon: Facebook|When clicked, the Facebook homepage opens in a new tab|Clicked the icon|The Facebook homepage opened in a new tab|

#### Form Success page links

|Feature|Expect|Action|Result|
|---|---|---|---|
|Navbar Logo link|When clicked, the homepage opens|Clicked the logo|The homepage opened|
|Navbar "Shop & Events" link|When clicked, the homepage opens and scrolls to the events header|Clicked the link|The homepage opened and scrolled to the events header|
|Navbar "Subscription Box" link|When clicked, the homepage opens and scrolls to the subscription box header|Clicked the link|The homepage opened and scrolled to the subscription box header|
|Navbar "Contact" link|When clicked, the homepage opens and scrolls to the footer's contact details section|Clicked the link|The homepage opened and scrolled to the footer's contact details section|
|"Return to the homepage" button|When clicked, the homepage opens|Clicked the button|The homepage opened|
|Footer social media icon: Bluesky|When clicked, the Bluesky homepage opens in a new tab|Clicked the icon|The Bluesky homepage opened in a new tab|
|Footer social media icon: TikTok|When clicked, the TikTok homepage opens in a new tab|Clicked the icon|The TikTok homepage opened in a new tab|
|Footer social media icon: Facebook|When clicked, the Facebook homepage opens in a new tab|Clicked the icon|The Facebook homepage opened in a new tab|

#### 404 Error page links

|Feature|Expect|Action|Result|
|---|---|---|---|
|Navbar Logo link|When clicked, the homepage opens|Clicked the logo|The homepage opened|
|Navbar "Shop & Events" link|When clicked, the homepage opens and scrolls to the events header|Clicked the link|The homepage opened and scrolled to the events header|
|Navbar "Subscription Box" link|When clicked, the homepage opens and scrolls to the subscription box header|Clicked the link|The homepage opened and scrolled to the subscription box header|
|Navbar "Contact" link|When clicked, the homepage opens and scrolls to the footer's contact details section|Clicked the link|The homepage opened and scrolled to the footer's contact details section|
|"Return to the homepage" button|When clicked, the homepage opens|Clicked the button|The homepage opened|
|Footer social media icon: Bluesky|When clicked, the Bluesky homepage opens in a new tab|Clicked the icon|The Bluesky homepage opened in a new tab|
|Footer social media icon: TikTok|When clicked, the TikTok homepage opens in a new tab|Clicked the icon|The TikTok homepage opened in a new tab|
|Footer social media icon: Facebook|When clicked, the Facebook homepage opens in a new tab|Clicked the icon|The Facebook homepage opened in a new tab|

### Forms

#### Event modal form

|Feature|Expect|Action|Result|Image|
|---|---|---|---|---|
|Events section "Book event" button|When clicked, the modal Event form opens|Clicked the button|The modal Event form opened| ![Events modal form](docs/events-form.png)|
|Name validation|An error message is displayed if the form is submitted when Name is empty|Submitted the form when Name was empty|An error message was displayed| ![Event form Name validation](docs/events-form-name-validation.png)|
|Empty Email Address validation|An error message is displayed if the form is submitted when Email Address is empty|Submitted the form when Email Address was empty|An error message was displayed| ![Event form empty Email Address validation](docs/events-form-email-validation.png)|
|Invalid Email Address validation|An error message is displayed if the form is submitted with an invalid Email Address|Submitted the form with an invalid Email Address|An error message was displayed| ![Event form invalid Email Address validation](docs/events-form-invalid-email-validation.png)|
|Event validation|An error message is displayed if the form is submitted with no Event selected|Submitted the form with no Event selected|An error message was displayed| ![Event form Event validation](docs/events-form-event-validation.png)|
|Seats validation|An error message is displayed if the form is submitted with no Seats selected|Submitted the form with no Seats selected|An error message was displayed| ![Event form Seats validation](docs/events-form-seats-validation.png)|
|Redirection after successful submission|When the form is successfully submitted, the Form Success page is loaded with the form's input values in the URL|Submitted the form|The Form Success page was loaded with the input values shown in the URL| ![Event form Seats validation](docs/events-form-submission-success.png)|

#### Subscription Box form
|Feature|Expect|Action|Result|Image|
|---|---|---|---|---|
|Name validation|An error message is displayed if the form is submitted when Name is empty|Submitted the form when Name was empty|An error message was displayed| ![Event form Name validation](docs/subscription-box-form-name-validation.png)|
|Empty Email Address validation|An error message is displayed if the form is submitted when Email Address is empty|Submitted the form when Email Address was empty|An error message was displayed| ![Event form empty Email Address validation](docs/subscription-box-form-email-validation-missing.png)|
|Invalid Email Address validation|An error message is displayed if the form is submitted with an invalid Email Address|Submitted the form with an invalid Email Address|An error message was displayed| ![Event form invalid Email Address validation](docs/subscription-box-form-invalid-email-validation.png)|
|Redirection after successful submission|When the form is successfully submitted, the Form Success page is loaded with the form's input values in the URL|Submitted the form|The Form Success page was loaded with the input values shown in the URL| ![Event form Seats validation](docs/subscription-box-form-submission-success.png)|

### 404 errors (page not found)

|Feature|Expect|Action|Result|
|---|---|---|---|
|Bespoke 404 error page|When the user tries to navigate to a missing page, the bespoke 404 error page opens|Visited a URL that doesn't exist on the site|The 404 error page opened|

![404 error page test](docs/404-page-not-found-test.png)

## Responsiveness

All pages are responsive, with layouts that work well on small, medium and large screens. The wireframe layouts were used for the initial implementation, but when the site moved to a single-page design the responsive layouts were changed to better suit the structure of a one-page site.

During final testing I found no issues with the responsive design as these had all been picked up and resolved during development.


### Homepage on mobile

![Homepage on mobile](docs/responsive-homepage-mobile.jpeg)

### Homepage on tablet

![Homepage on tablet](docs/responsive-homepage-tablet.jpeg)

### Homepage on desktop

![Homepage on desktop](docs/responsive-homepage-desktop.jpeg)

### Form Success page on mobile

![Form Success on mobile](docs/responsive-form-success-mobile.jpeg)

### Form Success page on tablet

![Form Success on tablet](docs/responsive-form-success-tablet.jpeg)

### Form Success page on desktop

![Form Success on desktop](docs/responsive-form-success-desktop.jpeg)

### 404 Error page on mobile

![404 Error on mobile](docs/responsive-404-mobile.jpeg)

### 404 Error page on tablet

![404 Error on tablet](docs/responsive-404-tablet.jpeg)

### 404 Error page on desktop

![404 Error on desktop](docs/responsive-404-desktop.jpeg)

## Browser tests

I tested the site's functionality and responsiveness on Edge, Chrome and Firefox, as these are some of the most popular browsers.

All of the functionality and responsiveness screenshots above were taken on Edge, so I've included a few additional screenshots of the site on Chrome and Firefox in this section. 

### Homepage at tablet width on Chrome

![Homepage on Chrome](docs/browser-testing-chrome-homepage.png)

### Event form validation at tablet width on Chrome

![Event form validation on Chrome](docs/browser-testing-chrome-homepage-event-form.png)

### Form Success page at desktop width on Firefox

![Form Success on Firefox](docs/browser-testing-firefox-form-success.png)

### 404 Error page at desktop width on Firefox

![404 Error on Firefox](docs/browser-testing-firefox-404.png)

## Code validation

### HTML validation

HTML validation was carried out using the [W3 HTML Validator](https://validator.w3.org/).

#### index.html

*Error: Header must not appear as a descendant of the footer (fixed)*
- The footer contained a header element which has now been removed.

*Error: The for attribute of the label element must be the ID of a non-hidden form control (fixed)*
- On the events form, the "event" and "seats" inputs didn't have ID attributes. To fix this, I gave them the same ID as their name attributes.

*Error: Duplicate ID (fixed)*
- The events and subscription box forms both had inputs with IDs "name" and "email". To fix this, I gave them IDs using prefixes "events" and "subscription-box".

*Warning: Section lacks heading (fixed)*
- Some sections didn't have a heading as a direct descendent. I fixed this by changing these sections to divs as I had used too many section elements.

*Info: Trailing slash on void elements (not fixed)*
- Trailing slashes are inserted by the Prettier formatting extension that I use in VS Code. Given that the point of using an opinionated auto-formatter is to standardise formatting and avoid formatting arguments, I decided to leave these trailing slashes in place, even though they are not considered best practice.

![Homepage HTML validation](docs/validation-html-homepage.png)

#### form-success.html

*Error: Header must not appear as a descendant of the footer (fixed)*
- The footer contained a header element which has now been removed.

*Warning: Section lacks heading (fixed)*
- The social media section lacked a heading. I converted this section into a div as it didn't have enough content to warrant being a section.

*Info: Trailing slash on void elements (not fixed)*
- Trailing slashes are inserted by the Prettier formatting extension that I use in VS Code. Given that the point of using an opinionated auto-formatter is to standardise formatting and avoid formatting arguments, I decided to leave these trailing slashes in place, even though they are not considered best practice.

![Form Success HTML validation](docs/validation-html-form-success.png)

#### 404.html

*Info: Trailing slash on void elements (not fixed)*
- Trailing slashes are inserted by the Prettier formatting extension that I use in VS Code. Given that the point of using an opinionated auto-formatter is to standardise formatting and avoid formatting arguments, I decided to leave these trailing slashes in place, even though they are not considered best practice.

![404 HTML validation](docs/validation-html-404.png)

### CSS Validation

CSS validation was carried out using the [W3 CSS Validator](https://jigsaw.w3.org/css-validator/).

#### styles.css

*Errors: None*

![CSS validation errors](docs/validation-css-style-error.png)

*Warnings: 3*
  - There were warnings about CSS variables not being statically checked. As the CSS variables have effectively been tested by the site's functional and visual tests, these warnings can be ignored.

![CSS validation warnings](docs/validation-css-style-warnings.png)

### Javascript validation

Javascript validation was carried out using [JS Hint](https://jshint.com/).

#### script.js

*Warnings or errors: None*

![Javascript validation](docs/validation-js.png)

## Contrast checker

Contrast strength was checked using the [WebAim Contrast Checker](https://webaim.org/resources/contrastchecker/).

### Contrast between #FFFFFF (white) text on #567A79 (green) background

All tests passed at AA level.

![Testing white and green contrast](docs/testing-contrast-white-green.png)

### Contrast between #FFFFFF (white) text on #504746 (brown) background

All tests passed at AA and AAA levels.

![Testing white and brown contrast](docs/testing-contrast-white-brown.png)

## Lighthouse

Each page was tested with Lighthouse, using Mobile and Desktop settings.

|Page|Device|Result|
|---|---|---|
|index.html|Mobile| ![lighthouse mobile result for index.html](docs/testing-lighthouse-index-mobile.png) |
|index.html|Desktop| ![lighthouse desktop result for index.html](docs/testing-lighthouse-index-desktop.png) |
|form-success.html|Mobile| ![lighthouse mobile result for form-success.html](docs/testing-lighthouse-form-success-mobile.png) |
|form-success.html|Desktop| ![lighthouse desktop result for form-success.html](docs/testing-lighthouse-form-success-desktop.png) |
|404.html|Mobile| ![lighthouse mobile result for 404.html](docs/testing-lighthouse-404-mobile.png) |
|404.html|Desktop| ![lighthouse desktop result for 404.html](docs/testing-lighthouse-404-desktop.png) |

## Unfixed bugs

There are no remaining bugs that I am aware of. Having said that, even after thorough testing I cannot completely rule out the possibility of some hidden bugs.
