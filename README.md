# Milestone1 : Perfection Gym
The purpose of the project was to showcase Perfection gym, describe its ethos and promote its novel qualities in order to attract suitable members.

# UX

## User Stories
Members and prospective members understand that Perfection is a boutique, fun, vibrant and energetic gym, devoted to fitness and equipped to a high end specification.

Perfection Gym is relatively expensive and the website should target financially suitable members or members with 
significant social media presence for promotional purposes. No explicit prices will be displayed as this tends to attract negative 
publicity and tarnishes the brand with accusations of elitism or social predujice. Perfection wants prospective members to contact them 
through the site and once their background and profile is assessed prices will be discussed.

Perfection aims to revolutionise the fitness industry and plans to promote this concept extensively in order to expand locations and sell 
ancillary products such as Health Food; Clothing and online Fitness packages.


## Strategy
The aim of this project is to create a website to convey the Gym ethos and widely generate interest. It is anicipated that this will be a 
multi-phase project and the website is part of a muti-media strategy to promote the Gym.

## Scope
The energetic, avant-garde and unorthodox nature of Gym must be prominent as it wants to revolutionise the fitness concept. 
Members should be attracted by its no-nonsense and novel approach. The site will not contain Prices since these are not a deciding factor 
for the demographic they wish to attract. However, price levels can be inferred from the website.

## Structure
All pages should boldly illustrate the Gym culture and its values where possible. Gym pictures should demonstrate something new and exciting.
The landing page should display an unconventional and aggressive mission statement that entices the user to investigate further.
The users should be led to the Gym 'concept' and 'joining' pages so that members are attracted by its culture and want to join. 
The trainers should be cheeky, fun and physically impressive. Gym contact details are readily available.  

## Skeleton
[WireFrame - Landing Page](assets/images/WireFrame-Index.jpg)

[WireFrame - Concept](assets/images/WireFrame-Concept.jpg)

[WireFrame - Trainers](assets/images/WireFrame-Trainers.jpg)


## Surface
The Black and Charcoal colors convey a luxury brand. The Gym pictures, including models, display fun, intensity and theatre.
The web text should be short, brash, confident and provocative. 

## Technologies
1. HTML
2. CSS
3. Bootstrap 3.7


## Features left to Implement
In future phases would animate the trainers and link to their social media profile in order to promote the Gym and 
their personal brand. The Gym aims to liaise with DJs to promote its onsite music and have training blogs 
and tips for members also. Future version would sell health food and clothing ranges.

# Testing 
The 'Concept' page describes the training concepts usings cards. The cards are responsive with photos and descriptions which 
are consistent with the Gym culture. The navbar enables the user to hop to other pages easily. 

The 'Joining' option is always available. The 'Joining' form will not be submitted unless entries are valid. 
The form requests a full name rather than separate first name and surname for a better UX. 

The timetable page displays class times and uses Bootstraps responsive Table class to acheive this. 

The trainer page also used Bootstrap cards to showcase the trainers. The cards squeezed on reducing screen size which
was unsightly. I resolved this through a solution found on Stack Overflow which rearranged the card stack rather than squeeze them. 
The address on the Navbar disappears on reduced screen size to make the index page more appealing.

The 'JoinUs' page did not implement the black background color through class declaration and could only be 
implemented using an inline 100% height value. An inline font size of 4em was used to override the standard h2 weighting
for the 'PAIN is the REMEDY' banner. 


This site was tested across Chrome, FireFox and Internet Explorer and on multiple screen sizes to ensure compatibility and responsiveness. 
Internet Explorer wrapped the landing page heading due to issues in handling FlexBox. This is a minor issue for a non-critcal 
browser and does not justify the substantial effort required to fix it.

The HTML code was submitted to W3C Markup validation and yielded no issues.

CSS code was submitted to jigsaw which highlighted that -ms-flex was an invalid call and that @import on line 6 was not permitted.
I removed -ms-flex but retained the font import statement.

# Acknowledgements

The Gym images and model shots were obtained from Google images and www.canva.com. Ideas were generated from virgin gyms (www.virginactive.co.uk) 
and Rebel gym (www.1Rebel.co.uk).

