# Mendix.GlobusTheme

Objectivity’s UI resources module and theme for building apps on the Mendix 9 platform.

It can be a useful tool for everyone involved in the app creation process — from Mendix Developers, through UX Specialists, UI Designers, UI Developers to Business Analysts.

Our design team prepared new styles for building blocks and widgets, such as forms, buttons, lists, tooltips, checkboxes, typography and many more. You can use them to create mock-ups and proofs of concepts that fit your clients’ branding by simply choosing the right colours and adding logotypes.

Globus Theme for Mendix 8 is available on this link: https://marketplace.mendix.com/link/component/117130

## Typical usage scenario

A useful tool for:
- Starting new projects
- Styling your application
- Preparing your own Company Design System
- Demo
- POC

## Features and limitations
### Features
The basic version of Globus Theme contains the most commonly used components of Mendix. All of them have been tested on mobile devices and are fully RWD (Responsive Web Design). The basic package includes the following elements.

Widgets:

- Alerts
- Badges and labels
- Buttons
- Checkboxes
- Data grid
- Groupboxes
- List view as Grid (including Responsive Web Design solution)
- Multiselect
- Radio buttons
- Switches
- Tabs
- Tables (including Responsive Web Design solution)
- Text fields
- Tooltips
- Typography

Building blocks:

- Breadcrumbs
- Cards
- Forms
- Headers
- Wizards

Others:

- Basic SVG icons

### Limitations
- Did not test on the Internet Explorer

## Dependencies
- Mendix Studio PRO, created and tested on version 9.6.6
- To customise the Globus Theme, SASS/CSS knowledge is necessary

## Installation
You can install Globus Theme Module in two ways:
1. Download from Mendix Marketplace in Mendix Studio Pro. To do this, click on the basket icon in Mendix Studio Pro, and search for Globus Theme Module in Marketplace.
2. You can download the module from this page and import it to your app, but we recommend installation from Mendix Studio Pro. It will be easier to update in the future.

## Configuration
After we have already installed the module, you need to import variables from Globus into the main application theme.
1. Cut the variables from `theme/web/custom-variables.scss`
2. In `theme/web/custom-variables.scss` add `@import "../../themesource/Globus/web/custom-variables.scss` to the top of the file
3. Rebuild your project, if you have any errors in Mendix Studio Pro, close and open again application
4. If you require a custom login page. Copy login.html file from themesource/Globus/web/ and replace the file in theme/web/

## Bugs
The are no known bugs at the moment.

## Demo
https://globus-sandbox.mxapps.io/
