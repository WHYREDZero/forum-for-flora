# Forum for Flora
I worked as a Summer Intern with the Police Reforms department of MP Police, under the guidance of DGP Maithili Sharan Gupta in May 2020. Under the same, my project included creating a forum for people to discuss and promote floral agriculture. 
## Introduction
During the past few years, the government of India has taken upon a new goal, Swachh Bharat. However, keeping the country clean shouldn’t be the only goal. Making the country beautiful, healthy, and green should add as an incentive to that goal.
## Project Strategy
Some people think in similar ways and might look for a place to discuss their ideas. Online social media platforms are, however, too general and distracting to discuss this. We proposed to build a forum that stays specific to the topic and provides services beneficial to its users.
## Step-By-Step Process
* Basic research on web portals as knowledge management systems.
* Building a general-purpose forum.
* In-depth analysis on horticulture.
* Adapting the forum by adding/removing features.
## Project Objectives
|  Object Hierarchy  |                                                    Overall Outcome                                                   |
|:------------------:|:--------------------------------------------------------------------------------------------------------------------:|
| Overall objective  | To help people in the field of horticulture come together.                                                           |
| Specific objective | To categorize people and help them with horticulture accordingly.                                                    |
| Results            | Allow people to connect without distractions. Help people take advantage of internships, startups, projects, etc.    |
| Activities         | Conducting research on various topics under web portals.                                                             |
## Implemented Solution
### Homepage with Integrated Login and Sign up
It is the initial page of the project. This page will contain a brief about the web portal. Below the description, there will be two tabs, log-in, and sign-up. These will allow the users to create an account or log in to an existing one. We will store user data using SQL.
### Passwordless Login and Signup
Passwords are insecure. No matter how secure you make them, they always have downsides. Passwords are tough to remember if someone knows it, then your account is simple to get access to. Instead, we can set up a partially password-less system. During sign-up, we will ask people for their email and phone number only. For sign-in, we will ask the user for their email and send an OTP to their registered mobile number. Using this method, we can prevent the creation of dummy accounts that are used to scam users. It also eliminates the need for having an account recovery option (people can’t forget their email and phone number), which is sometimes used to hack into accounts. We will never show the email and phone number to other users there will be no option to show it to anybody else. 
### User Classification
During sign-up, we can ask users to classify themselves as normal, info-provider, or organizations. Accordingly, we can suggest relevant content and tasks for a user. We designed the dashboard of each user according to the information provided.
### Discussions Tab
A user can create a post to discuss a topic, complete with image, video, social media, external links, comment, and reply support. It is like a social media post but will be focused on floriculture. The external social media support will extend to websites like Facebook, Twitter, Instagram, YouTube, Medium, etc. 
Tags will also be added to a post to help the recommendation section and the search function. 
The discussion tabs will also allow for integrating and taking advantage of events like internships and hackathons.
### Tags Feature For Posts
This feature will integrate into every other feature on the portal. Using python and Django library we can make a recommendation system to suggest discussions, planting requests, and trades to a user. During sign-up, a user will have to follow a few tags to help design the discussions page dynamically. It will also allow a user to search posts better. This feature is like hashtags on social media sites.
### About Us Page
This page will contain information about the developers, the mentors, the college, and the MP police department. This page will have a feedback form for users to fill up and will only be visible to users when signed in. This feedback form will allow users to report bugs, rate existing features, and ask for additional features.
### Planting Request Tab
In this section, the user could click a picture of a region that will benefit from planting flowers. Alongside that, they could attach a description and location of the place. Other users could accept these requests and plant flowers in the region. It is a five-step process.
* A user posts a request to the portal with a picture of a place, the location, and a description. Again tags will be supported here.
* Other users can see these requests and accept them. 
* After accepting the request, the user will have to go to the location and plant flowers.
* Once the flowers are planted, the user can take a picture of the newly planted flowers and upload them to the portal. This feature uses geo-fencing to ensure that a user can upload the image within 100 meters of the planting location.
* The original user now has to verify the plantation by going to the position and marking the task as done or not. Again this will use geo-fencing to ensure that the user is pressing verify within 100 meters of the planting location.
### Trading Tab
Under this tab, users can trade florist equipment with other users. A user could request florist equipment from other users. The user could also put up a piece of equipment for trading. The system will match users via tags and notify them. They could trade equipment in real life. A minimal chat option will be available with this.
## Conclusion
We have mentioned again and again that social media can become distracting quickly. To help an individual remain focused, all features need to be redesigned. Some features also need to be removed to make the workflow smoother. While general-purpose tools can be easy to use, they take too many resources compared to specific purpose tools. 
