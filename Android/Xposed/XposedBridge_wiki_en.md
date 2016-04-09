# XposedBridge_wiki_en
[原文链接](https://github.com/rovo89/XposedBridge/wiki)  
created date:2016/02/15  
last modify date:2016/04/09

## [Home](https://github.com/rovo89/XposedBridge/wiki)
---
Please have a look at the [page overview](https://github.com/rovo89/XposedBridge/wiki/_pages) for available documentation.

## [Development tutorial](https://github.com/rovo89/XposedBridge/wiki/Development-tutorial)
---
Alright.. you want to learn how you can create a new module for Xposed? Then read this tutorial (or let's rather call it "extensive essay") and learn how to approach this. This includes not only the technical "create this file and insert ...", but also the thinking behind it, which is the step where value is created and for which you really need to understand what you do and why. If you feel like "TL;DR", you can just look at the final source code and read the "Making the project an Xposed module" chapter. But you will get a better understanding if you read the whole tutorial. You will save the time spent for reading this later because you don't have to figure everything out yourself.

### The modification subject
---
You will recreate the red clock example that can be found at [Github](https://github.com/rovo89/XposedExamples/tree/master/RedClock) as well. It includes changing the color of the status bar clock to red and adding a smiley. I'm choosing this example because it is a rather small, but easily visible change. Also, it uses some of the basic methods provided by the framework.

### How Xposed works
---
