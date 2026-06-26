# KDE Connect - Android app - DEGOOGLED

For some reason the official kde app grabs a device name list from: https://storage.googleapis.com/play_public/supported_devices.csv

`src/main/java/org/kde/kdeconnect/helpers/DeviceHelper.kt`

Why tf this app needs to talk to google just to set a device name...?

So I stripped it out. GFY google. KDE should at least prompt user before connecting to spyware domains by default...

In case it isn't blatantly obvious, this is not the official build. 
