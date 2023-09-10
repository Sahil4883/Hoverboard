# Testing <!-- omit in toc -->

[<img alt="Live page Badge" src="https://img.shields.io/badge/live_page-purple?logo=googlechrome&logoColor=white">](https://lmcrean.github.io/Hoverboard/) [<img alt="Full Documentation Research Badge" src="https://img.shields.io/badge/Testing-purple?logo=mdBook">](https://github.com/lmcrean/Hoverboard/blob/main/testing.md) [![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/lmcrean/Hoverboard?color=green)](https://github.com/lmcrean/Hoverboard/commits/main) [![GitHub closed issues](https://img.shields.io/github/issues-closed/lmcrean/Hoverboard?color=green)](https://github.com/lmcrean/Hoverboard/issues?q=is%3Aissue+is%3Aclosed) [![GitHub issues](https://img.shields.io/github/issues/lmcrean/Hoverboard?label=%20
)](https://github.com/lmcrean/Hoverboard/issues) [<img alt="workflow" src="https://img.shields.io/badge/Issues_workflow-grey?logo=github">](https://github.com/lmcrean/Hoverboard/blob/main/testing.md) [![HTML](https://img.shields.io/github/issues/lmcrean/Hoverboard/html?logo=html5&logoColor=white&label=HTML&color=yellow)](https://github.com/lmcrean/Hoverboard/labels/html) [![CSSl](https://img.shields.io/github/issues/lmcrean/Hoverboard/css?logo=css3&label=CSS&color=yellow)](https://github.com/lmcrean/Hoverboard/labels/css) [![Documentation](https://img.shields.io/github/issues/lmcrean/Hoverboard/documentation?logo=mdBook&label=Documentation&color=yellow)](https://github.com/lmcrean/Hoverboard/labels/css)

This testing page covers technical accounts that do not fit into the readme. This includes research.

Table of Contents:
- [1. Strategy and Scope Testing](#1-strategy-and-scope-testing)
  - [1.1. Research](#11-research)
    - [1.1.1. VLE Websites](#111-vle-websites)
    - [1.1.2. Articles on Paperless Schools](#112-articles-on-paperless-schools)
    - [1.1.3. CSS resources](#113-css-resources)
  - [1.2. Client Premise](#12-client-premise)
  - [1.3. Client Experience of the website and objective:](#13-client-experience-of-the-website-and-objective)
- [2. Manual Testing](#2-manual-testing)
  - [2.1. Responsiveness by Feature](#21-responsiveness-by-feature)
  - [2.2. Browser Testing](#22-browser-testing)
  - [2.3. HTML Hyperlinks test](#23-html-hyperlinks-test)
  - [2.4. HTML form test](#24-html-form-test)
- [3. Automatic Testing](#3-automatic-testing)
  - [3.1. W3C HTML Validator](#31-w3c-html-validator)
  - [3.2. W3 CSS Jigsaw Validator](#32-w3-css-jigsaw-validator)

# 1. Strategy and Scope Testing

## 1.1. Research
In my initial research, I drew inspiration from websites like SeeSaw, ClassCharts and SatchelOne, which offer progressive features for virtual learning environments (VLEs). These platforms excel in terms of user-friendly design, intuitive interfaces, and effective visualization of learning materials. Additionally, articles on paperless schools highlighted the relevance that a fully developed version of this mock-up website might have.

### 1.1.1. VLE Websites
<img width="941" alt="image" src="https://github.com/lmcrean/VirtualClassroomMockup/assets/133490867/4d4a36f0-7c02-43b0-947a-383b1d64a6c8" caption="Copyright SeeSaw 2023">

Copyright SeeSaw 2023

As part of my research I looked at VLE websites, specifically SeeSaw, ClassCharts, SatchelOne and Showbie. I wanted to gain an understanding of how they presented their product, their features, their testimonials and their sign up forms. I also looked at how they used colour, font, images and icons. I also looked at how they used responsive design, for example how they used media queries to change the layout of their website as the viewport width changed. I created a table below to collect notes on the front-end Design.

Showbie had the friendliest UI due to it's use of slogans and links.

Seesaw was the most convincing in content, due to it's use of background-videos, clear logos and awards features.

Website | Design Notes
---|---
[SeeSaw](https://web.seesaw.me/) | The welcome page introduces the platform's features, credentials and reassures the user about privacy concerns. Consistent font, consistent photography media, buttons are consistent layout and quite large, Features are summarised in simple colorful graphics, with + icon to visualise, Heading, subheading, sticky button The front-end is efficient, user friendly, intuitively designed. It uses simple icons to visualise the learning and show the platform on a phone, tablet and computer. Banner-button is a motif.
[ClassCharts](https://www.classcharts.com/)|Welcome page has a nice use of overlapping phone and content, summarising features with icons, use of animated statistics to make relevant to assessment data.
[SatchelOne](https://www.teamsatchel.com/)|Front-end has an appealing loading graphic, summary of app graphics works really well, use of fade in animation as page scrolls.
[Showbie](https://www.showbie.com/)|Divided by banners, interspersed with testimonials throughout the website. Sign up page reminds of the brand and it's purpose. Circular motifs with vector graphics. JS Carousel.|

### 1.1.2. Articles on Paperless Schools

> A recent study conducted showed that schools in the UK spent nearly half a billion pounds on paper each year, which is the equivalent of 3m Chromebook devices

\- Ieva Kulikovska, Education Software Specialist, [*Steps towards becoming a paperless school - reduce waste and save money*](https://www.theaccessgroup.com/en-gb/blog/edu-steps-towards-becoming-a-paperless-school-reduce-waste-and-save-money/#:~:text=Being%20a%20paperless%20school%20means,forms%2C%20permissions%20slips%20and%20newsletters.), 2022

On an implicit level the aforementioned article influenced the strategy plane of the project.

<details>
<summary> Summary of Article findings </summary>

This article discusses the benefits and steps towards becoming a paperless school. It emphasizes that going paperless can reduce waste, inefficiency, and costs, while improving school security, communication, and teaching methods. The article highlights the advantages of digital systems, such as creating a secure database, better communication with parents, increased student engagement, and the ability to automate paper-heavy processes. It also acknowledges potential challenges, such as digital literacy barriers and the importance of maintaining personal interactions in education. </details>

### 1.1.3. CSS resources
https://github.com/kevin-powell/learn-grid-the-easy-way/blob/main/style.css

Kevin Powell's CSS resource had helpful ideas for concise CSS selectors, particularly with grid display.

https://youtu.be/VQraviuwbzU

Kevin Powell also offers useful info here about min-height, max-width, font-size: clamp(,,) as alternatives to media queries 

## 1.2. Client Premise
<details>
<summary>
Click here to read a user backstory</summary>

Dr. Emily Williams is Headmaster at Meadowbrook Academy. She is expecting an Ofsted School Inspection in the next 5 years. Although her recent inspection feedback was positive, inspectors pointed out that various problems deriving from the sheer volume of paper. The top 5 include:

- it can take weeks for teachers to organise books for review by school leaders
- learning journeys quickly going out of date as the curriculum changes
- the paper copiers regularly break down every week
- important assessment documents/ paper resources occasionally are mislaid
- while there are VLE's (virtual learning environments) in place, these are limited to setting homework, merits and changing seating plans. They do not account for coursework portfolios.

One day her friend, Headmaster Benjamin Reynolds from Green Orchard School, recommends a new and promising Virtual Learning environment called Hoverboard. Benjamin has been trialling Hoverboard to reduce paper usage and organise data. THe software has a more ambitious scope than current VLEs by enabling users a chance to organise classwork on a cloud server. Later that day, Dr. Emily look's up Hoverboard on a search engine and visits their promotional website.
</details>

## 1.3. Client Experience of the website and objective: 
The table below summarises how the user's needs influences the design requirements.

| Page | user needs  | user experience  | website content  | design  | 
|---|---|---|---|---|
| 1 |  Dr. Emily needs to be able to visualise the mission of Hoverboard's product. | **She sees the homepage which demonstrates that Hoverboard are trying to help transition schools transition to a better and richer VLE.**   |   The content is themed around education, technology and ease of use. |  The client needs the front-end design to be positive, engaging and professional in tone.   |
| 2 | She wants to find out more about the features that Hoverboard offers,  |  **She visits Page 2 which demonstrates what unique features Hoverboard has**  | The content informs how the product integrates student classwork, such as peer feedback, quick teacher grading and gallery views | The tone is informative, persuasive and reassuring. The client needs the front-end design to use a clean layout that clearly visualises the product being used. |
|3| needs to access the free trial product| ** Dr. Emily visits page 3 where she books a free trial for one year.** She fills in a form which captures her essential data. At the end a message appears that thanks her and assures her that their customer welcome lead will be in contact. | a sign up form with a submit button |  The client needs the front-end design to be easy to read and use.| 

***

# 2. Manual Testing

## 2.1. Responsiveness by Feature
The features were tested on mobile, tablet, laptop and desktop. in this link are some early tests of the website on different devices.  https://github.com/lmcrean/Hoverboard/issues/143

## 2.2. Browser Testing 
Broswer testing was conducted on the following browsers: Opera, firefox, safari, chrome, edge using browsertack.com

## 2.3. HTML Hyperlinks test
https://github.com/lmcrean/Hoverboard/assets/133490867/739c450a-0fd7-4da3-bf7e-5b1fb6b2b2e6

15th Jul '23

navbar links are working, as are article links, footer links are mostly working. Instagram link worked after fixing misspelt url in html tab.
  
***
## 2.4. HTML form test

https://github.com/lmcrean/Hoverboard/assets/133490867/76d18415-44fa-4166-9f3a-612002c2e90a

15th Jul '23

The video demonstrates initially enterring the form correctly, then tests loopholes by entering incorrect passwords, emails and mobile numbers. The form submits to thank you page correctly, uses a simple PHP GET form, correctly identified misuse of email and 11-digit mobile number.

* 1 issue with fix password vs confirm password being required to match 
* the directed thank page heading and button doesn't appear, lacks a UX design, img link appears broken

# 3. Automatic Testing


The Automatic Testing set out to 
* use lighthouse testing to identify files that could be resized and accessibility that can be improved.
* Pass W3C Validator Testing for both HTML5 and CSS3, therby removing excess code and broken links.

***

## 3.1. W3C HTML Validator
W3 Validator results 15th July '23 

<img width="701" alt="image" src="https://github.com/lmcrean/Hoverboard/assets/133490867/aea19703-ddf3-461d-a36b-2cc2446da299">

<img width="672" alt="image" src="https://github.com/lmcrean/Hoverboard/assets/133490867/d14805e9-52c3-4212-aa6c-abdea29c67d1">


<img width="796" alt="image" src="https://github.com/lmcrean/Hoverboard/assets/133490867/7fb7aaa6-75d7-46bd-916f-d4aa97c2b7f5">

[See Issue and commit links here <img src="https://img.shields.io/github/issues/detail/state/lmcrean/Hoverboard/73">
](https://github.com/lmcrean/Hoverboard/issues/73)

## 3.2. W3 CSS Jigsaw Validator

<img width="913" alt="image" src="https://github.com/lmcrean/Hoverboard/assets/133490867/f1d9dee6-bb6f-4fdf-a1de-8a32bc930deb">

