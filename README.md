## Readme

# Table of contents
- [App Demo](#App-Demo)
- [How to Run](#How-to-Run)
- [Context](#Context)
- [Content](#Content)
- [How it's written](#How-it's-written)
- [Inspiration](#Inspiration)


# App Demo

https://user-images.githubusercontent.com/25262431/166058501-12bc6d2a-96c2-4dc7-bf2d-f1fe7932abb0.mp4


# How to Run
First make sure to install XCode version 13 or later and have iPhone X or later versions.

Clone the repository:
```bash
git clone https://github.com/AshkanGoharfar/AR-online-shopping-iOS.git
```

Next, go to the project directory.
```bash
cd AR-online-shopping-iOS
```

Next, run the following command to create pod file.
```bash
pod init
```


Open the pod file by the following command to create pod file.
```bash
open podfile
```

Copy and paste the follwing text to the podfile


```
# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'AR-online-shopping-iOS' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for AR-online-shopping-iOS

  target 'AR-online-shopping-iOSTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'AR-online-shopping-iOSUITests' do
    # Pods for testing
  end

  pod 'Firebase/Core'
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'
  pod 'Firebase/Storage'
  pod 'SDWebImageSwiftUI'

end
```

Finally, run the following command to install the dependencies to the podfile.
```bash
pod install
```

Connect your iphone to your Mac and run the code :)

# Context
## How Augmented Reality in Ecommerce Can Deliver a More Enticing Shopping Experience?

One of the biggest challenges of online shopping is that it doesn’t lend itself well to a full sensory product experience. In a brick-and-mortar environment, you can try on clothes, touch fabrics, or see for yourself just how big a couch looks in a room. 

While those things aren’t technically possible in ecommerce, augmented reality (AR) applications offer a way to give customers deeper and more complete information about your products — right from their own home.

# Content
This iOS App is an online shopping app with Augmented Reality feature.

# How it's written
The front-end was developed using SwuiftUI, ARKit, MessageUI, and FocusEntity. The User Authentication and Cloud Stroge was developed using Google Firebase.


# Inspiration

We would be more than happy for any future collaboration towards adding new features and improving screens.