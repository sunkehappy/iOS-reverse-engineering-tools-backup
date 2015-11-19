# iOS-reverse-engineering-tools-backup
Some guys find the old lsof could not be downloaded. But I have it and I want to share it.

## What files are here?

Currently only the lsof-arm7-iOS4.2 and dumpdecrypted-for-iOS6.dylib. Other files will be added later.

### Why the Reveal lib?

Because I find that the new Reveal version (1.6.x) dynamic library is not compatible with our iPhone 4S with iOS 8.4. When I copy the new version to the device's MobileSubstrate/DynamicLibraries/ directory. The device could not bool! And when I boot into safe mode and replace the libReveal.dylib with the older version (1.5.1). All goes well.
