# sampoJavaRecipe
A template with runtime and compile script for Sampo S2
The runtime that gets deployed with the application is Java 1.8, avoid the use of implementations that this version does not support.

the javaMQTT zip folder is a signed application that has a read delay of 2 seconds.

The file that is to be edited exists as zipcontents/bin/nur_java_mqtt.java. To edit read delay, change the time on line 172.

When you want to deploy the application, drag the zipcontents into the program here, under Create:
https://www.nordicid.com/nordicidapplicationsigningtool_v_1_0_3/

zipcontents/bin/run already contains the right start parameters to launch the compiled java program. 
Application name must match the name in End, "pkill -u 'appname'"

Backend port does not need to be filled.

Save when done, and upload the zip folder under the web-ui for the Sampo unit, in the applications section. 