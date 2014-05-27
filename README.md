Sneer API - 5 Minute Tutorial
====

This project is a simple game of Rock/Paper/Scissors almost ready to play online.

[Image]

In this tutorial, we are going to add the missing code to use the Sneer cloud.

  - Clone this project using git and import it into the Android Development Toolkit.

  - Create a libs folder in the root folder of your project. Download the latest snapi-no-deps.jar from here[link] and add it to the libs folder.

  - Run the project. The app itself will tell you what to do to make it work, so you can stop reading here and just use the app. :)

  - To access the cloud:

```JAVA
Cloud cloud = new Cloud();
```

  - To challenge a friend for a match:

```JAVA
cloud.pub...
```

  - To listen to challenges from friends:

```JAVA
cloud.sub…
```

  - etc.
