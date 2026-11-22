\# Ravinder Singh - Facility Contribution and Validation Record



\*\*Project:\*\* Navix - IndoorPulse Web Portal  

\*\*Responsibility:\*\* Facility  

\*\*Date:\*\* 23 November 2026  

\*\*Branch:\*\* `ravi/facility-admin-documentation`



\## 1. Repository Setup



\- Personal GitHub fork: `Ravi6280/navix`

\- Original repository: `rizwanhanda/navix`

\- Working branch: `ravi/facility-admin-documentation`

\- Origin and upstream remotes verified.

\- Working tree was clean before documentation was created.



\## 2. Facility-Related Source Review



The existing Navix web portal was reviewed to understand its indoor facility mapping and management functionality.



Areas examined:



\- Interactive 3D indoor map console.

\- Building floor selection and stacked floor representation.

\- Route selection and A\* pathfinding.

\- Accessible elevator-only routing.

\- Emergency SOS nearest-exit routing.

\- Route simulation and portal transitions.

\- Sample building map configurations.

\- JSON map import and export functionality.



This section records source-code review, not newly implemented features.



\## 3. Map Import and Export Review



The existing JSON map importer checks for the presence of `nodes` and `edges` arrays before loading a map.



The source review identified that deeper validation of imported map data could be improved.



This is a recorded observation, not a claim that validation improvements have been implemented.



\## 4. Archive and API Integration Review



The portal contains a Deliverable and Cloud Map Archive interface.



The source includes:



\- GET request to `/api/presentations`.

\- POST request to `/api/upload`.

\- Backblaze B2 storage gateway integration in the upload interface.



These integrations were inspected in the frontend source code. Backend connectivity and live upload functionality have not been independently verified.



\## 5. Testing and Validation Status



\- Repository structure and existing source code reviewed.

\- Existing map console functionality inspected in source.

\- JSON import and export implementation inspected.

\- API integration references inspected.



No independent browser-based, live API, backend or device testing is claimed in this record.



\## 6. Current Status



This document records repository setup, Facility-related source review, and observations about the existing web portal.



It does not claim that new Facility application features have been implemented.



Further implementation and testing will be documented separately when completed.



---



\*\*Prepared by:\*\* Ravinder Singh

