# 01-Curriculum-Vitae
## https://whoisaleafreinn-vitae.pages.dev/

### Description:
This is for the purpose of our first assignment that were made by our mentor (Atif Aiman Alserembani) in order to sharpen our HTML skills.
Most of the CSS codes are not structured properly due to getting fimiliarised with the surface of front-end development.
Hence, expect some less readability on the codes. If there is any improvements that can be made from my codes, feel free to fork the files.
The low readability on the codes will be mitigated in future by adding comments on later versions.

##
#### v1.0:
- Initial deployment for public view on 10/6/2023.

##
#### v1.1:
- Fixed the issue with unrecognised font when deployed and hosted in github.io
- The fonts-family that will be used is ***'Avenir'*** family.
- Added through **'@font-face'** in CSS.

##
#### v1.2:
- Added some **transitions** for *Introduction Description*, *Drop down details for Professional Experiences*, *Box Details for Education* and *Sub-Container for Skills*.
- Tweaked the *Navigation bar* from left-alligned to centered, with the addition to adding translucent background along the bar.
- Added a background image for all pages and transforming the **background-color** some of the elements to **transparent** value in order to blend in with the background image.
- For *Skills* page, added the description in order for the user to interact with the page easily.

##
#### v1.3:
- Generated '.css' files and transferred the styling from '.html' to '.css' for each of the pages inside *styles* directory.
  
![hover presentation](https://github.com/aleafreinn/01-Curriculum-Vitae/blob/main/assets/readme/hover%20presentation.gif)
- Overhauled the *Introduction Page* by:
	1. Adding the *Interactive Banner* where the user can hover the mouse to it and shows *nickname*.
	2. Adding the *Multilingual Greet Message* where it will constantly change the language of "Greetings!"
	3. Modified the *Main Header Name* and added description for "uprising software developer" message.
	4. Removed the *Professional Picture* due to inserting the *Interactive Banner* as a substitute.
	5. Minor tweaks to the '.html' script for improvement and maintainability.

##
#### v1.4:
- *Background image* for every page has been set to **repeat** for the parameter **background-repeat** due to "Image blend" fix for repeat pattern.
- *Scrollbar* display has been overhauled where the **scrollbar-thumb** parameter has been set to translucent color (open .html files to see the details) and the background color has been set to transparent (no color) in order for making the page style matched with its pattern.
- *Introduction Page* title has changed to *Welcome Page*.

![specialisation presentation]()
- Added the section *Specialisation* in *Welcome Page* in which:
	1. The specialisation comprises of *"Video editing", "Modelling"* and *"Programming"* with each of the "mini-sections" have their own containers and images added.
	2. Each of specialisations encompases **_The Gallery_** (except for *Programming Container*) where the functionality depends on Javascript that were made below the *.sub-container .github-style* class inside "<div>" tag. (open .html files to see the details). **_The Gallery_** can be scrolled sideways by using **Mouse Scrollwheel Upwards/Downwards** or by clicking the **Arrow** icons beside the frame.
	3. The *"Programming"* container follows **_Github_** theme in order for theme-appropriateness purposes and the container also comprises of 3 Tabs (that depends on Javascript in order to show info) which is *"Overview", "Repositories"* and *"Projects (WIP)"*.

- Added *Social Media Navigation* at the left side of **main-sub** class container which can be navigated to *"Twitter", "Instagram"*, and *"Youtube"*.
