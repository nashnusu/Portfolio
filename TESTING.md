# Testing

> [!NOTE]
> Return back to the [README.md](README.md) file.

## Code Validation

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|About| [about.html](https://nashnusu.github.io/Portfolio/about.html)| ![screenshot](/assets/images/aboutval.png) | 
|Education| [education.html](https://nashnusu.github.io/Portfolio/education.html) |![screenshot](/assets/images/eduvalidate.png) | 
|Get in touch| [getintouch.html](https://nashnusu.github.io/Portfolio/getintouch.html)|![screenshot](/assets/images/getvalidate.png | 
|Home| [index.html](https://nashnusu.github.io/Portfolio/index.html) |![screenshot](/assets/images/indexvalidate.png) | 


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| About | [about.css](https://nashnusu.github.io/Portfolio/about.css) |![screenshot](/assets/images/aboutcsval.png) |
| Education | [education.css](https://nashnusu.github.io/Portfolio/education.css) |![screenshot](/assets/images/educsv.png)
| Get in touch | [getintouch.css](https://nashnusu.github.io/Portfolio/getintouch.css) |![screenshot](/assets/images/getvalidate.png) 
| Home | [index.css](https://nashnusu.github.io/Portfolio/index.css)) |![screenshot](/assets/images/indexvalidate.png) |


## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](/assets/images/Homemobile.png) | ![screenshot](/assets/images/Hometablet.png) | ![screenshot](/assets/images/homedesk.png) | Works as expected |
| About| ![screenshot](/assets/images/aboutmobile.png) | ![screenshot](/assets/images/abouttablet.png) | ![screenshot](/assets/images/aboutdesktop.png) | Works as expected |
| Education | ![screenshot](/assets/images/edumobile.png) | ![screenshot](/assets/images/edutablet.png) | ![screenshot](/assets/images/edudesk.png) | Works as expected |
| Get intouch| ![screenshot](/assets/images/getmobile.png) | ![screenshot](/assets/images/gettablet.png) | ![screenshot](/assets/images/get.png) | Works as expected |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Safari | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot]() | ![screenshot](/assets/images/homechrome.png) | ![screenshot](/assets/images/homfire.png) |![screenshot](/assets/images/homedesk.png) | Works as expected |
| About| ![screenshot](/assets/images/aboutchotme.png) | ![screenshot](/assets/images/aboutfire.png) | ![screenshot](/assets/images/aboutdesktop.png) | Works as expected |
| Education | ![screenshot](/assets/images/educhomre.png) | ![screenshot](/assets/images/edufire.png) | ![screenshot](/assets/images/edudesk.png) | Works as expected | | Works as expected |
| Get in touch | ![screenshot](/assets/images/getchrome.png) | ![screenshot](/assets/images/getfire.png) | ![screenshot](/assets/images/get.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](/assets/images/homelightmob.png) | ![screenshot](/assets/images/homlidesk.png) |
| About | ![screenshot](/assets/images/ablightmob.pngl) | ![screenshot](/assets/images/abolightdesk.png) |
| Education | ![screenshot](/assets/images/edulightmob.png) | ![screenshot](/assets/images/edulightdesk.png) |
| Get in touch | ![screenshot](/assets/images/getlightmob.png) | ![screenshot](/assets/images/getlightdesk.png) |


## Defensive Programming
Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
| Navigation bar | Expected to work consistently on all pages and device sizes. |Clicked all links across devices (desktop, tablet, mobile).  |Navigation was consistent and functional. | ![screenshot](/assets/images/homedesk.png)|![screenshot](/assets/images/Homemobile.png)|
| Form validation|Form should not submit empty or incorrect values. |Tried submitting the contact form with empty fields and invalid email. |Form submission was blocked with error prompts. | ![screenshot](/assets/images/req.png) |
| Responsive layout| Content should adapt correctly to screen size. |Resized browser and tested on phone and tablet. | Layout adjusted smoothly without overlapping elements. | ![screenshot](/assets/images/aboutmobile.png)|
| External links| External links should open in new tabs securely.  | Clicked GitHub links  | Links opened in new tabs as expected.| ![screenshot](/assets/images/githublink.png) |

## User Story Testing

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user | I would like to clearly navigate between all pages | so that I can easily access different sections of the site from anywhere. | ![screenshot](/assets/images/homedesk.png) |
| As a user | I would like to view featured projects with descriptions | so that I can assess the type and quality of work the developer produces. | ![screenshot](/assets/images/feature.png) |
| As a user | I would like to see an education section | so that I can understand the academic qualifications of the developer. | ![screenshot](/assets/images/edudesk.png) |
| As a user | I would like to contact the developer easily | so that I can reach out for collaboration, questions, or feedback. | ![screenshot](/assets/images/get.png) |
| As a user | I would like external links to open in a new tab | so that I can explore them without losing my place on the site. | ![screenshot](/assets/images/githublink.png) |
| As a user | I would like the website to be responsive | so that I can browse it comfortably on any device. | ![screenshot](/assets/images/Homemobile.png) |![screenshot](/assets/images/Hometablet.png) |


## Bugs
-Navigation bar overlapped content on smaller screens
How it was found: Manually tested site responsiveness on mobile viewports-Fix: Added CSS media queries to adjust layout and padding-Status: ✅ Fixed

-Layout shifting occurred on the Education page
How it was found: Visual glitch seen during browser testing-Fix: Refined container widths and spacing using Flexbox-Status: ✅ Fixed

-Contact form gave no feedback after submission
How it was found: Tested form submission without success confirmation-Fix: Implemented JavaScript alert on form submission-Status: ✅ Fixed

-Some external links didn’t open in new tabs
How it was found: Clicked external links during final walkthrough-Fix: Added target="_blank" to <a> tags for all external links-Status: ✅ Fixed

### Known Issues
-Known Issue: None
Description: No known issues at the moment.
Possible Solution: N/A
Status: ✅ None

> [!IMPORTANT]
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

