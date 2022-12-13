TODO  <br>

2. insert FAQ post H3 screenshot into Demo <br>
3. is git hack ok or use pages for live demo  <br>
7. insert how i set up github pages  <br>
8. Improve format of README: spacing, heading discipline

# README for get_settled

---

### Get Settled

Get Settled is a submission for Portfolio 1, Code Institute's Diploma in Full Stack Development (E-commerce Applications.) The website is a static HTML and CSS project intended to respond to the client's desire for an affiliate marketing content-based website MVP. The content is designed for a community of British people who have moved to Ireland and are seeking to naturalise as Irish after 2022 (when the application process changed significantly.) 

---

### Demo

A live demo can be 
<a href="https://raw.githack.com/bluebindy/get_settled/main/index.html">accessed here.</a>


The Home page:

![Screenshot of get settled home page]( /assets/images.css/get_settled-home-page.png?raw=true "Home Page")

The How To page:

![Screenshot of get_settled How To page ]( /assets/images.css/get_settled-how-to.png?raw=true "How To Page")

The FAQ page:
insert when h3 tag fixed. 



---
### Technologies
1. HTML
2. CSS

---

### UX

User Stories <br>
As a Brit wanting to naturalise as Irish, I want easy to find answers to common questions

As an affiliate marketer, I want a content-based site broken into common questions so I can insert affiliate links in a value-driven way for the user. 

Strategy  <br>
The strategic aim is to create a site that users find easy to scan for common questions and provides the client with natural opportunity to insert affiliate links in a later version. The tone is intended to be peer-created and accessible to encourage sharing but alsocredible to foster trustworthiness. 

Scope  <br>
This version is intended to offer minimum content only. The intention is that subsequent versions add content and also affiliate links. 

Structure  <br>
The three page structure is designed to break common questions into manageable sections for users while encouraging time spent on the site. The landing page is designed to presents an email mailing list sign-up form above the fold to maximise sign-ups. The strict replication of page structure was intended to reduce user effort and increase the sense of familiarity to foster a brand of cutting-through-confusion. 

Skeleton  <br>
  The wireframe for the home page, desktop version:

  ![Screenshot of wireframe for home page]( /assets/images.css/wireframe-home-desk.png?raw=true "Home Page")

  The wireframe for the How To page, desktop version:
![Screenshot of wireframe for home page]( /assets/images.css/wireframe-howto-desk.png?raw=true "Home Page")

  The wireframe for the FAQ page, desktop version:
![Screenshot of wireframe for home page]( /assets/images.css/wireframe-faq-desk.png?raw=true "Home Page")

  The wireframe for the How To page, mobile version:  <br>
![Screenshot of wireframe for home page]( /assets/images.css/wireframe-faq-mobile.png?raw=true "Home Page")


Surface  <br>
The high-contrast and naive colour scheme was chosen to flag the peer-driven nature of the resource, and contrast to a higly-stylised corporate effort. The orange and green theme was selected specifically to reference the Irish flag and provide a visual reference to the purpose of the site. 

---
### Features
  <br>
<strong>Features included in this current version</strong>  <br>
The website includes a navigation bar and user entry email form. Content is accessed through a scrollbar where it extends beyond the initial text space. <br>
  <br>
<strong>Features planned for later versions</strong>  <br>
As more content is added, a website search function will be added for UX purposes. When the client is ready to convert the site to an affiliate revenue website, affiliate links will be added.  

---

### Deployment

Github pages were used for deployment. The landing page ('Home') is index.html, as is required by Github Pages for successful deployment. If using Gitpod, code can be commited from the local filesystem to Github using 'git commit -m "" ' on the terminal. Code can be pushed form the local filesystem to Github by using 'git push' on the terminal. 

The original repository is available at: <a href="https://github.com/BlueBindy/get_settled">get_settled</a> and is created by <a href="https://github.com/BlueBindy">Fiona Thompson under username BlueBindy</a>. The repository can be cloned to run locally by inserting `git clone https://github.com/BlueBindy/get_settled.git` into a terminal. To create a repository that is not forked from the original, use `git remote rm origin` in the terminal CI. The site deployed from the original repository will automatically reflect new commits made to the master branch.

Github Pages were created by nominating index.html from the main branch of the repository as the entry file for the publishing source. Then settings/Code and Automation/

To set up GIthub Pages, from the repository, select main as a publishing source.

FINISH deployment here...

**The deployment write-up should include full instructions on how to get the application from code to hosting. I’d suggest explaining (1) how you set up Github Pages, (2) how one commits and pushes code from the local filesystem to Github and how Github Pages automatically picks that up, and (3) how one might clone and run it locally.**

---
## Testing

 ### 1. Functionality Testing 
---
All tests peformed on 'bluebindy.github.io/get_settled/' on Chrome, Safari and Firefox browsers on a 13-inch early 2015 Macbook Air using MacOS Monterary v12.5.1. The exception to this is the Lighthouse accesssibility test which was performed on Chrome only.  <br>

---

 Test label: Social media links   <br>
 Test action: Click social media icons in footer   <br>
 Expected outcome: Hover hand and highlight appears, click opens correct page in new tab. Expected page for links is home page of social media platform as there are no social media accounts created for this project.   <br>
 Test outcome: PASS  <br>

 ---

 Test label: Embedded text links   <br>
 Test action: Click link   <br>
 Expected outcome: Hover hand and green higlight and underline appears on mouse over; click opens correct page in new tab. On return to website, text is momentarily highligted green and then changes to a different green highlight. Highlight disappears when different part of website is clicked.   <br>
 Test outcome: PASS   <br>

---

Test label: Email form  <br>
Test action: Enter first name, last name and email address into appropriate fields and click 'Send'.
Expected outcome: When appropriate text is entered, the Code Insitute's formdump page opens in a new tab, confirming details entered. On return to website, entered data is cleared when website is refreshed. When incorrect data is entered (specifically, something other than a functioning email is entered in the Email field, or nothing is entered in First Name or Last Name) a user error warning appears. 
Test outcome: PASS  <br>

---

Test label: Navigation menu  <br>
Test action: Click on navigation links at top of website  <br>
Expected outcome: On mouse over, a hover hand, green highlight and underline appears. On click, the user is taken to the correct website page. Clicking on Get Settled logo produces hover hand but no highlight or underline and takes user to Home page. No highlight remains when user is on selected web page. Clicking navigation links should not open a new tab but keep user on the same tab.  <br>
Test outcome: PASS  <br>

---

Test label: Images  <br>
Test action: Images can be seen on website  <br>
Expected outcome: On page load, all images (both decorative and semantic) appear and load with less than 1 second delay and are not stretched or distorted.  <br>
Test outcome: PASS  <br>

---

Test label: Fonts  <br>
Test action: Fonts are visible  <br>
Expected outcome: On page load, Oswald loads and is readable.  <br>
Test outcome: PASS after modifications. Initially Oswald did not load on Safari browser, but the default sans serif was produced instead. CSS code 'font-display: swap' was added to the body element to trigger loading of Oswald.  <br>

---

Test label: Responsivity  <br>
Test action: Website responds to varying screen sizes by producing a layout that is readable and intuitive to users.  <br>
Expected action: When the website is viewed on desktops (2560 px and 3072 px) and mobiles (320 px, 490 px and 428 px), the layout automatically re-assembles in an intuitive and readable layout. Navigation menu, social media links, email form and embedded text links are accessible.  <br>
Test outcome: PASS  <br>

---
### 2. Browser Compatability
Test label: Browser compatibility  <br>
Test action: Request website (using 'bluebindy.github.io/get_settled/') on Chrome, Firefox and Safari browsers.  <br>
Expected action: Website appears (including all images) as expected, with all elements, within 2 seconds. <br>
Test outcome: PASS  <br>

---

### 5. Accessibility
Test label: Accessibility testing  <br>
Test action: Perform a Lighthouse test using Chrome Developer Tools.   <br>
Expected action: Best Practices, SEO and Accessibility should return 95+ and Performance should return 90+.  <br>
Test outcome: PASS after initial feedback was incorporated. Feedback included compressing images and converting to WebP for Performance. Feedback also included providing additional padding for social media icons for Accessibility. Producing stable Lighthouse results required all background browsers to be closed and icognito browser mode to be used.   <br>

---

### 6. Validator Testing
Test label: W3 HTML validation  <br>
Test action: Perform a W3 HTML validation test   <br>
Expected action: W3 HTML validation passed with no issues outstanding  <br>
Test outcome: PASS after initial feedback was incorporated. Initial W3 html testing recommended additional H2/3/4 headings and fewer H1 headings. Some stray and unclosed tags were also highlighted. After recommendations were implemented, W3 html testing indicated no further issues.  <br>
 
---

Test label: W3 CSS validation (Jigsaw)  <br>
Test action: Perform a W3 CSS validation test  <br>
Expected action: W3 CSS validation passed with no issues outstanding  <br>
Test outcome: PASS after initial feedback was incorporated. Initial W3 CSS testing indicated some duplicate tags and an error in a function name. Once removed no further issues were reported. 

---

---

## Copyright and acknowledgements

Responsiveness structure was developed based on the Responsive Flexbox Layout by CSS Coder at <a href=" https://www.youtube.com/watch?v=S0a7PEOi0do">Responsive Flexbox Layout Page in 4 minutes</a> . The meta data was inserted using Emmet shortcut. The default template for Gitpod is from <a href="https://github.com/Code-Institute-Org/gitpod-full-template">the Code Institute's 'my_full_template'</a>. 

<a href="https://www.fontpair.co/all">Fontpair</a> was used for font selection. <a href=" https://colorhunt.co/">Colorhunt</a> was used for palette selection. <a href = "https://imagecolorpicker.com/en">ImageColorPicker</a> was used to identify colors in images.  Icons are sourced from <a href="https://fontawesome.com/">FontAwesome</a>. <a href="https://tinypng.com/">TinyPNG</a> was used to compress images. <a href="https://convertio.co/">Convertio.co</a> was used to convert JPEG images to WEBP. <a href="http://raw.githack.com/">GitHack</a> was used to provide a live demonstration of the website.

The background image on the first aside on each page (khara-woods-irish.jpg) was taken by <a href="https://unsplash.com/@kharaoke?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Khara Woods</a> on <a href="https://unsplash.com/photos/_EaLWd6q4QM">Unsplash</a> and is free to use under the Unsplash licence. The crowd image on FAQ (rawpixel-irish-flag.jpeg) is from <a href="https://www.rawpixel.com/image/654282">Raw Pixel</a> and has a royalty free commercial licence, with required attribution: 'Image by rawpixel.com' 

HTML and CSS approaches typically taken from <a href="codeinstitute.net">Code Institute's Diploma in Full Stack Development (E-commerce Applications)</a> HTML and CSS modules. Additional suggestions, on CSS particularly, taken from <a href="https://www.w3schools.com/html/default.asp">w3schools</a>.

README structure based on <a href="https://github.com/Code-Institute-Solutions/readme-template">Code Institute's example</a>. The approach to the Deployment and Testing sections reflects guidance from <a href="https://dev.to/brianmk">Brian Macharia.</a>  

The live demo for the README was created based on <a href="https://lirad.medium.com/two-ways-to-create-a-live-demo-for-your-github-project-5436b048a40e">Diego Lira's suggestion.</a>

All content is written by Fiona Thompson. 

Mentoring from <a href="https://dev.to/brianmk">Brian Macharia</a>. All errors and ommissions the responsibility of Fiona Thompson. 

### ENDS
---