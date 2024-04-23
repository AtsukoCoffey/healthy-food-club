# Healthy Food Club
The Healthy Food Club is a community that hosts cooking sessions with brief health-related lectures and introduces alternative menus to promote a healthier lifestyle.  
  
During our activities, we strive to raise awareness about the prevalence of chemicals in our lives and their impact, specially focus on the food additives, fertilizers, pesticide, and those regulations, to monitor them for a safer society and healthier life collectively.

![ Live site view ](assets/images/readme-img/amiresponsive.png "Live site view")
## **[Live site](https://atsukocoffey.github.io/healthy-food-club/)**


## Table Of Contents
1.	[ UX DESIGN ](#ux)
2.	[ EXISTING FEATURES ](#features)
3.	[ FEATURES LEFT TO IMPLEMENT ](#featureleft)
4.	[ TECHNOLOGY USED ](#Tech)
5.	[ TESTING ](#testing)
6.	[ BUGS ](#bugs)
7.	[ DEPLOYMENT ](#deployment)
8.  [ CREDITS ](#credits)
9.  [ CONTENT ](#content)
10. [ ACKNOWLEDGEMENTS](#acknowledgements)


<a name="ux"></a>

# UX DESIGN

## 1. Strategy Plane
### Target users 
1.	Young people who are about to start living independently, as well as their parents
2.	Everyone who cares about food additives, health and simply enjoys cooking.

### User value 
1.	Users can access and learn crucial information that could have an impact on their health and well-being.
2.	Users can find the community which is promoting everyone’s health through lectures and cooking lessons.
3.	Users can learn alternative cooking knowledge to avoid potentially dangerous food additives and unnaturally excessive processed food.

### Difference from competitors and substitutions
1.  The Healthy Food Club is not just recipes, but has more emphasis on learning.
2.  The cooking menu for the session is aligned with the lecture content, making it more practical.


## 2. Scope Plane 
### General user stories
*	As a user, I want to clearly understand what services are offered on this website.
*	As a user, I want to be able to easily navigate through to find contents.
*	As a user, I want the website to work on different devices and formats that I use.
*	As a user, I want a simple sign-up process with selecting my preferred option.
*	As a user, I want to feel that healthy cooking is interesting and not difficult.
*	As a user, I want to see articles that offer a variety of perspectives on health to fit my problem awareness.

### Target users and who are interested in this website
*	As a user, I want to find out when the next cooking session is and what the lecture subject will be clearly..
* As a user, I want to find what kind of people are organising the Healthy Food Club and are they trustworthy or not.
* As a user, I want to find out the schedules of future sessions.

### The website owner stories
*	As a site owner, I want to gather people for cooking & lecture sessions.
*	As a site owner, I want to convey clearly who we are and our purpose, to give users a sense of trust and confidence.
*	As a site owner, I want to share useful information and chemical studies.
*	As a site owner, I want to encourage people’s awareness about chemicals in our life.
*	As a site owner, I want to inform and educate about European and national regulations on food additives.
*	As a site owner, I want to provide inspiration for alternative cooking ideas.
*	As a site owner, I want to convey clearly that the Healthy Food Club is not just recipes cooking club.

## 3. Structure Plane

* The website should have a Navigation menu that is consistent across all pages.
* The website should have a fixed footer to access anytime to see this site's SNS.  
* The website should give the user a way to contact through a form.
* The website should have breadcrumbs to help users feel a strong sense of place and also give access to former pages when it expands to become a larger website.
*	The website should have hover interaction for links, abbreviation, and tooltips with additional information to enhance user experience.
* The landing page should show what this site is offering intuitively.
* The Info page should have a variety of articles that are categorized by different perspectives.
* Burger icon is commonly used to smaller screen, so using this convention to represent the navigation suits users' expectations.
*	The Sign-up page submit button should be clearly visible and interactive when mouse hover it. It should also change colour and text after submitting to indicate that the form was sent.


## 4. Skeleton Plane

### Wireframes

<details>
<summary>Home page mobile Wireframe</summary>

![Home page mobile Wireframe](assets/images/wireframe/wireframe1.gif "Home page mobile Wireframe")
</details>

<details>
<summary>Home page tablet and PC Wireframes</summary>

![Home page tablet and PC Wireframe](assets/images/wireframe/wireframe2.gif "Home page tablet and PC Wireframe")
</details>


## 5. Surface Plane

### Colour
At the planning stage, I chose this colour scheme, which has a healthy, lively, clear and optimistic feeling, from the Adobe colour website.  
  
![Colour scheme](assets/images/readme-img/colour-scheme1.png "Colour scheme")

However, using only these colors couldn’t provide enough contrast, so I adjusted the color scheme as below.  
  
![Colour scheme 2](assets/images/readme-img/colour-scheme2.png "Colour scheme 2")


### Typography

I selected "Poiret One" for the “Healthy Food Club” Logo from Google font API. It is attractive and has sharp features and it’s not too heavy.  
I was considering using "Quicksand" for the best readability, however our target users are young people and since it’s not a huge business website so a little bit unique font like "Josefin Sans" might appeal well to this unique community. 
* "Poiret One"
* "Josefin Sans"


<a name="features"></a>

# EXISTING FEATURES

## The Header And Navigation Bar
![Header and Navigation Bar](assets/images/readme-img/feat-header.png "Header and Navigation Bar")

The header, with the logo, is the face of the website. So I chose the strongest colour in my colour scheme to appeal, along with unique logo. This header includes the navigation bar which is full responsive to all size of devices and it swaps to the toggle button to hide and show the navigation links for small screen sizes, less than 768px width. I borrowed this toggle button technic from “Love Running” project in Code Institute LMS. ( Credit section )  
The navigation bar has links to the logo, home page, information page and sign-up page and also has an easy to recognize icons.  
This feature is on all three pages and is identical in each page to allow for easy navigation.


## The Landing Page Hero Image
![Hero Image](assets/images/readme-img/feat-hero.png "Hero Image")

The landing hero image is really important as it should convey clearly the website purpose and show the atmosphere of this community, I am happy that I could find out a picture that a smiling girl preparing food in the kitchen.  
The overlay text also conveys logically what this site is about, my main message was basically like this “let’s study together for a healthier life together”. Since I am not native Irish so I asked my family for help to consider making it more natural phrase. ( Credit section )  
This section introduces the user to “Healthy Food Club” with an eye catching css animation which technique is borrowed from again “Love Running” project in Code Institute. . ( Credit section ) 


## Upcoming Session Info Section
![Upcoming Session info](assets/images/readme-img/feat-upcoming.png "Upcoming Session info")

This section Informs about the next closest cooking session summary with a link to draw into the session schedule page.  
This section is deliberately placed just under the hero image with outstanding background colour to be visible in the first loading view angle. The reason is that this info shows clearly what activities exactly the “Healthy Food club” is offering in this website.  

About this coding part, I consider using the `<figure>` element for an image since it is a part of the other page's content also it contains independent information. At same time, I wanted to use the `<picture>` element for responsivity though I wasn't familier with these codes so referenced other websites. ( Credit section )

## About Us Section
![About us](assets/images/readme-img/feat-aboutus.png "About us")

Introduce about us and our purpose to give user feel confidence. Also if the user is living around Athlone town, we’d like to let them know this community session is holding at Technological University of the Shannon (TUS) where everybody can visit freely.

## Article YouTube Section
![Article Youtube](assets/images/readme-img/feat-article-youtube.png "Article Youtube")

This section shows a health related video that made by WHO, it promotes the overview of healthy life styles. I am aiming this will pique user’s interest and redirect them to the information page.

## The Footer
![The footer](assets/images/readme-img/feat-footer.png "The footer")

The footer section includes links to the relevant social media sites. The links will open to a new tab to keep this website open and allow easy navigation for anytime user can visit the social media sites.

## Breadcrumb
![Breadcrumb](assets/images/readme-img/feat-breadcrumb.png "Breadcrumb")

This feature lets users know which page they are on, giving a strong sense of place. It will be important if the site becomes larger.

## Information Page

This page is for the varieties of health information, they are categorised and present some leading text that explains what kind of information in here. There are only 4 categories at the moment with sample pictures, however this page will be expand over the time with more information. 



### Cooking basic knowledge
![Info - Cooking basic knowledge](assets/images/readme-img/feat-info-basic.png "Info - Cooking basic knowledge")

This category is for beginners ( young people who don’t have much cooking experiences ). Talk about tips like “Use different cutting board for meat and vegetables - preventing bacterial transmitting”…

### Healthy gut
![Info - Healthy gut](assets/images/readme-img/feat-info-gut.png "Info - Healthy gut")

This category is talking about our microbes which we can't see exactly but there're a lot of studies published and spotlighting these areas.  
This is a kind of general knowledge for who's interested in our body systems.

### Study on food additives and sickness
![Info - Study on food additives and sickness](assets/images/readme-img/feat-info-research.png "Info - Study on food additives and sickness")

This category Introduces some studies on how our food development activities, such as excessive refining of ingredients or breeding improvement, can actually cause illness at the genetic level.  
I'd like to find the sources from Academic papers and public trusted information.

### Tips and tricks! 
![Info - Tips and tricks!](assets/images/readme-img/feat-info-tip.png "Tips and tricks!")

This category is for those who have just become interested in, but feel expensive or difficult. It shows the first easy steps to start.


## The Sign-up Form
![The sign-up form](assets/images/readme-img/feat-signup.png "The sign-up form")

Sign-up form is interactive for user experience with mouse hovering colour, also submission button has some functions as mentioned above. ( Structure Plane ) This section will allow users to get signed up along with specifying which session if they would like to take part in or joining the community mailing list. The user will be asked to submit, their full name and email address for required information and phone number and cooking experience inputs are optional information.  
My mentor Alan taught me “pattern” attribute for this form inputs. This can prevent incorrect user inputs to submit. ( Credit section )

* First name, Last name inputs are texts only
* Phone number input is numbers only
* Email address needs "@"mark


## Session Schedule
![Session schedule](assets/images/readme-img/feat-session-schedule.png "Session schedule")

This feature informs future session dates, lecture titles and cooking menus with pictures. 

## Where To Find us
![Where to find us](assets/images/readme-img/feat-wheretofind1.png "Where to find us")
![Where to find us](assets/images/readme-img/feat-wheretofind2.png "Where to find us")

This feature is showing contact information and map of the venue.  
Added a link under the contact information section, I want to lead users back into the form section again.

I had a problem with google map ( Bugs section ) Lighthouse auditing told me about third party cookies in this map. 



<a name="featureleft"></a>

# FEATURES LEFT TO IMPLEMENT

## Information Architecture (IA)

In the info page, categories and articles will be expanding over time, so new pages will be created in each category folder for organizational purposes. Or if possible, develop the system using a technology like DOM to generate HTML pages by coding. 

## Online Session Feature

For future growth, an online session feature might be good idea for meeting people who live far away from Athlone town. Also it might be better for new users who want to listen to lectures only or just learn the cooking part to feel free to join in.

------------------------------------------

<a name="tech"></a>

# TECHNOLOGY USED

## HTML
> Used to structure my webpages

## CSS
> Used to style and add layout

## Font Awesome
> Used for all the icons in this project

## Google Fonts
> Used for all the fonts used in this project and to compare potential fonts.

## Google Map API
> 
<a name="testing"></a>


# TESTING

**Testing for links and Form**
| Test |Outcome  |
|--|--|
|All links on Navigation lead to their correct pages| |
|Contact us button leads to contact form on contact us page| 
|Footer social links all lead to their respective social media sites ||
|Contact form submits when all criteria is filled correctly|   |
|User prevented from submitting form without correct elements| |
|Form Validation presents when incorrect input type is entered ||

**Testing for responsiveness**
| Test |Outcome  |
|--|--|
|Home page, , 

## W3 Validator
![W3 validator index.html](assets/images/readme-img/test-w3validator-index.png "W3 validator index.html")
![W3 validator info.html](assets/images/readme-img/test-w3validator-info.png "W3 validator info.html")
![W3 validator signup.html](assets/images/readme-img/test-w3validator-signup.png "W3 validator signup.html")
## W3 CSS Validator
![W3 validator css](assets/images/readme-img/test-w3validator-css.png "W3 validator css")
## Google Lighthouse Testing
![Lighthouse validator index.html](assets/images/readme-img/test-lighthouse-index.png "Lighthouse validator index.html")
![Lighthouse validator info.html](assets/images/readme-img/test-lighthouse-info.png "Lighthouse validator info.html")


<a name="bugs"></a>

# BUGS

## Header

I found unexpected spaces around the title and toggle button. It was making problem for middle size screen.
  
Solution : I found my mistake with “Flex justify-content” was “space-around”, I meant to set “space-between”. It took time to find out though it was good opportunity to use Google dev tool to inspect the css.


## Youtube-iframe Video

I struggled with figuring out how to set the video height automatically to fit the screen size. After tried and failed, I found a good technique that involves using padding-bottom with the ratio of the video width at stackoverflow.  

![Youtube height technique](assets/images/readme-img/bug-stackoverflow-youtube-height.png "Youtube height technique")
![Youtube height technique](assets/images/readme-img/bug-stackoverflow-youtube-height2.png "Youtube height technique")


## Youtube-iframe Align Center

I struggled again to set this `<iframe>` `align:center`, without using `text-align` of `flex` to the parent `<article>` element or outer `<div>` element’s properties setting. This simple and fantastic technique persuaded me very well.  

![Youtube iframe align center](assets/images/readme-img/bug-stackoverflow-howtoalign-iframe1.png "Youtube iframe align center")
![Youtube iframe align center](assets/images/readme-img/bug-stackoverflow-howtoalign-iframe2.png "Youtube iframe align center")


## Hero Image CSS Animation Scale 1 to 1.1 

caused excess space around the page  
Solution : `overflow: hidden` for outside `<div>`  

![Hero image CSS animation scale 1 to 1.1](assets/images/readme-img/bug-hero-css-anima.png "Hero image CSS animation scale 1 to 1.1")


## Youtube Video Optimizing For Lighthouse
Google Lighthouse audit told me, the YouTube Java Script is unnecessary and it’s better to remove it for faster loading. I searched about it and doubt it’s true, I think it’s necessary when user start video.  
Alternatively we can stop reading Java Script when page loading, with using the source=doc attribute.  

![Youtube video optimizing for lighthouse](assets/images/readme-img/bug-youtube-js.png "Youtube video optimizing for lighthouse")


## Google Map – Remove Third-party Cookies

At beginning I had five third-party cookies related to google map. This cause SEO score of Lighthouse audit not high - around 70. After looked around the solution, I found this “ Prepare for third-party cookie restrictions “ article, I consider to sign up to google map API for cookie-less map, however I had to register my credit card which I wasn’t willing to. Therefore I had just tried to set my browser’s cookie blocked, and get the map URL from other map website. ( I got from MAPS.IE - My mentor showed me this website in my second project meeting - ) In this way I can audit Lighthouse with no third party cookie problem. However this cookies warning appeared again after my browser’s third-party cookies on.  

* [Google Map – remove third-party cookies](https://developers.google.com/privacy-sandbox/3pcd?utm_source=lighthouse&utm_medium=devtools "Google Map – remove third-party cookies")  
* [MAPS.IE](https://www.maps.ie/ "MAPS.IE")


<a name="deployment"></a>


# DEPLOYMENT

> "Deployment" in web application development refers to the process of making a web application available for end users to access on the internet.  

1. Log in Git hub and access to purpose repository.
2. Click on 'Settings'.
3. On the left-hand sidebar, click on 'Pages'.
4. Source is 'Deploy from Branch'.
5. Select 'Main' branch.
6. Folder is 'root'.
7. Click 'Save'.
8. Click on 'Code'. After a few minutes refresh your repo.
9. On the right-hand side, in the Environments section, click on 'github-pages'.
10. Deployments page click the link to see the live site.

![Deployment pic1](assets/images/readme-img/deploy1.png)

![Deployment pic2](assets/images/readme-img/deploy2.png)

![Deployment pic3](assets/images/readme-img/deploy3.png)



<a name="credits"></a>

# CREDITS

## CSS `[attribute="value"]` Selector

I leaned this selector at “Love Running” walk through project, using this for button’s functions. For making it my tool, I checked at W3 schools web site for further more information.
* [CSS Attribute Selectors](https://www.w3schools.com/css/css_attribute_selectors.asp "CSS Attribute Selectors")


## Meta Element `<meta http-equiv="X-UA-Compatible" content="IE=edge">`

I researched that what is this meta tag for, I guess we might not need this tag anymore though, just in case for the people who still using old version of IE, it might be better to help them.   

![Meta tag X-UA-compatible](assets/images/readme-img/credit-perplex-meta-xua-compatible1.png "Meta tag X-UA-compatible")
![Meta tag X-UA-compatible](assets/images/readme-img/credit-perplex-meta-xua-compatible2.png "Meta tag X-UA-compatible")


## Figure And Picture Element 

In the upcoming session section, I consider using the `<figure>` element for an image since it is a part of the other page's content also it contains independent information. At same time, I wanted to use the `<picture>` element for UI responsivity. But I wasn’t familiar with both elements to use so I looked for some hints around but couldn’t find out using both. I asked perplexity whether I could include picture element in the figure element. It seems no problem to include it. 

![Figure tag and picture tag](assets/images/readme-img/credit-figure-picture.png "Figure tag and picture tag")
![Figure tag and picture tag](assets/images/readme-img/credit-perplex-figure.png "Figure tag and picture tag")

## Hero Image CSS Animation Scale 1 to 1.1 
When I learned this css animation technique through the “Love Running” project in Code Institute, I was amazed to discover that I could create animation without Java Script, which was common 20 years ago. 
![Hero image CSS animation scale 1 to 1.1](assets/images/readme-img/credit-hero-css-anima.png "Hero image CSS animation scale 1 to 1.1")

## Breadcrumb
I looked for what is suitable element for the breadcrumb links. In W3 website the answer was <nav> and using aria attribute for describing the location so I referred this css code.  

![Breadcrumb](assets/images/readme-img/credit-breadcrumb-w3c2.png "Breadcrumb")
![Breadcrumb before selector](assets/images/readme-img/credit-breadcrumb-before-selector.png "Breadcrumb before selector")


## Form  Autocomplete Attribute
Lighthouse validator suggested me to use autocomplete attribute for form, and I found this is really helpful for user.  

* [Form autocomplete attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete "Form  autocomplete attributer")

## Form Input Pattern Attribute
My mentor Alan taught me about this `<input>` pattern attribute for preventing invalid form data to submit.
EG. for alphabet only and 3 letters `pattern="[A-Za-z]{3}"`  

* [Form input pattern attribute](https://www.w3schools.com/tags/att_input_pattern.asp#:~:text=The%20pattern%20attribute%20specifies%20a,pattern%20to%20help%20the%20user "Form input pattern attribute")

## Hero Image Optimizing For LCP
The hero image is not a small size image. After I read this article, I tried to optimize the reading time of the hero image using `<link rel="preload">’ for increasing LCP score.  

* [Optimize Largest Contentful Paint](https://web.dev/articles/optimize-lcp?utm_source=lighthouse&utm_medium=lr#optimize_when_the_resource_is_discovered "Optimize Largest Contentful Paint")



## Imagery

### Hero image  
<a href="https://www.freepik.com/free-photo/young-smiling-woman-making-bruschetta-with-healthy-ingredients-while-preparing-food-kitchen_25777232.htm#fromView=search&page=1&position=49&uuid=0bc03e1b-f752-44c6-9880-1b484845ce49" width="500">Image by Drazen Zigic on Freepik</a>


### Picture pastrami beef  
<a href="https://www.freepik.com/free-photo/sliced-beef-pastrami-pastrami-with-turkish-bacon-closeup-top-view-traditional-turkish-food_37833736.htm#query=pastrami&position=0&from_view=keyword&track=sph&uuid=26cf64d1-d161-45da-a382-231c4d0c2ee6" width="300">Image by ededchechine on Freepik </a>


### A cutting board and a knife
Image by <a href="https://pixabay.com/users/rambling_roy-29593818/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7471627">Roy Stephen</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7471627">Pixabay</a>


### Wash vegetable
Image by <a href="https://pixabay.com/users/myccf-20343736/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=6064523">MYCCF</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=6064523">Pixabay</a>


### Healthy gut
<a href="https://www.freepik.com/free-photo/close-up-young-womans-hands-slim-belly_1147751.htm#fromView=search&page=1&position=4&uuid=1ebdfc47-60a3-4a3a-b410-88118cc29503">Image by katemangostar on Freepik</a>


### Stethoscope and prescription on 
<a href="https://www.freepik.com/free-photo/stethoscope-prescription-laptop_1129630.htm#fromView=search&page=1&position=1&uuid=f4a7e8ec-52a1-4d5a-a01a-0b7970a5e091">Image by jannoon028 on Freepik</a>


### Apple vinegar
Photo by Tijana Drndarski: [https://www.pexels.com/photo/photo-of-slice-green-apple-and-cinnamon-stick-3338676/](https://www.pexels.com/photo/photo-of-slice-green-apple-and-cinnamon-stick-3338676/)


### Baking
Photo by Gil Goldman: [https://www.pexels.com/photo/fresh-bread-loafs-on-table-in-bakery-4268507/](https://www.pexels.com/photo/fresh-bread-loafs-on-table-in-bakery-4268507/)


### vegetables  
<a href="https://www.freepik.com/free-ai-image/world-health-day-celebration-with-healthy-food_138542824.htm#query=healthy%20food&position=7&from_view=keyword&track=ais&uuid=ab2f5d84-4557-4db6-a6b3-9449a4cfd196">Image by freepik</a>




## Adobe color API  
[ Adobe Color EXPLORE 'food' keyword ](https://color.adobe.com/search?q=food "Adobe Color EXPLORE 'food' keyword")

## Youtube: 
A healthy diet, a healthier world (WHO)  
[A healthy diet, a healthier world (WHO) ](https://www.youtube.com/watch?v=XMcab1MFaLc "A healthy diet, a healthier world (WHO) ")


## Map of TUS  
[https://maps.app.goo.gl/yFF4T7ChemuH2YJt5](https://maps.app.goo.gl/yFF4T7ChemuH2YJt5)


<a name="acknowledgements"></a>

# ACKNOWLEDGEMENTS



<!-- 
![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for Codeanywhere. If you are using Gitpod then you need [this template](https://github.com/Code-Institute-Org/gitpod-full-template) instead.  We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Codeanywhere and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **August 30th, 2023**

## Codeanywhere Reminders

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere, in the terminal, type:

`python3 -m http.server`

A button should appear to click: _Open Preview_ or _Open Browser_.

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere with no-cache, you can use this alias for `python3 -m http.server`.

`http_server`

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A button should appear to click: _Open Preview_ or _Open Browser_.

In Codeanywhere you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In Codeanywhere, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

---

Happy coding!
 -->