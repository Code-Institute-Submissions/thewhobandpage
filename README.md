Frontend Development The Who Band-page

This is website made in the perspective of the band The Who and its manager. This website encomposes The Who's biography, calender, photos, 
videos, and music. On the calendar page there is a section that allows the visitor to request the band for private parties, weddings, 
and concert venue owners. This site will help concert venue owners, fans, and potential fans get information about the band, listen 
to music, watch music videos, and request concerts with the band from the manager. 

UX


This site was made with the mobile first appraoch with a user experience that always have user-ease in mind. The site will require
the least amount of clicks necessary while giving content directly to users with ease. 
As a user everything on the site is found in just one click with the simple yet effective navbar on every page.
As a user there there is a footer with some band details and additional hyperlinks to direct to different parts of the website without having 
to scroll back to the very top of the page.
As a user it is important to be able to connect with the band through popular social media site, the social media pages 
are on the footer of every page with their popular symbols with direct links to their various pages while opening in a new tab to never 
forget what site they came from.
As a user, simplicity is needed while looking for what they want. To achieve that, the sites functionality allows
users to have simple yet effective means to find information fast. 


All drawn out wireframes have been downloaded in images as index.jpg calendar.jpg music-videos.jpg MP3's.jpg and Thanks.jpg

Features

The Home screen allows the user to learn more about the band including see the current and all past lineups. In that home page there are also details from the band, like the amout of time played, records sold and interesting facts about the band. 
On the Music Videos and Photos page this allows users to experience the band and some of the most iconic photos and music videos that have been preformed over the last 5 and a half decades of the bands existance. 
The Calendar screen provides a list of all upcoming concerts for the bands current tour and the availability for users that want the band to preform for weddings private parties and coorporate events to get in contact with the business manager to try to set that event up.
The MP3's screen will aloow users on the go to listen to some of the bands most iconic hits. These are different than the featured videos on the site but will allow users that may have a slower internet speed or not wanting to deal with videos to still enjoy the band. 
The Thank you screen will br brought up for all users who submit an application to book an event. This helps users get the feedback that their event request was received and will be taken care of. 
The Header in each page allows users to simply and effectively browse the different aspects that the site provides and provides clarity to know exactly what is needed. 
The Footer connects the user to different places on the website in a different way like clickig on a short biography to return to the home band page to learn more about the band. The footer also has a place to click to see current tour dates and even connect the user to social media sites of the band. 


Features Left to Implement

The featured videos and MP3's will be updated regularly to keep the traffic coming, along with new songs before they are given to the general public. 
Having The Who shop that has all the band appearal, tickets, and merchandise.
Having a premium subscriber section that lets users have discounted prices on merch and tickets available before going on sale on places like ticketmaster.


Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
This project used HTTP5, CSS3, bootstrap, SASS, and font awesome.
I used the outline of a timeline from code pen, found here (https://codepen.io/bsngr/pen/Ifvbi) and changed icons, information, and colors to make it to a tour date schedule that includes all relevant information. 
A CSS button from W3Schools found here (https://www.w3schools.com/css/css3_buttons.asp). This was for the submit button for the form on the calendar page.
For the MP3 audio I used W3 again (https://www.w3schools.com/html/html5_audio.asp). This added the ability to have an MP3 page where fans can help listen to music who may be on their phones with limited data use or people who have slower connections so all fans can still listen to The Who. 
Bootstrap was used to keep the 1/3 2/3 ratio to seperate the pages body and make sure that the ratio changes depending on screen size.
For the header on each page (https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css) effects were controled through here. This helped transitions look professional and reliable having the UX appealing and easy to use.
Font awesome from bootstrap (https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css). This allowed different areas to have slightly different fonts depending on what was needed or have the desired appeal more easily. 

Testing

I ran all the code on each html through a w3 validator to make sure there is no code messed up, repeated, or incomplete. 
https://github.com/benmurphy09/thewhobandpage/blob/master/calendar.html
https://github.com/benmurphy09/thewhobandpage/blob/master/index.html
https://github.com/benmurphy09/thewhobandpage/blob/master/mp3s.html
https://github.com/benmurphy09/thewhobandpage/blob/master/music-video-photos.html
https://github.com/benmurphy09/thewhobandpage/blob/master/thanks.html

On the home screen all navbar buttons redirects to the proper coresponding place. Also the footer with all three areas redirects to the proper page with external links to their actual social media pages with hyperlinks. 
On the Music video screen all the navbar links go to the proper redirection. The footer has the three links directing to other parts of the bandsite. The screen is responsive and not only changes the 1/3 to 2/3 layout but some of the pictures change as well. All of the total of seven photos look clear on mobil and desktop through browsers. Three music videos are currently in place on the page, all of which at the time of writting are all working links with good sound quality. 
On the Calendar page the navbar still has the links send to the proper location. The footer has the same functionality with every link working and redirecting appropriately. The calendar looks great with the location date and time of the show. There is the form for people to request an event such as large or private birthdays, venues wanting to host a concert, or coorperate gigs. The name requires text. The phone number has to be numbers in a ###-###-#### pattern. The email must have an @ symbol with text after. The concert summary must have some text to be submitable to prevent people from posting blanks forms. 
On the MP3's page the navbar and footer have the same functionability listed above and all works the same. This page has 2 popular mp3's to allow people in rural areas or alower internet connections to still allow their fans to hear their music. With switching from cloud9 to AWS then to GITPOD The MP3's seem to not work with the current GITPOD preview window. There is other people explaining this GITPOD bug here https://octolinker-demo.now.sh/gitpod-io/gitpod/issues/738
The Thanks page has the same navbar and footer that works the same. On the left 1/3 panel the concerts are still listed. On the other 2/3 panel there is a thank you for submitting your concert request note letting the person know their application has been submitted.

Contact form:
Empty forms are not submittable. An error message for the name come up "Please fill out this field". If filled out then this message switches to the phone, then to email, then to concert and venue request forms. 
On the Email section there is a requirement to have "example@moreText" but does not have a requirement for .com, .edu, .org, .net, etc. 
The Phone number only allows ###-###-#### format. It can not be submitted without this format. This may cause potential problems with international venues. 
There is a text space lastly and there needs to be information input or it will not submit. This will prevent venueless, and informationless requests that bogs down the system and slows down contacting real potential clients. 
The input box sizes are responsive to screen size differentials. 
The mobile size has an elongated scroll to reach the form. When the browser gets larger there is a 1/3 2/3 screen shift that makes a more eye appealing site with ease of use in mind to prevent more scrolling than necessary.
Mozilla, Internet explorer, chrome, and Opera all look the same. 

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Credits
Content

The Biography for the home page and the footer, along with the band members current and past were all taken and pieced together from;
https://www.catawiki.com/stories/4993-keep-on-rocking-the-5-oldest-bands-still-performing-today
https://www.imdb.com/name/nm1277963/bio 
https://en.wikipedia.org/wiki/List_of_best-selling_music_artists

The Timeline was copied and modified from https://codepen.io/bsngr/pen/Ifvbi
The button styling was copied from https://www.w3schools.com/css/css3_buttons.asp
The audio for the MP3's were researched and implemented from https://www.w3schools.com/html/html5_audio.asp to ensure that the audio is playable through many different browsers.

Media

Videos
Pinball Wizard https://www.youtube.com/watch?v=acKotWHn0i4
Baba O'Riley https://www.youtube.com/watch?v=sfffDpuek5M
Won't Get Fooled Again https://www.youtube.com/watch?v=UDfAdHBtK_Q

Picture
Picture 1 from https://files.greatermedia.com/uploads/sites/27/2015/09/85575315.jpg
Picture 2 from https://glidemagazine.com/wp-content/uploads/2016/02/whohyde3.jpg
Picture 3 from http://musica-hifi.com/wp-content/uploads/2017/02/The_Who.jpg
Picture 4 from https://courses.cs.washington.edu/courses/cse455/12au/projects/project1/web/voting/artifacts/webpages/nanabyte/TheWho.jpg
Picture 5 from https://images-na.ssl-images-amazon.com/images/I/51G%2BnJ6IoTL._AC_UL320_SR262,320_.jpg
Picture 6 from https://images-na.ssl-images-amazon.com/images/I/812iIwHCqhL._AC_UL320_SR226,320_.jpg
Picture 7 from https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/The_Who%2C_Oakland%2C_CA%2C_May_2016.jpg/220px-The_Who%2C_Oakland%2C_CA%2C_May_2016.jpg

MP3's
Who are you audio ripped from https://www.youtube.com/watch?v=r5kmCgVhADY
Eminance Front audio ripped from https://www.youtube.com/watch?v=ItQavimuoAc

Acknowledgements

A huge acknowledgement goes to the previous site made in the class for our Resume.
The 1/3 to 2/3 ratio was a perfect fit for all the information needed for this band
page. The ratio allows maximum information on every page without overload or
excessive and unnecessary scrolling.