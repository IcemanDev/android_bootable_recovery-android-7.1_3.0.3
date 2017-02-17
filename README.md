# android_bootable_recovery-android-7.1_3.0.3
**Team Win Recovery Project (TWRP)**

You can find a compiling guide [here](http://forum.xda-developers.com/showthread.php?t=1943625 "Guide").

#Insert the boardconfig.mk
#For Version TWRP
TW_SPECIFIC_VERSION_STR := "3.0.3-x by Github"

#For time Zone Italy
TW_SPECIFIC_TIME_ZONE_VAR := "CET-1CEST,M3.5.0,M10.5.0" 
TW_SPECIFIC_TIME_ZONE_GUISEL := "CET-1;CEST,M3.5.0,M10.5.0"

#For H24 hours
TW_SPECIFIC_MILITARY_TIME := "1"

#For Screen_timeout_secs
TW_SCREEN_TIMEOUT_SECS := "120"

#For reverse navbar (default "0")
TW_SPECIFIC_SAMSUNG_NAVBAR := "1"
