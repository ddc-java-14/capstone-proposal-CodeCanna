## Summary

This application is intended to help users understand and map the sky above them.  All the user has to do is launch the app and hold
your phone towards the heavens, and watch as constellations are mapped out and named as well as the stars that make them up.

The idea is to show an augmented reality view of the night sky with an overlay of the stars that are there whether visible or not.  You can use
this app in day as well because the stars are still there, just not visible.  The user will be able to select a constellation and 
either favorite it, or search wikipedia for info on it.

## Intended users
* Hobbyist getting into astronomy
* Astronomy teachers for young students
* Astronomers pocket star map

For each type of intended user, include at least 1 _user story_. A user story is usually just 1 simple sentence (no more than 2 sentences), in the voice of the intended user, stating a specific task that the user performs using the app, and the benefit that will be obtained. The simplest user stories take the form
* Beginners/Hobbyists
  > As a hobbyist with a new interest in Astronomy, I want to use the Augmented reality view of the sky to help me identify constellations.

* Teachers
  > As a teacher teaching my students about astronomy, I want to use the real-time star-map to keep my students on the same page, everyone can get the app and see what I see.

* Professionals
  > As a professional Astronomer I could use the Augmented reality for shows, and the fact that the app updates regularly to keep the audience on the same page. 

## Client component

### Functionality
The gui will consist of a home-screen where the users can log-in if that's in scope, and if it's not then enter their email address to get their list of
saved constellations.

The next screen will be a menu for navigating to the AR star map, the users saved list, and perhaps a constellation or NASA pic of the day.

### Persistent data
* Their list of saved/favorite constellations.
* Info about the each saved constellation
* Their email (If they prefer).
* Their password (If they prefer).
    
### Device/external services
* Access to the Database through the API
* Camera
* Real-time astronomy data
    
## Server component

### Functionality
* Provides the astronomy data
* Handles user data

### Persistent data
* User emails
* User passwords
* User saved data 
### External services
Real-time astronomy data from an as yet to be determined source, most likely wherever Sellarium gets its data from. 

## Stretch goals/possible enhancements 
* Allow users to share and see others saved constellations
* Allow users to connect stars and create their own (Unofficial) constellations
* Create a user-driven image database
