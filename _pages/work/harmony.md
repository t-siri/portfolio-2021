---
layout: work-view
title: Work • Harmony design system
permalink: /work-harmony
type: des
img1: harmony
img2: harmony-1
img3: harmony-2
img4: harmony-3
img5: harmony-4
img6: harmony-5
img7: harmony-6
img8: harmony-7
dev: true
---

{% contentfor introduction %}
During my employment with <a href="https://workingmouse.com.au/" target="_blank">WorkingMouse</a>, I had the opportunity as a UIX designer, front-end developer and standards documenter to work with <a href="www.codebots.com" target='_blank'>Codebots</a> and design a bot styling library alongside bot components. 

Harmony is a library with standardised and documented HTML and SCSS that is shared across both bots in Codebots. What these bots provide from Codebots is a quick kickstart to an application, providing simple components alongside complex components (extensions). 

The designs of these components have been consistently re-iterated alongside the code through out the years upon creation. 
{% endcontentfor %}


{% contentfor problem %}
Codebots is an online platform that allows developers to quickly kickstart their application with the foundations of common application requirements. At the end of 2018, it was announced that the company wanted to create new bots using modernised languages. It was crucial that these bots have pre-set components and extensions available such as the CRUD (Create, Read, Update, Delete), Timelines, Dashboard, Forms and Workflows. Given the complexity of these extensions and the limitation in time on completing these components, it was important to narrow down these extensions to a Minimal Viable Product. To a standard where the extensions are usable with key features that represents what they do. From there, I spent time on user research and product research in order to refine these extensions. I surveyed developers and asked them what they wanted to see in regards to what Codebots can provide with extensions. I then surveyed project managers and asked them what their everyday workflow is and how these extensions could provide simplicity to their everyday routine. 

Once user interviews were completed, I was able to narrow down the problem for each extension:

* Timelines 
    * Ability to view in timelines view 
    * Ability to view in list view (responsiveness)
    * Quickly jump to a time gap and view changes in their application
    * Jump to current date
    * Filter out type of information
    * Search specific information
* CRUD
    * List view of data
    * Sort tables
    * Filter tables
    * Search data
    * To create, read, update and delete data
    * Dashboard
    * Ability to quickly throw a dashboard together
    * Create custom graphs
    * Place graphs in layouts
    * Save, edit, and publish dashboards
* Forms
    * Ability to create forms
    * Create skip logic
    * Create specific types of questions
    * Requirements on forms
    * Preview and publish
    * View results
* Workflows
    * Easily move around workflows and edit them
{% endcontentfor %}


{% contentfor solution %}
Each extensions were ideated independently given the course of how long they took. It was important to start surveying for ideas for each extension to ensure that the MVP (Minimal Viable Product) will be beneficial to Codebots once the platform goes live. Since there were multiple use cases and audiences for Codebots and these extensions, a significant amount of time was spent in regards to the ideation stage. It was also important to understand the user flow of each audience type in order to include the right features and functionalities and cater to the users. Multiple ideas were retrieved from multiple users during workshops and then voted on which ideas would be the quickest to accomplish and also align with the MVP of the product. After a few workshops during the ideation stage, we gathered a significant amount of useful information and started to refine these ideas. Each extension had requirements that were separated into three stages: Must have, Should have and Could have. This allowed us to refine the MVP with Must haves and depending on time, we could then include the Should haves. 
{% endcontentfor %}


{% contentfor outcome %}
From refining what is required of the extension to produce the MVP, me and my colleagues started sketching out ideas on potential screens and the flow of the screens. These sketches were constantly re-iterated after user testing them with potential users. Once the sketches have reached to a point where our users understood the purpose and the use of the extension, we started wireframing the sketches and connecting the screens together. User testing was immediately conducted and these wireframes were updated, specifically in regards to the extension’s components and functionality of the components. From wireframes being refined, we moved onto the Hi-Fi prototype. The prototype was tested on all audiences, given the complexity of some of these extensions, we wanted to make sure that the designs of the extensions were simple and clear to use. We would tell our user what their goal is upon testing the prototype and observe how they navigate throughout the screens. Gathering information from that, the prototype was re-iterated until our user was able to conveniently accomplish the goal we set out for them during user testing. From there I started documenting the components and extensions, alongside the SCSS library that will style these components to a standardised manner.
{% endcontentfor %}


{% contentfor development %}
It was very important that the SCSS and HTML code written in Harmony was clear, concise and well documented. As the code will be shared across multiple developers and will have to be customisable, I conducted user research with developers (specifically front-end developers). I wanted to understand how they felt about SCSS and what their limitations were in regards to the language. 

From there I was able to split up the code into sections: Abstracts, Elements, Components and Extensions. The order of these sections were imported specifically in order for developers to apply minimal custom code to customise the look of their application. I have set up the code in a way where it is simple to modify the look of the application by just focusing on two sections: Abstracts and Elements. Given how components and extensions are a group of elements, the custom code change would cascade down and automatically apply these changes. 

The library comes in three different styles, Codebots light theme, dark theme and neutral theme. Depending on the users and how much they want to customise the look of their application, they had the ability to choose the theme they would like to work with. Harmony is also accessible in regards to DOM structure and colour accessibility. Functions and mixins were written and used to specifically ensure that all components were accessible. Given that the DOM structure is documented to standards, the library styles both new bots using the same code and any future bots as long as the front-end follows the documented standards. 
{% endcontentfor %}