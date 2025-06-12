### Functionality

#### Links

- Homepage
  - Navigation: All links working
  - Why Random: Contact Details link works
  - Footer: Social media links open correctly in new tabs
- Form Success page
  - Navigation: All links working
  - Thank-you section: Button works
  - Footer: Social media links open correctly in new tabs

#### Forms

- Event form
  - Modal opens correctly
  - Validation works for all fields
  - Redirects to Form Success page after submission
  - Field values correctly posted upon submission (visible in URL of Form Success page)
- Subscription Box form
  - Validation works for all fields
  - Redirects to Form Success page after submission
  - Field values correctly posted upon submission (visible in URL of Form Success page)

### Browsers and Responsiveness

I tested the site across a wide range of device sizes on Chrome, Edge and Firefox, as these are some of the most popular browsers.

All pages are responsive, with layouts that work well on small, medium and large screens. The wireframe layouts were used for the initial implementation, but when the site moved to a single-page the responsive layouts were changed to better suit the structure of a one-page site.

During final testing I found no issues with the responsive design as these had all been picked up and resolved during development.

### Validators 

#### HTML Validation

Validation was carried out using the [W3 HTML Validator](https://validator.w3.org/).

##### index.html
- Error: Header must not appear as a descendant of the footer (fixed)
  - The footer contained a header element which has now been removed.
- Error: The for attribute of the label element must be the ID of a non-hidden form control (fixed)
  - On the events form, the "event" and "seats" inputs didn't have ID attributes. To fix this, I gave them the same ID as their name attributes.
- Error: Duplicate ID (fixed)
  - The events and subscription box forms both had inputs with IDs "name" and "email". To fix this, I gave them IDs using prefixes "events" and "subscription-box".
- Warning: Section lacks heading (fixed)
  - Some sections didn't have a heading as a direct descendent. I fixed this by changing these sections to divs as I had used too many section elements.
- Info: Trailing slash on void elements (not fixed) 
  - Trailing slashes are inserted by the Prettier formatting extension that I use in VS Code. Given that the point of using an opinionated auto-formatter is to standardise formatting and avoid formatting arguments, I decided to leave these trailing slashes in place, even though they are not considered best practice.

##### form-success.html
- Error: Header must not appear as a descendant of the footer (fixed)
  - The footer contained a header element which has now been removed.
- Warning: Section lacks heading (fixed)
  - The social media section lacked a heading. I converted this section into a div as it didn't have enough content to be a section.
- Info: Trailing slash on void elements (not fixed) 
  - Trailing slashes are inserted by the Prettier formatting extension that I use in VS Code. Given that the point of using an opinionated auto-formatter is to standardise formatting and avoid formatting arguments, I decided to leave these trailing slashes in place, even though they are not considered best practice.

#### CSS Validation

Validation carried out using the [W3 CSS Validator](https://jigsaw.w3.org/css-validator/).  

##### styles.css
- No errors
- Warnings
  - There were warnings about imported style sheets (for Google Fonts) not being checked by the validator, and CSS variables not being statically checked. In this case, these warnings can be ignored.

### Contrast Checker

Contrast checked using the [WebAim Contrast Checker](https://webaim.org/resources/contrastchecker/).

- #FFFFFF (white) text on #567a79 (green) background: 4.71:1 contrast, passed all tests at AA level
- #FFFFFF (white) text on #504746 (brown) background: 9:1 contrast, passed all tests at AA and AAA levels

### Lighthouse

Each page was tested with Lighthouse, using both Mobile and Desktop Device settings.

##### index.html
![The site's lighthouse test results](docs/readme-lighthouse-index.png)

Accessibility and Best Practices scored 100 in all tests. 

Performance varied from 60% to 67%. To improve this, I used [Tiny PNG](https://tinypng.com/) to reduce the size of all images. Even after this change, the page's performance score only fell into the amber 50-89% range.

##### form-success.html
![The site's lighthouse test results](docs/readme-lighthouse-form-success.png)

The Accessibility score was 100%, but the Best Practices score was 81%. This was because the page included a H1 element without a specified font size. To fix this, I changed the heading to H2, which improved the score to 100%.

The Performance score was consistently around 80%.

### Unfixed Bugs

There are no remaining bugs that I am aware of, but even after thorough testing I cannot completely rule out the possibility of some hidden bugs.
