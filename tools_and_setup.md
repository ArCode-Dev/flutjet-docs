# Tools & Setup

## Introduction to Flutter
Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for [mobile](https://docs.flutter.dev/), [web](https://flutter.dev/multi-platform/web), and [desktop](https://flutter.dev/multi-platform/desktop) from a single codebase. It is very easy to learn and currently it is getting more and more popular. With this blog post, you will learn some basic stuff about Flutter and after reading it, you will be able to create a simple application using this technology.

[Click here](https://flutter.dev/) to check out more details about flutter.

## Prerequisite

Flutter & Dart [SDK](https://docs.flutter.dev/get-started/install)<br>
Anyone IDE [Android Studio](https://developer.android.com/studio) (Recommended), [Visual Studio Code](https://code.visualstudio.com/) or [IntelliJ IDEA](https://www.jetbrains.com/idea/)<br>

To edit this project you must have Flutter and Dart installed and configured successfully on your computer.
Set up your editor - Install the [Flutter and Dart plugins](https://docs.flutter.dev/get-started/editor?tab=androidstudio).

If you have got Android SDK installed and configured, to install Flutter you only need to:
1. Download Flutter SDK from official website and extract it.
2. Add path to previously extracted SDK to your PATH variable
3. Run flutter doctor tool to check if everything is configured correctly.
4. All above steps are mentioned here: https://flutter.dev/docs/get-started/install/



## Android Studio – Windows​

Download Android Studio - https://developer.android.com/studio/ <br>
Get the Flutter SDK - https://flutter.dev/docs/get-started/install <br>
Learn more about Android Studio - https://developer.android.com/studio/intro/ <br>

### Step 1 : Get the Flutter SDK

- Download the following installation bundle to get the latest stable release of the Flutter SDK:

- Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, C:\src\flutter; do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges).

### Step 2 : Update your path

If you wish to run Flutter commands in the regular Windows console, take these steps to add Flutter to the PATH environment variable: From the Start search bar, enter ‘env’ and select **Edit environment variables for your account**. Under **User variables** check if there is an entry called **Path:**

If the entry exists, append the full path to **flutter\bin** using ; as a separator from existing values. <br>
If the entry doesn’t exist, create a new user variable named Path with the full path to **flutter\bin** as its value.

?> **Info** <br>
Note that you have to close and reopen any existing console windows for these changes to take effect.

**You are now ready to run Flutter commands in the Flutter Console!**




## Android Studio – Mac OS

Download Android Studio - https://developer.android.com/studio/<br>
Download Xcode - https://apps.apple.com/us/app/xcode/id497799835?mt=12<br>
Get the Flutter SDK - https://flutter.dev/docs/get-started/install<br>
Learn more about Android Studio - https://developer.android.com/studio/intro/<br>

### Step 1 : Get the Flutter SDK

Download the following installation bundle to get the latest stable release of the Flutter SDK:<br>
Download SDK and extract downloaded file, just double click on that. and just copy extracted folder and paste it to your desired location (for example, Documents\flutter).

### Step 2 : Update your path

!> Warning
Path variable needs to be updated to access “flutter” command from terminal. you can just update path variable for current terminal window only. and if you want to access flutter commands from anywhere in terminal, we need to update SDK path permanently.

To update PATH variable, we need to open terminal.

To update PATH variable for current terminal window only, then enter this command 
```export PATH="$PATH:`pwd`/flutter/bin"```
 and hit enter key.

To update PATH variable permanently, then Open or create **.bash_profile** file. to open or create that file, then enter 
```sudo open -e $HOME/.bash_profile```
 and hit enter key.

Append below line to bash_profile file at bottom of all other content. ```export PATH="$PATH:[PATH_TO_FLUTTER_GIT_DIRECTORY]/flutter/bin"``` as [PATH_TO_FLUTTER_GIT_DIRECTORY] is actual path of SDK folder.

Run this command on terminal ```source $HOME/.bash_profile``` to refresh PATH variables.

Then check whether our SDK is successfully installed or not.

**You are now ready to run Flutter commands in the Flutter Console!**

Run ```flutter doctor``` into terminal, If you are getting check list of flutter sdk requirements, it means SDK is successfully installed on your machine. and you can start building flutter apps on your machine.

**If you find any issue during environment setup in macos, please go online [Click here](https://docs.flutter.dev/get-started/install/macos)**



## Android Studio – Linux​​

Download Android Studio - https://developer.android.com/studio<br>
Get the Flutter SDK - https://flutter.dev/docs/get-started/install/linux<br>
Learn more about Android Studio - https://developer.android.com/studio/intro/<br>

### Step 1 : Get the Flutter SDK

Download the following installation bundle to get the latest stable release of the Flutter SDK: <br>
Download SDK and extract downloaded file, just double click on that. and just copy extracted folder and paste it to your desired location (for example, Documents\flutter).

### Step 2 : Update your path

!> Warning
Path variable needs to be updated to access “flutter” command from terminal. you can just update path variable for current terminal window only. and if you want to access flutter commands from anywhere in terminal, we need to update SDK path permanently.


You’ll probably want to update this variable permanently, so you can run flutter commands in any terminal session. To update PATH variable, we need to open terminal.
```
export PATH="$PATH:[PATH_TO_FLUTTER_GIT_DIRECTORY]/flutter/bin"
```

Run ```source $HOME/.``` to refresh the current window, or open a new terminal window to automatically source the file.
Verify that the ```flutter/bin``` directory is now in your PATH by running:

```
echo $PATH
```

Verify that the flutter command is available by running:

```
which flutter
```

**You are now ready to run Flutter commands in the Flutter Console!**
