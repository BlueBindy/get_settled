# README for get_settled

---

## Get Settled

The Get Settled website is a static HTML and CSS project. The intended goal is to facilitate the (theoretical) client's desire for an affiliate marketing content-based website MVP. The content is designed for a community of British people who have moved to Ireland and are seeking to naturalise as Irish after 2022 (when the application process changed significantly.) The process can be daunting and confusing; the website aims to help clarify the process.

---

### Demo

A live demo can be 
<a href="https://raw.githack.com/bluebindy/get_settled/main/index.html" target="_blank">accessed here.</a>


A screenshot of the Home page, illustrating the email mailing list sign-up form and navigation bar (to all pages) can be found below. 
* The email mailing list includes feedback on user progress (with warning signs appearing if the data is not entered correctly and a confirmation screen when the form has been correctly completed.) This reassures the user and helps them achieve their goal of joining the mailing list. 
* The landing page includes a welcome text explaining the site's intention and establishes credibility by noting that only official information sources are used. 
* Social media links are available at the bottom of the screen and open in a new window to aid user orientation. When the client creates social media accounts, these links can direct the website user directly to them (currently they point to the home page of the social media platform.)

![Screenshot of get settled home page]( /documentation-images/get_settled-home-page.webp?raw=true "Home Page")

A screenshot of the How To page can be found below. 
* The How To page presents common application questions and concise answers in non-legal language. The answer text includes text links to source materials (opening in a new window for ease of orientation) so the user can confirm or research information for themselves. 
* Navigation and social media links also appear on this page.

![Screenshot of get_settled How To page ]( /documentation-images/get_settled-how-to.webp?raw=true "How To Page")

A screenshot of the FAQ page can be found below. 
* The FAQ page lists some of the most common questions that applicants have. Concise and easily understandable answers are provided, complete with links to source material. 
* The FAQ page also has a farewell image, designed to reassure and inspire the website user on their application journey. * The FAQ page also has a navigation bar and social media links.

![Screenshot of get_settled How To page ]( /documentation-images/get_settled-faq.webp?raw=true "How To Page")


A screenshot of the 404-error page can be found below. 
* This page is not included on the navigation bar of the other website pages. Instead, it is the page a user would see if they used a link that does not exist, has been moved or has a broken link. This page does however include the navigation menu so they can navigate back to a page that does exist.

![Screenshot of get_settled 404-error page ]( /documentation-images/get_settled-page-not-found.webp?raw=true "Page Not Found")

---
### Technologies
1. HTML
2. CSS

---

### UX
**User Stories** <br>
As a Brit wanting to naturalise as Irish, I want easy to find answers to common questions

As an affiliate marketer, I want a content-based site broken into common questions so I can insert affiliate links in a value-driven way for the user. 

**Strategy**  <br>
The strategic aim is to create a site that users find easy to scan for common questions and provides the client with natural opportunity to insert affiliate links in a later version. The tone is intended to be peer-created and accessible to encourage sharing but also be credible to foster trustworthiness. 

**Scope**  <br>
This version is intended to offer minimum content in a minimum viable product (MVP) only. The intention is that subsequent versions add content and also affiliate links. 

**Structure**  <br>
The three page structure is designed to break common questions into manageable sections for users while encouraging time spent on the site. The landing page is designed to present an email mailing list sign-up form above the fold to maximise sign-ups. The strict replication of page structure was intended to reduce user effort and increase the sense of familiarity to foster a brand of cutting-through-confusion. 

**Skeleton**  <br>
  The wireframe for the home page, desktop version:

  ![Screenshot of wireframe for home page]( /documentation-images/wireframe-home-desk.webp?raw=true "Home Page")

  The wireframe for the How To page, desktop version:
![Screenshot of wireframe for home page]( /documentation-images/wireframe-howto-desk.webp?raw=true "Home Page")

  The wireframe for the FAQ page, desktop version:
![Screenshot of wireframe for home page]( /documentation-images/wireframe-faq-desk.webp?raw=true "Home Page")

  The wireframe for the How To page, mobile version:  <br>
![Screenshot of wireframe for home page]( /documentation-images/wireframe-faq-mobile.webp?raw=true "Home Page")


**Surface**  <br>
The high-contrast and naive colour scheme was chosen to flag the peer-driven nature of the resource, and contrast to a higly-stylised corporate effort. The orange and green theme was selected specifically to reference the Irish flag and provide a visual reference to the purpose of the site. 

---
### Features  <br>
**Features included in this current version**  <br>
The website includes a navigation bar in the header so the user can navigate between pages. An email form with validation is provided on the home page, enabling the user to join a mailing list and to receive feedback on their progress. These features can be seen in the screenshots available in the Demo section. Text links wtihin answers open source material in a new window, so the user still has the website open while viewing source material. The 404 error page includes a navigation bar so the user can navigate back to an existing page. <br>
  <br>
**Features planned for later versions**  <br>
As more content is added, a website search function will be added for UX purposes. When the client is ready to convert the site to an affiliate revenue website, affiliate links will be added.  

---

### Deployment

The website is deployed to GitHub Pages. The landing page ('Home') is index.html, as is required by Github Pages for successful deployment. If using Gitpod, code in all files can be added to staging by using 'git add .' on the terminal. Code can be commited from the local filesystem to Github using 'git commit -m "" ' on the terminal. Code can be pushed form the local filesystem to Github by using 'git push' on the terminal. 

The original repository is available at: <a href="https://github.com/BlueBindy/get_settled" target="_blank">get_settled</a> and is created by <a href="https://github.com/BlueBindy" target="_blank">Fiona Thompson under username BlueBindy</a>. The repository can be cloned to run locally by inserting `git clone https://github.com/BlueBindy/get_settled.git` into a terminal. To create a repository that is not forked from the original, use `git remote rm origin` in the terminal. 

Deployment to GitHub Pages is done by navigating from the repository (use 'https://github.com/BlueBindy/get_settled' in a browser) to settings tab (in the menu above the repository, not in the User Profile) and then to source. From here, select the master branch. The <a href="https://github.com/BlueBindy/get_settled/deployments/activity_log?environment=github-pages" target="_blank">deployed version</a> (use 'https://bluebindy.github.io/get_settled/' in a browser) is specified as 'Active'. The deployed site is then viewable by clicking the 'View Deployment' button. The site deployed from the original repository will automatically reflect new commits made to the master branch (potentially after a short queuing delay).

---
## Testing

 ### 1. Functionality Testing 
---
All tests peformed on 'bluebindy.github.io/get_settled/' on Chrome, Safari and Firefox browsers on a 13-inch early 2015 Macbook Air using MacOS Monterey v12.5.1. The exception to this is the Lighthouse accesssibility test which was performed on Chrome only.  <br>

---

 **Test label:** Social media links   <br>
 **Test action:** Hover over link, click link, view opened page, return to website via browser tab, click elsewhere on website.Repeat on Chrome, Firefox and Safari.   <br>
 **Expected outcome:** On mouse over, hover hand, green highlight and black bottom border appears. Click opens correct page in new tab. Expected page for social links is home page of relevant social media platform as there are no social media accounts created for this project. On return to website, icon remains briefly green highlighted, with black bottom border before changing to a paler green with bottom border. Highlight and bottom border disappear when screen refreshed or somewhere else on page clicked.   <br>
 **Test outcome:** PASS  <br>

 ---

 **Test label:** Embedded text links   <br>
 **Test action:** Hover over link, click link, view opened page, return to website via browser tab, click elsewhere on website. Repeat on Chrome, Firefox and Safari.   <br>
 **Expected outcome:** Hover hand, green higlight and black bottom border appears on mouse over; click opens correct page in new tab. On return to website, icon remains briefly green highlighted, with black bottom border before changing to a paler green with bottom border. Highlight and bottom border disappear when screen refreshed or somewhere else on page clicked.    <br>
 **Test outcome:** PASS after code modifications were incorporated for Safari and Firefox and with a README exception when viewed from GitHub. 
 * Initially Firefox and Safari browser defaults were overriding CSS color choices on unvisited and visited links. A class was added to the text links to increase their specificity to override the browser defaults in turn. When the class was targetted with CSS color preferences the color presentation in Safari and Firefox aligned with the Chrome experience and the desired experience. 
 * When viewed from GitHub, the text links in README do not open in a new window. A number of sources (StackOverflow, LaraCast forum, Code Institute Tutor session) suggest that GitHub does not allow this feature based on HTML code. *Users who wish to open these links in a new tab can instead use: CTRL+click (on Windows and Linux) or CMD+click (on MacOS).*  <br>

---

**Test label:** Email form  <br>
**Test action:** Enter first name, last name and email address into appropriate fields and click 'Send' ('appropriate text'). Click send without entering first name, last name and email address ('missing data'). Click send after entering email address without '@' ('incorrect data'). Repeat on Chrome, Firefox and Safari.  <br>
**Expected outcome:** When appropriate text is entered, the Code Insitute's formdump page opens in a new tab, confirming details entered. On return to website, entered data is cleared when website is refreshed. When missing or incorrect data is entered (specifically, something other than a functioning email is entered in the Email field, or nothing is entered in First Name or Last Name) a user error warning appears and data is not sent.  <br>
**Test outcome:** PASS  <br>

---

**Test label:** Navigation menu  <br>
**Test action:** Hover over menu link, click link, view selected website page page, return to a different website via menu link click. Repeat for Safari, Chrome and Firefox. <br>
**Expected outcome:** On mouse over, a hover hand, green highlight and black bottom border appears. On click, the user is taken to the correct website page. Clicking on Get Settled logo produces hover hand but no highlight or underline and takes user to Home page. No highlight or bottom borner remains when user is on selected web page. Clicking navigation links should not open a new tab but keep user on the same tab.  <br>
**Test outcome:** PASS  <br>

---

**Test label:** Images  <br>
**Test action:** Hard refresh broswer cache, navigate to web page with image, time image load time, inspect image. Manually minimise desktop screen size and inspect image. Repeat on Chrome, Firefox and Safari. Repeat using Chrome Developer Tools set for iPhone 5/SE (320 by 568), Surface Duo (540 by 720), iPad Mini (768 by 1024) and Pro Display XDR (6016 by 3384).   <br>
**Expected outcome:** On page load, all images (both decorative and semantic) appear and load with less than 1 second delay and are not stretched or distorted.  <br>
**Test outcome:** PASS after file compression and conversion to WebP.   <br>

---

**Test label:** Fonts  <br>
**Test action:** Inspect fonts after hard cache refresh on Chrome, Safari and Firefox browsers. Repeat while manually adjusting window size from minimum to maximum.  <br>
**Expected outcome:** On page load, Oswald font loads and is legible.  <br>
**Test outcome:** PASS after modifications. 
* Initially Oswald did not load on Safari browser, but the default sans serif was produced instead. CSS code 'font-display: swap' was added to the body element to trigger loading of Oswald (based on a developer.mozilla.org suggestion). Oswald successfully loaded on Safari after this code addition. However, this CSS code failed the W3 Jigsaw test ('Property font-display doesn't exist: swap') and on inspection, as it was apparent it is alreaddy embedded in the Google Fonts url import, it was removed. The failure to load Oswald font error could not be reproduced on later testing after the code was removed. Instead, Oswald loaded on Safari on all subsequent tests.  <br>

---

**Test label:** Responsivity  <br>
**Test action:** Manually minimise desktop screen size and inspect each web page. Repeat on Chrome, Firefox and Safari.  Repeat using Chrome Developer Tools set for iPhone 5/SE (320 by 568), Surface Duo (540 by 720), iPad Mini (768 by 1024) and Pro Display XDR (6016 by 3384).  <br>
**Expected outcome:** When the website is viewed on a range of screen sizes, the layout automatically re-assembles in an intuitive, legible and expected layout. Navigation menu, social media links, email form and embedded text links are accessible.  <br>
**Test outcome:** PASS after code modification for H3 text overlay on FAQ image. 
* Initially this text did not stay in an appropriate position; on very small screens it either migrated up or disappeared. Positioning was modified from cardinal to percentage units as suggested by Brian Macharia. This modification resulted in the text appearing as expected on a range of screens. <br>

---
**Test label:** Code format compliance  <br>
**Test action:** Review all HTML (particularly attributes) and CSS (particularly rules) code, and all file and directory names.  <br>
**Expected outcome:** No uppercase letters used; no spaces found. Multiple words in HTML and CSS declarative code are joined using hyphens, except for repository level names which should use an underscore where necessary. All names are distinctive and intrinsically meaningful. CSS code is filed in an file external to HTML pages and linked to the HTML page in the HEAD element.  <br>
**Test outcome:** PASS after discrepancies were modified (particularly variations in use of hyphen and underscore in attribute names).  <br>

---

**Test label:** Images and links include accessibility labels.  <br>
**Test action:** Review all images and links for accessibility label or clarify why not present.  <br>
**Expected outcome:** All semantically relevant images include self-explanatory accessibility label.All text links include self-explanatory label as part of text.  <br>
**Test outcome:** PASS. Images used for decorative purposes only have no accessibility labels, but this is acceptable.  <br>

---

**Test label:** File organisation  <br>
**Test action:** Review all files and directories  <br>
**Expected outcome:** Index.html is registered as 'Home' page via listing as entry file for the site on GitHub Pages. All static files to be published on the website are within assets/images.css/ . All files for README.md are within documentation-images/  . All css files are within assets/css/ .All files are grouped by type.  <br>
**Test outcome:** PASS.  <br>

---

### 2. Browser Compatability
**Test label:** Browser compatibility  <br>
**Test action:** Request website (using 'bluebindy.github.io/get_settled/') on Chrome, Firefox and Safari browsers.  <br>
**Expected outcome:** Website appears (including all images) as expected, with all elements, within 2 seconds. <br>
**Test outcome:** PASS after modifications listed in manual testing section. <br>

---

### 5. Accessibility
**Test label:** Accessibility testing  <br>
**Test action:** Perform two Lighthouse tests using Chrome Developer Tools (First Mode Navigation and Device Mobile and then second, Mode Navigation and Device Desktop.) across all pages (to check for consistency of results.) <br>
**Expected outcome:** Best Practices, SEO and Accessibility should return 95+ and Performance should return 90+.  <br>
**Test outcome:** PASS after initial feedback was incorporated. 
* Mobile results were 100 for Accessibility, Best Practices and SEO; Performance was 97. Desktop results were 100 for Accessibility, Best Practices and SEO; Performance was 98. 
* Feedback included compressing images (for the web page and also README images) and converting to WebP for Performance. Additional Performance feedback included using preload and dns-prefetch for the Google Fonts in the HTML head to speed up page load but this produced varying results and was removed. Feedback also included providing additional padding for social media icons for Accessibility. 
* Producing stable Lighthouse results required all background browsers to be closed and icognito browser mode to be used.   <br>

---
### 6. Validator Testing
**Test label:** W3 HTML validation  <br>
**Test action:** Perform a W3 HTML validation test on all pages (Home, How To, FAQ and Page Not Found)   <br>
**Expected outcome:** W3 HTML validation passed with zero errors and ideally no warnings (desired not essential).  <br>
**Test outcome:** PASS (0 errors, 0 warnings) after initial feedback was incorporated. 
* Initial W3 HTML testing recommended additional H2/3/4 headings and fewer H1 headings. Some stray and unclosed tags were also highlighted. Feedback also suggested some sections were changed to divs unless headers were used. Headers for these sections (eg Line 18, index.html) were not semantically appropriate and so divs were used in all noted instances. After recommendations were implemented, W3 HTML testing indicated no errors or warnings.  <br>
 
---

**Test label:** W3 CSS validation (Jigsaw)  <br>
**Test action:** Perform a W3 CSS validation test  <br>
**Expected outcome:** W3 CSS validation passed with no issues outstanding  <br>
**Test outcome:** PASS after initial feedback was incorporated. Initial W3 CSS testing indicated some duplicate tags and an error in a function name. Once removed no further issues were reported.  <br>

---

---

## Copyright and acknowledgements

**Resources**  <br>

<a href="https://www.fontpair.co/all" target="_blank">Fontpair</a> was used for font selection. <a href=" https://colorhunt.co/" target="_blank">Colorhunt</a> was used for palette selection. <a href = "https://imagecolorpicker.com/en" target="_blank">ImageColorPicker</a> was used to identify colors in images.  Icons are sourced from <a href="https://fontawesome.com/" target="_blank">FontAwesome</a>. <a href="https://tinypng.com/" target="_blank">TinyPNG</a> was used to compress images. <a href="https://convertio.co/" target="_blank">Convertio.co</a> was used to convert JPEG images to WEBP. <a href="http://raw.githack.com/" target="_blank">GitHack</a> was used to provide a live demonstration of the website.

**Media**  <br>
The background image on the first aside on each page (khara-woods-irish.jpg) was taken by <a href="https://unsplash.com/@kharaoke?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText" target="_blank">Khara Woods</a> on <a href="https://unsplash.com/photos/_EaLWd6q4QM" target="_blank">Unsplash</a> and is free to use under the Unsplash licence. The crowd image on FAQ (rawpixel-irish-flag.jpeg) is from <a href="https://www.rawpixel.com/image/654282" target="_blank">Raw Pixel</a> and has a royalty free commercial licence, with required attribution: 'Image by rawpixel.com' 

**Code and structure**  <br>
HTML and CSS approaches based on <a href="https://codeinstitute.net/ie/" target="_blank">Code Institute's Diploma in Full Stack Development (E-commerce Applications)</a> HTML and CSS modules. Additional suggestions, on CSS user feedback particularly, taken from <a href="https://www.w3schools.com/html/default.asp" target="_blank">w3schools</a>.

Responsiveness structure was developed based on the Responsive Flexbox Layout by CSS Coder at <a href=" https://www.youtube.com/watch?v=S0a7PEOi0do" target="_blank">Responsive Flexbox Layout Page in 4 minutes</a> . The meta data was inserted using Emmet shortcut. The default template for Gitpod is from <a href="https://github.com/Code-Institute-Org/gitpod-full-template" target="_blank">the Code Institute's 'my_full_template'</a>. 

Mentoring from <a href="https://dev.to/brianmk" target="_blank">Brian Macharia</a>. All errors and ommissions the responsibility of Fiona Thompson. 

README structure based on <a href="https://github.com/Code-Institute-Solutions/readme-template" target="_blank">Code Institute's example</a>. The approach to the Deployment and Testing sections reflects guidance from <a href="https://dev.to/brianmk" target="_blank">Brian Macharia.</a>  

The live demo for the README was created based on <a href="https://lirad.medium.com/two-ways-to-create-a-live-demo-for-your-github-project-5436b048a40e" target="_blank">Diego Lira's suggestion.</a>

**Content**  <br>
All content is written by Fiona Thompson. 


### ENDS
---