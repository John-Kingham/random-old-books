# Random Old Books

Random Old Books is a website built for a fictional retailer of the same name that sells vintage books printed more than 20 years ago.

The business has one physical bookshop, where it also holds regular events with authors (events are free, but participants often buy books while they're at the store), and it has a mail-order subscription box service where subscribers are sent one random book per month.

The company's unique selling proposition is that it believes in the positive power of random events and chance encounters, so it adds a dash of randomness to its customers' lives by placing books randomly on its bookshelves and by sending out a random book each month to subscription box subscribers.

Todo: Include an image showing what the site looks like on various device sizes.

## User Experience Design

### Site Goals (Strategy Plane)

The backstory is that the Random Old Books business is struggling to remain viable as it doesn't have enough customers and its existing customers don't make enough repeat purchases. To help fix this problem, the manager wanted a new website to be developed with the following goals:

1. Raise awareness of the business and its services (a vintage bookstore, a subscription service and regular events)
2. Maintain the company's relatively understated branding
3. Make it easy for users to find and contact the store
4. Inform users about upcoming events and make it easy for them to book events
5. Inform users about the subscription box service and make it easy for them to sign up for a trial
6. Make it easy for users to subscribe to the company's free monthly e-newsletter, which promotes the store, upcoming events and the subscription box service

### User Personas (Strategy Plane)

There are three main user personas, one for each of the business's three main services (bookstore, subscription box, events):

**The Adventurous Browser**: Loves the thrill of unpredictability. Often buys books from authors they've never heard of, accepting whatever fate hands them.

**The Online Surprise Seeker**: Prefers reading experiences where every month brings a surprise. Embraces the challenge of reading whatever book they get, treating it as an opportunity to experience new things.

**The Conversational Enthusiast**: Values engaging discussions more than just the books themselves. Enjoys interacting with authors and readers, asking thought-provoking questions, and participating in lively debates.

### User Stories (Scope Plane)

#### User Story 1: A professional-looking, responsive, user-friendly interface

User story

- As an **Adventurous Browser**, I want to see a professional website that looks good on various screen sizes and is easy to navigate, so I'm not put off by a poor user experience.

Acceptance Criteria

- The website is responsive and looks good across all common screen widths.
- The site's pages and sections are intuitively laid out and easy to navigate.
- The site follows best practices for accessibility.

Tasks
- Use responsive design principles to ensure the site looks good on various device sizes.
- Structure the site based on best practices, so that all sections are easy to navigate to.
- Include accessibility attributes for screen readers. 

#### User Story 2: Enticing images and descriptions of the business, its products and services

User story
- As an **Adventurous Browser**, I want to learn about the business, its products and services, so I can decide if I'd like to visit the store.

Acceptance Criteria
- The site contains high-quality images of the store, subscription boxes and events, in prominent positions and in a way that looks attractive.
- The site contains enticing descriptions of the business, its bookshop, subscription service and events, which are clearly visible and easy to read on the homepage and other relevant pages.

Tasks
- Add high-quality images to the homepage and other pages.
- Add enticing descriptions to the site in intuitive and easy to find locations.

#### User Story 3: Location, opening hours and contact details

User story
- As an **Adventurous Browser**, I want to be able to easily find the store's location and opening hours, so I know where and when to visit.

Acceptance Criteria
- Each page prominently displays the store's location and opening hours.
- Each page prominently displays the company's email and phone number.

Tasks
- On each page, add a footer containing the store's location and opening hours, and the company's email and phone number.

#### User Story 4: Subscription box subscription form

User story
- As an **Online Surprise Seeker**, I want to be able to easily find a subscription box sign-up form, so I can subscribe immediately.

Acceptance Criteria
- The website contains a subscription box sign-up form.
- The form is located on the subscription box page which also includes compelling images and a detailed description of the service.

Tasks
- Create a subscription box page and a form success page.
- Add compelling images and descriptions of the subscription box service to the subscription box page.
- Add an easy to use sign-up form to the subscription box page that takes the user to the form success page.
- Add a thank you message and a "return to homepage" button to the form success page.
- Add relevant validation to the form.

#### User Story 5: List of events and booking form

User story
- As a **Conversational Enthusiast**, I want to see a list of upcoming events and a booking form, so I can decide which event to attend and book my place.

Acceptance Criteria
- The site includes a list of upcoming events in a prominent position, along with their status (seats available / fully booked).
- The site includes an event booking form where users can book their place on events where seats are still available.

Tasks
- Add an Events page.
- Add a list of events to the page, including the name of the speaker, a brief description and the events booking status (seats available / fully booked).
- Add an events booking form to the page that takes the user to the form success page after submission.
- Add relevant validation to the form.

#### User Story 6: E-newsletter sign-up form

User story
- As an **Conversational Enthusiast**, I want to be able to easily subscribe to the company's free e-newsletter, so I can be kept up to date with the latest events and book my seat before they've all gone.

Acceptance Criteria

- Users can sign up to the e-newsletter from any page on the site.
- The sign-up form is accessible from each page's footer.

Tasks

- Add a description of the newsletter to the footer of each page.
- Add an e-newsletter sign-up button that opens a modal which contains the sign-up form.

### Site Structure (Structure Plane)

To pass all of the acceptance tests, the site needed the following sections:

**User Story 1**: A professional-looking, responsive, user-friendly interface

- A **Navigation** section so users can easily navigate around the site

**User Story 2**: Enticing images and descriptions of the business, its products and services

- A **Business Hero** section with an enticing image of the store and a good elevator pitch for the business and its services
- A **Services** section with images and brief descriptions for each service (the store, the subscription box, the regular events)
- A **Subscription Box Hero** section with an enticing image and description of the subscription box service.
- An **Events Hero** section with an enticing image and description of the regular events.

**User Story 3**: Location, opening hours and contact details

- A **Contact Details** section where users can find all relevant contact details

**User Story 4**: Subscription box subscription form

- A **Subscription Box Details** section detailing the features and benefits of the service
- A **Subscription Form** section that contains the sign-up form
- A **Thank You** section that contains a thank-you message and a homepage button

**User Story 5**: List of events and booking form

- An **Events List** section containing details of upcoming events
- An **Event Booking Form** section that contains the event booking form

**User Story 6**: E-newsletter sign-up form

- A **Newsletter Sign-up** section containing a description of the newsletter and a sign-up button

These sections were allocated to various web pages based on their importance and the intuitive flow of information that most users would expect (e.g. putting the list of events directly above the event booking form).

The resulting website structure is shown below.

**TODO: This image needs updating to the latest version**

![Random Old Books Structure Diagram](assets/images/Random%20Old%20Books%20Structure%20Diagram.png)

### Wireframes (Skeleton Plane)

After laying out the site's structure, I used [Wireframe.cc](https://www.wireframe.cc) to build laptop, tablet and mobile wireframes for each page. Click on the links below to see an image of each wireframe.

- Home
  - [Laptop](assets/docs/1-Home-Laptop.png)
  - [Tablet](assets/docs/2-Home-Tablet.png)
  - [Mobile](assets/docs/3-Home-Mobile.png)
- Subscription box
  - [Laptop](assets/docs/4-Subscription-Box-Laptop.png)
  - [Tablet](assets/docs/5-Subscription-Box-Tablet.png)
  - [Mobile](assets/docs/6-Subscription-Box-Mobile.png)
- Events
  - [Laptop](assets/docs/7-Events-Laptop.png)
  - [Tablet](assets/docs/8-Events-Tablet.png)
  - [Mobile](assets/docs/9-Events-Mobile.png)
- Form success
  - [Laptop](assets/docs/10-Success-Laptop.png)
  - [Tablet](assets/docs/11-Success-Tablet.png)
  - [Mobile](assets/docs/12-Success-Mobile.png)

### Colour Palette, Fonts, Images and Content (Surface Plane)

- Colour palette:
  - To be decided when the first page is built. 
  - Probably from: https://craigandrose.com/collections/vintage-styles-art-deco
- Fonts (Google Fonts)
  - https://fonts.google.com/
  - To be decided.
- Images
  - To be decided.
  - Probably: https://unsplash.com/

## Features 

### Existing Features

### Features Left to Implement

## Testing 

### Validator Testing 

### Unfixed Bugs

## Deployment

## Credits 

### Content 

- README.md
  - I used [Code Institute's README.md template](https://github.com/Code-Institute-Solutions/readme-template/blob/master/README.md) as the starting point for this document.
  - I also referenced Code Institute's *Creating a README* slide deck.
- User Experience Design
  - I read [The Elements of User Experience](http://www.jjg.net/elements/) and used it to guide me through the user experience design phase.
- User Personas
  - I used Microsoft Co-Pilot to help me develop the user personas.
- Colour palette
  - Used https://imagecolorpicker.com/ to extract hex colours from images.
  - Used https://webaim.org/resources/contrastchecker/ to adjust foreground and background colours until a sufficient contrast was achieved to pass all checks.
- Favicon
  - Used https://gauger.io/fonticon/ to create a favicon image from an icon.
  - Used https://favicon.io/ to convert the favicon into multiple favicon formats.
  - Converted hex to RGB using https://www.rgbtohex.net/hex-to-rgb/.

### Media

