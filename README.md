# LeagueFriendFinder
                                league local matchmaking application Documentation

  This repository is for the largest coding segments of the LeagueFriendFinder aplication, which allows you to find like
minded and ranked players within a certain distance from your location. All this is done without the hassle of having to 
create an account for the app to find others to play with. The rest of the files related to this project are included  
attached to the zip file i submitted, so as to enable the compilation and running of the application through xcode. The 
application is not yet in the state i want it to be, and so i have not yet submitted it to the appstore. i want to 
properly implement the ranked system into matchmaking and allow you to find duo partners for quick games rather than 
having to find a full team. All this has to be done is a beautiful display and quality app, so as to gather the attention
of potential users, and have previous users recommend the application. All images used in the application are 
official images and each one is edited in photoshop to show the perfect amount of a champion and maintain a 
streamlined state. All legal issues are also followed based on the Riot games legal jibber jabber page.

ViewController1: The home screen of the application after loading. Featuring ranked selection as well as a changable 
portrait and name, this screen will automatically save your information for return visits and transport it to the 
other required inputs for them in other view controllers by itself.

ViewController2: The selection screen. This view allows the selection of a certain type of queue that you would like to 
play, along with your choices for role and champion. This will ensure that other people are found with roles that are not 
identical to yours. This is also the first screen where location services will have to be enabled to find other users in 
vicinity. I have not implemented a map in this screen showing users around you, as i feel some people might find this 
intrusive to their privacy. This was also seconded by some friends i asked about the topic. All images are also 
generated here for use. I am also most likely going to replace the images with just the portrait and no words, 
as i feel that people using the app will already know who all the champions are, and this will make the view controller
look more beautiful.

ViewController3: This view contains a basic chat screen that saves all data implemented into it and loads it whenever 
required. There is still a large amount of customization required in this particular section of the app, as it needs
to be streamlined and gather a more qualified look.

ViewController4: The bread and butter of the app. This viewController handles all matchmaking as soon as its loaded by 
automatically utilizing the saved data from the first and second screens, and finding people related to your queries. 
It then will populate these people into cells, listing their summoner names and portrait, as well as class and champions
in a very beautiful display. It also handles sending your information to those you have matched with to create a 
lobby, and utilizes functions to manage all this. A function here also assigns portraits based on the recieved 
champion and class integers from the parse database servers.

The rest of the files are not as important as these, and are available to view in the zip file. This app was created
with the notion that simple things could accomplish difficult tasks, and as such i created the entire thing using
simple functions and loops, utilizing the Parse Backend service to store and manage data.
