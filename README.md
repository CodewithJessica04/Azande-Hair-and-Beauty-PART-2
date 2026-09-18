1. Azande Hair & Beauty Website

A responsive business website for Azande Hair & Beauty, developed as
part of a web development Portfolio of Evidence (POE).

The website provides customers with a central place to explore
hairstyles and prices, learn about the business, read salon rules and
frequently asked questions, view contact information, and access
appointment information.

> Current development stage: Part 2 --- CSS\
> JavaScript functionality is planned for Part 3 and is not
> implemented yet.


2. Project Overview

Azande Hair & Beauty currently uses platforms such as Instagram and
WhatsApp to communicate with customers and promote services. This
project introduces a dedicated website that organises important business
information into a professional, accessible, and responsive online
platform.

The website is designed around a gold, black, white, and light-grey
visual identity.

3. Project Objectives

The project aims to:

-   Create a professional online presence for Azande Hair & Beauty.
-   Provide clear information about hairstyles and prices.
-   Showcase hairstyles using an organised gallery.
-   Make important business information easy to find.
-   Provide dedicated FAQ and salon-rules pages.
-   Provide appointment and contact information.
-   Create a responsive layout for desktop, tablet, and mobile devices.
-   Prepare the website for interactive functionality in Part 3.

4. Development Structure

The project is being completed in three main parts.

  -----------------------------------------------------------------------
  Part              Technology        Purpose           Status
  ----------------- ----------------- ----------------- -----------------
  Part 1            HTML5             Website structure Completed
                                      and page content  

  Part 2            CSS3              Styling, layout   Completed /
                                      and responsive    Current
                                      design            

  Part 3            JavaScript        Interactivity and Planned
                                      enhanced          
                                      functionality     
  -----------------------------------------------------------------------

------------------------------------------------------------------------

5. Part 1 - HTML5

Part 1 focuses on building the structure and content of the website
using semantic HTML5.

The website contains the following HTML pages:

5.1 index.html

The Home page introduces Azande Hair & Beauty and provides quick access
to important areas of the website.

Main content includes:

-   Navigation
-   Hero section
-   Featured hairstyles
-   Business features
-   Promotional content
-   Booking links
-   Social-media information
-   Footer

5.2 hairstyles.html

The Hairstyles page presents the available hair services in a visual
gallery.

It includes:

-   Women's hairstyles
-   Men's hairstyles
-   Hairstyle images
-   Hairstyle names
-   Prices
-   Booking links

5.3 book-appointment.html

The appointment page provides a structured booking-enquiry form.

The form includes fields for:

-   Full name
-   Phone number
-   Hairstyle
-   Preferred date
-   Preferred time
-   Service type
-   Hairpiece requirements
-   Additional notes

5.4 about.html

The About page introduces Azande Hair & Beauty and provides information
about the business.

It includes:

-   Business background
-   Brand information
-   Services
-   Business values
-   Mission and vision information

5.5 faq.html

The FAQ page provides answers to common customer questions relating to:

-   Hair preparation
-   Hairpieces
-   House calls
-   Cancellations
-   Payments
-   Weekend appointments
-   Men's hairstyles
-   General bookings

Interactive accordion behaviour will be added in Part 3.

5.6 rules.html

The Rules and Policies page communicates important information customers
should understand before making an appointment.

Topics include:

-   Wash and blow-dry requirements
-   Booking confirmation
-   Early cancellation
-   Pricing
-   House calls
-   Late arrival
-   Weekend appointments

5.7 contact.html

The Contact page provides the business's contact information and enquiry
form.

It includes:

-   Phone information
-   WhatsApp access
-   Email information
-   Location information
-   Contact form
-   Map/location section

5.8 404.html

A custom error page is provided for unavailable or incorrect website
addresses.

It gives the visitor a clear option to return to the Home page.

------------------------------------------------------------------------

2. Part 2 - CSS

Part 2 focuses on the visual presentation and responsive design of the
HTML pages.

The website uses one main stylesheet:

css/style.css


The stylesheet provides a consistent design across the entire website.

2.1 Colour Scheme

The primary colour palette consists of:

  Colour       Hex Code    Usage
  ------------ ----------- -------------------------------------------
  Gold         `#D4AF37`   Branding, buttons, borders and highlights
  Black        `#111111`   Headings, footer and strong contrast
  White        `#FFFFFF`   Main page backgrounds
  Light Grey   `#F8F8F8`   Section backgrounds
  Grey         Various     Supporting text and borders

2.2 Typography

The website uses:

-   Play fair Display - branding and prominent headings.
-   Inter - navigation, body text, forms, buttons and supporting content.

2.3 CSS Features

The stylesheet includes styling for:

-   Global page structure
-   Navigation bar
-   Buttons
-   Hero section
-   Hairstyle cards
-   Responsive grids
-   Feature cards
-   Promotional sections
-   Booking form
-   Contact form
-   FAQ content
-   Rules and policy cards
-   About page
-   Contact page
-   Footer
-   404 page
-   Tablet layouts
-   Mobile layouts

2.4 Responsive Design

The website is designed to adapt to different screen sizes.

Responsive CSS media queries are used for:

-   Desktop computers
-   Tablets
-   Mobile phones
-   Small mobile devices

Elements such as grids, images, headings, forms and navigation adjust
according to available screen space.

------------------------------------------------------------------------

3. Part 3 - JavaScript

JavaScript has not been implemented yet.

Part 3 will introduce interactive functionality after the HTML and CSS
stages are complete.

Planned functionality includes:

-   Mobile navigation behaviour
-   FAQ accordion interaction
-   Hairstyle category/tab interaction
-   Booking-form processing
-   WhatsApp booking integration
-   Form validation where required

The project should therefore **not be considered JavaScript-complete at
the current stage**.

------------------------------------------------------------------------

## Current Project Structure

``` text
Azande-Hair-Beauty/
│
├── index.html
├── hairstyles.html
├── book-appointment.html
├── about.html
├── faq.html
├── rules.html
├── contact.html
├── 404.html
│
├── css/
│   └── style.css
│
├── images/
│   ├── logo.jpg
│   ├── hairstyle-images...
│   └── other-images...
│
└── README.md
```

A `js` folder is not required during Parts 1 and 2. It can be introduced
when Part 3 begins.

The planned structure for Part 3 will be:

``` text
js/
└── main.js
```

------------------------------------------------------------------------

## Sitemap

The website follows this main structure:

``` text
Home
│
├── Hairstyles
├── Book Appointment
├── About Us
├── FAQ
├── Rules & Policies
├── Contact
└── 404 Error Page
```

------------------------------------------------------------------------

## Design Approach

The website follows a clean and professional beauty-industry design.

The interface focuses on:

-   Clear navigation
-   Strong visual hierarchy
-   Hairstyle imagery
-   Readable typography
-   Consistent branding
-   Simple page layouts
-   Visible calls to action
-   Mobile responsiveness
-   Accessible content organisation

------------------------------------------------------------------------

## Wireframes

Low-fidelity wireframes were created during the planning and design
stage to define the placement of:

-   Navigation
-   Hero content
-   Images
-   Hairstyle cards
-   Forms
-   FAQ content
-   Rules and policies
-   Contact information
-   Footers

These wireframes guide the HTML structure and CSS layout before
interactive functionality is introduced.

------------------------------------------------------------------------

## Technologies

### Current

-   HTML5
-   CSS3

### Planned for Part 3

-   JavaScript

### Development Tools

-   Visual Studio Code
-   Git
-   GitHub
-   Web browser developer tools

------------------------------------------------------------------------

## Testing

During Parts 1 and 2, testing focuses on:

-   Navigation links
-   Correct page links
-   Image paths
-   CSS connection
-   Page layout
-   Form layout
-   Responsive behaviour
-   Mobile display
-   Tablet display
-   Desktop display
-   Browser compatibility
-   Readability and consistency

Interactive JavaScript testing will be completed during Part 3.

------------------------------------------------------------------------

## Future Improvements

Possible future improvements include:

-   Full WhatsApp booking integration
-   Interactive FAQ accordions
-   Mobile navigation
-   Hairstyle filtering
-   Improved form validation
-   Search-engine optimisation improvements
-   Website analytics
-   Additional accessibility improvements
-   Online booking/database functionality if required in a future
    version

------------------------------------------------------------------------

## Project Status

**Part 1 --- HTML:** Completed\
**Part 2 --- CSS:** Completed / Current Stage\
**Part 3 --- JavaScript:** Not started yet

------------------------------------------------------------------------

## Author / Development

Website developed for **Azande Hair & Beauty** as part of the website
development project.

------------------------------------------------------------------------

## Copyright

© 2026 Azande Hair & Beauty. All rights reserved.
