# Xcode: Just Enough

## Objectives

1. Get acquainted with Xcode just enough to start playing with Swift.
2. Distinguish the four main areas of Xcode and how to find information printed to Console Output Viewer.
3. Say hello to the iOS Simulator.

## What is Xcode?

There are iPhones, Macs, Apple Watches & Apple TV's which represent the hardware offered by Apple. Powering these various devices is software. There are different pieces of software deployed on each device, names you might already be familiar with.

* iOS, MacOS, tvOS, watchOS

Being a developer, you will want to create various applications for these various operating systems (everyone has an app idea). 

There needs to be a place where we can create this software. We use a Word document to create essays, stories or... I'm not really sure, I don't use Word documents anymore but you get the point.

Xcode serves as our Word document. It's a place where we write code.


The programming languages we can utilize within Xcode are Swift & Objective-C. When this code is written, we can then *run* the application. When doing so, Xcode is able to take the code we wrote and read it. It does more than read the code, it's able to compile it and allow any of the above devices to run it!

This process described above is known as an Integrated Development Environment, or IDE. Xcode then is the IDE provided by Apple that allows us to create apps.

![Xcode](http://i.imgur.com/H5IUNEe.png)

Here is me opening up Xcode and starting a new project. I have the ability to begin an iOS, watchOS, tvOS or MacOS (here it's still OS X) application. It's that simple.

We can hit next and create our project. We will be asked to provide the name of our app.

![example](http://i.imgur.com/MHcgw8r.png)

After hitting next, we can begin to write our code! The language I'm using here will be Swift.

![locate](http://i.imgur.com/WGqFvDu.png)

I've selected the `ViewController.swift` file in the left pane. By doing this, this brings up a document in the center (main) window where we can now write some code!

Here's an example of me writing some code in this `ViewController.swift` file.

![ex](http://i.imgur.com/WvSiOB0.png)

So now that I've written some code in this `ViewController.swift` file, how can we make it *run*. 

In the upper left corner of Xcode, you should see what appears to be a Play Button with a Square (stop) button to the right of it. If you were to click the Play button, your app will run! So lets do that.

![runn](http://i.imgur.com/y8Mp5FA.png)

'Hello everyone' was printed to the console here. But that's not really a fun application (I know).

You should have also noticed, that something else appeared on screen when you ran your app.

![simulator](http://i.imgur.com/7JxaDCZ.png)

This is the Simulator. It simulates what your app will look like. That way, you aren't required to plug and run your app on your iPhone when developing an app. We can do so right from our computer. 

Lets change the background color to blue.

![blue](http://i.imgur.com/hzDDoMG.png)

After including this code, if we were to run our app (You can also do this pressing command + r) - the simulator should look like this:

![bluee](http://i.imgur.com/zjyrEaw.png)

This is the process of creating an app.


**Note:** *The first time you open Xcode, your machine will ask you if you want to enable "Developer Mode". Go ahead and do this; don't be scared of it! What it does is allow you to debug your projects without OS X asking for your administrator password every time. If you previously selected "No" the first time that you opened Xcode, don't worry! Just open your terminal and type* `$ DevToolsSecurity -enable`.

## Xcode Areas

![xcodeThing](http://i.imgur.com/tNpTjA3.png)

The workspace window always includes the editor area. When you select a file in your project, its contents appear in the editor area, where Xcode opens the file in an appropriate editor. For example, in the figure above, the editor area contains AdventureScene.swift, a swift code file that is selected in the navigator area on the left of the workspace window.

The workspace window displays up to three optional areas used in performing different tasks in the development life cycle. Hiding areas not in use can help you focus on your current task. You can hide or show these optional areas by using the workspace configuration buttons on the far right side of the toolbar:

![nav](http://i.imgur.com/oxJnlOP.png)  Show and hide the navigator area. Use this area for navigating all facets of your project, including files, symbols, breakpoints, build issues, tests, breakpoints, and build reports. You can also search for any string in your project.

![debug](http://i.imgur.com/jQ22SM6.png)  Show and hide the debug area. Use this area for viewing variables, interacting with the debugger console, and controlling the execution of your app.

![rightThing](http://i.imgur.com/BZ0INGj.png)  Show and hide the utilities area. Use this area to inspect or modify attributes of files, graphical user interface elements, sprites, and other elements in your project. Also use it to access a library of ready-made resources. See Accessing Resources and Inspecting Elements.

---




<p data-visibility='hidden'>View <a href='https://learn.co/lessons/reading-ios-intro-to-xcode'> Xcode: Just Enough</a> on Learn.co and start learning to code for free.</p>
