
<p align="center">
<img src="https://raw.githubusercontent.com/goposse/ripper/assets/ripper_logo.png" align="center" width="460">
</p>

> <b>Ripper</b> : great, fantastic - "that is a ripper of an image downloader"<br/>
> <b>Ripper, you little!</b> : Exclamation of delight or as a reaction to good news<br/>

Ripper is an image download library written in Swift for iOS. It is simple, easy to use, and doesn't come stuffed with things you don't need.

[![CocoaPods](https://img.shields.io/cocoapods/v/Ripper.svg?style=flat-square)](#)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat-square)](https://github.com/Carthage/Carthage)
[![Platform](https://img.shields.io/cocoapods/p/Ripper.svg?style=flat-square)](#)


# Features

- Full featured, but none of the bloat
- Easy to understand, Builder(ish)-based architecture
- Download directly to a `UIImageView`, block, or both (so you can edit it before it ends up in your View)
- Resize images on download simply
- Built in request caching and cancelation


# Installation

## CocoaPods

Add the following line to your `Podfile`:

`pod 'Ripper', '~> 0.5'`

Then run `pod update` or `pod install` (if starting from scratch).

## Carthage

Add the following line to your `Cartfile`:

`github "goposse/Ripper" ~> 0.5`

Run `carthage update` and then follow the installation instructions [here](https://github.com/Carthage/Carthage#adding-frameworks-to-an-application).


# The basics

To come

# FAQ

## Why should I use this?

It's up to you. There are other fantastic frameworks out there but, in our experience, we only need a small subset of the things they do. The goal of Ripper was to do one thing and one thing well. Not to deal with the possibility of "what if?". As we add new things to the library, we intend to work very hard to stay true to this one principle.

## Has it been tested in production? Can I use it in production?

The code here has been written based on Posse's experiences with clients of all sizes. It has been production tested. That said, this incarnation of the code is our own. It's fresh. We plan to use it in production and we plan to keep on improving it. If you find a bug, let us know!

## Who the f*ck is Posse?

We're the best friggin mobile shop in NYC that's who. Hey, but we're biased. Our stuff is at [http://goposse.com](http://goposse.com). Go check it out.

# Outro

## Credits

Haitch is sponsored, owned and maintained by [Posse Productions LLC](http://goposse.com). Follow us on Twitter [@goposse](https://twitter.com/goposse). Feel free to reach out with suggestions, ideas or to say hey.

### Security

If you believe you have identified a serious security vulnerability or issue with Ripper, please report it as soon as possible to apps@goposse.com. Please refrain from posting it to the public issue tracker so that we have a chance to address it and notify everyone accordingly.

## License

Ripper is released under a modified MIT license. See LICENSE for details.