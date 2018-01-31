# ClassroomVR

About
Although the internet has made educational resources available to larger audiences, online-learning can not replace the value of the in-person interaction between a student and a teacher. WebVR can help improve the online education experience by providing students and teachers with an immersive environment that re-introduces the value of face-to-face interaction.

AfterClassVR is a proof-of-concept WebVR application that shows how teacher could inhabit a virtual environment with their students. It was built during the 2017 WebVR Hackathon in New York. All students are muted by default It provides tools to the teacher to manage in-class discussions by giving them a tools to mute and un-mute students who want to ask questions.

How we built it
AfterClassVR was built in A-Frame using Hayden Lee's networked A-Frame framework to handle networking and voice chat between users.

We also set the scene up on sketchfab to utilize their robust rendering presentation tools. https://sketchfab.com/models/3141494928ef4c18a870b28b5b76507d. From there you can link to the project.

Challenges we ran into
Syncing a global state between users is very hard, since WebRTC (on which networked a-frame is built) seems to be peer-to-peer. Syncing common objects that aren't avatars, and interacting with children created by templates prooved to be very hard to set up.


What's next for AfterClassVR
Future versions could look into allowing larger scale classes, improving the discussion-management tools provided to the teacher, and allowing teachers to import course materials into the virtual environment like images and 3d models.
