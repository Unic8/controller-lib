# controller-lib
This Android-library should help you to show a common game controller on the screen and react to its user input

At the moment the only supported Buttons are the Directionbuttons (8-way) and the Action-Input of a user, such as on the Playstation- or the XBox-Controller

This library uses VectorDrawable and has downwards support down to API Level 7 (using MrVector)

## Dependencies:
* [MrVector](https://github.com/telly/MrVector) in Version 0.2.0
* appcompat
 
## How to add to your project:
To use this library, add a new repository to your repositories, setup in gradle:
```groovy
allprojects {
    repositories {
        jcenter()
        ...
        maven {
            url "https://jitpack.io"
        }
        ...
    }
}
```
then add this library as a dependency

```groovy
compile 'com.github.Unic8:controller-lib:0.0.1'
```

# Screenshot
![screenshot_2015-03-21-17-55-19](https://cloud.githubusercontent.com/assets/2174386/6766014/971adf68-cff5-11e4-9f7d-530251462886.png)



