TODO  <br>
1. insert wireframes into UX->Skeleton  <br>
2. insert screenshot into Demo (just FAQ post H3 now) <br>
3. insert live demo link into Demo (is git hack ok or use pages?)  <br>
4. insert user stories into file directory  <br>
5. perform testing and insert results to Testing  <br>
6. format testing secion  <br>
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
insert screenshot here

As an affiliate marketer, I want a content-based site broken into common questions so I can insert affiliate links in a value-driven way for the user. 
insert screenshot here. 

Strategy  <br>
The strategic aim is to create a site that users find easy to scan for common questions and provides the client with natural opportunity to insert affiliate links in a later version. The tone is intended to be peer-created and accessible to encourage sharing but alsocredible to foster trustworthiness. 

Scope  <br>
This version is intended to offer minimum content only. The intention is that subsequent versions add content and also affiliate links. 

Structure  <br>
The three page structure is designed to break common questions into manageable sections for users while encouraging time spent on the site. The landing page is designed to presents an email mailing list sign-up form above the fold to maximise sign-ups. The strict replication of page structure was intended to reduce user effort and increase the sense of familiarity to foster a brand of cutting-through-confusion. 

Skeleton  <br>
    insert Wireframes here

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

Github pages were used for deployment. The landing page ('Home') is index.html, as is required by Github Pages for successful deployment. 

The original repository is available at: <a href="https://github.com/BlueBindy/get_settled">get_settled</a> and is created by <a href="https://github.com/BlueBindy">Fiona Thompson under username BlueBindy</a>. The repository can be cloned to run locally by inserting `git clone https://github.com/BlueBindy/get_settled.git` into a terminal. To create a repository that is not forked from the original, use `git remote rm origin` in the terminal CI. The site deployed from the original repository will automatically reflect new commits made to the master branch.

**The deployment write-up should include full instructions on how to get the application from code to hosting. I’d suggest explaining (1) how you set up Github Pages, (2) how one commits and pushes code from the local filesystem to Github and how Github Pages automatically picks that up, and (3) how one might clone and run it locally.**

---
## Testing

 ### 1. Functionality Testing 
### | Test Label | Test Action | Expected Outcome | Test Outcome | 
---
| Menu nav links function | Click link | Hover hand and highlight appears, click opens correct page | PASS |

---
 
| Social media links function | Click icon | Hover hand and highlight appears, click opens correct page (new tab) | PASS |

Correct page for links is home page of social media platform as there are no social media accounts created for this project. 
 
 ---
| Embedded page links function | Click icon | Hover hand and highlight appears, click opens correct page (new tab) | PASS |
 
 ---

 | Email form functions | Enter details, click submit | Prompt text disappears, Submit returns validation error if no data entered | PASS |

 ---

### 2. Browser Compatability
 The test standard is that the website renders correctly (all elements appear as expected) on Chrome, Firefox, Safari and all elements render within a maximum of **X** seconds. The test was performed using Developer Tools in the appropriate browsers. The results were successful on all browsers and maximum load time of **x seconds**. PASS

 ---


### 3. Responsivity 
The test standard is that content adjusts to a variety of screen widths with all content readable and with a UX format familiar to users. The content rendered appropriately on screen sizes : iPhone5 (320px wide), **??** and 5K iMac Pro (5120 x 2880 px) using Developer Tools on Chrome, Firefox and Safari. PASS

---

### 5. Accessibility
Automated testing: **Lighthouse**
**Is any other testing required for this project?**

### 6. Manual Testing
W3C HTML: https://validator.w3.org/
W3C CSS:https://jigsaw.w3.org/css-validator
Image rendering: All media renders correctly on deployed site. 

Initial W3 html testing recommended additional H2/3/4 headings and fewer H1 headings. Some stray and unclosed tags were also highlighted. After recommendations were implemented, W3 html testing indicated no further issues. 

Initial W3 CSS testing indicated some duplicate tags and an error in a function name. Once removed no further issues were reported. 

Lighthouse testing revealed acceptable scores for accessibality (97+), however performance issues were noted, with scores in the 80s. Images were compressed and converted to WebP to improve performance, improving Lighthouse performance to 90+. Semantically relevant images have alt attributes and link text is descriptive.

Class names are all lower case and without spaces. File names are hyphenated where needed to avoid spaces in syntax.  

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