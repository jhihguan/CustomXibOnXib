This is demo code to show Your Custom Xib UIView(w/ or w/o autolayout) on another Xib or Storyboard View Controller

The most important UIView base code is inside `BaseView` or [here](https://gist.github.com/jhihguan/4d36fad70eb92b0a9dec). Because showing Xib on another Xib you have to implement `initWithFrame` with some view setup function. And be aware of the `TARGET_INTERFACE_BUILDER`, it's a must have bundle init type check method.