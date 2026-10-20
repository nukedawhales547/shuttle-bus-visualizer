# shuttle-bus-visualizer
CSSD 1161 Project - 2026

### Data & Content
This section outlines the shuttle schedule attributes, route labeling rules, and offline QR pass storage for the YorkU Shuttle Bus Visualizer.

## Content

### 1. Key Data Attributes
- **Schedule Info:** Origin, destination, departure time, live ETA, and available seat count.
- **Boarding Pass:** Reservation ID, booking status, and boarding QR payload.

### 2. Route & Storage Rules
- **Dynamic Labels:** Routes update labels (e.g., `Shuttle K` for Keele, `Shuttle MK` for Markham) to avoid confusion
- **Capacity Control:** Prevents bookings when full and restores seats upon cancellation.
- **Offline Storage:** Boarding QR passes are saved directly to device local storage (`localStorage`) for offline scanning.
