# DateKit README #

### What is DateKit?

* *DateKit* is a simple Swift framework to simplify operations on NSDate instances. Playground presenting all the features will be available soon.
* Version: 0.1

### Setup
Download/clone repo and you can start using DateKit.

DateKit requires Quick and Nimble (bdd and matchers frameworks). They can be added manually to DateKit project. Download [Quick](https://github.com/Quick/Quick) and [Nimble](https://github.com/Quick/Nimble) from Github and add them to DateKit project.

Alternatively you can use CocoaPods. There is a Podfile in DateKit, so all you need to do is to run code below (in Terminal):

```
pod install
```
Please remember that CocoaPods are in beta for Swift. Don't forget to get pre-release version of CocoaPods: `gem install cocoapods --pre`.
Close DateKit project. Open DateKit.xcworkspace file and run tests as usually (cmd + U).

### Playground
There's a Playground on the repo, so you can play a bit with DateKit. To use Playground create a workspace with DateKit.project (or use the one created by cocoapods), build DateKit, and then drag playground into the workspace. Have fun!

Any questions can be asked to r.szeja@snowdog.pl
