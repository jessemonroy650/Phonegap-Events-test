## Notes on Testing Events in Phonegap
Date: 2015-07-02

**Current Status of untested**

event | status | Android | iOS
------|--------|---------|----
pause            | untested | - | -
resume           | untested | - | -
backbutton       | untested | - | N/A
menubutton       | untested | - | N/A
searchbutton     | untested | - | N/A
startcallbutton  | untested | - | cannot test
endcallbutton    | untested | - | cannot test
volumedownbutton | untested | - | -
volumeupbutton   | untested | - | -

**Inprocess of Testing**
* https://github.com/jessemonroy650/Phonegap-PauseResume-test  (pause,resume)
* https://github.com/jessemonroy650/Phonegap-PhysicalButton-test  (backbutton,menubutton,searchbutton)
* https://github.com/jessemonroy650/Phonegap-CallButton-test (startcallbutton,endcallbutton)
* https://github.com/jessemonroy650/Phonegap-VolumeButton-test (volumedownbutton,volumeupbutton)

**Already Tested**

event | status 
------|--------
deviceready     | Working as expected on all current [Demo Examples](http://codesnippets.altervista.org/examples/phonegap/demos/PUBLIC.Apps.html)
batterycritical | Working on [Phonegap-Battery-Test](https://github.com/jessemonroy650/Phonegap-Battery-Test)
batterylow      | :::
batterystatus   | vvv
online          | Working on [Phonegap-Network-Info-Test](https://github.com/jessemonroy650/Phonegap-Network-Info-Test)
offline         | :::

