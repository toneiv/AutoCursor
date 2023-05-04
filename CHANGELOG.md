# Changelog
## 1.7.0 (19094) - 04/05/2023
* Support for the potential conflict with the tracker when a drag action is executed
* Redesign of animations
* New Action: **Turn off screen**
* Improved on-screen keyboard management
* Improved screen rotation management
* Improved display of available widgets
* Fixed bugs in the "Show left/right cursor" widget
* Fixed bugs in the "Temporarily disable triggers"

## 1.6.8 (17605) - 06/12/2022
* New Action: **Adjust Volume (System, Media, Notification, Ringtone or Alarm) with slider** (see **Media actions**)
* New Action: **Adjust Brightness with slider** (see **Actions**)
* Ability to set the thickness of a trigger to a minimum value of 5px
* Improved management of trigger rotation
* Various bug fixes and improvements
 
## 1.6.7 (17071) - 12/09/2022
* Vibration strength can now be adjusted up to 500ms

## 1.6.6 (17025) - 29/08/2022
* Vibration strength can now be adjusted up to 500ms

## 1.6.5 (16754) - 27/06/2022
* New Action: **Toggle Flashlight** (Android Marshmallow and up)
* New Action: **Scroll backward** and **Scroll forward** : can be used for example to scroll through a web page
* Ability to set the shape of the trigger (rectangle, rectangle with round corners, line) (see **Trigger look**)
* Ability to set the strength and colour of the halo for different state of the tracker (see **Settings** / **Color**)
* Ability to use an intent to activate/deactivate the trigger of your choice (see **https://autocursor.toneiv.eu/faq** / **Intent/Tasker**)

## 1.6.3 (16252) - 25/05/2022
* Various bug fixes and improvements

## 1.6.2 (16147) - 16/05/2022
* New: auto click with pointer on first release after swipe
* New: auto click with pointer after each move
* New: menu available on the tracker with following actions : copy text, toggle auto-click, close
* New: Copy text action available through the tracker menu
* New: improved animations, performance and memory footprint
* Fixed: bad behaviour of the Toggle Auto-rotate action

## 1.5.7 (14211) - 10/03/2022
* New: improved compatibility with native Android navigation gestures
* Various bug fixes and improvements

## 1.5.6 (14145) - 26/02/2022
* Fixed: on some devices a significant delay could be observed when clicking on the tracker
* Various bug fixes and improvements

## 1.5.5 (14107) - 31/01/2022
* Fixed: a shift when manipulating the cursor could appear on some devices

## 1.5.4 (14068) - 15/01/2022
* Fixed : ability to define launcher in blacklist list
* Fixed : Auto Cursor now works on more system screens
* New: Ability to specify the location of the cursor on the screen when using the "Show left/right cursor" shortcut (see https://autocursor.toneiv.eu/faq.html#intent02)

## 1.5.3 (14046) - 10/01/2022
* Various bug fixes and improvements

## 1.5.2 (13987) - 16/12/2021
* Fixed: bug affecting click on trigger

## 1.5.1 (13984) - 16/12/2021
* New: **Recent applications menu** position : the position of the menu on the screen is now configurable (see **Recent Apps** / **Size and appearance**)
* New: Action/application/shortcut selection screens are now filterable
* Various bug fixes and improvements<br>

## <a href="https://github.com/toneiv/AutoCursor/milestone/13">1.5.0</a> (13831) - 08/12/2021
* New: **Recent applications** action available: including the ability to set sound and vibration on click and long click, the ability to set a blacklist (application not to be displayed in the recent menu) as well as the ability to customise columns, rows and icon size
* New: **Previous App** action can now be used instead of **Previous App Native** action,
* New: vibration and sound can be set for trigger (see **Misc** / **Trigger sound and vibration**)
* New: vibration and sound can be set for cursor (see **Settings** / **Cursor sound and vibration**)
* New: Added information to fix the bug affecting the tab group view in **Google Chrome**: this is an option available in **Chrome** when an application uses the accessibility service (see in **Google Chrome Settings** / **Accessibility** / Uncheck **Simplified view for open tabs**)
* New: Round corner on trigger option : it is now possible to enable or disable this option (see **Trigger** / **Trigger look**)

## 1.4.7 (13103) - 16/10/2021
* Update **Google Play Billing Library** to 4.0.0
 
 ## <a href="https://github.com/toneiv/AutoCursor/milestone/12">1.4.6</a> (13032) - 11/10/2021
* Update **Target API level 30 (Android 11)**
* New: possibility to fix delay for the **Previous App Native** action (see **Choose Action** / **Actions** / **Previous App Native** then long click)
* New: **Fixed: top of the screen** option for **Vertical reference point** (see **Auto Cursor** / **Behaviour**)
* New: Option to temporarily turn off gestures when keyboard is showing (see **Misc** / **Keyboard Behaviour**)
* New: Option to show the nav bar when keyboard is showing (see **Misc** / **Keyboard Behaviour**)
 
## 1.4.5 (12943) - 29/04/2021
* New: possibility to reduce the long click delay of the cursor to 250 ms
 
## 1.4.4 (12939) - 29/04/2021
* Fixed: bug affecting icon color and transparency

## 1.4.3 (12928) - 28/04/2021
• Fixed: compatibility issue with backup and restore on Android 11
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/AutoCursor/milestone/11">1.4.2</a> (12901) - 22/03/2021
* New: possibility to add a glowing halo effect on tracker
* Improved "click & drag" functionality
* Various bug fixes and improvements

## 1.4.1 (11941) - 03/03/2021
* New: possibility to add several independent triggers<br>
* New: simplified interface for positioning triggers<br>
* New: possibility to choose delay for long click activation on the cursor<br>
* Improvement in click, long click and drag detection<br>
* New: Hungarian translation thanks to István Kriskó &lt;istvan.krisko@gmail.com&gt;<br>
* Memory footprint improvements<br>
* Performance improvements<br>
* Various bug fixes and improvements<br>
* Fixed: missing translations available again<br>

## <a href="https://github.com/toneiv/AutoCursor/milestone/10">1.3.5</a> (9459) - 08/01/2021
* New:  possibility to choose action on cursor long click (none, long click, click, remove cursor)<br>
* New:  possibility to choose action on cursor long click and drag (none, drag)<br>
* New:  possibility to choose color for the cursor<br>
* Various bug fixes and improvements<br>

## 1.3.4 (9634) - 04/01/2021
* New : sound feedback can be added for click and/or long click on the triggers (see Misc settings)<br>
* New : triggers can be set to remain in portrait mode position (see Misc settings)<br>
* New : triggers can be set to appear only in portrait or lanscape mode (see Misc settings)<br>
* Various bug fixes and improvements<br>

## <a href="https://github.com/toneiv/AutoCursor/milestone/7">1.3.3</a> (7796) - 09/12/2020
* New: cursor can be set to have no delay and thus remain on the screen until it is manually removed

## 1.3.2 (7569) - 05/12/2020
* Fixed: crash in tuto screen for 4.4. android version

## <a href="https://github.com/toneiv/AutoCursor/milestone/8">1.3.1 (7565)</a> - 04/12/2020
* Fixed: Auto Cursor is available again in settings screen in Android 10
* Overall efficiency and fluidity improvement
* Various bug fixes and improvements

## 1.2.1 (6522) - 20/11/2020
* Various bug fixes and improvements

## 1.2.0 (6400) - 19/11/2020
* New: option to remove the cursor by flinging it on any side of the screen (see Settings)
* New: navigation drawer
* Enhancement of interface lisibility
* Various bug fixes and improvements

## 1.1.15 (5729) - 10/11/2020
* New: option to choose animation on tracker click
* Various bug fixes and improvements
  
## 1.1.14 (5655) - 05/11/2020
* Various bug fixes and improvements

## 1.1.13 (5459) - 27/10/2020
* New: option to hide "Auto Cursor is displaying over other apps" persistent notification (see Misc settings)
* Fixed: compatibility with latest Google Review API
* Fixed: error with classic and modern cursor icon in Android 4.4

## 1.1.12 (5196) - 07/10/2020
* Various bug fixes and improvements

## 1.1.11 (5193) - 30/09/2020
* New: improvement in compatibility with Android 11
* Various bug fixes and improvements

## 1.1.10 (4972) - 02/09/2020
* Fixed: increased blacklist compatibility (especially with games)

## 1.1.9 (4854) - 01/09/2020
* New: interface enhancements
* Various bug fixes and improvements

## 1.1.8 (4723) - 28/08/2020
* Fixed: unexpected crash in tutorial screens for Android 4.4

## 1.1.7 (4625) - 26/08/2020
* Fixed: on some devices, the purchase service for the Pro was not working properly

## 1.1.6 (4533) - 24/08/2020
* Various bug fixes and improvements
## 1.1.5 (4522) - 09/08/2020
* Various bug fixes and improvements

## 1.1.4 (4518) - 09/08/2020
* New: improvement for click on trigger detection
* Various bug fixes and improvements

## 1.1.3 (4498) - 08/08/2020
* New: improvement in compatibility with future Android 11
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/AutoCursor/milestone/6">1.1.2 (4432)</a> - 06/08/2020
* New: option to choose size of the cursor
* New: option to choose shape of the cursor
* New: option to choose animation on cursor click
* New: live update of cursor and tracker when editing options
* Various bug fixes and improvements

## 1.1.1 (4126) - 28/07/2020
* New: ability to remove 250ms delay on click (when No Action on Double click is selected)
* Various bug fixes and improvements

## 1.1.0 (4080) - 27/07/2020
* Various bug fixes and improvements

## 1.0.1 (3217) - 08/07/2020
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/AutoCursor/milestone/5">1.0.0 (3110)</a> - 06/07/2020
* New:  ability to duplicate settings from one side to another (see Trigger / Template)
* New : ability to define action on double click on the tracker
* New : ability to define action on click outside the tracker
* New : ability to define action when clicking outside while pressing the tracker
* New : ability to define a vertical dynamic reference point for the tracker (see Cursor / Vartical reference point)
* New : ability to define waiting time for second action on each trigger (see Trigger / Actions)
* Fixed: the cursor launched with shortcuts did not always reach the side
* Fixed: the cursor launched with shortcuts wasn\'t set properly on landcape mode

## <a href="https://github.com/toneiv/AutoCursor/milestone/4">0.9.3 (2821)</a> - 01/07/2020
* New:  min delay for disapperance of cursor set to 200ms
* New: 2 shortcuts, show cursor left and show cursor right

## <a href="https://github.com/toneiv/AutoCursor/milestone/3">0.9.2 (2646)</a> - 29/06/2020
* New:  possibility to choose the style for the tracker countdown
* New:  ability to precisely position the triggers as a percentage of the screen
* New:  live update of the trigger when changing its settings
* Fixed: enhanced precision when dragging the cursor
* Fixed: prevents accidental clicks when dragging the cursor

## 0.9.1 (2432) - 25/06/2020
* Fixed: the cursor did not display correctly in landscape mode

## <a href="https://github.com/toneiv/AutoCursor/milestone/2">0.9.0 (2313)</a> - 22/06/2020
* New: possibility to choose the sensitivity to cursor movement
* New: Auto Cursor is available when Quick Settings is displayed
* Fixed: improved management of clicks and long clicks on triggers
* Overall efficiency and fluidity improvement

## 0.8.5 (2136) - 18/06/2020
* Fixed: cursor will not interact with triggers or tracker while moving
* Fixed: cursor stopped working unexpectedly with some devices
* Various bug fixes and improvements

## <a href="https://github.com/toneiv/AutoCursor/milestone/1">0.8.4 (2094)</a> - 17/06/2020
* New: improved cursor drag functionality: ability to perform complex move
* New: animation when performing drag or move
* New: improved cursor trail fluidity
* New: added cursor trail effect
* New: 2 shortcuts, start and stop Auto Cursor
* Fixed: less intrusive popup warning for Huawei devices

## 0.8.3 (1403) - 09/06/2020
* Fixed: bug with Google Play

## 0.8.2 (1366) - 08/06/2020
* New: cursor now available for Android Versions lower than Nougat (24)

## 0.8.1 (1345) - 08/06/2020
* New: cursor compatibility mode to improve its operation with some versions of Android
* Fixed: the tracker was not correctly drawn when changing dimensions
* First public relead

