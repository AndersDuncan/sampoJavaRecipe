# sampoJavaRecipe
A template with runtime and compile script for Sampo S2
The runtime that gets deployed with the application is Java 1.8, avoid the use of implementations that this version does not support.

The file that is to be edited exists as src/src/nur_java_mqtt.java
and has a compile script in the same folder that takes care of the dependencies and copies the output to the zip template and an output folder in src.

When you want to deploy the application, drag the zip folder into the program here, under Create:
https://www.nordicid.com/nordicidapplicationsigningtool_v_1_0_3/

zip/bin/run already contains the right start parameters to launch the compiled java program. 
Application name must match the name in End, "pkill -u 'appname'"

Backend port does not need to be filled.

Save when done, and upload the zip folder under the web-ui for the Sampo unit, in the applications section. 