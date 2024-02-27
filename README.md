<p align="center">
  <h1 align="center">Neumorphism UI Design</h1>
  <h3 align="center">Signin | Signup | OTP Confrim | Deshbord | Toast</h3>
  
<div align="center">

<a href="https://t.me/banrossyn" target="_blank"><img src="https://img.shields.io/badge/Telegram-%40banrossyn-28a8ea"></a>
<a href="https://wa.me/+919694260426/" target="_blank"><img src="https://img.shields.io/badge/whatsapp-%40+919694260426-28a8ea"></a>
<a href="https://www.linkedin.com/in/banrossyn/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-banrossyn-informational"></a>
<a href="mailto:banrossyn@gmail.com"><img src="https://img.shields.io/badge/Email-banrossyn%40gmail.com-blue"></a>

</div>

# 
![nemourphism design](https://user-images.githubusercontent.com/97843190/174239916-c71ebce6-e902-46cf-aa65-f993041a527c.jpg)

# Build Neumorphism designs in Android.

Dependency

Add this in your root `settings.gradle` file (**not** your module `build.gradle` file):

```gradle

dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.PREFER_SETTINGS)
    repositories {
    ....
        maven { url "https://jitpack.io" }
        ...
    }
}
```

Then, add the library to your module `build.gradle`
```gradle
dependencies {
    implementation 'com.github.fornewid:neumorphism:{latest_version}'
}
```

## Features
- Draw a shadow background on widgets for Neumorphism.
  Supported on the following widgets:
  - ViewGroup: CardView
  - View: Button, FloatingActionButton, ImageView
- Draw a text shadow on TextView for Neumorphism.
