## Notes on Testing Events in Phonegap
Date: 2015-07-02

**Current Status of untested**

event | status | Android | iOS 
------|--------|---------|-----
pause            | untested | - | -
resume           | untested | - | -
volumedownbutton | untested | - | -
volumeupbutton   | untested | - | -
backbutton       | untested | - | N/A (Not Available on iOS)
menubutton       | untested | - | N/A (Not Available on iOS)
searchbutton     | untested | - | N/A (Not Available on iOS)
startcallbutton  | cannot test | - | N/A (I don't own a blackberry.)
endcallbutton    | cannot test | - | N/A (I don't own a blackberry.)

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

