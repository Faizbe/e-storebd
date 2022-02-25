

## 1. Sign-in using a Google account
Watch this video to learn about google sign in: [Google SignIn with Flutter](https://www.youtube.com/watch?v=Q00Foa8CiDk&t=833s)

### Apple firebase setup:

Follow the video carefully for ios setup.

### Android firebase setup:

For SSH1 fingerprint: from your terminal, go to the "android" folder

```
$ cd android
$ ./gradlew signingReport
```

Before doing that, make sure that Java Environment is already set up on your computer. 
<img style="align:center;" width="100%" height="auto" src="screenshots/SHA1.png" />
Copy & paste this SHA1 key to the firebase insert box befire generating the "google-services.json" file.

## Packages used in "pubspec.yaml":
```
  # For accessing FontAwesome icons
  font_awesome_flutter: ^9.2.0
  # For swiping effects
  flutter_swiper_null_safety: ^1.0.2
  # For signing in with Gmail account
  google_sign_in: ^5.2.1
  # For Statementing
  get: ^4.3.8
```

## 5. Dashboard
Charts are drawn using "syncfusion_flutter_charts" dart package. [Documentation](https://help.syncfusion.com/flutter/cartesian-charts/getting-started)

