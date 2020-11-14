# exARcise

# Inspiration
Obesity afflicts over 13 million children, according to the U.S. Centers for Disease Control and Prevention. The risk of childhood obesity also increases with age, with over 20%
of all children 12 to 19-year olds being classified as obese. Furthermore, study after study has found that childhood obesity dramatically increases the risks of dangerous health 
consequences in adulthood.

COVID-19, and the lockdowns imposed to combat it, have made this complex and far-reaching problem even worse!
Schools all around the world have closed, which means no recess, no sports, and no gym class. Many communities have implemented strict social distancing guidelines which have 
closed outdoor spaces like playgrounds and parks. Unfortunately, these measures have accidentally encouraged kids to spend even more time just sitting around indoors. In fact, 
University of Missouri sociology professor Joseph Workman estimates that just six months of school closure could result in a 4.86% increase in childhood obesity.

I built the EX-AR-CISE app to help solve this problem, by giving kids and adult a creative way to have fun exercising in their own homes.

# What it does
ExARcise uses augmented reality to gamify exercise for kids and adults to encourage them to exercise. The app is a platform that facilitates the creation of interesting and fun 
real-world activities by providing easily embeddable augmented reality experiences.
The core of the app is the AR-enabled 3D Models, which I power through ARFoundation. The Button of different exercise has the information the app needs to pull up the 3D model,
which then displays an exercise tutorial/example into the real world. 
In this pandemic situation children and adults do not need to go outside or gym for the exercise session, what they have to do is just download this app and enjoy the EX-AR-CIE 
session at their home, also this will reduce the chance of getting affected by COVID-19. It will also help in maintaining the social distancing norms as the user is in the home.

# How I built it
Since EX-AR-CISE is meant to be accessed via a mobile device, responsiveness is a key design feature. Therefore, I chose to build a Unity app, styled in Material UI so the app 
is accessible and easy to use on all sized devices. 
For the AR portion of the app, I used AR Foundation, because it allows me to easily manage and track my AR experiences, and change them in the future. To use AR Foundation’s 
built-in rendering system, our app has an embedded system for viewing the experiences. You just have to choose the exercise you want to perform and then press the button; this
triggers an appropriate 3D Model performing the desired exercise in the real world.

# Challenges I ran into
One major challenge with the app that I came across was in encapsulating AR Foundation’s full rendering process into the app.
Accomplishments that I'm proud of
The main thing I am proud of is getting the AR Foundation to work so well! I'm really proud of the simple process I created for the user.

# What's next for exARcise
In the future, I want to expand exARcise in the following ways:

· Expand out the library of exercise models, exercise badges, etc.

· Enable the user to create personalized workout routines and sets

· Add mindfulness and wellbeing activities, like yoga poses

· Adding Reward System in Upcoming Version

# Build With
* UNITY3D
* ARFoundation
* c#

