Accessibility Guidelines
========================

Accessibility guidelines for developers working with the money advice service

## Overview

We want the Money Advice Service's (MAS) website and products to be as accessible as possible and useable by the widest demographic. 

We aim to reach AA level of the [WCAG 2.0 Guidelines](http://www.w3.org/TR/WCAG20/) which sets the benchmark for accessibile digital products.

## Who is this document for?

This document is to aid developers, content editors, user experience (UX) designers and project managers in building accessible products.

## Requirements

At MAS we strive to meet the WCAG 2.0 AA level as a minimum. This means we must ensure that our website and our digital products are:

- Perceivable;
- Operable;
- Understandable; and 
- Robust

The following sections will help you understand the four key areas of ensuring accessible websites.

## Perceivable

All of our products and our website, including all of the information presented and the user interface is presented in a way that all users can perceive and understand.

### How we do this

- Ensure all HTML documents are structured in a logical way and use semantic markup (start with structured content and then layer on style);
- Ensure all links and text have strong contrast against their backgrounds;
- Ensure the page does not break when the user increases the text size up to 200%.
- Do no use images in place of text.
- Provide alternative ('alt') text for all images;
- Provide descriptive text transcripts for video and audio files;
- Provide captioning for videos;

## Operable

All of our products and our website must be operable by all our users.

### How we do this

- Core functionality must not rely on JavaScript;
- Content must be keyboard accessible; 
- Users must be able to control automatically updated content (eg pause, stop or hide);
- There should be no flashing content - moving, blinking and scrolling content must not last more than five seconds or flash more than three times per second;
- Skip links are to be used to bypass repeated navigation elements (eg. skip to content); 
- Frames must be titled;
- Pages must have descriptive titles;
- A logical tab order for links and form elements must be provided;
- Links must be meaningful and easy to understand (use descriptive links, not ‘click here’);
- Use meaningful labels for form and heading elements (use descriptive headings, not ‘More information’);
- Ensure the order of navigation links and form elements etc is logical, and it is visually apparent where the current keyboard focus is 

## Understandable

The user interface and the language used to construct the content must be easily understood by all our users.

### How we do this

	•	Use plain English and keep content brief by including essential information only  
	•	Follow the Digital content standard for guidelines on length  
	•	Avoid jargon and unusual words. If they are necessary, use the <abbr>  element or link to a definition  
	•	Identify the language of the page and parts of the page using HTML lang  attribute (e.g. <html lang="en"> or <blockquote lang="fr">)  
	•	Ensure all pages appear and operate in a predictable way  
	•	When a user interacts with an object or a page element receives focus (ie  tabbing onto a link), do not use pop-up windows or make changes that could  confuse them  
	•	JavaScript can be used but it must not hinder accessibility. For more complex  interactions, provide cues or pointers to ensure users are aware of what is  November 2013 TfL Unclassified Page 2 of 4 NOTE: You must refer to www.tfl.gov.uk/toolkit for the latest version of this document  
happening. See W3C’s WAII-ARIA overview for information on making dynamic 
content and advanced user interface controls accessible 
	•	Use consistent navigation elements  
	•	Use consistent labelling for frequently used elements to help users predict  how they are used across the site (eg 'Search', 'Contact')  
	•	Provide label tags for all form elements  
	•	Provide all necessary information about a form element within its label (eg if  control is required or it requires a specific format, value or length)  
	•	Present form errors in an accessible, intuitive manner (eg highlight errors  where they have been made and describe the error or what the user needs to do)  


## Robust

All of our content must be robust enough that is can be interpreted reliability by a variety of user agents and assistive technologies.

You must use valid, semantic HTML5 and CSS3.

## Why we care about accessibility

The Money Advice Service has a responsibility to provide money advice to the entire population of the UK, regardless of their disability or personal circumstances. 

This is both a legal obligation imposed upon us by [government] (cite) and a goal set out by the Money Advice Service development team.

We strongly believe that a more accessible website will provide a robust and useful website for our disabled users. Furthermore, an accessible website encourages better user experience and visual design for all of our users.

- Ensuring content and features are accessible to more people, including users with physical and/or cognitive disabilities  
- Reducing the complexity of sites and/or providing usable alternatives to help users find information and complete tasks quickly and easily  
- Increasing findability with search engine optimisation  
- Increasing potential use in more situations, ie accessible websites can be used on a range of devices, including those that use low bandwidth or older technology  
- Minimising the need to produce or maintain alternative format materials  
- Decreasing the potential for high legal expenses associated with defending against legal action 


## Document Contents

- Links
- Audio and video
- Popups, auto refresh and redirects
- Clarity
- Navigation
- Colour contrast
- Page titles
- Images
- Frames
- Structure
- Tables
- Scripts
- Markup
- Measures
- Stylesheets
- Forms
- Accessibility statement


## Overview 




## Accessibility Review

Our guidelines are reviewed by the [Digital Accessibility Centre](http://www.digitalaccessibilitycentre.org) in Neath, Wales.

## Amendments

If you have any advice on where we can improve our accessibility guidelines, please email alex.williams@moneyadviceservice.org.uk and we update our policy.

## Acknowledgments

[Web Accessibility Standard](http://www.tfl.gov.uk/cdn/static/cms/documents/onl-std-010-web-accessibility-standard.pdf)
