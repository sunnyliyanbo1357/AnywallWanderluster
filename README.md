# AnywallWanderluster


This is a test version for Wanderluster. We used ParsePlatform Anywall to implement map and user chat log.

See more about Anywall: https://github.com/ParsePlatform/AnyWall.git

Copyright Yanbo Li. Cornell Tech. Cornell University.

### Background

Have you ever visited a place, done everything according to your homework yet still feel that your experience lack a touch of local flavor? If you are someone who seeks a more in-depth experience, who has an appetite for not only the authentic food but also the culture, the sprite or even a friend of the place, you are in luck. We want to offer a bridge that connects an interested tourist to an experienced local. Through a friendly local guide, you can acquire all the information you need, especially the ones you can't find online. What we offer is not only a connection to the city of your dream but also a new perspective, a chance to see and experience the city through its citizens' eyes. 


### Xcode Project Setup

1. Clone the repository
2. Install all project dependencies from [CocoaPods](http://cocoapods.org/#install) by running this script:
```
cd AnyWall-iOS
pod install
```
3. Open the Xcode workspace at `AnyWall-iOS/AnyWall.xcworkspace`
4. Add your Parse application id and client key in `PAWAppDelegate.m`

#### Configuring Facebook integration

1. Set up a Facebook app at http://developers.facebook.com/apps

2. Set up a URL scheme for fbFACEBOOK_APP_ID, where FACEBOOK_APP_ID is your Facebook app's id.

3. Add your Facebook app id to `Info.plist` in the `FacebookAppID` key.

### Learn More

To learn more, take a look at the [AnyWall iOS](https://parse.com/tutorials/anywall) tutorial.
