# JADA (Just Another Dictionary App)
(Licensed under the MIT License)

<img src="./assets/icon.png" alt="drawing" width="200"/>

A simple free and open-source dictionary app that uses the API created by [Meet Developer](https://github.com/meetDeveloper) which you can check out [here](https://github.com/meetDeveloper/googleDictionaryAPI). This dictionary app uses that API to show definitions for the words entered by the user. It supports multiple languages and best of all it has dark mode.

## Download
Currently the app is only available on Github releases due to some compilcated personal reasons. You can [download the app from Github releases here.](https://github.com/sbeve72/JADA/releases)

## Multi Language support

This dictionary supports multiple language as the API I am using does too. The languages supported are the following

* English
* Hindi
* Spanish
* French
* Japanese
* Russian
* German
* Italian
* Korean
* Brazilian Portuguese
* Turkish

*This dictionary does not support Arabic even though the API supports the language as there seems to be some issues with arabic side of the API. I have tested it with different arabic words and it never returns an output. I will add support for Arabic if I figure out the reason it isn't behaving like it should.* ***I encourage people who know Arabic to help me figure out the issue***

## Versioning

The app uses a special blend of [Semantic Versioning](https://semver.org/#semantic-versioning-200) and some conventions decided by me to follow for this app since the guidelines for MAJOR in MAJOR.MINOR.PATCH are not compatible with Android Apps.
Everything is essentially the same except for a few key differences with MAJOR:
* MAJOR would be incremented if MINOR reaches 9
* It can also be incremented whenever a new library is added and used in the app
* It may also be incremented whenever the app stops supporting an old API level

## What's special

The dictionary was made with clean architecture practices and ease of reading of the code in mind.

It uses Kotlin entirely and it uses Navigation Components and parts of the MVVM architecture pattern.

It uses Retrofit2 to access a webserver that uses the API mentioned above to retrieve information about the word entered by the user in the search bar and to show the results it uses a recycler view. It also uses Material Components throughout the app wherever possible.

This app can be used by absolute beginners as a way to learn some basic things like using ViewModels or LiveData or Material Components.

I have commented every piece of code that I believed was not part of common things you do in Android Development. All the logic and operations done by me that are not common practices and unique to this particular app were explained with comments.

There can be found many parts that could use some improvement since I by no means claim to be a perfectly skilled or experienced developer, in fact, relative to so many awesome developers out there, I am very much new. I would like to get suggestions to improve my code or app from other experiened developers.

## Screenshots

* ### Welcome Fragment
<img src="assets/Screenshot_Welcome_Fragment_Light.png" alt="Welcome Fragment Light" width=300>
<img src="assets/Screenshot_Welcome_Fragment.png" alt="Welcome Fragment Dark" width=300>

* ### Result Fragment
<img src="assets/Screenshot_Result_Fragment_Light.png" alt="Welcome Fragment Light" width=300>
<img src="assets/Screenshot_Result_Fragment.png" alt="Welcome Fragment Dark" width=300>

* ### Change Language Dialog
<img src="assets/Screenshot_Change_Language_Dialog_Light.png" alt="Welcome Fragment Light" width=300>
<img src="assets/Screenshot_Change_Language_Dialog.png" alt="Welcome Fragment Dark" width=300>