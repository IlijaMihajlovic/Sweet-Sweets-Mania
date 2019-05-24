# Sweet-Sweets-Mania-SpriteKit-Game

![platform-ios](https://img.shields.io/badge/platform-ios-Blue.svg)
![swift-version](https://img.shields.io/badge/swift-4.2-Orange.svg)
![lisence](https://img.shields.io/badge/license-MIT-Lightgrey.svg)

A single player game in SpriteKit created completely programmatically without the use of .sks files and Xcode Scene Editor. 
I used Firebase as a backend and implemented its Sign up/Login with Facebook and Anonymously into the app, and saved users data like: UID, email address, username and profile image into Firebase Database and Firebase Storage, likewise, I implemented a persistent store so all user data is saved after the user quits the app.
During the development of the app, I followed the MVC design pattern, likewise, I used Sketch for creating most of the UI.
___
## Side Note
* Currently, I do not have an iPhone, so I'm unable to test the app on a physical device. I apologize in advance for maybe possible bugs.

   Kind regards,

   Ilija 🖖 😄
___

## Requirements
- Swift 4.2
- Xcode 9.2+
- iOS 11.0+
___

## Getting the files

* Use GitHub to clone the repository locally, or download the .zip file of the repository and extract the files.
___

## Example how the UI looks

* This is the "welcome screen" that the user is presented during the first launch of the app. On the screen, we can see the background with the name of the app with Facebook Sign-Up Button and the Sign-Up Anonymously Button.
At the very bottom of the screen, we can see the Terms of Service and Privacy Policy.

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania/blob/master/Images/welcomeSceneWoman.png)

* Here we can see like on the first image the welcome screen, the main menu, and on the far right side, the settings slide menu after, the user presses the settings button.

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania/blob/master/Images/firstThreeScreens.png)

* On this image, we have three screens.
On the left side is the "gameplay screen". In the middle is the "game over" screen with the replay button, the best score, the current score and the back button on the top left corner of the screen.
On the far right side of the image, we have the "gameplay" screen with the SKStoreReviewController pop-up asking the user to rate the app on the App Store. We are asking the user to rate the app after he/she presses the replay button for a new game. In the future version of the app, I will implement the request after the user finishes a level successfully.

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania-SpriteKit-Game/blob/master/Images/GameScenes.png)

* Now we're in what I call the "swiping controller". Here I used a UICollectionViewController and UICollectionViewFlowLayout methods to implement the page to page swiping mechanism UIPageViewController with the flexibility UICollectionView has.
UIPageControl was used for the dots representing on what page the user is currently on, and how many pages there are.
Also we have two buttons on near the button of the screen for navigating through the pages together with the UIPageControl in a UIStackView.
On each page, there is a UITextView and a UIImageView that represent a different image and a different text.

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania/blob/master/Images/SwipingController.png)

* On this image we have the "user profile controller" with the image on left showing when the user sign-up anonymously. And on the right side is signing up with Facebook. Also, there are buttons for signing out, one to the main menu and one for fetching users data. This one changes the UILabel and UIImageView with the user's profile image from Facebook and users email address.

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania-SpriteKit-Game/blob/master/Images/UserProfileScene.png)
  
* Last but not least a short sneak peek how the project looks. 😄💻

   ![alt text](https://github.com/IlijaMihajlovic/Sweet-Sweets-Mania-SpriteKit-Game/blob/master/Images/project.png)
___


## License
```
MIT License

Copyright (c) 2019 Ilija Mihajlovic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
