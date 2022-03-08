
# Dzogchen Beara
Welcome!
# Introuduction
Dzogchen Beara is a website desgined for Tibetan Buddish Retreat centre on the wild atlantic way.  Dzogchen Beara is part of Rigpa, an international network of Buddhist centres dedicated to making the Buddhist teachings of meditation, compassion and wisdom available to the modern world. The site provies information about the centre and things you can do there. The main aim of this project is to incourage people to vist Dzoghen Beara and to get vital feedback on their stay.The site is targeted to people who are looking to go on a retreat and to get a break from thier busy and hectic lives. 

A live website can be found [here]( https://cathalshandon.github.io/my-first-project/)

## Table of Contents 
 
# Table of Contents
[1. User Experience](#ue)
 - [Site skeleton (wireframes)](#wireframes)
   - [Home page](#home-page)
   - [Gallery page](#gallery-page)
   - [Feedback page](#feedback-page)

[2. Features](#features)

<a name="ue"></a>
# 1. User Experience
Most adults at some stage might feel stressed or under pressure during their busy days. Perhaps some have anxious feelings and something worries can develope at certain time in thier life.

Users of this site will gain information about the retreat and what you can do there like medidate and get rid of all there stress and worry. The site also has a link in it for book to book a stay at the retreat.

The user can also navigate through the site easily, understand the information being presented, give feedback on there stay and view the websites cleary on different devices.

<a name="wireframes"></a>
## 1.2 Site Skeleton
[Balsamiq](https://balsamiq.com/) was used to create wireframes of the website. This was very useful as it gives the template of the UI. Wireframes were designed for web browser and a mobile browser format. The concept design (wireframes) of webpages prepared is presented below.

<a name="home-page"></a>
### Home Page
![Desktop Version](./assets/images/Home-desktop.png)

![Mobile](./assets/images/Home-mobile.png)

<a name="gallery-page"></a>
### Gallery Page
![Desktop Version](./assets/images/gallery-desktop.png)

![Mobile ](./assets/images/gallery-mobile.png)

<a name="feedback-page"></a>
### Feedback Page
![Desktop Version](./assets/images/feedback-desktop.png)

![Mobile ](./assets/images/feedback-mobile.png)

 <a name="features"></a>
# 2. Features
[Go to the top](#table-of-contents)

### Home page:
- A picture of the temple looking across the ocean is displayed just below the title.
- The page contains the title "About" by which is divied into four divisions. The first being the locationand the community, The second being spiritual, third being the history of the locality and the fourth being the accommdation with a link to the page where can book a stay.

The screenshot of Home page is below:
(./assets/images/Home.png)
### Gallery page:
- The gallery page just has the title Dzogchen Beara and is again divided into four sections with pictures.
- The first is "Medidation" with image of people medidiating and the benefits of medidiating, second is "Amazing views" with image of the centre overlooking the altanic ocean, third which is the "Cafe and Shop" image of the shop and opening times, and the fouth being "Shrine Room" image of people medidiating in the shrine room and information about the room.

The screenshot of Gallery page is below:
(./assets/images/gallery.png)
### Feedback page
- The feedback pages includes the ability to message the retreat, provide feedback and suggestions. 
- Includes giving a rate on your stay forms where users can choose the options from (strongly agree, agree, neutral, disagree, strongly disagree) using radio-button option.
- The Submit and Reset buttons with hoever effect on it
- The form use the method="POST" action="https://formdump.codeinstitute.net/"
- I use the option of placeholder for full name and email address.

The screenshot of Feedback page is below:
(./assets/images/Feedback.png)
# 3. Technologies Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5) (markup language) was used for structuring and presenting content of the website.
 * [CSS3](https://en.wikipedia.org/wiki/CSS) (Cascading Style Sheets) was used to provide the style to the content written in a HTML.
* [Balsamiq](https://balsamiq.com/) was used to create wireframes of the website (desktop and mobile version).
* [Google Fonts](https://fonts.google.com/) was used to import font-family "Playfair" and "Roboto" into style,css file and which was used throughout the pages of the website.
* [Font Awesome](https://fontawesome.com/) was used to improt icons to the sites.
* [Chrome](https://www.google.com/intl/en_uk/chrome/) was used to debug and test the source code using HTML5 as well as to test site responsiveness.
* [Github](https://github.com/) was used to create the repository and to store the project's code after pushed from Git.
* [Gitpod](https://www.gitpod.io/) was used as the Code Editor for the site

# 4. Testing
[Go to the top](#table-of-contents)
## 4.1 Testing using tools
### 4.1.1 Google Developer Tools
I made use of google developer tools (Chrome DevTools) as a debugging tools. When using this tool I inspected for every elements that I added in HTML and CSS style. Once I was happy with them I copied the CSS style code from Chrome DevTools and paste in my CSS style sheet.I also used the the tool in order to make sure that design web pages are responsive to all device sizes

### 4.1.2 W3C Validator Tools
[W3C Markup](https://validator.w3.org/#validate_by_input+with_options) was used to check for any errors within my HTML pages.


## All 3 pages:
 ### Navigation bars
 TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Home page | When I click on "Home", the browser redirects me to the Home page. When I hoever over the "Home" it underlines it.| PASS
Gallery page | on click "Gallery", the browser redirects me to the Gallery page. The hoever effect underline appears when mouse is on "Gallery". | PASS
Feedback page| on click to "feedback page", the browser redirects me to the feedback page. The hoever effect underline appears when mouse is on "feedback page". | PASS
Responsive| All pages and elements were responsive (mobile and website) using differnt breakpoints.| PASS
Text|Checked if all fonts and colors used are consistent or not|PASS
Back to top|Checked if the page redirect to the top of the page when clicking the back to top on the bottom left corner of the page| PASS
|||

### Footer
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Facebook | on clicking Facebook icon, a new tab opens and redirects to the Facebook website.| PASS
Twitter|Checked if submit and reset button works or not.| PASS
Youtube| on clicking youtube icon, a new tab opens and redirects to the youtube we.| PASS
Instagram| on clicking instagram icon, a new tab opens and redirects to the instagram website.  | PASS

### Home page
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Media|Hero image checked to ensure it loaded .| PASS
Responsive| All pages and elements were responsive (mobile and website) using different breakpoints.| PASS
External Links|Checked if the external link "Book here" redirect to the Accomadtion page and open in new tab.| PASS
Accessssibilty|Checked the accessibility of the page using lighthouse | PASS
(./assets/images/home-lighthouse.png)
### Gallery page
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Media|All images on the pages load. All images were checked if it blurred in different screen sizes.| PASS
Responsive| All pages and elements were responsive (mobile and website) using differnt breakpoints.| PASS
Accessssibilty|Checked the accessibility of the page using lighthouse | PASS
(./assets/images/gallery-lighthouse.png)
### Feedback page
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Radio buttons|Checked if radio button works or not.| PASS
Responsive| All pages and elements were responsive (mobile and website) using differnt breakpoints.| PASS
Accessssibilty|Checked the accessibility of the page using lighthouse | PASS
Google maps|Checked if google map when clicked on view larger map redirect to the google map page in new tab works ot not| PASS
Submit/Reset|Checked if submit and reset button works or not.| PASS
(/assets/images/feedback-lighthouse.png)