<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109402767-733f5c00-790d-11eb-9d2d-f14149d75d08.png">
  <br />
  Chrome OS Guide
</h1>

#### A guide on setting up your Chrome OS with all the essential Applications, Tools, and Games to make your experience with Chrome OS great! 

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

# Table of Contents

1. [Getting Started](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#getting-started)

2. [Getting Software](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#getting-software)

3. [Gaming](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#gaming)

4. [Setting up a macOS workspace](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#setting-up-a-macos-workspace)

5. [Setting up a Windows 10 Workspace](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#setting-up-a-windows-10-workspace)

6. [Android Development](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#android-development)

7. [Flutter Development](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#flutter-development)

8. [Machine Learning](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#machine-learning)


# Getting Started

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109402979-31171a00-790f-11eb-8c43-4c0e4a6cc923.png">
  <br />
  Chrome OS Desktop
</p>

[Chrome OS Features](https://www.google.com/chromebook/chrome-os/) is a Linux-based operating system developed by Google, with an emphasis on simplicity and security. As a cloud-based operating system, it uses the Chrome web browser as its primary user interface. In 2016, access to Android apps via the Google Play Store available on select Chrome OS devices. Finally, in 2018 Linux apps are now running natively on select devices via [Project Crostini](https://chromeos.dev/en/linux).

[Chrome OS Enterprise](https://chromeenterprise.google/os/)

[Chrome OS VM for Chromium developers](https://chromium.googlesource.com/chromiumos/docs/+/HEAD/cros_vm.md)

[Using LXD(Linux container manager) on your Chromebook](https://ubuntu.com/blog/using-lxd-on-your-chromebook)

[Using VScode on Chrome OS](https://code.visualstudio.com/blogs/2020/12/03/chromebook-get-started)

[Chromebook Community - Google Support](https://support.google.com/chromebook/community?hl=en)

[Chrome OS Wiki](https://chromeos.fandom.com/wiki/Chrome_OS)

[Chromium OS](https://www.chromium.org/chromium-os) is an open-source project that aims to build an operating system that provides a fast, simple, and more secure computing experience for people who spend most of their time on the web.

[chromeOS.dev](https://chromeos.dev/) is the digital home for all things Chrome OS. Learn how to adapt and optimize your existing apps to work on Chrome OS, the success other companies have had doing so, how to use Chrome OS as your developer machine, and keep up-to-date with the latest on Chrome OS.

[Chrome Unboxed](https://chromeunboxed.com) is a great website for learning all things Google Chrome. Such as the news, updates, reviews and unboxings.

[Android Runtime for Chrome (ARC)](https://en.wikipedia.org/wiki/Google_App_Runtime_for_Chrome) is a compatibility layer and sandboxing technology for running Android applications on desktop and laptop computers in an isolated environment. It allows applications to be safely run from a web browser, independent of Chrome OS at near native speeds.

[CloudReady](https://www.neverware.com/) is a ChromeOS alternative built from the source available in ChromiumOS repositories developed by Neverware. Neverware was [acquired by Google in December 2020](https://arstechnica.com/gadgets/2020/12/google-acquired-neverware-makers-of-cloudready-chromeos-variant/).


# Getting Software

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

## Chrome WebStore

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109402771-75a1b600-790d-11eb-8971-7d5a8ee166e9.png">
 </p>

## Google Play Store

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109402773-776b7980-790d-11eb-9357-eb7ca1ecb8b4.png">
</p>

## Flatpaks

[Setting up Flatpaks for Chrome OS](https://www.flatpak.org/setup/Chrome%20OS/)https://www.flatpak.org/setup/Chrome%20OS/

[FlatHub](https://flathub.org/) is a build and distribution service for Flatpak applications.

[FlatHub Forum](https://discourse.flathub.org/)

**Open terminal and run:**

```sh
sudo apt install flatpak
```
```sh
flatpak --user remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/106686365-055a7b80-657f-11eb-9b58-1de28abe2e5b.png">
 </p>
 
## Snaps

[Snap Store](https://snapcraft.io/store) is a build and distribution service for Snap applications.

[Snapcraft Forum](https://forum.snapcraft.io/)

**Open terminal and run:**

```sh
sudo apt install libsquashfuse0 squashfuse fuse
```

```sh
sudo apt install snapd
```

```sh
sudo snap install 'app'
```

 <img src="https://user-images.githubusercontent.com/45159366/106686375-08ee0280-657f-11eb-9918-5385d8c09148.png">
 <img src="https://user-images.githubusercontent.com/45159366/106686378-0a1f2f80-657f-11eb-83aa-37ac96c7b032.png">
 
 
## AppImages

[AppImageHub](https://www.appimagehub.com) is a build and distribution service for AppImage applications.

[AppImage Manager](https://github.com/AppImageCrafters/appimage-manager) is a package manager for AppImages.

[AppImage Forum](https://discourse.appimage.org/)

**Open the terminal and run:**

```sh
chmod a+x Appname.AppImage
```
**Then:**
```sh
./Appname.AppImage
```
 <img src="https://user-images.githubusercontent.com/45159366/106686382-0b505c80-657f-11eb-9d74-9a94ec0d0693.png">
 
## Setting up GNOME Software Center

The [GNOME](https://www.gnome.org/) Software Center is similar to the Google Play Store but mainly developed for Linux desktops running the GNOME Desktop environment.

**Open Terminal and Run:**
```sh
sudo apt install gnome-software gnome-packagekit
```
 <img src="https://user-images.githubusercontent.com/45159366/107159312-fb03fd00-6943-11eb-933c-188617e63fd1.png">
 
## CrossOver Chrome® OS

[CrossOver Chrome OS](https://www.codeweavers.com/crossover#chromeos) let's you run Windows programs that are not available in the Google Play store alongside mobile apps. Scrap remote sessions with multiple users. Run utility software like Quicken and Microsoft Office, or DirectX games. Also, run games from your Steam library will run with CrossOver Chrome OS at native speeds. 

## Web Apps

[Google Workspace (formerly G Suite)](https://workspace.google.com/)
 
[Microsoft 365 with Office apps(formerly Office Online)](https://www.microsoft.com/en-us/microsoft-365/free-office-online-for-the-web)

[MATLAB Online](https://matlab.mathworks.com) allows to users to uilitize MATLAB and Simulink through a web browser such as Google Chrome.

[Jitsi Meet](https://jitsi.org/jitsi-meet/) is a fully encrypted, 100% open source video conferencing solution.

[Cisco Webex Web App](https://help.webex.com/en-us/n1pxgbz/Cisco-Webex-Web-App) is the web based verison of Cisco Webex video conferencing solution. 

[Apple Music(Web)](https://music.apple.com/) is the web app version of Apple Music that runs in Safari, Google Chrome and Mozilla Firefox.

[Adobe Lighroom Online photo editor](https://lightroom.adobe.com) is an online web version of Adobe Photoshop Lightroom. Adobe account required to sign-in to app.

[Adobe Spark(Web)](https://spark.adobe.com) is an applications let you make cool Social Graphics, Short Videos, and Web Pages. Adobe account required to sign-in to app.

[Photopea](https://www.photopea.com/) is an advanced online image editor supporting PSD, XCF, Sketch, XD and CDR formats. (Adobe Photoshop, GIMP, Sketch App, Adobe XD, CorelDRAW).

[GitHub](https://github.com/) provides hosting for software development version control using Git. It offers all of the distributed version control and source code management functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.Learn more about all other integrations with Azure.

[GitLab](https://about.gitlab.com/) is a web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license, developed by GitLab Inc.

[Bitbucket](https://bitbucket.org/) is a web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems. Bitbucket offers both commercial plans and free accounts. It offers free accounts with an unlimited number of private repositories. Bitbucket integrates with other Atlassian software like Jira, HipChat, Confluence and Bamboo.

# Gaming

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

## Game Streaming

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) use the **Chromebook version** to play all your games in Google Chrome or any Chromium-based web browser such as Brave, Vivaldi, and Microsoft Edge. Also, available as a Electron Desktop App in the [Snap store Geforce NOW](https://snapcraft.io/geforcenow).
 <img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig. 

<img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms.

[Xbox Project xCloud](https://www.xbox.com/en-US/xbox-game-streaming/project-xcloud) is Microsoft's cloud-based Xbox game-streaming technology **(currently in Beta)**. **Play games like Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of Thieves, Cuphead, Red Dead Redemption 2, and 100+ other games on your mobile device or Chrome web browser**. Microsoft's Xbox Project xCloud does require an [Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) subscription.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

## Steam

Get Steam with [CrossOver Chrome OS](https://www.codeweavers.com/crossover#chromeos) or [Steam Flatpak](https://flathub.org/apps/details/com.valvesoftware.Steam).
 
 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">
 

# Setting up a macOS workspace

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

**REQUIREMENTS**

The recommended hardware specifications are Intel Core i5 and i7, 16 GB Memory, and 128/256 GB HDD/SSD.

 <img src="https://user-images.githubusercontent.com/45159366/109562469-487f1000-7a93-11eb-8f62-760955f0fc61.png">

   - Chrome OS 85 or later
   - QEMU > 2.11.1
   - A CPU with Intel VT-x / AMD SVM support is required
   - A CPU with SSE4.1 support is required for >= macOS Sierra
   - A CPU with AVX2 support is required for >= macOS Mojave
   - Internet access for the installation process

**Open the terminal and run: **
```sh
sudo apt install qemu uml-utilities virt-manager dmg2img git wget libguestfs-tools p7zip
```

[OpenCore for macOS](https://dortania.github.io/OpenCore-Install-Guide/)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107092246-15a96b00-67b8-11eb-91fb-27494c7f1d4f.jpg">
 </p>
 
 
# Setting up a Windows 10 workspace

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

## Using Parallels Desktop software to create a Windows virtual machine

**REQUIREMENTS**

 <img src="https://user-images.githubusercontent.com/45159366/109562467-474de300-7a93-11eb-81b5-1674257044a6.png">

[Parallels®️ Desktop for Chromebook Enterprise](https://www.parallels.com/products/desktop/chrome/)

[Set up Parallels Desktop for Chromebook Enterprise and Education](https://support.google.com/chrome/a/answer/10044480?hl=en)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110054992-fb0fd680-7d10-11eb-9a94-16c266b2491a.png">
 <br />
  Parallels®️ Desktop for Chromebook Enterprise
</p>


## Using GNOME Boxes to create a Windows virtual machine

**REQUIREMENTS**

   - Chrome OS 85 or later
   - QEMU > 2.11.1
   - A CPU with Intel VT-x / AMD SVM support is required
   - [WindowsGuestDrivers/Download Drivers - KVM](https://www.linux-kvm.org/page/WindowsGuestDrivers/Download_Drivers)
   - Internet access for the installation process

**Open the terminal and run:**
```sh
sudo apt install qemu-kvm libvirt-clients libvirt-daemon-system bridge-utils virtinst libvirt-daemon nano -y

sudo apt install qemu uml-utilities virt-manager gnome-boxes
```
**Then:**
```sh
cd /etc/libvirt

sudo nano qemu.conf

xhost +
```

[GNOME Boxes](https://wiki.gnome.org/Apps/Boxes) is an application that gives you access to virtual machines, running locally or remotely. It also allows you to connect to the display of a remote computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107092256-1cd07900-67b8-11eb-9ae9-f389045dad26.png">
 <img src="https://user-images.githubusercontent.com/45159366/107093639-72a62080-67ba-11eb-8d88-477929a5516b.png">
 <img src="https://user-images.githubusercontent.com/45159366/107092270-222dc380-67b8-11eb-82cc-d41e9e8a39e0.png">
</p>

# Android Development

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

[Android Studio](https://developer.android.com/studio/) is the development suite for Google's Android Operating System(OS). It's built on [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/) software and designed specifically for Android development. It is available for download on Windows, macOS and Linux.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637349-29530380-743f-11eb-8c61-549064b7d80b.png">
</p>

[LineageOS](https://lineageos.org/) is a free and open-source operating system for various devices, based on the Android mobile platform.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108647222-f0ca1e80-746c-11eb-8e55-0e9808bb24fc.png">
</p>

[Anbox](https://anbox.io/) is an application that provides a container-based approach to boot a full Android system on a regular GNU/Linux system like Ubuntu, Debian Fedora, and openSUSE.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637384-34a62f00-743f-11eb-9edc-83267a673b38.png">
</p>

[Anbox Cloud](https://anbox-cloud.io/) is the mobile cloud computing platform delivered by Canonical. Run Android in the cloud, at high scale and on any type of hardware.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637983-efcfc780-7441-11eb-80fc-b3d1612593ca.png">
</p>

[Genymotion](https://www.genymotion.com/) is a very fast Android emulator. The program itself is based on VirtualBox and is known for its effectively fast speed and is usefulness for running Android apps on a Windows, Mac and Linux desktop.

**Desktop**

Local virtual devices with high performances.

 - Emulate a wide range of virtual device configurations (Android versions, screen size, hardware capacities, etc.)
 - Simulate multiple scenarios thanks to our full set of hardware sensors (GPS, network, multitouch, etc.)
 - Cross-platform: Windows, Mac and Linux
 - Manipulate easily with ADB
 - $412 per year for employees in a company (BUSINESS). All features, advanced support.
 - $136 per year for freelancers (INDIE). All features, best effort support.
 - [Free](https://www.genymotion.com/download/) for personal use only (learning & entertainment). Limited features, no support.
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637388-37a11f80-743f-11eb-9f37-6e22e1172f2d.png">
</p>

[Scrcpy](https://github.com/Genymobile/scrcpy) is an application by Genymotion that provides display and control of Android devices connected on USB (or over TCP/IP). It does not require any root access and works on GNU/Linux, Windows and macOS. The Android device requires at least API 21 (Android 5.0).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637389-396ae300-743f-11eb-971a-f5b554033552.jpg">
</p>

# Flutter Development

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719686-0abbaa00-fb39-11ea-978d-91e55844dd7a.png">
</p>

[Flutter](https://flutter.dev/) is Google's UI toolkit for crafting beautiful, natively compiled applications for mobile(Andorid and iOS), web, and desktop(Windows, MacOS, Linux, and Google Fuchsia) from a single codebase. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.

## Flutter Learning Resources

[Flutter Gems](https://fluttergems.dev) is a curated package guide for Flutter which functionally categorizes some of the most useful and popular flutter packages available on pub.dev Flutter Gems A Flutter package landscape guide comprising 1500+ neatly categorized useful and popular packages.

[Dart](https://dart.dev/) is an open-source, scalable programming language, with robust libraries and runtimes, for building web, server, and mobile apps using the Flutter framework.

[Flutter documentation](https://flutter.dev/docs)

[Style Guide for Flutter](https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo)

[Creating your first Flutter app](https://flutter.dev/docs/get-started/codelab)

[Build and release an Android app using Flutter](https://flutter.dev/docs/deployment/android)

[Flutter Tools & techniques](https://flutter.dev/docs/development/tools)

[Dart and Flutter: The Complete Developer's Guide on Udemy](https://www.udemy.com/course/dart-and-flutter-the-complete-developers-guide/)

[Creating an Interactive Story with Flutter on Coursera](https://www.coursera.org/projects/story-creating-flutter)

[Flutter for Beginners course on Pluralsight](https://www.pluralsight.com/courses/flutter-getting-started)

[Flutter Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/flutter)

[The Complete Flutter App Development Bootcamp with Dart by App Brewery](https://www.appbrewery.co/p/flutter-development-bootcamp-with-dart)

[Adding Firebase to your Flutter app](https://firebase.google.com/docs/flutter/setup)

[Using Firebase and Firestore with Flutter](https://flutter.dev/docs/development/data-and-backend/firebase)

[Fuchsia Project](https://fuchsia.dev/)

[Getting Started with Fuchsia](https://fuchsia.dev/fuchsia-src/get-started)

[Fuchsia Reference](https://fuchsia.dev/reference)

[Contributing to Fuchsia](https://fuchsia.dev/fuchsia-src/CONTRIBUTING)

## Flutter Tools

[Firebase](https://firebase.google.com/) is a Backend-as-a-Service (BaaS) app development platform that provides hosted backend services such as a realtime database, cloud storage, authentication, crash reporting, machine learning, remote configuration, and hosting for your static files.

[FlutterFire](https://firebase.flutter.dev/) is a set of [Flutter plugins](https://flutter.io/platform-plugins/) that enable Flutter apps to use [Firebase](https://firebase.google.com/) services. You can follow an example that shows how to use these plugins in the [Firebase for Flutter](https://codelabs.developers.google.com/codelabs/flutter-firebase/index.html#0) codelab.

[FlutterBoost](https://github.com/alibaba/flutter_boost) is a Flutter plugin which enables hybrid integration of Flutter for your existing native apps with minimum efforts.

[Go-flutter](https://github.com/go-flutter-desktop/go-flutter) is a package that brings Flutter to the desktop. project implements the [Flutter's Embedding API](https://github.com/flutter/flutter/wiki/Custom-Flutter-Engine-Embedders) using a single code base that runs on Windows, macOS, and Linux. For rendering, [GLFW](https://github.com/go-gl/glfw) fits the job because it provides the right abstractions over the OpenGL's Buffer/Mouse/Keyboard for each platform.

[Appwrite](https://appwrite.io/) is a secure end-to-end backend server for Web, Mobile, and Flutter developers that is packaged as a set of Docker containers for easy deployment.

[Fluro](https://github.com/theyakka/fluro) is a Flutter routing library that adds flexible routing options like wildcards, named parameters and clear route definitions.

[Flame](https://flame-engine.org/) is a minimalistic Flutter game engine.
 

# Machine Learning

[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109402792-979b3880-790d-11eb-8d70-90b9b170beb0.jpeg">
 </p>
 
 **The recommended hardware specifications are Intel Core i5 and i7, 16 GB Memory, and 128/256 GB HDD/SSD.**
 <img src="https://user-images.githubusercontent.com/45159366/109562469-487f1000-7a93-11eb-8f62-760955f0fc61.png">

[TensorFlow Lite](https://www.tensorflow.org/lite/guide) is a set of tools to help developers run TensorFlow models on mobile, embedded, and IoT devices. It enables on-device machine learning inference with low latency and a small binary size.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j. 

[Caffe](https://github.com/BVLC/caffe) is a deep learning framework made with expression, speed, and modularity in mind. It is developed by Berkeley AI Research (BAIR)/The Berkeley Vision and Learning Center (BVLC) and community contributors.

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[nGraph](https://github.com/NervanaSystems/ngraph) is an open source C++ library, compiler and runtime for Deep Learning. The nGraph Compiler aims to accelerate developing AI workloads using any deep learning framework and deploying to a variety of hardware targets.It provides the freedom, performance, and ease-of-use to AI developers.

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

[Cluster Manager for Apache Kafka(CMAK)](https://github.com/yahoo/CMAK) is a tool for managing [Apache Kafka](https://kafka.apache.org/) clusters.

[BigDL](https://bigdl-project.github.io/) is a distributed deep learning library for Apache Spark. With BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.

[Eclipse Deeplearning4J (DL4J)](https://deeplearning4j.konduit.ai/) is a set of projects intended to support all the needs of a JVM-based(Scala, Kotlin, Clojure, and Groovy) deep learning application. This means starting with the raw data, loading and preprocessing it from wherever and whatever format it is in to building and tuning a wide variety of simple and complex deep learning networks.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

 ## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Chrome-OS-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Chrome-OS-Guide/blob/main/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
