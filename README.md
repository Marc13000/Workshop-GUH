# Workshop-GUH

# Prerequisites

- You can download the latest version of our IDEs with free educational licenses. Information about these can be found here: [JetBrains Educational Licenses](https://www.jetbrains.com/community/education/#students)
- Setup Github Student Developers Pack along with a Github account for access to Github copilot (In IDE AI): [GitHub Student](https://education.github.com/pack)

- ## Install JetBrains Toolbox app.
The Toolbox app provides an easy upgrade path to new versions as they become available. You can also manage multiple versions of JetBrains products, working with stable releases while exploring experimental ones.
- ## Log into Toolbox with your JetBrains account.
- ## Click Install next to the Fleet icon.
- ## Check your version of the JDK.
Currently, Fleet requires the Java Development Kit 17.0 and later to be installed for Kotlin Multiplatform development. To do that, run the following command in your command-line tool:
```
java -version
```
- ## Install Android Studio and Xcode so that you can run your app on Android and iOS simulators.
Install kdoctor to test setup:
```
brew install kdoctor
kdoctor
```
To ensure the installation is complete, open both Android Studio and Xcode at least once. It may also be necessary to reopen Android Studio and Xcode following an update.

Note: You can choose to just run and test on one of these for the hackathon.

To run and debug Android applications on the current machine, you'll need to create a virtual device in Android Studio.

If you experience problems running an iOS project, verify that you can run the embedded project in the iosApp folder from Xcode on this destination. Then restart Fleet.
