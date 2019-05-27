# AR With Unity

<p align="center">
  <br>
  <img width="400" src="img/unity-logo.png" alt="logo of Unity">
  <br>
  <br>
</p>

>Getting started with **Augmented Reality (AR)** using *Unity*.

Want to develop AR apps but not sure where to start? Here's a curated list on how to get started in Augmented Reality with Unity using different SDKs to develop AR apps.

Let's get started!

# Pre-requisites
> Must know either C# or Javascript for coding.<br>
> Must have latest Android/iOS device supported by different SDK.

# Quickstart
- Download [Unity](https://unity3d.com/get-unity/download/archive) version 2018 or above.
- Choose *Android/iOS/Vuforia* build support depending upon your requirements.
- Download Microsoft [Visual Studio Community 2017](https://visualstudio.microsoft.com/).
- Platform specific SDK such as Android build tools are also required.

# SDK List
| ☆ | Name | Description |
| --- | --- | --- |
★★★ | [ARKit](#ARKit) |  ARKit is a unique framework that enables brands and developers to design and create unparalleled experiences for compatible iPhone and iPad devices (compatible iPhone’s and iPad’s must be equipped with an A9 processor or above). The ARKit SDK functions in the same way as most AR SDK’s function, by enabling digital information and 3D objects to be blended with the real world but offers largely unparalleled accessibility in terms of the number of existing devices that it supports.
★★★ | [ARCore](#ARCore) | Google’s proprietary augmented reality SDK. Similar to ARKit, it enables brands and developers to get AR apps up and running on compatible Google smartphones and tablets. One of the most notable features of ARCore is that it also supports iOS-enabled devices and gives developers unparalleled access to users across both platforms.
★★★ | [ARFoundation](#ARFoundation) | Unity has always been at the forefront of handheld AR development and we’ve supported ARCore and ARKit from the start. But with AR Foundation and the software architecture it leverages, we can now offer developers a common API which supports core functionality for ARCore, ARKit, and future platforms.
★★☆ | [Vuforia](#Vuforia) |Vuforia is one of the most popular platforms to help you work with augmented reality development. It implements the following functionalities: recognition of the different types of visual objects (a box, cylinder, plane), text and environments recognition, VuMark (a combination of picture and QR-code). Also, using Vuforia Object Scanner, you can scan and create object targets. The recognition process can be implemented using the database (local or cloud storage). Unity plugin is simple to integrate and very powerful.
★★☆ | [Wikitude](#Wikitude) | Wikitude is an SDK specifically designed for developing mobile AR apps and prototypes. The company was founded back in 2008 in Salzburg, Austria. When the Wikitude SDK was initially launched, the platform was designed with a core objective: to enable AR developers to create location-centric augmented reality experiences through the Wikitude World Browser app. Fast forward to 2012 and Wikitude repositioned its core technology offering by launching the Wikitude SDK with geolocation features, tracking, and image recognition all baked directly into the core platform.
★★☆ | [Kudan](#kudan) | Wikitude is an SDK specifically designed for developing mobile AR apps and prototypes. The company was founded back in 2008 in Salzburg, Austria. When the Wikitude SDK was initially launched, the platform was designed with a core objective: to enable AR developers to create location-centric augmented reality experiences through the Wikitude World Browser app. Fast forward to 2012 and Wikitude repositioned its core technology offering by launching the Wikitude SDK with geolocation features, tracking, and image recognition all baked directly into the core platform.
★★☆ | [MaxST](#maxst) | Maxst specializes in providing AR software solutions for a variety of industries including fashion, publication, travel & leisure, and advertising. The company launched their first Augmented Reality SDK in South Korea. Later it created and introduced the AR Virtual Fitting System which gave shoppers an opportunity to try on clothing and apparel before making a purchase. Other Maxst products and services include image processing, Augmented Reality tours and AR games. Downside: Maxst, doesn’t offer Geolocation, Cloud recognition or SLAM support.
★★☆ | [ARToolKit](#artoolkit) | ARtoolKIt is an open source tracking library for augmented reality. ARtoolKit implements the following functionalities: Single-camera or stereo-camera camera position/orientation tracking, Tracking of simple black squares, Tracking of planar images, Camera calibration and optical stereo calibration, Plugins for Unity and OpenSceneGraph, Optical head-mounted display support, Free and open source software, Fast enough for real time AR applications.
★☆☆ | [EasyAR](#easyar) | EasyAR is offered in both a free basic version and a Pro version at a $499 licensing fee that starts from 100 uses per day. Winner of the 2016 World Augmented Reality Expo’s Best Software Award, EasyAR is capable of simultaneously recognizing and tracking multiple 3D objects in real time. Available in versions for iOS and Android, EasyAR can be used with both PCs and mobile devices. Other benefits include the absence of watermarks and no irritating time limitations. A possible downside: some users, have reported difficulties with EasyAR’s image stability.
★☆☆ | [8th Wall](#8th-Wall) | True Web AR. Create rich augmented reality experiences that work on every mobile device.
★★★ | [Lumin (Magic Leap)](#Lumin-(Magic-Leap)) | Create new worlds within our world. Trailblazers, storytellers and dream chasers — new worlds are yours for the making. Become a Magic Leap creator and start pioneering the uncharted frontier of spatial computing.
★★★ | [MixedReality Toolkit (HoloLens)](#MixedReality-Toolkit-(HoloLens)) | MRTK-Unity provides a set of foundational components and features to accelerate MR app development in Unity. The latest Release of MRTK (V2) supports HoloLens/HoloLens 2, Windows Mixed Reality, and OpenVR platforms. Provides the basic building blocks for unity development on HoloLens, Windows Mixed Reality, and OpenVR, Showcases UX best practices with UI controls that match Windows Mixed Reality and HoloLens Shell, Enables rapid prototyping via in-editor simulation that allows you to see changes immediately, Is extensible. Provides devs ability to swap out core components and extend the framework.

## ARKIT
- [Apple ARKit Documentation](https://developer.apple.com/documentation/arkit)
- [A curated list of awesome ARKit projects and resources. ](https://github.com/olucurious/Awesome-ARKit)


## ARCore
- [Google ARCore SDK for Unity](https://github.com/google-ar/arcore-unity-sdk)
- [Unity API Reference for ARCore](https://developers.google.com/ar/reference/unity/)
- [ARCore for All](https://github.com/tomthecarrot/arcore-for-all)


## ARFoundation
- [ARFoundation Docs](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@1.0/manual/index.html)
- [Example content for Unity projects based on AR Foundation](https://github.com/Unity-Technologies/arfoundation-samples)


## Vuforia
- [Vuforia Documentation](https://library.vuforia.com/articles/Training/getting-started-with-vuforia-in-unity.html)
- [Quick demo Augmented Reality application with Vuforia in Unity platform](https://github.com/jkredzvr/Unity-Vuforia-Tutorial)


## Wikitude
- [Wikitude examples](https://github.com/Wikitude)
- [Wikitude Documentation](https://www.wikitude.com/external/doc/documentation/latest/unity/)


## Kudan
- [Kudan Github](https://github.com/kudan-eu)


## MaxST
- [MaxstARSDK Unity extra samples](https://github.com/maxstdev/MaxstARSDK_Unity_Sample)


## ARToolKit
- [ARToolKit for Unity v5.x](https://github.com/artoolkit/arunity5)


## EasyAR
- [Download Easy AR](https://www.easyar.com/)
- [EasyAr Documentation](https://www.easyar.com/doc/)


## 8th Wall
- [8th Wall Tutorials](https://www.8thwall.com/tutorials.html)
- [8th Wall Github](https://github.com/8thwall/)
- [8th Wall Docs](https://docs.8thwall.com/)


## Lumin (Magic Leap)
- [Download Lumin SDK](https://creator.magicleap.com/downloads/lumin-sdk)
- [Magic Leap awesome resources ](https://github.com/exokitxr/awesome-magicleap)
- [
Magic Leap Developer Resources](https://github.com/MagicLeapDevs/MagicLeapDevResources)


## MixedReality Toolkit (HoloLens)
- [MixedRealityToolkit-Unity](https://github.com/Microsoft/MixedRealityToolkit-Unity)
- [A Unity hololens app to detect faces and display their attributes](https://github.com/UoA-eResearch/hololens_facial_recognition)
- [A Unity library for estimating and replicating the current environment's lighting](https://github.com/microsoft/MRLightingTools-Unity)


# License
> Open for everyone to contribute and use.

Licensed under the [MIT License](https://opensource.org/licenses/MIT).