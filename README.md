


# What's New in Accessibility?

WCAG 2.1 in a nutshell



## Presented By





### David MacDonald

Invited Expert at WCAG

CanAdapt Solutions Inc. David MacDonald is president of CanAdapt and is in his 15th year with the WCAG Working group. He is the only Canadian Invited Expert [listed on the WCAG 2.0 standard.](https://www.w3.org/TR/WCAG20/#acknowledgments) He is on the core team working on the next version of WCAG 2.1.



### Erin Marchak

Associate Director, Drupal Practices

Myplanet Erin has 6 years of Drupal experience and excels at Accessible front-end development and custom Drupal modules. She has her ‘Grand Master’ Drupal certification, and regularly presents on Decoupled Drupal 8 best practices.


## What are the WCAG 2.0 Guidelines?

Ensure content is accessible to a wider range of people, regardless of technology


## What new success criteria have been recommended for WCAG 2.1?

63 Success Criteria from WCAG 2.0 are grandfathered into WCAG 2.1


# Success Criteria: Level A



## Responsive design down to 320px is mandatory
### [Zoom content](https://rawgit.com/w3c/wcag21/resize-content_ISSUE-77/guidelines/sc/21/resize-content.html)

Drupal 7 sites with out-of-the-box admin menu are no longer compliant


## Authentication does not force people to recall a password
### [Accessible Authentication](https://rawgit.com/w3c/wcag21/accessible-authentication_ISSUE-23/guidelines/sc/21/accessible-authentication.html)

Use password reset links and social login


## People must be able to override keyboard shortcuts
### [Character key shortcuts](https://rawgit.com/w3c/wcag21/single-key-shortcuts_ISSUE-69/guidelines/sc/21/character-key-shortcuts.html)

Developers using custom mega menus or custom modules


## People can use only one finger or touchpoint
### [Pointer gestures](https://rawgit.com/w3c/wcag21/pointer-gestures_ISSUE-61/guidelines/sc/21/pointer-gestures.html)

Developers using custom GIS services or other custom modules



## Equivalent labels exist for visual and non-visual users
### [Accessible Name](https://rawgit.com/w3c/wcag21/speech-input_ISSUE-68/guidelines/sc/21/speech-input.html)

Don't use "short names" when populating fields or forms

## Events are triggered on touch-up
### [Accidental Activation](https://rawgit.com/w3c/wcag21/accidental-activation_ISSUE-65/guidelines/sc/21/accidental-activation.html)

Use standard jQuery click handling when building interfaces

# Success Criteria: Level AA

## Conventional name of elements can be determined
### [Purpose of Controls](https://rawgit.com/w3c/wcag21/support-personalization_ISSUE-6/guidelines/sc/21/purpose-of-controls.html)

Use semantic HTML5 elements for forms or page structure


## 4.5:1 and 3:1 contrast minimums
### [Graphic Contrast (Minimum)](https://rawgit.com/w3c/wcag21/graphics-contrast_ISSUE-9/guidelines/sc/21/graphics-contrast.html)

Themers and Front-End Developers should be careful



## Interactive elements need 4.5:1 contrast
### [User Interface Component Contrast (Minimum)](https://rawgit.com/w3c/wcag21/user-interface-component-contrast-minimum_ISSUE-10/guidelines/sc/21/user-interface-component-contrast-minimum.html)

Themers and Front-End Developers should be careful



## People can change the text without losing functionality
### [Adapting Text](https://rawgit.com/w3c/wcag21/adapting-text_ISSUE-74-78-79/guidelines/sc/21/adapting-text.html)

Fixed width layouts are no longer compliant



## Tooltips that appears on hover (or focus) are easy to interact with
### [Content on Hover or Focus](https://rawgit.com/w3c/wcag21/popup-interference_ISSUE-75/guidelines/sc/21/content-on-hover-or-focus.html)

Keep it simple when creating tooltips on forms


## Give people a method to prevent interuptions or popups
### [Interruptions (minimum)](https://rawgit.com/w3c/wcag21/interruptions-minimum_ISSUE-47/guidelines/sc/21/interruptions-minimum.html)

Don't overuse Drupal.announce()





## Major interactive elements need to be at least 44x44px
### [Target Size](https://rawgit.com/w3c/wcag21/target-size_ISSUE-60/guidelines/sc/21/target-size.html)

Developers building complex admin interfaces should be careful





<section class="blank color--ice" id="subsection--aa--orientation">





## Elements cannot exist only in a specific device orientation
### [Orientation](https://rawgit.com/w3c/wcag21/orientation_ISSUE-70/guidelines/sc/21/orientation.html)



## Notify users when content changes on a site
### [Change of content](https://rawgit.com/w3c/wcag21/change-of-content_ISSUE-2/guidelines/sc/21/change-of-content.html)

Use Drupal.announce() when bringing in ajax content




## How you can provide feedback to WCAG 2.1

Look at each Success Criterion and ask yourself...

 1\. Is it testable? 2\. Is it implementable? 3\. Is it scalable? 4\. Is it doable?

To comment, [open a new issue on Github](https://github.com/w3c/wcag21/issues/new)



