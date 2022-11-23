# Walkz
The Walkz website is a social group website for dog lovers that like to be active outdoors with their dogs.

The aim of the website is to promote healthy activity outdoors and in the process, meet new people with similar interests.

Users of the website will find information regarding meet up locations including Google map coordinates, times, distance of walk, a sign up form, social media links for the social group and some brief information regarding the benefits of being active with a friend/friends.

![Responsive Mockup](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-mockup.png)

## Existing Features
-   **Navigation Bar**
    -   Is featured across all pages, is fully responsive and includes links to the home page, meet up locations page & sign up page.
    -   The nav bar is identical across all pages to allow for easy navigation and creates familiarity for the user.
    -   With the use of this nav bar avoids the user having to use the "back" button to navigate to a previous page.

-   **Site Name**
    -   Is featured across all pages, is fully responsive & is linked to the home landing page when clicked by the user.

![Site Name & Nav Bar](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-nav-bar.png)

-   **Center Logo & Quote**
    -   The center logo features a paw print background image set within a circular div of which can also be seen within the title tab of the entire website.
    -   The center logo combined with the quote _"Be active with a friend"_ aims to grab the attention of users that enjoy being active with their dogs.

![Site Logo & Quote(Be active with a friend)](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-center-logo-fav.png)

-   **Club Ethios Section**
    -   The Club Ethios section opens with a brief introductory as to what the _Walkz_ website is about.
    -   From intro the user will be able to identify if the _Walkz_ website is something of interest based on their own interests/hobbies i.e Being active with their dogs & indirectly meeting new people.
    -   Followed from the intro, the user can see some benefits of signing up with the _Walkz_ group.

![Club Ethios Section](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-club-ethios.png)

-   **Call to Action CTA**
    -   Upon reading the intro to the _Walkz_ home page, the user has the option to _"Sign Up"_ if interested.
    -   The _"Sign Up Today"_ text is hyperlinked and upon clicked will redirect the user to the Sign Up page.

![Call to Action](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-signup.png)

-   **Meet Up Location Section**
    -   This section allows the user to see _Meet up_ locations, days of the week the meet ups happens, times & a rough distance covered.
    -   These locations, days, time & distance can be updated in the future if anything where to change.
    -   Additionally the each location name is hyperlinked that when clicked will redirect the user to a _Meet ups_ page with Google Map coordinates for that location.

![Meet ups Section](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-locations.png)

-   **Meet Up's Landing Page & subsequent locations**
    -   The locations home page presents the user with Google Map information regarding the meet up locations.
    -   Each location is hyperlinked and again will present the user with Google Map information for the location clicked.

![Meet ups landing page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-locations.png)

-   **The Footer**
    -   The footer contains social media icons that when clicked will open the associated social platform in a new tab.
    -   These social media links further encourages the user to interact with similar minded people associated with the _Walkz_ website/social group.

![Footer and Social Media links](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-locations.png)

-   **The Sign Up Page**
    - The sign up page allows the user to sign up to the *Walkz* social group site & to select a preference in terms of meet up location.
    - The user will enter their full name & email in order to sign up.
    - Once signed up the user will be notified via the *"Thank You"* page that they have successfully signed up & will be contacted regarding the next available/organised outing.

![Sign Up landing page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-signup-page.png)
![Thank you page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-thank-you-page.png)

## Features left to Implement
-  Database for collecting user information
   - Currently user information is not collected as website is in a beta phase. Instead the user upon entering their information & clicking the *"Sign Up"* button on the *"Sign Up Page"* is redirected via hyperlink to a mock confirmation page.

## Validator Testing
-  HTML
   - No errors were returned when passing through the official W3C validator.

-  CSS
   - No errors were returned when passing through the official Jigsaw validator.

-  Accessibility
   - Through the use of Lighthouse as part of devtools, I confirmed that the colours & fonts used are easy to read & accessible.

![Lighthouse Report - Home Page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-access-home-page.png)

## Testing Overall
-  I confirmed that the site functions & is responsive across Google Chrome, Safari & Firefox.

![Safari - Walkz Home Page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-safari.png)   
![Firefox - Walkz Home Page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-firefox.png)   

## Bugs & Tweaks
- When I deployed the site initially to GitHub pages, I discovered that the Google Maps was not loading as part of the *Meet ups* location page.
- Through the use of the *Lighthouse* reporting & *stack overflow* I found the shortened *bitly* links used to link the map location did not include the HTTP as part of a secured link.
- Once the links were adjusted to include HTTPS, the links worked for the map locations.

![Location page Google Maps bug](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-access-bb-bug.png)
![Lighthouse report detailing bug](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-access-bb-bug-info.png)
![Fixed Location page](https://github.com/Simonb567/portfolio-1/blob/main/media/walkz-access-bb.png)
