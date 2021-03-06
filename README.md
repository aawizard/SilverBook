# SilverBook

SilverBook is an everyday Android App that helps students predict their G.P.A., manage their scores and manage their attendance.

## Why SilverBook

In IIIT-A and many other colleges, students get their G.P.A. only after the end term exams and there is nothing that can be done to improve them. SilverBook is an android app that enables users to predict their GPA right from the first test, so that they know where they stand at the moment and can pour in their efforts accordingly. Additionaly there is an attendance management feature that keeps a track of their attendance, and tells them the number of classes they can bunk/must attend to get their attendance on track, in real time.

## Getting Started

To get this project up and running on your local machine, all you need to do is clone or download this project, set up [Firebase Console](https://firebase.google.com/docs/android/setup), Open this project in android studio and run it on any android device or emulator.

### Prerequisites

A google account to set up firebase.

## Using the Application

On the very first screen users are asked for some basic information(College,Batch and Branch) which is used to automatically fetch subjects(For some selected colleges). The users then Sign-Up/ Sign-In using Firebase Auth UI. Users also get an option to add/delete their own subjects. Along with the Feedback and Share options there is an App reset option to clear all the data and logout the user. 
Note that the attendance data and scores are stored locally and none of it is uploaded. You may check out the source code for the same. Also note that, the authorisation is handled using Google's own Auth UI. So rest assured there is no way I can save or even see your passwords.(When you sign-in/up).

## Built with

* [Firebase](https://firebase.google.com/) - Used for a large number of features.
* [Maven](https://dl.google.com/dl/android/maven2/index.html) - Dependency Management.
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - For Pie Charts used in the app.

## Contributing

I am open to contributions. Contact me on [Facebook](https://www.facebook.com/mishraprateekaries) for any queries.

## Versioning

This is SilverBook v1.24 Pilot-3. Numbers to the left of decimal signify major releases, numbers to the right of decimal signify major commits and Pilot signifies the group of people this app is released for.

## Authors

* Prateek Mishra

See also the list of [contributors](https://github.com/MiKinshu/SilverBook/graphs/contributors) who participated in the project.

## Acknowledgements
* I am thankful to PhilJay MP Android Chart for the awesome graphing library.
* I am very greatful to the person who designed the icon, I searched a lot for his name but in vain.
* A huge shoutout to Sunidhi Kashyap and Siddharth Rajawat for their contributions in this project.
