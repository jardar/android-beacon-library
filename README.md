Android Beacon Library
=======================

An Android library providing APIs to interact with beacons.  Please visit the
[project website](http://altbeacon.github.io/android-beacon-library/) for how to use this library.

**IMPORTANT:  By default, this library will only detect beacons meeting the AltBeacon specification.**

If you want this library to work with proprietary or custom beacons, see the [BeaconParser](http://altbeacon.github.io/android-beacon-library/javadoc/org/altbeacon/beacon/BeaconParser.html) class.

## What does this library do?

It allows Android devices to use beacons much like iOS devices do.  An app can request to get notifications when one
or more beacons appear or disappear.  An app can also request to get a ranging update from one or more beacons
at a frequency of approximately 1Hz.

## Documentation

The [project website](http://altbeacon.github.io/android-beacon-library/) has [full documentation](http://altbeacon.github.io/android-beacon-library/documentation.html) including [Javadocs.](http://altbeacon.github.io/android-beacon-library/javadoc/)

## Changes from the 0.x library version

This library has changed significantly from the 0.x library version and is now designed to work with
open AltBeacons which fully support Android without any intellectual property restrictions.  For
more information on how to migrate projects using the 0.x APIs to the 2.x APIs, see
[API migration.](api-migrate.md)

## Binary Releases

You may [download binary releases here.](http://altbeacon.github.io/android-beacon-library/download.html) 

## How to build this Library

This project uses an AndroidStudio/gradle build system and is known working with Android Studio
1.0.11 and Gradle 2.2.1

Key Gradle build targets:

    ./gradlew test # run unit tests
    ./gradlew build # development build
    ./gradlew release  # release build  

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

This software is available under the Apache License 2.0, allowing you to use the library in your applications.

If you want to help with the open source project, contact david@radiusnetworks.com


