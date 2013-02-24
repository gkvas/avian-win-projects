avian-win-projects
==================

Solution and project files for building win32 and wince Avian

Windows CE
----------

Copy classpath.jar and zlibce.dll to the device root.

Deploy avian-wince-dll
Deploy avian-wince-dynamic

Debugging settings for avian-wince-dynamic:

Remote executable: \avian-dynamic.exe
Command arguments: -Xbootclasspath:\classpath.jar -cp \Print.jar Print4

In this example, "Print.jar" contains the main class "Print4"

Deployment settings for avian-wince-dynamic:

Remote directory: \
