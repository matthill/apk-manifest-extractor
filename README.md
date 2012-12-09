apk-manifest-extractor
======================

Extracts the AndroidManifest.xml file from an Android jar

This code is a simplified version of Prasanta Paul's apk extractor.  I removed the external dependencies and added a function to pull the AndroidManifest.xml file in memory (rather than extracting everything to disk).

Ant will compile the code and build a jar.  You can execute it with ant -jar ./apkextractor.jar [Name of your apk file].  It will print out the apk string to the console.

