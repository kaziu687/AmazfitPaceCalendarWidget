[![latest release](https://img.shields.io/badge/latest%20release-v1.5-green.svg?style=flat-square)](https://github.com/GreatApo/AmazfitPaceCalendarWidget/releases/latest)

# Amazfit Pace Calendar Widget
![Amazfit Pace Calendar Widget Banner](other%20files/amazfit-calendar-widget.png)

After [Quinny899](https://github.com/KieronQuinn)'s excellent work, we are able to make widget/apps!
So, here is the first Calendar Widget for our Amazfit Pace/Stratos!



### Features
- This is a Pace/Stratos Widget
- Long press for settings
- Navigate between months (Swipe / Buttons)
- Refresh to current date
- Select calendar colors
- Show/Hide year number
- Select Sunday or Monday for 1st week day
- Vibration on button touches
- Supported languages: English, Chinese, French, German, Greek, Hungarian, Italian, Japanese, Portuguese, Russian, Slovak, Spanish



### Download

Get a ready to use binary
 - From our [XDA topic](https://forum.xda-developers.com/smartwatch/amazfit/app-widget-calendar-pace-t3751889)
 - From our [Github Releases](https://github.com/GreatApo/AmazfitPaceCalendarWidget/releases/latest)

Or if you are hardcore, compile the source code with Android Studio.



### Installation
To install this widget, you will need a PC with the ADB installed. Connect your Amazfit on your PC and fire up a terminal.

```shell
adb uninstall com.dinodevs.pacecalendarwidget
adb install -r PaceCalendarWidget.apk
adb shell am force-stop com.huami.watch.launcher
```



### Screenshots (Version 1.5)
![Amazfit Pace Calendar Widget v1.5](other%20files/com.dinodevs.pacecalendarwidget-1.3.png)
![Amazfit Pace Calendar Widget v1.5](other%20files/com.dinodevs.pacecalendarwidget-1.3-settings.png)



### Thanks to the Developers

This porject was made posible by:

 - GreatApo - *Widget Creator* - [ [Github](https://github.com/GreatApo) | [XDA](https://forum.xda-developers.com/member.php?u=3668555) ]
 - Quinny899 - *Widget Example Creator / Springboard Settings Creator* - [ [Github](https://github.com/KieronQuinn) | [XDA](https://forum.xda-developers.com/member.php?u=3563640) ]
 - XDA developers community (testers, translators, developers)

Some more links:

 - GreatApo's [Amazfit Pace Calendar Widget - XDA topic](https://forum.xda-developers.com/smartwatch/amazfit/app-widget-calendar-pace-t3751889)
 - Quinny's [Springboard Settings - XDA topic](https://forum.xda-developers.com/smartwatch/amazfit/app-springboard-settings-pace-rearrange-t3748651)
 - Quinny's [Widget Creation guide - XDA topic](https://forum.xda-developers.com/smartwatch/amazfit/dev-create-custom-home-screen-pages-pace-t3751731).
