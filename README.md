## Website Title (Homeland Living | real estate developer)

Is a website for people interested in real estate and newly build apartments/houses in particular.

I am very curious about residential real estate development and how the industry is changing in view of the sustainability issues, affordable housing and the complexities of designing and planning new residential buildings that fit with the neighborhood but likewise fit with the architecture of a given area. 

The goal of the website is attraction of interest in the product and to convey message of quality, reliability of project completion, and sustainability in construction work. Content and images of the website are more a teaser to create interest as the prodcut itself (residential real estate) is an emotional choice of customers with further detailled explanation once user has taken action to get in touch with real estate developer ("Homeland Living").

![Multi_Device_Image](readme_images/multi_device_image.png)

## Purpose

The project is a static website with 6 number of pages.

The website is built with HTML and CSS for Code Institute's Full Stack Developer course - Project 1

**[FinalProject](https://werner-staeblein.github.io/Project-1/)**

# User Experience

## First time users
**User Story 1: Potential homebuyer**

Wants to navigate website easily on all conceivable device. User is interested in newly built apartments or townhouses
Wants to see key characteristics of apartments for sale such as availability, size

**User Story 2: Potential homebuyer**

Explore information about neighborhood, amenities, assessment of location and overall offering

**User Story 3: Potential homebuyer**
Information thorugh images and floor plan structures available. Information on potential sustainability, reliability, quality

**User Story 4: Potential homebuyer**
Possibility to obtain further information with contact optionality, possible receive newsletter

## Returning users
        
**User Story 1: Returing visitor**

See if new property listings or projects have become available			
                
**User Story 2: Returing visitor**

Return to the website to support decision-making and information-gathering for potential purchase of real estate			
                
## All users
Users want to view and access the website from different devices with various screen-sizes			
Website shall be accessible with screenreaders			

# Structure

The website has 6 pages. From the homepage, all pages can be visited. Key of navigation centered around multiple options to view current projects/products on offer. Site-specific content rather than placeholder text was used

# Homepage

Message to user that user can find information about residential construction 

Image of visioanry building to increase appeal and attractiveness/stickiness of user. Create curiositiy about "hello"-product (visionary building)

Highlight key projects for different segment of buyers (Urban Living, Golden Agers, Vision Living) and provide information about features sought after by prospective buyers (substainability, quality of craftmanship, energy efficiency)

![Starting_page](readme_images/finished_starting_page.png)

![Starting_page](readme_images/finished_starting_page_part_2.png)

![Starting_page](readme_images/finished_starting_page_part3.png)

# Website goal

+ engage user to find more information and get in contact
+ brand representation
+ route user to to products page and contact page to initate contact 

# Design
Inital drawings and idea with wireframe. Some content originally in wireframe changed in final version. Set-up of layout and structure to allow for definition of utilities class such as utilities classes for flexbox

![wireframe_first_page](readme_images/wireframe.png)

# Color Scheme

![Color Palette](readme_images/color_palette.png)

Color palette used with meaning and interpreation of blue color in mind. Blue conveys a **sense of trust, stability and reliability**. 

Color blue as core for the color scheme also conveys dependability, an important factor for the underlying product advertised ('dependable real estate developer')

# Typograhpy

Font type that **conveys stability and credibility (Open Sans)** used.
Google font-type hosted locally (without CDN) for reasons of European GDPR. Minimal loss on performance through local hosting of googlefonts but GDPR rules weigh more than performance benefit of CDN

# Images

Difficult to obtain consistent AND FREE images (assets) that can be used for this project on sites such as Pexels, Unsplash, Pixaby was difficult

Images generated with image-generator, in particular to be able to generate an image that shows a visionary type of housing

Image Generator used:

**[DeepAI](https://deepai.org/)**

Other selected images (unsplash, pexels) are free of licenses.

# Accessibility

- use of aria labels with descriptive alt text for non-test elements and tags to provide information for screenreaders and cater for the visutally impaired
- use of ARIA roles and aria-label to ensure smooth experience with screenreaders
- Website was checked with Google Lighthouse for color balance to be sufficient and to have best possible access for users with color blindness

# Visual effects

## Hover on buttons
Some subtle highlighting of background-color on hover/focus state for buttons

## Buttons
Uniform styling of all buttons across all the different pages sith subtle uniform hover/focus-state effect

# Features

### Logo (Home Page)

Logo created with LogoMaker of Experte.de **[LogoCreatorExperte.de](https://www.experte.de/logo-maker#/creator)**

The logo that serves as a link to the homepage is used in the navigation and footer. With click on logo, user can navigate back to homepage (index.html) all the time

![Logo](readme_images/logo.png)

### Icons in Navbar

Navbar includes fontawesome icons

![Icon_features_navbar](readme_images/icon_features_navbar.png)

### Buttons

Well-designed buttons to enhance website navigation. Guides users towrds important section of projects or contact page

![Button](readme_images/button.png)

### Hover Effects
Mild hover effects on buttons to add layer of responsiveness. Visual feedback, signaling to users that an element is interactive. This responsiveness contributes to a more engaging and dynamic user experience, making the website feel modern and user-focused.

### scroll to top button with arrow
For users with mobile devices, an easilty recognizable scroll-to-top button with arrow was included in footer

![Scroll_to_Top](readme_images/scroll_to_top_feature.png)

### submenu in footer
To ease navigation, a submenu with links to important pages was included in the footer

![FooterSubmenu](readme_images/submenu_footer.png)

### confirmation of form submission
User receives feedback upon successful submission of the contact form. I also tested the form to work with formdump.codeinstitute.net

![ConfirmationSubmission](readme_images/confirmation_submission.png)

### Hamburger Menu for small devices (tablet/smartphones)
To allow for a proper collapsing of the menu/navbar, a CSS-based hamburger menu was used so
that navbar/menu can be opened/closed by user. Once link in hamburger menu is clicked, menu disappears on forwarding to clicked page 

![Hamburger_Menu](readme_images/hamburger_menu.png)

### subtle hover effect with opacity on hover on images
A subtle opacity effect on hover on images was used

# Technologies used

- HTML, CSS

- **[GitHub](https://www.github.com)** - GitHub for storage of files

- **[GitPod](https://www.gitpod.io/)** - GitPod as IDE for development of this site

- **[Git](https://git-scm.com)** - Version control system Git

- **[GoogleFonts](https://fonts.google.com/)** - Google Fonts stored locally in project to company with European GDPR that does not allow for usage of CDN

- **[FontAwesome](https://fontawesome.com/)** - Fontawesome stored locally as CDN not allowed under European GDPR

- **[HTMLValidator](https://validator.w3.org/)** - W3C HTML markup validator for validation of HTML code

- **[JigsawCSS](https://jigsaw.w3.org/css-validator/)** - W3C Jigsaw CSS validator for validation of CSS code

- **[DeepAI](https://deepai.org/)** - to generate images

- **[Visual Code Studios](https://code.visualstudio.com/)** - IDE used to draft the webiste and make working progress remarks in the README.md including placehoders to check for final polishing

- **[Google Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools)**- To check responsiveness of page, debug code, and important lighthouse checks for performance, accessibility, best practices, SEO

- **[Techsini](https://techsini.com/multi-mockup/index.php)** - to generate multi-device image with different screensizes and devices possibly used by user

- **[Balsamiq](https://balsamiq.com/)** - to generate wireframe and layout for first page and think about structure of containers, sections, image/text combinations

- A template provided by Code Institute for the workspace of the project

# Testing

Testing was ongoing with DevTools of Google. Testing done across other Browsers (Firefox, Edge)

The following issues were addressed while testing:

* remove redundant .css files in fontawesome folder so that only the fontawesome .css in the folder that are used in the project (reduces render-blocking files and increases site-load speed)

* ARIA warnings in lighthouse addressed with aria-labels and use of role to ensure conformity with accessibility guidelines across all pages

* ARIA warning on contrast. Occassionally, the lighthouse testing showed an insufficient contrast (scores reported yb lighthouse not always consistent with various test cycles). Change of colors and background colors to ensure sufficient contrast

* Performance and load of website was insufficient initally. Reduced image sizes to ensure that performance is improved

*  Lighthouse testing indicates minimal performance losses (values of 98-99) on mobile for use of fontawesome and google fonts locally (instaed of CDN). In order to be compliant 
with GDPR (a European law always matters more than a lighthouse performance score), I decided to maintain fontawesome and googlefonts locally without CDN as performance loss
is still acceptable. No performance losses on desktop

* manual checks that no broken internal links exist

* descriptive name files, descriptive image names without spaces or capitalisations to ensure cross-platform compatibility

* ensured that code is indented in consistent manner to ease readability with no unnecessary repeated blank lines

* Checked that valiation on input fields is done before submission via HTML valiation in input fields

* Checked responsiveness manually on various screensizes and devices including iPhone SE, iPhone XR, iPhne2Pro, SamsungGalaxy S8+, SamsungGalaxyS20Ultra, IPad Pro, IPad Air, IPad Mini

* Tried a fade-in effect for each of the pages with @keyframes such as every new page would be fading in with opacity from zero to 1. This CSS feature, however, would have had substanial effects on performance and lighthouse testing suggested to drop this idea and feature altogether for performance reasons

**Automated testing and validation**

1. **[W3 Markup Validation](https://validator.w3.org/) - HTML Validation**

All sites of the website was tested with HTML validator while developing. No errors or warnings were found on any of the pages

2. **[W3 Jigsaw](https://jigsaw.w3.org/css-validator/) - CSS Validation**

The CSS stylesheet was tested with CSS validator (jigsaw) while developing. No errors were found.

![style.css CSS validator check](readme_images/jigsaw_CSS_validator_check.png)

3. **[Google Lighthouse](https://developers.google.com/web/tools/lighthouse)**

Lighthouse reported some minor performance losses for use of fontawesome and googlefonts locally. Both stored locally instead of CDN for reasons of GDPR. Minor losses on performance acceptable rather than using GDPR non-compliant CDN

**lighthouse test desktop (scores reported by lighthouse)**

| File                |  Perf.  | Access. | Best P. | SEO     |
|---------------------|---------|---------|---------|---------|
| index.html          |   100   |   100   |   100   |   100   |
| projects.html       |   100   |   100   |   100   |   100   |
| quality.html        |   94    |   98    |   100   |   100   |
| references.html     |   100   |   100   |   100   |   100   |
| contact.html        |   100   |   100   |   100   |   100   |
| contact2.html       |   100   |   100   |   100   |   100   |

**lighthouse test mobile (scores reported by lighthouse)**

| File                |  Perf.  | Access. | Best P. | SEO     |
|---------------------|---------|---------|---------|---------|
| index.html          |   98    |   100   |   95    |   100   |
| projects.html       |   99    |   100   |   95    |   100   |
| quality.html        |   99    |   98    |   95    |   100   |
| references.html     |   99    |   100   |   95    |   100   |
| contact.html        |   100   |   100   |   95    |   100   |
| contact2.html       |   100   |   100   |   95    |   100   |

# User Stories

| Expectations of user website             | Realisation in website              |
| --------------------- | ---------------------- |
| User wants to easily be informed about available projects       | Website provides information on properties in development, including location, surroundings, and available floorplan structures       |
| Local resident user wants information on construction progress, developments in the neighborhood       | Website showcases images and plans of planned projects, including information on potential amenities in the surroundings for local residents in the neighborhood       |
| User wants to be informed on key themes such as quality or sustainability       | Website allows users to obtain information about sustainability (green buildings) and quality control in the development process       |
| Returning user wants updates on potential new projects       | Website informs the returning user about the development progress and sales starting dates, including the number of units still available       |
| Mobile users want a responsive and mobile-friendly design       | Website is responsive for various devices, ensuring a user-friendly experience with different devices and screen sizes       |
| Potential property investor user wants to see key information on floor plans, development location, and short informative facts       | Website provides key parameters that investors watch out for in the projects section       |

# Deployment

This project is deployed to GitHub pages. The deployment steps are as follows:

1. Log in to Github und www.github.com
2. Find repository of this project named (Werner-Staeblein/Project-1)
3. In the headings of the repository find "settings". The settings are on outer right hand side next to "insight" and "security" in the repository sub-heading. Click "settings" here 
4. In settings, a navigation on the left-hand side is shown. This navigation has the first heading "General". In this column that starts with "General" and und der "code and automation" click the link named "Pages". This link named "Pages" is directly on top of the submenu "Security". What matters here is that "Pages" is clicked.
5. You will now see a heading named "GitHub Pages". In the GitHub Pages, go to "build and deployment". In the heading "Branch" choose the options "main" and "/root"
6. Click Save
7. The project from the GitHub site will be deployed at the URL displayed under "Deployments". This heading "Deployments" can be found on the starting page of the GitHub Project. This starting page of the GitHub project can be found here

The link to the project is 
**[FinalProject](https://werner-staeblein.github.io/Project-1/)**

# Credits

- The tutorial from Code Institute (Live Running Project) particularly helpful for the navigation.

- The video "Pure CSS Hamburger Menu & Overlay" on YouTube by author TraversyMedia was used to better understand workings of checkbox hack for hamburger menu. As this is pure HTML/CSS project, I was watching out for possibilities for a hamburger menu without using JS and used this video mentioned as guide to understand the workings of the "CSS-Hamburger-Checkbox-Hack"

# Content

Text content of this website was written by the owner.

Readme.md file follows the structure of Readme.md provided by Code Institute **[Code Institute readme template](https://github.com/Code-Institute-Solutions/readme-template)**. 

I also reviewed a variety of different Readme.md prepared and included in the respective GitHub profiles of Code Institute students. I tried to pick the best of all ideas and suggestions.

# Acknowledgments

Special thanks to my mentor David Bowers. Incredible to see how much value I was able to add with his ideas and instructions.

My fellow students at CI have helped a lot with their various postings, questions, answers with myself being able to pick up ideas, avoid mistakes and stay motivated