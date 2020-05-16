![](assets/images/readme-image.jpg)
  
# Sarek National Park Website
This is a static website made using HTML and CSS.

## External user's goals:
A website with basic information for those who want to travel to, or are seeking more information about Sarek National Park in northern Sweden.
  
## Site owner's goal:
To provide a simple and minimalist website, containing the basic and necessary informational on starting a journey towards the park.  

## Website structure:
Seeing as Sarek is a niche national park having no accommodations or facilities for tourist, this website was built for those who "know what their getting into" and as such aims to answer basic questions like "How to get there?", "What can I expect?" and so on.
    
With the above in mind, 4 sections are included on the website, these are:
  
* Facts
* Get here
* Plan your trip
* Contact
  
### Facts
The Facts section contains a short introduction to the park, and has 3 sub-sections, they are:
  
* The Park
* Environmental
* Wildlife
  
### Get here
The Get here section contains information on how to get to the park, or more precisely how to get close to the park considering: 
  
"There are no roads leading up to the national park."
  
### Plan your trip 
The Plan your trip section is intended to give visitors to the park some advice on what to expect when they arrive and some pointers on what to bring. The Plan your trip section has 3 sub-sections, they are:
  
* What to bring
* Weather
* What to do
  
This sections also contains a highlighted warning, reminding the user that  Sarek is a "..high-alpine area with almost no accommodation for tourists.."
  
### Contact
The contact section contain information on how to get in touch with those who manage the park. 
  
It contains a visitor address, telephone number and social media links under a "Tourist information" heading. A contact form is also provided, aswell as an integrated map of the park.

## Design
The website is built to be easy to navigate, using a "one page" approach. Photographs are used to provide natural breaks between some sections. Also, simple icons are used in some sections to break between the introduction paragraph and the sub sections.
  
## Built with
* HTML  
* CSS  
* Bootstrap  
  
The website was coded in Visual Studio Code - https://code.visualstudio.com/
  
## Testing
* http://ami.responsivedesign.is/ was used to check responsiveness on different Apple products.
  
* With the help of friends and family the website has been tested on different computers and mobile phones, including iPhone 12, Sony Xperia Z3 Compact and Huawei P10.
  
* The website has been tested on Chrome, Edge and Firefox on Windows 10 and Chrome and Firefox on Ubuntu (version 20.04).

* Tested contact form under the "Contact" page. The form submits correctly, and returns the submitted text and correct values/name attributes on Code Institute's formdump website.

* The HTML and CSS validator at W3 (https://validator.w3.org/) was used when testing the code. The only remaining errors are related to the google maps integration using iframes. This is explained separately under the "Notes" section in the readme.
  
### Known issues
When the website link is shared via Facebook, and opened in Facebook's embedded browser this will load Google maps and not the website.

## Deployment
The code is hosted on my own personal GitHub page, the link to the repository is https://github.com/oyvindwagner/milestone
  
To achieve this I created an account on GitHub, created a new repository where the code and files for the project are hosted.

The website is deployed to the internet using GitHub pages, the link to the project is https://oyvindwagner.github.io/milestone/
  
To achieve this I went to the "Settings" tab on the repository page, under the section "GitHub Pages" it is possible to publish the contents of the repository to the web.
  
## Sources
  
### Text content resources:  
https://www.sverigesnationalparker.se/  
https://en.wikipedia.org/wiki/Sarek_National_Park  
  
### Fonts
This website uses "Montserrat" and "Jost" retrieved from Google Fonts at https://fonts.google.com/
  
### Icons
This website uses assorted icons from Font Awesome at https://fontawesome.com/
  
### Images:
All images from https://www.unsplash.com and from the following photographers:  
  
https://unsplash.com/@hendrikmorkel  
https://unsplash.com/@villepalmu  
https://unsplash.com/@wandervisions  
https://unsplash.com/@vald  
https://unsplash.com/@marcuslofvenberg  
  
### Code
Code and documentation from Bootstrap at https://getbootstrap.com/docs/4.1/  
Page image divider code courtesy of Xahed Kamal - https://stackoverflow.com/users/3866364/xahed-kamal  
Tutorials/code by Michal Szymanski at https://mdbootstrap.com/user/ascensus/  
  
## Notes
Due to being limited to using HTML and CSS, the integrated google map under the "Contact" section was integrated using iframe - this would ideally have been done using JavaScript. The map integration returns errors when the code is run through a validator, as the W3C are trying to phase out the use of iframes.
  
This website is built for educational purposes only.  
  
  