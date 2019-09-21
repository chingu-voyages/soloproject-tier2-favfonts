# Chingu Voyage Pre-Work Solo Project (Tier 2): *Favorite Fonts* #

![Landing Page ScreenShot](./assets/favoriteFontsLanding.png)

## Overview ##

This project is a great opportunity to develop a clean and modern webpage. The *Favorite Fonts* app will be completed accross tiers, with each tier adding a level of complexity. You are currently on the *Tier 2* repo. You'll be responsible for coding the **HTML**, **CSS**, and **JavaScript** to get the structure, styling, and functionality up and running.

As you add skills to your developer toolbag you'll be able to come back to this project and add in the Tier 3 features. Ultimately you'll have a great portfolio piece, and will have implemented a number of common and in-demand features.

**Frameworks *are* allowed in Tier 2; however, no frameworks were used in the creation of the Tier 1 / Tier 2 / Tier 3 versions of the application's front-end.**

## Instructions ##

Tier 2 can be completed without use of a back end. In other words, you accomplish the desired outcome (including extras) in vanilla HTML, CSS, and JavaScript.

General instructions for all Pre-Work Projects can also be found in the Chingu Voyage Handbook (URL posted in the #read-me-first channel on Discord).

**Requirements**

*Structure*
- [ ] Header with minor navigation
- [ ] Major navigation / page-manipulation
- [ ] Main section for the font cards
- [ ] Font cards which display the Font Name, the creator, the sample text, and an add button
- [ ] Button that allows user to click and scroll back up to the top (there could be up to 959 fonts displayed, so you need this!)
- [ ] Footer section with your developer information

*Style*
- [ ] Sample text in each card should be displayed in the corresponding font
- [ ] Buttons/links should be evident (make sure the cursor changes, etc.)
- [ ] Implement a way to handle overflow from sample text as the font size is adjustable

*Functionality*
- [ ] Text typed into the sample text (type something) box should immediately change the sample text in each font card
- [ ] The sample text should return to the default sample if the input box no longer has any input
- [ ] Font size chooser should have at least four sizes and should immediately change the sample text font size in each font card
- [ ] Implement the 'reset' icon on the far right of the major navigation; it should reset the sample text and font size
- [ ] On load, the page should display fonts sorted by current popularity, as returned by the Google Fonts API *(see below)*
- [ ] The search feature should be fully functional and should display matching fonts (it's up to you if you want to do this via a 'submit' or through onchange)
- [ ] When the search input is cleared (via reset button or manually), the fonts should automaticaly display sorted by poplarity again

**Extras (Not Required)**

- [ ] Make your design fully responsive (small/large/portrait/landscape, etc.)
- [ ] Implement the light/dark mode toggle buttons
- [ ] Implement the change display icon so you can flip between a grid layout and a list layout for the font cards
- [ ] Make the 'add-font' icon add the font to a list (localHost, Cache API, etc) for front-end persistence; users can then delet the font from the card

## API Information ##

This project utilizes the (**Google Fonts API**)[https://developers.google.com/fonts/docs/getting_started] and the (**Google Fonts Developer API**)[https://developers.google.com/fonts/docs/developer_api]. You will need to register for a free api key in order to complete this project as calls to the developer api are severely capped without one.

Please do *not* use the Google Web Font Loader for Tier 2.

## Example ##
![Tier 2 Gif](./assets/tier2Preview.gif)
