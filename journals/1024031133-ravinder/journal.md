# UCS503P Engineering Journal — Ravinder Singh (1024031133)



* **Project Title:** IndoorPulse — Infrastructure-Free Multi-Floor Indoor Positioning & 3D Topological Routing System

* **Student Name:** Ravinder Singh

* **Roll Number:** 1024031133

* **GitHub Handle:** `@Ravi6280`

* **Repositories:** `Ravi6280/IndoorPulse-Android` | `Ravi6280/navix`

* **Assigned Individual Responsibility:** Facility

* **Project Team:** Rizwan Handa, Harjot Siddhu, Ravinder Singh, and Pooja



---



## Week 1: Project Introduction

**Focus:** Understanding the course project and its objectives.



**Notes:** The project was developed as part of the UCS503P Software Engineering Lab. IndoorPulse was selected as the team's project, with the objective of developing an infrastructure-free indoor positioning and multi-floor navigation system. The project involved an Android application and a web-based platform. This entry records the project context; it does not claim individual implementation work.



## Week 2: Project Domain and Problem Understanding

**Focus:** Understanding the indoor navigation problem.



**Notes:** The team's project journal describes the challenges associated with indoor positioning, including the limitations of relying on external infrastructure such as Wi-Fi fingerprinting and Bluetooth beacons. The proposed direction was to explore smartphone sensors and offline mapping as part of the IndoorPulse system. My individual implementation activities for this week are not independently documented.



## Week 3: Project Concept and Initial Architecture

**Focus:** Understanding the proposed IndoorPulse solution.



**Notes:** The project concept focused on indoor positioning, map creation, and navigation across multiple floors. The Android application was intended to support map surveying, while the Navix web platform provided a browser-based map interface. I used the project context to understand the overall system and the purpose of its different components.



## Week 4: Project Proposal and Technology Overview

**Focus:** Understanding the project scope and selected technologies.



**Notes:** The project used Kotlin and Android development technologies for the mobile application, with Room used for local database persistence. The web platform was developed using HTML, CSS, and JavaScript. The overall architecture helped establish how the mobile and web components fit into the same project. No individual feature implementation is claimed in this entry.



## Week 5: Android Application Structure

**Focus:** Reviewing the Android application's organization.



**Notes:** The Android application was reviewed to understand its major components and how the application manages indoor map data. The project uses a local database structure for buildings, floors, nodes, and edges. Understanding these entities was relevant to my assigned Facility responsibility.



## Week 6: Understanding Indoor Map Data

**Focus:** Reviewing the facility-related data structure.



**Notes:** The Android source structure includes building, floor, node, and edge entities. These represent the main elements required to store indoor map information. I reviewed the relationship between these entities and how map information is associated with buildings. This provided context for reviewing facility-related functionality.



## Week 7: Surveyor Interface Overview

**Focus:** Understanding the map surveying interface.



**Notes:** The project includes a Surveyor interface with controls for map-related operations. The reviewed interface includes node-type selection, undo and redo controls, position synchronization, node placement, and portal-related controls. This review helped me understand how facility map information is created and managed within the application.



## Week 8: Map Management Operations

**Focus:** Reviewing building and map management functionality.



**Notes:** The Android source review covered operations available through the map management layer, including building creation, renaming, node updates, floor changes, deletion, undo and redo, and portal linking. These operations helped establish the scope of facility-related functionality present in the application.



## Week 9: Mid-Semester Academic Period

**Focus:** Academic coursework and project continuity.



**Notes:** This period falls within the semester's academic schedule. The team journal records a mid-semester examination period. I am not recording any specific project implementation or testing activity for myself during this week because an individual activity record is unavailable.



## Week 10: Reviewing the Application's Data Layer

**Focus:** Understanding local database persistence.



**Notes:** I reviewed the Android database implementation to understand how indoor map data is stored. The application uses Room with entities representing buildings, floors, nodes, and edges. The database review helped me understand how facility information is persisted locally and accessed by the application.



## Week 11: Reviewing Map Data Access

**Focus:** Understanding database access operations.



**Notes:** The MapDao implementation was reviewed to understand how the application observes building maps, retrieves map-related information, and performs building and node operations. This review was useful for understanding the connection between the facility data model and the application's map management functionality.



## Week 12: Reviewing Map Import and Export

**Focus:** Understanding indoor map data portability.



**Notes:** I reviewed the map import and export functionality in the Android application. The implementation exports map information in JSON format and supports importing map data by creating new identifiers for imported records. This helped me understand how facility map information can be backed up and transferred.



## Week 13: Navix Web Platform Overview

**Focus:** Reviewing the web-based project component.



**Notes:** I reviewed the Navix web platform to understand its role in the overall IndoorPulse system. The website contains an interactive map console, multi-floor visualization, route selection, and map import and export interfaces. The review was focused on understanding the existing system rather than claiming independent development of these features.



## Week 14: Reviewing Web Map Functionality

**Focus:** Understanding the browser-based map interface.



**Notes:** The Navix source was reviewed to identify the main functionality available in the web interface. The reviewed implementation includes floor selection, route selection, 3D map visualization, accessible routing options, emergency exit routing, and route simulation. This provided a better understanding of how the web component represents the indoor facility map.



## Week 15: Facility Responsibility and Validation Review

**Focus:** Reviewing facility-related functionality and documenting observations.



**Notes:** I focused on my assigned Facility responsibility and reviewed the available Android source code and project structure. The review covered building and floor information, map entities, node and edge relationships, and the available facility management operations. I documented observations and validation information separately so that my individual contribution could be identified clearly.



## Week 16: Android Build and Unit-Test Verification

**Focus:** Verifying the Android project build and available unit tests.



**Notes:** I ran the Android Gradle build and debug unit-test tasks to verify the current project state. The following command completed successfully:



```powershell

.\\gradlew.bat --no-configuration-cache :app:assembleDebug :app:testDebugUnitTest

```



The reported result was **BUILD SUCCESSFUL**. The test report showed 36 tests, with 36 passed, 0 failed, 0 errors, and 0 skipped. This verification covered the Android build and JVM unit tests; it does not represent instrumented or physical-device testing.



## Week 17: Individual Documentation and Final Project Review

**Focus:** Recording individual contribution and preparing project evidence.



**Notes:** I prepared an individual Facility validation record and added documentation to my Android and Navix repository branches. The Android documentation commit was `1c647bd`, and the Navix documentation commit was `e614b2d`. I also reviewed the project source and recorded the scope and limitations of the validation performed.



My documented contribution is focused on Facility-related source review, validation documentation, Android build verification, unit-test verification, and maintaining individual GitHub evidence. I have not claimed independent implementation of the pathfinding engine, pedestrian dead reckoning algorithms, or field-testing activities that I did not perform.



---



**Individual Contribution Summary**



My assigned responsibility in the IndoorPulse project was Facility. My documented individual work includes:



1. Reviewing the Android facility and indoor-map data structure.

2. Reviewing building, floor, node, and edge management operations.

3. Reviewing the Surveyor interface and map import/export functionality.

4. Reviewing the Navix web platform and its facility-map interfaces.

5. Running the Android debug build and JVM unit tests.

6. Verifying the reported result of 36 passed unit tests.

7. Preparing individual facility validation documentation.

8. Maintaining individual documentation commits in my GitHub repositories.



**Verification Scope:** The recorded build and unit-test results establish successful execution of the specified Android build and JVM unit-test tasks. They do not establish physical-device testing, instrumented testing, or independent verification of the live cloud services.
