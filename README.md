# straight-to-the-point
----------------------------------------------------
TITLE:  Straight to the Point Archery Academy
-----------------------------------------------------
DESCRIPTION OF PROJECT

This site contains a series of pages to provide information  about Straight to the Point Archery Academy.  The site includes the following pages:

1.	 Home – the page contains summary information about the firm and includes links to pages that provide further detail
2.	Lesson/Group Events – the page provides a listing of services offered as well as information about each type of service including a description of the service, schedule, cost, prerequisites for the services
3.	Our Facilities – the page provides information about the facilities available and includes information on location.  The page also provides a video of disabled archers participating in an archery competition
4.	Our Staff – the page includes information about staff members who are available to work with as well as the company leader.

-----------------------------------------------------

TECHNOLOGIES USED

The site is written using semantic HTML and CSS styling.

-----------------------------------------------------

ACCESSIBILITY

The site was evaluated using the following tools:

•	WAVE Web Accessibility Evaluation Tool (https://wave.webaim.org/). 

•	Colbinder: Coblis Color Blind Simulator (https://www.color-blindness.com/coblis-color-blindness-simulator/) 

•	Review other A11Y standards – see below for any changes made 

The following summarizes the findings of this evaluation and the actions taken to improve the accessibility of the website:

•	Contrast:  the evaluation identified an issue with contrast between the text and background in both the header and footer (contrast ration 2.87:1) .  In addition, the use of the aqua blue color (specified by the style guide) did not provide enough contrast against the white background (contrast ration 2.87:1).

To resolve this in the header and text, I changed the blue color to a slightly deeper shade of blue.  This changed the contrast ratio to 4:58:1.     For the footer, the contrast ratio was 1:1 because I am using an image as the background.  Since the validator could not recognize the color of the image, it was using white as the background color as well.  I added the new blue color as a background color to the footer and deepened the blues of the image using photoshop to present more contrast.


•	Skip to Main Content – I added a hidden link so users using a screen reader can easily move to the main-content of the page.

•	Modified lessons, facilities and staff pages to insure that no heading level is skipped.  These pages started with h2.  Changed to start with h1 and had each subsequent header assigned to the next h# element based on the order in the hierarchy.


-----------------------------------------------------





