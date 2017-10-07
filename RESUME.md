# Carmen Alvarez - Open source projects

c@rmen.ca - [http://rmen.ca](http://rmen.ca) 

[https://github.com/caarmen](https://github.com/caarmen) - [https://play.google.com/store/apps/developer?id=Carmen%20Alvarez](https://play.google.com/store/apps/developer?id=Carmen%20Alvarez)

### Summary

Developer with over 15 years experience, 7 years of Android development, and 4 years of open-source projects published on GitHub. 

## Poet Assistant
*Android app - [GitHub](https://github.com/caarmen/poet-assistant), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.poetassistant) - Offline rhymer, thesaurus, dictionary, editor and playback for composing poetry.*

**Sole Author** (February 2016 - Current)

* *Why?* One night, during a bout of insomnia, I tried to pass the time by composing a poem on my mobile phone. Frustrated by having to constantly switch between a text editor, and multiple websites in a browser for the rhymer, thesaurus and dictionary, I decided to create an application integrating these features.
* *Downloads*: 114,000 as of October 2017.
* *Features*: Lookup and cross-navigation between three dictionary sources (rhymer, thesaurus, definitions). Editor to compose a poem. Playback to listen to the poem. Share and import poems. Random word of the day notification. Search by pattern. Save favorite words. Lookup in the different dictionaries from text selection is possible from the editor and external applications.
* *Settings*: Voice speed and pitch for playback, dark/light theme, different layout options, rhyming rules.
* *Data sources*: the rhymer data is from the [Carnegie Mellon Pronouncing Dictionary](http://svn.code.sf.net/p/cmusphinx/code/trunk/cmudict/). The thesaurus is from the [WordNet 2.0 thesaurus](https://github.com/LibreOffice/dictionaries/tree/master/en). The definitions are from the [WordNet 3.0 dictionary](http://wordnet.princeton.edu/wordnet/download/current-version/). Some features rely on word frequencies, using the [Google Ngram Viewer](http://storage.googleapis.com/books/ngrams/books/datasetsv2.html).
* *Android Apis*: Text-to-speech, search by voice, printing, Storage Access Framework, Data Binding, Day/Night theming, lookup from external apps, custom search suggestions.
* Available on F-Droid.
* *Compatibility*: min: ICS 4.0.3, target: Oreo 8.
* *Libraries*:
    - Personal application libraries: [Rhymer](https://github.com/caarmen/rhymer), [Porter Stemmer](https://github.com/caarmen/porter-stemmer).
    - 3rd party application libraries: Support Library, Retrolambda, EventBus, Dagger, RxJava2, Prefs, GreenDao (later removed)
    - Debugging and testing libraries: Leak Canary, Espresso, Robolectric, Fest Reflection, Ben-manes.

## Network Monitor
*Android app - [GitHub](https://github.com/caarmen/network-monitor), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.networkmonitor) - Diagnostic tool which periodically checks the device's network conditions and logs results and device attributes. Provides various reporting features.*

**Primary Author** (May 2013 - August 2017)

- *Why?* My device had sporadic network connection failures on mobile data, and I wanted to track the errors and device and network conditions for better understanding of the connectivity issues.
- *Downloads*: 68,000 as of October 2017.
- *Features*: Collect connection test results and device attributes periodically. View the log in a WebView. Choose columns and filter values in the log view. Export the data to various formats (Csv, Html, Excel, Kml, Gnuplot, Database, Text summary). Send reports periodically by e-mail. Export and import log data. Speed test.
- *Settings*: Light/dark theme, notification settings for when connection tests fail, performance tuning.
- *Android Apis*: TelephonyManager Apis to retrieve information about signal strength, sim status and operator, network operator. WifiManager to retrieve WiFi connection information. NetworkStats to identify data-consuming apps. ContentProvider for persistence.
- *Foss and "proprietary" flavors*: The Foss flavor excludes features requiring Google Play Services, and is published on F-Droid. The "proprietary" flavor is published on the Play Store.
- *Libraries*: Support Library, Permissionsdispatcher, Google Play Services, Streamsupport, Retrolambda, JExcelApi, Apache commons-net, Licenses dialog
* *Compatibility*: min: ICS 4.0, target: Oreo 8.
- Available on F-Droid.

## French Revolutionary Calendar
*[Library](https://github.com/caarmen/french-revolutionary-calendar), Android app - [GitHub](https://github.com/caarmen/FRCAndroidWidget), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.frenchcalendar) and Wear 2.0 complications - [GitHub](https://github.com/caarmen/FRCComplication), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.frc.complications) - Library, Android application, and Android Wear complications about the French Revolutionary Calendar.*

**Primary Author** (July 2011 - Current)

- *Why?* I was intrigued by the concept of a new calendar.
- *Downloads*: 7,500 as of October 2017.
- *Languages*: Kotlin (the library) and Java (the Android app).
- *Library Features*: An Api to convert between Gregorian and French Revolutionary Calendar dates, to convert between 24-hour time and decimal time, to lookup the "object of the day". (The French Revolutionary Calendar designated a plant, mineral, animal, or agricultural tool for each day of the year). Available in 7 languages: English, French, Spanish, Catalan, German, Italian, Basque. The Basque translations were contributed by an enthusiast, and the other translations are from Wikipedia pages.
- *Android App Features*: Widget to display the current date on the device home screen. Daily notification. 2-way date converter between Gregorian and French dates.
- *Android Wear Complications*: Provides complications for: the day of the week, the date, the object of the day, and decimal time.
- *3rd party libraries*: Color picker preference, Font picker preference. No support library as the app supports Api level 3.
- *Contributions from enthusiasts*: Basque translation (library and app), Italian translation (app).
- Available on F-Droid.
- Integration with Travis CI.
- *Compatibility*: min: Cupcake 1.5, target: Oreo 8.

## Scrum Chatter
*Android app - [GitHub](https://github.com/caarmen/scrumchatter), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.scrumchatter) - Track how long team members speak during a meeting.*

**Primary Author** (June 2013 - April 2017)

- *Why?* Our daily meetings took too long with 8 to 10 team members. This was a humorous attempt to encourage team members to get to the point.
- *Downloads*: Shamefully low.
- *Features*: Create multiple teams. Create a meeting, manually tap on a team member when s/he speaks (no voice recognition). Export data to Excel. View stats in graphs inside the app: average speaking time per person, total speaking time per person, meeting duration over time, member speaking duration over time. Share graphs and text summaries of meetings.
- *Android Apis*: ContentProvider for persistence.
- *Libraries*: Support library, Retrolambda, HelloCharts, android-flowlayout, JExcelApi, RxJava2, RxAndroid, ben-manes, ContentProvider generator.
- *Contributions from enthusiasts*: Japanese translation.
- *Compatibility*: min: Gingerbread 2.3, target: Nougat 7.1
- Available on F-Droid.

## Pálida Muerte
*Android app - [GitHub](https://github.com/caarmen/PalidaMuerte), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.android.palidamuerte) - Selection of poems by Francisco Álvarez Hidalgo*

**Sole Developer** (April 2014 - January 2015, July 2017)

- *Why?* To distribute a collection of poems by my father in a new medium (he published them on a website)
- *Downloads*: Shamefully low.
- *Features*: Read poems in six "books". Mark poems as favorites. Search for poems by text. Share a poem. Print a poem.
- *Note*: the poem text is not on GitHub as it is not "open source".
- *3rd party libraries*: Support library, ben-manes, dexcount.
- *Compatibility*: min: ICS 4.0, target: Nougat 7.1
- *Android Apis*: ContentProvider, Search.

## Nounours
*Android app - [GitHub](https://github.com/caarmen/nounours-android), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.nounours), X11 screensaver - [GitHub](https://github.com/caarmen/nounours), [Download](http://rmen.ca/nounours-linux.html) - Interactive teddy bear in an application, live wallpaper, Android Wear 1.0 watchface, and X11 screensaver*

**Primary Developer** (May 2009 - February 2017)

* *Why?* To discover Android. This was my Android "Hello world" program.
* *Downloads*: My buddy Nounours: 34,000. Nounours and friends: 37,000. Bugdroid Buddy: 52,000.
* *Features*: 
    - App: Interact with the teddy bear in the application. Record his movements and share them as an animated gif. Choose from some pre-set animations. 
    - Live wallpaper: Choose Nounours or Bugdroid with a selection of themes and color settings, for the live wallpaper on the device's home screen.
    - Daydream: For supported devices, choose Nounours to appear when the device is plugged in and the screen locked.
    - Android wear 1.0 watchface. Choose Nounours or Bugdroid for the watchface character. In non-ambient mode, basic interaction by tapping on the character.
    - X11 screensaver: integration with the xscreensaver program on Linux.
- *Languages*: Java, C
- *Libraries*: [libnounours](https://github.com/caarmen/libnounours), Color picker preference
- Available on F-Droid.
- *Compatibility*: min: Cupcake 1.5, target: Nougat 7.1
- *Trivia*: This app was selected as one of 10 "Prix du Public" finalists in the ["SFR Jeunes Talents Développeurs"](http://www.pointgphone.com/resultats-concours-android-sfr-jeunes-talents-developpeurs-2636/) competition in Paris on May 13, 2009.

## You're a Winner!
*Android app - [GitHub](https://github.com/caarmen/youreawinner), [Play Store](https://play.google.com/store/apps/details?id=ca.rmen.youreawinner)*

**Troll Developer** (January 2013)

* *Why?* Some users commented on a geography game I published on the Play Store (not open-source), saying it was too difficult. This app was a troll response to those users: "If you want a game that's easier to win, try You're a Winner!"
* *Downloads*: Appropriately low
* *Features*: Press on a red button to score random points and view a positive affirmation. Share your score.
* *Compatibility*: min: Donut 1.6, target: ICS 4.0.4


## SunriseSunset
*[Java library](https://github.com/caarmen/SunriseSunset) - Library to determine the sunrise, sunset, and twilight times for a given location on a given date*

* *Why?* A developer of a live wallpaper webcam app needed a utility to know if a webcam was currently filming a location during day or night.
* *Features*: Convert between Gregorian and Julian dates. Get the sunrise, sunset, solar noon, civil, nautical, and astronomical twilight times, and day length for a location and date.
