# User Stories

### User Story 1 (Route Discovery)
**As an** undergraduate student in a hurry,  
**I want** to search for the fastest shuttle route between my residential college and faculty building,  
**so that** I can reach my scheduled class on time without manually scanning multiple static PDF schedules.

- **Linked Requirement:** FR2
- **Acceptance Criteria:**
  1. Selecting an origin and destination calculates and renders the fastest recommended route within 1.5 seconds.
  2. The recommendation card clearly displays the total estimated journey duration, designated bus line, and boarding stop.

---

### User Story 2 (Minimizing Last-Mile Walk)
**As a** student commuter carrying heavy textbooks or project equipment,  
**I want** the system to prioritize routes that minimize walking distance,  
**so that** I do not have to walk long distances under hot or rainy weather conditions to reach my destination.

- **Linked Requirement:** FR3
- **Acceptance Criteria:**
  1. The routing algorithm selects a slightly longer bus trajectory if it saves the user more than 300 meters of pedestrian walking.
  2. The route itinerary clearly itemizes in-vehicle riding distance versus walking distance and highlights walking segments on the map.

---

### User Story 3 (Transfer & Stop Guidance)
**As a** campus visitor unfamiliar with the UiTM Shah Alam transit layout,  
**I want** step-by-step directions showing where to board, change buses, and alight,  
**so that** I do not miss my bus transfer or get lost while navigating across campus.

- **Linked Requirement:** FR4
- **Acceptance Criteria:**
  1. The itinerary step breakdown explicitly labels transfer nodes where a change of bus is required.
  2. Each instruction details pedestrian footpath connections between the bus stop shelter and the target campus building.
