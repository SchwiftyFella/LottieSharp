# LottieCore


| ![Logo](https://raw.githubusercontent.com/ascora/LottieSharp/master/Images/lottie_sharp-128.png) |.NET Core (WPF) port of Lottie# (https://github.com/ascora/LottieSharp)  |
|--|--|

**Usage**

```PM> Install-Package LottieCore -Version 1.0.0```

- Install from nuget: [LottieCore](https://www.nuget.org/packages/LottieCore/);
- Import into your xaml the library

    xmlns:lottieSharp="clr-namespace:LottieSharp;assembly=LottieSharp"

- Now you can include the control in your layout
```xml
<lottieSharp:LottieAnimationView 
    x:Name="LottieAnimationView" 
    DefaultCacheStrategy="None" 
    FileName="Assets/Spider Loader.json" AutoPlay="True" 
    VerticalAlignment="Center" 
    HorizontalAlignment="Center"/>
```
The FileName property points to an After Effects animation file. You can write the filename in xaml like shown or bind to a property in your viewmodel.

The AutoPlay property indicates if the animation starts when the usercontrol is loaded.

There are many free animations at: [LottieFiles](https://www.lottiefiles.com/)
