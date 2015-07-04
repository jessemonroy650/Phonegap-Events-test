## Notes on Testing Events in Phonegap
Date: 2015-07-02

**Current Status of untested**

event | status | Android | iOS 
------|--------|---------|-----
volumedownbutton | in progress | - | -
volumeupbutton   | in progress | - | -
backbutton       | untested | - | N/A (Not Available on iOS)
menubutton       | untested | - | N/A (Not Available on iOS)
searchbutton     | untested | - | N/A (Not Available on iOS)

**Inprocess of Testing**
* https://github.com/jessemonroy650/Phonegap-PauseResume-test  (pause,resume)
* https://github.com/jessemonroy650/Phonegap-PhysicalButton-test  (backbutton,menubutton,searchbutton)
* https://github.com/jessemonroy650/Phonegap-VolumeButton-test (volumedownbutton,volumeupbutton)

**Won't Test**
* https://github.com/jessemonroy650/Phonegap-CallButton-test (startcallbutton,endcallbutton)

**Already Tested**

event | status 
------|--------
deviceready     | Working as expected on all current [Demo Examples](http://codesnippets.altervista.org/examples/phonegap/demos/PUBLIC.Apps.html)
batterycritical | Working on [Phonegap-Battery-Test](https://github.com/jessemonroy650/Phonegap-Battery-Test)
batterylow      | :::
batterystatus   | vvv
online          | Working on [Phonegap-Network-Info-Test](https://github.com/jessemonroy650/Phonegap-Network-Info-Test)
offline         | :::
startcallbutton | cannot test - I don't own a blackberry.
endcallbutton   | cannot test - I don't own a blackberry.
pause           | Working on [Phonegap-PauseResume-test](https://github.com/jessemonroy650/Phonegap-PauseResume-test.git) **iOS has quirk**
resume          | Working on [Phonegap-PauseResume-test](https://github.com/jessemonroy650/Phonegap-PauseResume-test.git)

