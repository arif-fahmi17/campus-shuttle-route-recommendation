# Problem Statement

## Who is affected?
Daily UiTM Shah Alam undergraduate students, postgraduate commuters, and campus visitors who rely on internal shuttle transport to reach lectures, residential dorms, and administrative facilities.

## What exactly is going wrong?
Shuttle bus schedules and route maps are primarily published as static PDF documents, forcing students to manually sift through disjointed files to determine routes without real-time arrival certainty (Sulaiman et al., 2025). Furthermore, bus stops are unevenly distributed across campus relative to student density, failing to drop commuters close enough to their actual dormitories, sports complexes, or classrooms and resulting in excessive last-mile walking effort (Andi & Mohd Amin, 2024).

## Why does it matter?
The combination of manual schedule lookups and excessive walking creates severe travel friction, leading to missed lectures, prolonged waiting at stops, high physical fatigue, and unpredictable daily commutes.

## Problem statement (3 to 5 sentences)
University commuters at UiTM Shah Alam face persistent transit delays and physical strain due to static, unintegrated schedule information and uneven bus stop placement across campus. Currently, shuttle routes and timetables are distributed through static PDF documents, requiring students to manually interpret schedules without visibility into actual service reliability ([Sulaiman et al., 2025](https://www.researchgate.net/publication/395820386_OnBoard_A_Real-Time_Bus_Tracking_Mobile_Application_for_University_Campus)). 

Moreover, spatial mismatches between existing bus shelters and student destinations impose excessive last-mile walking distances on commuters traveling to dormitories, sports facilities, and faculties ([Andi & Mohd Amin, 2024](https://www.researchgate.net/publication/377063654_Evaluating_Bus_Transit_System_for_Efficient_Last_Mile_Transportation_in_Universiti_Teknologi_MARA_UiTM_Shah_Alam)). Without a unified, multimodal routing solution that accounts for both transit lines and pedestrian paths, students waste valuable time and experience unnecessary travel friction during peak campus hours.

---

## Users and Scope

### Main Users and Stakeholders
- **Primary Users:** Daily UiTM undergraduate students, postgraduates, and campus visitors navigating the campus.
- **Stakeholders:** UiTM campus transit administration and facilities management responsible for campus mobility.

### Scope Boundary
- **In Scope:**
  - Responsive, mobile-first web application accessible via mobile web browsers and QR code access points.
  - Multimodal campus network graph modeling UiTM Shah Alam internal bus lines, bus stops, and connecting pedestrian footpaths.
  - Graph-based pathfinding engine incorporating walking distance and bus transfer penalty functions.
  - Interactive route recommendation view displaying total estimated travel time, step-by-step transfer instructions, and integrated digital timetable schedules.
- **Out of Scope:**
  - Onboard physical vehicle GPS hardware tracking or telematics integration.
  - Native mobile application builds (no iOS App Store or Android APK deployments).
  - External public transit systems (RapidKL, Smart Selangor, or regional rail networks).
  - Automated ticketing, booking, or fare payment mechanisms (the shuttle service is free for university students).
