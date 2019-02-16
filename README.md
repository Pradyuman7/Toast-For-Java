# Toast-For-Java

<p align="center">
  <img width="250" height="250" src="https://user-images.githubusercontent.com/41565823/52897273-dd777f00-31d2-11e9-93e3-c30d8571e5d3.png">
</p>

<p align="center">
  A Java class that can be used for :bread: like popup messages in simple Java applications.
</p> 

## Usage

```java
String toastMsg = "This is the toast message";
int toastMsgTime = 3500; //3.5 seconds
int fadeInTime = 500; //0.5 seconds
int fadeOutTime= 500; //0.5 seconds
Toast.makeText(primarystage, toastMsg, toastMsgTime, fadeInTime, fadeOutTime);
```

Also, here `PrimaryStage` is the stage where the toast message will be attached. If you have only one stage then primaryStage is the parameter of the method start of your application. 
[Read more about this here](docs.oracle.com/javase/8/javafx/api/javafx/stage/Stage.html).

## How to import in Project

Simply go to release section, download the Java class or just copy paste the source code from here in your Javafx application.
