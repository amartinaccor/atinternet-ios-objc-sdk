# AT Internet iOS SDK
The AT Internet tag allows you to follow your users activity throughout your application’s lifecycle.
To help you, the tag makes available classes (helpers) enabling the quick implementation of tracking for different application events (screen loads, gestures, video plays…)

### Content
* Tag iPhone / iPad
* App Extension supported

### How to get started
  - Install our library on your project (see below)
  - Check out the [documentation page] for an overview of the functionalities and code examples

### Manual integration
Find the integration information by following [this link]

###Installation with CocoaPods

CocoaPods is a dependency manager which automates and simplifies the process of using 3rd-party libraries in your projects.

###Podfile

  - Basic iOS application : 

```ruby
target 'MyProject' do
pod "ATInternet-iOS-ObjC-SDK/iOS", ">=2.0"
end
```

  - iOS application with iOS App Extension : 

```ruby
target 'MyProject' do
pod "ATInternet-iOS-ObjC-SDK/iOS",">=2.0"
end

target 'MyProject WatchKit 1 Extension' do
pod "ATInternet-iOS-ObjC-SDK/WatchExtension", ">=2.0"
end

```

### License
MIT


   [this link]: <http://developers.atinternet-solutions.com/ios-en/getting-started-en/integration-of-the-objective-c-library-ios-en/>
   [documentation page]: <http://developers.atinternet-solutions.com/ios-en/getting-started-en/integration-of-the-objective-c-library-ios-en/>