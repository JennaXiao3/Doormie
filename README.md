# Doormie

As first-year students at university, we have all had our fair share of experiences with our roommates. We hear stories from our friends who talk about how their roommates stay out so late, stay in all day, are too loud, always need a quiet space, are hard to communicate with, are easy to get along, etc. To simplify the communication between two strangers (or friends) under the same roof, we built a mobile app...Doormie!

Doormie is a mobile app to track the status of your roommate(s) to ensure that everyone is aware of each other's circumstances. In general, there are 3 main statuses: "Away from home", "Quiet please", and "Chilling". "Chilling" is the default setting (no special circumstances), "Quiet please" is used to let your roommates know that they should refrain from being loud (ex. when you are studying, napping, in a meeting, in online class, etc.), and "Away from home" gives your roommates a notice that you will be gone. You can add a description to further explain your status such as "eating out with friends" or "playing video games". To reduce manuals inputs, scheduled statuses are implemented where you can have your status automatically change at a certain time.

We built Doormie using three main technological frameworks/services:

* We used React Native to facilitate the construction of the front-end of mobile application. Having worked with it extensively, Javascript is a language that all four of us were already very familiar with, so React Native was the obvious choice of a framework.
* To host our mobile application as well as emulate the app in real-time on our devices, we used Expo, an open-source platform designed to make React Native development easier
* Finally, we also used Firebase's Realtime Database service to store all of the user as well as roommates' information, as well as Firebase's Authentication service to securely handle registration and logging in
