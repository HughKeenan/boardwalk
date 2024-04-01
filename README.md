Boardwalk Acting School
Website for a fictional dramatic society based in Co. Carlow.

Boardwalk Acting School is a dramatic society based in the south-east of Ireland. It offers weekly classes in acting for adults and children teaching a range of techniques, with quarterly workshops in other disciplines such as directing. It offers a fun way for people to get involved in a hobby they might not have considered before, a chance to meet new people and overcome shyness and a fear of public speaking.

The target user of this site is someone looking to get involved in acting who is new to it, or someone already involved looking to expand their skillset. Users of this site will learn about what the school offers as well as class times, pricing information and the benefits of acting as a hobby. It will also provide opportunities to try less commonly taught aspects of acting through the quarterly classes.

Features:
Navbar
This is provided on every page and enables a user to navigate between the 3 sections of the site: the homepage, the class information, and the signup form to join the society. The version for mobile screens is hidden behind a "Menu" button that will provide it in a dropdown.

Landing page
The groups name is prominently posted at the top of the page, and beneath it is information relating to the group. This explains who the club is and a brief account of what it offers, as well as establishing credentials and future plans. Beneath this is a section explaining some of the benefits of acting as a hobby.

Footer
As with the navbar, this is the same on every page, and contains external links to the group's social media accounts. this benefits the group by increasing their followers and online visibility, and the user by helping them stay up to date on club news.

Classes
This page provides greater details about the classes offered for users who wish to know more. It provides a weekly timetable and pricing information, as well as details on special workshops for that quarter.

Joining page
This page is for those who wish to join the society, who will be periodically updated with information on future courses and productions being done by the society. Prospective members can also confirm whether they have prior acting experience, and the nature of it in greater detail using the text area.

Testing
Manual testing was conducted by using the links to navigate between the pages and all worked as intended, bringing the user to the intended destination. Using the inspect feature of the IDE, the look of the site on a mobile device screen was also examined. The site was opened on Google Chrome, Microsoft Edge, Safari and Firefox to ensure it worked on all of them. The form was also submitted on each.

Validator testing
The site was run through the W3C validator for HTML and Jigsaw for CSS.

Bugs encountered:
Icons for social media links initially would not display. This was resolved after re-examining the code and realising the embed kit from FontAwesome had not been added

Could not change color on social media icons. This was resolved after removing a second class tag from the HTML and putting the class name in the initial one.

Nav links were initially unresponsive and produced a 404 error. After review of information contained in the following link https://www.geeksforgeeks.org/how-to-create-links-to-sections-within-the-same-page-in-html/ it was determined that href links had not been equipped with the # symbol to denote the destination. Once added they were responsive.

When attempting to add images, the initial attempt to add in html resulted in an image too large for the page. A second attempt to add through css did not display the whole image.

After adding the form, initially clicking on submit provided no feedback. It emerged on reexamining the code that the action had not been properly set. Once added, the form worked as intended.

Links initially didn't work on deployment. This was due to the use of absolute links, and was rectified when these were changed to relative links

Alts did not initially display as the default black text did not show up on the black background. The solution was taken from here: https://stackoverflow.com/questions/9044611/how-to-style-alt-text-color

Deplyoment
This was done by using the following steps:
1. Going to the Settings page in the repository on GitHub
2. Selecting Pages on the menu on the left hand side of that page
3. Selecting "Deploy from a Branch" in the section marked Sourcxe and ensuring that the branch was set to main and the folder was set to /root.
4. Selecting save under branch
5. Navigating back to the repository's code page, then refreshing after a few minutes
6. moving to the deployments section on the right side of the code page and opening the link from there

Credits
Content
Photos used in this site were taken from pexels.com.

Icons for social media links were taken from font awesome.
Tips in how to best use flexboxes to display links in the footer were obtained from https://css-tricks.com/almanac/properties/a/align-items/

Information on how to fix navlinks was found here: https://www.geeksforgeeks.org/how-to-create-links-to-sections-within-the-same-page-in-html/

The code for embedding the map was taken from here: https://www.maps.ie/create-google-map/

The favicon came from here: https://favicon.io/emoji-favicons/performing-arts