# JSQMessagesViewController 

*An elegant messages UI framework for iOS*
[![Build Status](https://secure.travis-ci.org/jessesquires/MessagesTableViewController.png)](http://travis-ci.org/jessesquires/MessagesTableViewController) [![Version Status](https://cocoapod-badges.herokuapp.com/v/JSMessagesViewController/badge.png)][docsLink] [![license MIT](http://b.repl.ca/v1/license-MIT-blue.png)][mitLink]

![Messages Screenshot 1][img1] &nbsp;&nbsp;&nbsp; ![Messages Screenshot 2][img2]

> [More screenshots here](https://www.cocoacontrols.com/controls/jsmessagesviewcontroller)

## Features 

* Highly configurable & customizable
* Data detectors
* Timestamps
* Avatars
* Custom chat bubbles
* Subtitles
* Arbitrary message sizes
* Copy & paste messages
* Group chat
* Smooth keyboard animations
* UIDynamics for springy bubbles
* Dynamic input text view resizing
* Smooth animations
* Universal

## Requirements

* iOS 7.0+ 
* ARC
* [JSQSystemSoundPlayer][playerLink]

## Installation

#### From [CocoaPods](http://www.cocoapods.org)

`pod 'JSMessagesViewController'`

#### From source

* Drag the `JSQMessagesViewController/` folder to your project
* Install [JSQSystemSoundPlayer][playerLink]
* Add the `QuartzCore.framework`

## Getting Started

### Model

Your model objects should conform to the `JSQMessageData` protocol. 
However, you may use the provided `JSQMessage` class.

### View Controller

1. Subclass `JSQMessagesViewController`

### Demo Project

A demo project is included, `JSMessagesDemo.xcworkspace`. Run `pod install` first.

## Documentation

Read the fucking documentation. It is [available here][docsLink] via [CocoaDocs](http://cocoadocs.org). 
Thanks [@CocoaDocs](https://twitter.com/CocoaDocs)!

## Contributing

Please follow these sweet [contribution guidelines](https://github.com/jessesquires/HowToContribute).

## Donate

Support the developement of this **free**, open-source framework, via [Square Cash](https://square.com/cash).

<h4><a href="mailto:jesse.squires.developer@gmail.com?cc=cash@square.com&subject=$1&body=Thanks for developing JSMessagesViewController!">Send $1</a> <em>Just saying thanks!</em></h4>
<h4><a href="mailto:jesse.squires.developer@gmail.com?cc=cash@square.com&subject=$5&body=Thanks for developing JSMessagesViewController!">Send $5</a> <em>This control is great!</em></h4>
<h4><a href="mailto:jesse.squires.developer@gmail.com?cc=cash@square.com&subject=$10&body=Thanks for developing JSMessagesViewController!">Send $10</a> <em>This totally saved me time!</em></h4>
<h4><a href="mailto:jesse.squires.developer@gmail.com?cc=cash@square.com&subject=$25&body=Thanks for developing JSMessagesViewController!">Send $25</a> <em>I want new features!</em></h4>
<h4><a href="mailto:jesse.squires.developer@gmail.com?cc=cash@square.com&subject=$50&body=Thanks for developing JSMessagesViewController!">Send $50</a> <em>I love this project!</em></h4>

## Customization

> TODO

## Credits

Created by [@jesse_squires](https://twitter.com/jesse_squires), a [programming-motherfucker](http://programming-motherfucker.com).

Assets extracted using [@0xced](https://github.com/0xced) **/** [iOS-Artwork-Extractor](https://github.com/0xced/iOS-Artwork-Extractor).

Originally inspired by [@soffes](http://github.com/soffes) **/** [SSMessagingViewController][https://github.com/soffes/ssmessagesviewcontroller].

Many thanks to [the contributors](https://github.com/jessesquires/MessagesTableViewController/graphs/contributors) of this project.

## About

I initially developed this control to use in [Hemoglobe](http://www.hemoglobe.com) for private messages between users.

As it turns out, messaging is a popular thing that iOS devs and users want. Thus, I am supporting this project in my free time and have added features way beyond what [Hemoglobe](http://www.hemoglobe.com) ever needed.

Check out my work at [Hexed Bits](http://www.hexedbits.com).

## Apps Using This Control

* [Hemoglobe](http://bit.ly/hemoglobeapp)
* [Loopse](https://itunes.apple.com/us/app/loopse-spots-friends-sessions/id704783915?mt=8)
* [Oxwall Messenger](https://github.com/tochman/OxwallMessenger)
* [FourChat](https://itunes.apple.com/us/app/fourchat/id650833730?mt=8)
* [AwesomeChat](https://github.com/relatedcode/AwesomeChat)
* [Quick Text Message](https://itunes.apple.com/us/app/quick-text-message-fast-sms/id583729997?mt=8)
* [Libraries for developers](https://itunes.apple.com/us/app/libraries-for-developers/id653427112?mt=8)

*[Contact me](mailto:jesse.squires.developer@gmail.com) to have your app listed here.*

## License

JSQMessagesViewController is released under an [MIT License][mitLink]. See LICENSE for details.

Copyright &copy; 2014 Jesse Squires

*Please provide attribution, it is greatly appreciated.*

[docsLink]:http://cocoadocs.org/docsets/JSMessagesViewController/4.0.0

[mitLink]:http://opensource.org/licenses/MIT

[playerLink]:https://github.com/jessesquires/JSQSystemSoundPlayer

[img1]:https://raw.github.com/jessesquires/MessagesTableViewController/master/Screenshots/iphone5-screenshot-ios7.png
[img2]:https://raw.github.com/jessesquires/MessagesTableViewController/master/Screenshots/iphone5-screenshot5.png
