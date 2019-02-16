# Toast-For-Java
A java class that can be used for Toast like popup messages in simple Java applications

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
