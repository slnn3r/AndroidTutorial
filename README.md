# Getting Started with MAD  

![Steps](https://github.com/slnn3r/AndroidTutorial/blob/master/img/one-step-at-a-time-1080x630.jpg)

**“Every Journey Begins With A Single Step.” – Maya Angelou**

When you think about to develop a Mobile Apps you cannot avoid the needs to adapt the MAD concept (aka Mobile Application Development). In MAD, things may work differently from **Web Application, Windows Application and other application development**. This documentation would mainly focus on MAD of **Android Platform**, it is not a step-by-step guidelines but it includes necessary resources that may give you the rough idea on getting started with MAD. There is no steep learning curve in MAD, so one step a time and you are good.


## Table of Contents
1. [Understanding Mobile Development](#understanding-mobile-development)
2. [Android Development Overview](#android-development-overview)
3. [Android Development Tools and Resources](#android-development-tools-and-resources)
4. [Android Application Components](#android-application-components)
5. [Android Activity Life Cycle](#android-activity-life-cycle)
6. [Android UI Controls](#android-ui-controls)
7. [What else?](#what-else)



## Understanding Mobile Development

**Mobile vs Web Application**

There are some differences between Mobile and Web, I would highlight few points that differentiate both of them.

1. **Availability** - Web application rely on Internet Connection to being available for user to use, where Mobile application are mostly support both online and offline mode. Mobile application is a huge win when developing apps that required offline capability while it still able to support online functionality as well.

2. **Accessibility** - Web application tend to have higher accessibility than Mobile application, as web application is cross platform where it can be access by any online device in most web browser, while Mobile application have accessibility restriction by Mobile Platform such as Android, IOS, Windows, etc. Also, in Android, Mobile application's accessibility tend to restricted by the Android Version where older version Android is no longer support latest developed application.

3. **Capability** - Function Capability of Web and Mobile Application are very close to each other (check out: [What Web Can Do](https://whatwebcando.today/)), however there are still things that web application would not able to perform, but things where web application would perform better than Mobile application.

These are the things I highlighted as you would need to consider about them when you trying to develop a solution. Compatibility of the solution may vary depends on the technical requirements, business nature, etc. So, before develop a Mobile Application, make sure the solution work best in it.

Here some additional Reads on How Mobile Application is different from Web Application:
- [Should you build a native app or a web app?](https://medium.com/enabled-innovation/why-native-apps-are-better-than-web-apps-604867b20c50)
- [What are the difference between web app and mobile app?](https://www.quora.com/What-are-the-difference-between-web-app-and-mobile-app)
- [Differences between mobile applications and mobile websites](https://www.unitag.io/mobile-websites/what-is-the-difference-between-a-mobile-application-and-a-mobile-webpage)

<br>

**Mobile Application Category**

There are various type of Mobile Application, each of them access through Mobile Device but offer different advantages toward each other, here are some common Mobile Application Category currently available:

1. **Mobile Web Application** - It is basically a Website that access by using a **Web Browser Mobile Apps** or [WebView](https://www.stevesouders.com/blog/2014/10/09/do-u-webview/) in a Mobile Device. Will have some different compare to the "Desktop Version" of Website such as Screen Design may design to match Mobile Device screen size, able to access Mobile Device hardware, etc. Code in Web Language, such as HTML, JAVASCRIPT, etc and as long there is a web browser and internet connection, it can be access by any Mobile Device without any installation of file.

2. **Mobile Native Application** - It is a mobile application that coded in **Native Language** and only work on Native Platform. For an example, an Application is coded in JAVA Language and it only able to run at Android Platform or an Application is coded in SWIFT Language and it only able to run at IOS Platform, both of these Application is a Mobile Native Application. It required installation to the mobile device before it can be launch and having the offline capability.

3. **Mobile Hybrid Application** - It is a mobile application that run in the [WebView](https://www.stevesouders.com/blog/2014/10/09/do-u-webview/) of the Mobile Device. It is coded in Web Technology like HMTL, JAVASCRIPT, etc while it still able to work offline on the device, it required installation but it able to work on most type platform such as Android, IOS, Windows, etc on different devices.

4. **Mobile Compiled Application** - Similar like the Mobile Hybrid Application, it able to work offline, does required installation, cross platform but it does not run in the [WebView](https://www.stevesouders.com/blog/2014/10/09/do-u-webview/) and its performance is faster than the Mobile Hybrid Application. Coded in [React Native](https://facebook.github.io/react-native/), basically full JAVASCRIPT.

There are the brief description of different category of Mobile Application. The Mobile Hybrid Application and Mobile Compiled Application sometimes can be hard to differentiate, but still both of them are on a different page. Here a ([well-explained video](https://www.youtube.com/watch?v=rb8smP_xTTY)) if you really wanted to get to know more about the differences among the Mobile Application above.


<br>

## Android Development Overview

![Androids](https://github.com/slnn3r/AndroidTutorial/blob/master/img/manu-cornet-bugdroid-cartoon-android-evolution-key-lime-pie.jpg)


**Why Android Mobile Native Application?**

We going to look into specifically toward Android Mobile Native Application. These reason of choosing Android Mobile Native Application over the others is totally opinion-based, Here some of my personal thoughts:

1. **It is supported by Google** - Google offer a lot of great stuff, Cool Libraries, Great IDE tools, technical support, great platform like PlayStore, etc and all come in great quality and free or affordable charges.

2. **It is supported by a Large Community** - The community is huge, everyone is contributing and supporting each other directly or indirectly. There are a lot great Forum with a lot cool people who willing to offer up **reasonable** help, many great solutions, ideas, libraries are being shared and published.

I personally love open-source, it embraces the idea of "Sharing is Caring", maybe you could look into this [articles](https://www.androidauthority.com/develop-apps-for-android-rather-than-ios-607219/) that explain the other reason of choosing Android.



<br>

**Native Language Used in Android Development**

Currently there are 2 Available Native Language that widely supported by Google and the Community, they are:

1. **JAVA** - JAVA have been in the scene for a decade, a general purpose programming language that can be use to code web, windows application, mobile application and many more. I personally think JAVA is a very good place to start off learning the **Object Oriented Programming Concept** as well. For more info, Google it.

2. **KOTLIN** - JAVA officially is the first official language to code Android Native Mobile Application and being supported by Google. In 2017, Google officially announced that they will be offer **first-class support** toward KOTLIN and make it one of their official language to develop Android Native Mobile Application. It offers some great technologies such as Lambdas, etc, the code implementation is usually shorter and concise than JAVA. For more info, Google it.    

It's 2018, code in Modern Language like KOTLIN is very preferable. However, for novice, it would highly recommended to code in JAVA instead.

<br>

## Android Development Tools and Resources

**integrated development environment (IDE)**

Notepad++ or other text editing software is a very helpful tools in programming, some of us might tempted to solely use to code for showing off or something. **But please do not do that.** To ensure our life's misery stick to the minimum status, Google released **Android Studio** as their official IDE where we can have a great environment to develop the Android Mobile Application. Android Studio going to be our main tools, and it consumes great processing power, RAM memory and memory space as well, it would be very preferable to use a **Beafy Rig** to play with it, else you just have to endure and be patient with it sometimes.

Here some Resources to help you getting started with Android Studio:

1. [Where to Download Android Studio](https://developer.android.com/studio/) **(Download the Stable Release Only)**
2. [How to Setup Android Studio](https://www.youtube.com/watch?v=-Z74OmlQa90)
3. [A Quick Tour of Android Studio](https://www.youtube.com/watch?v=lGuh4lTWroY)

Time to verify if the Android Studio is properly setup in your PC, let's verify it by building your first mobile native applications. [Try this out](https://developer.android.com/training/basics/firstapp/).

Note: Do follow the sequence from **Overview** -> **Create an Android Project** -> **Run your app** -> **Build a simple user interface** -> **Start another activity**

<br>

**I'm Stuck, Help!**

<br>

## Android Application Components


<br>

## Android Activity Life Cycle

<br>

## Android UI Controls

<br>

## What Else?

**Develop with Version Control System (GIT)**

<br>

**Library**

<br>

**Architecture**
