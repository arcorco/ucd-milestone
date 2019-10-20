# UCD PROJECT - THE HUNTSMAN PUB
---

This project is a static (front-end only) website for a village pub. 
It showcases information about the pub, such as photographs, the pubs opening hours, food serving hours,
upcoming, the facilities at the pub, the food menu, a form to request a booking, contact information and social media links.

---

## UX

---
This project is aimed at customers to the pub, whether regular or new. 

•As someone who visits the pub regularly, they will want to know of any events coming up soon, and they can
view these events in the upcoming events section. They can also join a mailing list to keep up to date with any 
events or offers.

•As a new customer to the pub, they may require information prior to visit. They can access information
such as opening hours, facilities and an address by viewing their resepctive sections.

•As a customer wanting to eat food, they may wish to see a menu beforehand. They can view a menu in the image
carousel in the food and drink section (or download the menu via the link in the same section). They may also want
to book a table, which they can do via the form in the food and drink section, or by viewing the contact section for
contact information such as address, phone number and email.

#### Initial stages

•I researched websites for other pubs and hotels to get a feel of what information to supply to the user. Viewing these
website as a user myself (and someone who visits pubs) I decided what information I would find useful.

•I made wireframes initially for a multi-page layout, but decided a one-page layout would be more suited once I began 
creating the website.

•Wireframes created: [Home page](https://wireframe.cc/GKvtmL), [About page](https://wireframe.cc/lzhb6W), [Food and Drink page](https://wireframe.cc/UQ58HE).

#### Page layout
I decided on the one-page layout because the website content flowed between sections, so it wasn't necessary to separate the pages.
For users of the website, all information required was easy to scroll through. The one-page layout is also much better suited to mobile users.
Having one scrolling web page also stops users losing focus from navigating through different pages. Because of the one-page layout I decided on a fixed navigation bar. 
All of the written content is concise also.

#### Colour scheme
The colour scheme was inspired by the interior of the pub as seen on the pictures. I felt the blue-green colour stood out most against the grey tones used.
I further decided to add the pink-red colour as an accent to the blue-green as these are complementary and so pop against each other. 

#### Fonts
The fonts I decided on were clean and simple to efficiently get the information across to the user. I decided to use two similar fonts for the body of the 
website. One was used for the headers/titles and the other for the rest of the content. I also decided on a much different font for the logo of the pub
as this draws attention and stands out.

#### Social media links
Since this website is partially based on a real pub, I used links to their active social media accounts as well as their trip advisor page. They do not have an
instagram or a twitter account, but I felt it would be better for the user experience for the pub to appear to have more of a social media presence, so I linked 
these icons to the home page for instagram and twitter respectively.

---

## Features

---

#### Navbar
•Bootstrap navbar with collapse feature for mobiles tablets to improve user experience as this stops the navigation looking cramped. I decided to use three navigation
sections, where two sections encompass several subsections.

•About: Opening Hours, Upcoming Events, Food Serving Hours, Facilities

•Food and Drink: Menu download, Booking request, Guest Ales

•Contact us

•I also included social media links in the navbar via FontAwesome icons.

#### Introduction/Welcome
•The design idea I had for this section was for it to be the most eye-catching and show as much information about the pub within one page. For this reason I decided 
to have a "gallery" of images transitioning as the background to give a simple overview of how the pub looks. 

•There is the pub logo and a brief introductory paragraphin white text over a partially opaque background to allow the photographs to still be visible.

•Scrolling down a little reveals an opportunity to sign up to the newsletter. For this I used a Bootstrap modal so the user will remain on the website and not be moved
around or distracted.

•Bootstrap grid system used.

#### Opening Hours
•I decided on a conventional table approach for this section, with a hover feature that highlights each row.

•Bootstrap alert included to show a closure. 

•Bootrap grid system used for desktop view.

#### Upcoming Events
•Again for this section I decided a table was appropriate. I included a Bootstrap badge on each row to signify the dates
and add some colour to look more appealing.

•Bootstrap grid system used for desktop view.

#### Food Serving Hours
•To showcase some more colour and images I used Bootstrap cards which "pop out" as the user hovers over them due to the box-shadow.

#### Facitilies
•This section makes use of FontAwesome icons, Bootstrap grid system, jQuery and Animate.css. 

•Each icon is a visual description of a facility stated and an animation is triggered when hovering over the icon.

•A Bootstrap tooltip is also displayed upon hover over each icon with a description of the facility. jQueury was required to initialise
these tooltips. Using tooltips aided user experience as the lengthier text is hidden until the icon is hovered over, making the website
less cluttered and extra information is only revealed if required by the user.

#### Download our menu here
•This section includes an external download link for the menu pdf.

•The menu is also displayed as three images in a Bootstrap carousel.

•Bootstrap grid system used.

#### Request a booking
•Form used with the Number Of People option being a dropdown list from 1-6 to signify to the user the size of bookings accepted. Text type for Date, Time
and Additional Comments where Date and Time have placeholders to help the user know how the information should be input. Email type used for email address with an
example email address as placeholder. 

•Submit button used links to a modal to inform the user of a completion when filling out the form.

•Bootstrap grid system used.

#### Guest Ales
•Images, icons and table format used. As the used hovers over the rows they are highlighted in the same way as the rows in the Opening Hours table. 
This ties together the sections of the website and provides the user with a sense of harmony between sections. 

•Bootstrap grid system used.

#### Contact Us
•This section is mostly text, since the information needed from this section by the user is only portrayable through text. 

•To make the section more user friendly, I added icons which lighten in colour and shake when they are hovered over.

•Social media links also included in the same way as in the header. These link to external website and are animated on hover. 

•Bootstrap grid system used.

#### Footer
•The footer contains the same information as the Contact Us section, but in a more concise manner.

•Again, social media links are included.

## Features Left to Implement
•One feature I would like to implement is to have some instant validation for the user when submitting forms, i.e. whether the email inputted is of the 
wrong form or if a required field had not been filled out.

•Another feature idea would be a form in the Guest Ales section which would act as a poll for users to vote for a guest ale to be hosted at the pub, as this would provide
great user interaction. You can see from my wireframes that I had the idea to add this from the start, however I decided this feature would be implemented better 
in a website that is more than front-end only. 

---

## Technologies Used

---

•The framework used predominantly to build the website was [Bootstrap V4.3](https://getbootstrap.com/).

•Icons were from [Font Awesome](https://fontawesome.com/) and [Icons8](https://icons8.com/).

•Fonts were from [Google Fonts](https://fonts.google.com/). 

•Animations from [Animate.css](https://daneden.github.io/animate.css/).

•JQuery used to initiate tooltips.

#### Plugins
•https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css

•https://kit.fontawesome.com/12bb6f902f.js

•https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css

•https://code.jquery.com/jquery-3.3.1.slim.min.js

•https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js

•https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js

---

## Testing

---

Throughout building this project, it was tested using devTools on Google Chrome. I tested the responsiveness 
by altering the viewport size and also through the device toolbar. I used the element style section to test 
alterations on the website before inputting changes to my style.css file. This was particularly helpful when I encountered
problems with the layouts on different viewport sizes. I have also tested the website on browsers safari and google chrome, as
well as on a MacBook, iPhone X and iPhone 8 (physically, not on device toolbar). Deplyed version also tested on MacBook, iPhone X and iPhone 8.

#### Features Tested
•Internal links from the navbar and any modals.

•External links to any pages, ensuring they open up in new tab.

•Download link, ensuring it opens in a new tab.

•Margins and paddings altered for different devices.

•Altered grid layouts for different devices.

•Checked animations worked in both Google Chrome and Safari.

•Checked modals worked and were of a correct size for different devices.

•Ensured images were responsive. In particular altered the height of the background images in the header for mobile compared to desktop/tablet.

•Validated HTML and CSS with w3.org.

---

## Deployment

---

Deployed via GitHub Pages (https://arcorco.github.io/ucd-milestone)

---

## Credits

---

•The CSS for the animation of the background images in the header was obtained from https://tympanus.net/codrops/2012/01/02/fullscreen-background-image-slideshow-with-css3.

•The CSS for the speechbubbles was obtained from https://leaverou.github.io/bubbly/.

•The CSS for the checkered background in the cards was obtained from https://leaverou.github.io/css3patterns/ (colours changed).

•Images taken from https://www.pexels.com/. 