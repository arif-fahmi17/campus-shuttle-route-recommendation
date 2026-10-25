# Requirements

## Functional Requirements (What the system must DO)

- **FR1:** The system shall allow users to select an origin and a destination from known UiTM Shah Alam campus locations, including residential colleges, academic faculties, bus stops, and campus facilities.
- **FR2:** The system shall compute and display optimal route recommendations using a multimodal transit graph that connects shuttle bus lines with pedestrian footpaths.
- **FR3:** The system shall apply configurable penalty weightings for total walking distance and bus transfers when calculating and ranking route options.
- **FR4:** The system shall display step-by-step navigation instructions for the selected route, identifying boarding stops, alight stops, transfer intersections, and walking path segments.
- **FR5:** The system shall provide an integrated digital schedule viewer for all internal UiTM shuttle lines, detailing operating hours, stop sequences, and departure frequencies.

---

## Non-Functional Requirements (How the system must PERFORM)

- **NFR1 (Performance):** The route recommendation engine shall compute and return ranked route options within 1.5 seconds of origin/destination inputs under standard load.
- **NFR2 (Usability):** The web UI must be fully functional across viewport widths from 360px to 1440px+ without horizontal scrolling or broken interface components
- **NFR3 (Reliability):** The system must achieve 99.5% uptime during operational shuttle service hours.
