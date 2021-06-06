---
layout: work-view
title: Work • Solaris
permalink: /work-solaris
type: des
img1: solaris-1
img2: solaris-2
img3: solaris-3
img4: solaris-5
img5: solaris-4
img6: solaris-6
img7: solaris-7
---

{% contentfor introduction %}
During my employment with <a href="/workingmouse" target="_blank">WorkingMouse</a>, I had the opportunity as a UIX Engineer to work with <a href="/codebotsmarketing">Codebots</a>  and standardised the company’s front-end process. I developed an online design system for employees to refer to the company’s branding and design rules.

I designed the <a href="/codebotssolaris">Codebots Solaris Design System</a>, developed it and alongside worked on the components with my lead, Isaac Joekong and my coworker Raouf Al-Araji.
{% endcontentfor %}


{% contentfor problem %}
The problem that was defined within the workflow of Codebots was how designers and developers could not find the source of truth in regards to the company’s branding, resulting to inconsistency in design and development. It was clear that a source of truth needed to be produce in order to harmonise the workflow. 

To further understand the actual pain points and the struggles of the workflow, I conducted user interviews internally with designers and developers. It was discovered that it was uncertain on how components should look and be designed, therefore leading front-end development to become inconsistent as well given that development derives from prototypes. 
{% endcontentfor %}


{% contentfor solution %}
Upon narrowing down the problem, I started interviewing the designers and developers on what they wanted to see in this *source of truth*. I gathered what was important to designers in regards to consistency in components and what was important to developers in regards to consistency in states. 

Since Codebots have both light and dark theme, it was clear that components can become overwhelming and confusing, therefore documenting components for both categories was crucial. 

After gathering ideas from both parties, I was able to conclude what Solaris (source of truth) should contain:

<p class="b ul-heading">Designers</p>
* Components
    * Sizes
    * Padding
    * Fonts
    * Colours
* Rules
    * When and where to use components
    * How to use components
    * Purpose of different components
    * Theme rules
* Designers documentation
    * When to use the component in designs
    * Purpose of the component

<p class="b ul-heading">Developers</p>
* Component
    * What is available
    * States
    * Name of components
    * Values of components (padding pixels, height, fonts)
    * Types (outline buttons, solid buttons, text buttons, icon buttons)
* Ability to view component variations according to themes
* Developers documentation 
    * Ability to understand how to re-use and call components
    * How the code is written
{% endcontentfor %}


{% contentfor outcome %}
From refining the ideas, I started immediately with inspiration as there were multiple UI libraries out there. I gathered multiple libraries and documented on what was desirable and what was a pain point. This was in order to produce Solaris in a way that both designers and developers will use as a source of truth. 

I designed the Solaris Design System website and broke it up into sections because two different types of user groups were using them. I started building the website using Jekyll and added the first component type (Avatars). Once the foundations of the website was completed alongside the Avatars page, I immediately conducted user interviews and retrieved feedback and made a few tweaks to the layout of the website. 

The website resulted to being theme responsive and also sectioned into seven parts to prevent content overload. Each section was specifically written to the target audience (writers, designers and developers). The website is theme responsive as Codebots come in both light and dark theme, therefore it was important to see what components look like in both themes. The design section was heavily documented in regards to component types, states, looks and sizes for developers to reference off. There is also a *code* section for developers to document these components and how to use them internally. 
{% endcontentfor %}