# bwHC Data-Transfer-Objects for Java

Generates bwHC DTOs for Java.

For Scala, use: https://github.com/KohlbacherLab/bwHC-Data-Transfer-Objects

See https://ibmi-intra.cs.uni-tuebingen.de/display/ZPM/bwHC+REST+API for more information about DTOs and generating JSON
scheme from application.

The generated JSON scheme has been modified:

* Java package names have been removed from definitions
* Modifications to match example json file, generated using current image
* Grading and Relationship code enums got additional suffix "Code" to prevent name collisions.
* Extracted duplicated inline definitions

The generated scheme matches DTOs in docker
image https://github.com/KohlbacherLab/bwHC-REST-API-Gateway/pkgs/container/bwhc-backend/108270791?tag=1.0-SNAPSHOT-broker-connector