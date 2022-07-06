# Build & Run

!> **Important** <br>
All below steps are must be followed to build and run application

## Download Project

Download and find the your project folder, use your preferred IDE **(Android Studio / Visual Studio Code / IntelliJ IDEA)** to run the project.

![image info](./images/build_img1.png)


## Get Dependencies

After you loaded project successfully, run the following command in the terminal to install all the dependencies listed in the pubspec.yaml file in the project's root directory or just click on Pub get in pubspec.yaml file if you don't want to use command.
```
flutter pub get 
```

!> **Important** <br>
All below steps are must be followed to build and run application

![image info](./images/build_img2.png)


## Build and Run App

Locate the main Android Studio toolbar. <br>
In the **target selector**, select an Android device for running the app. If none are listed as available, select **Tools > Android > AVD Manager** and create one there. For details, see [Managing AVDs](https://developer.android.com/studio/run/managing-avds).
Click the run icon in the toolbar, or invoke the menu item **Run > Run**.

![image info](./images/build_img3.png)

After the app build completes, you’ll see the app on your device.

If you don’t use Android Studio or IntelliJ you can use the command line to run your application using the following command

!> **Important** <br>
Below step requires flutter path to be set in your Environment variables. See https://flutter.dev/docs/get-started/install/windows
```
flutter run
```

You will see below like screen after you have build your app successfully

![image info](./images/build_img4.png)


### Try hot reload

Flutter offers a fast development cycle with Stateful Hot Reload, the ability to reload the code of a live running app without restarting or losing app state. Make a change to app source, tell your IDE or command-line tool that you want to hot reload, and see the change in your simulator, emulator, or device.

!> **Important** <br>
Do not stop your app. let your app run.