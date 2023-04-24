# Zabani
A language learning app for children

Our prototype is provided as an APK file which can be downloaded and installed in any android device running Android 8.0 or higher. Furthermore, a demo of the application is also uploaded as a video file

This document briefly gives a walkthrough of the various screens implemented in our prototype and the functionality available. It also includes a short changelog which mentions any alterations from our original design as well as features we either have not yet been implemented due to lack of time, ability etc. Other changes due to research that showed us better is also present here.

One of the most important aspects of our product is its aesthetics and attractiveness. As our target audience is as an educational tool for children, it needed to be friendly and engaging. Thus we have taken the time to develop it from the design stage into as high fidelity as we could, with a bright colour pallet, background music etc etc.

We have also tried to keep the UI simple, with large buttons and minimal text to make it easier and more intuitive to use for children with as little experience and or adult supervision as possible.

OVERALL PROTOTYPE WALKTHROUGH

(START POINT) - SPLASH SCREEN
●	The user taps the app icon to launch the app.
●	The first page they are shown is the splash-screen, which acts as the loading screen for the app.
●	There is no interactivity on this page, it simply serves as an intermediary.
MAIN MENU
●	The user is given four buttons on their screen that they can press:
○	PLAY -takes the user to the LEVEL SELECT screen.
○	HELP - see tutorials for the various game modes from the HOW TO PLAY screen.
○	OPTIONS - various settings that the user could customise.
○	EXIT - leave the app.
LEVEL SELECT
●	The user is shown a screen with a ‘road-map’ of the various levels.
●	They can select one of the levels to play that stage.
MCQs
●	In this mode, the user is shown a question with the possible options at the bottom that they can choose from to answer and score points.
BLANKS
●	In this mode, the user is shown a sentence with one or more blank spaces. They must choose from the words provided to fill in the blanks and complete the sentence to score points.
SCORE RESULTS
●	After the user finishes a level’s questions, they are taken to this screen and shown their score.
HOW TO PLAY
●	Shows a list of buttons, one that goes to a TUTORIAL SCREEN for each of the gamemodes planned. 
●	In this prototype, only the screens for the MCQs and BLANKS have content implemented. 
●	Buttons functionality is present for the rest but not content.
TUTORIAL SCREEN(S)
●	Consists of a swipeable window screen when the user can go through the different pages of a tutorial and learn how to play the specific game that TUTORIAL SCREEN is for.
OPTIONS
●	A list of settings the user can customise:
○	Change Name 
○	Music ON/OFF toggle 
○	MENU TEXT 
○	RESET Scores 
●	The functionality of this menus settings has not been implemented.

CHANGELOG/NOTES

1.	Unfortunately, we were unable to get the infinite scrolling feature working in Android Studioand  so were unable to create a WORLD SELECT screen before our LEVEL SELECT screen. Thus for simplicity's sake the PLAY button goes directly to LEVEL SELECT.
2.	In our HI-FI design, we had back buttons on multiple screens for navigation purposes. However, after looking at Google’s Android app design guidelines and best practices we learnt that this is a poor design decision and the standard button bar’s  implementation of a back button is sufficient for this purpose. Hence, we have omitted it.
3.	Two of our gamemodes, (MCQs and BLANKS) have been properly implemented with some sample content provided for the levels. We did not have time to implement all the rest but for the purposes for our prototype’s functionality these two are sufficient as the other game modes will use similar screens and are only variants of the present format. 
4.	Prototype designed for Android 6.0 and up.
5.	Questions for games are limited placeholders, so repetitions may occur.

