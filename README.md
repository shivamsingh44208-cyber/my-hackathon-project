# HELPING HANDS — Frontend Prototype

Vanilla HTML5 + CSS3 + JavaScript. No backend or framework.

## Run
Open `index.html` in a modern browser.

## Demo
Click **🎬 Demo Mode**.
- Login as Donor in one tab.
- Login as NGO in another tab.
- Donor: Dashboard → Donate Food → complete the six steps.
- NGO: Nearby Food → Request Food.
- Switch to donor tab: refresh/navigation will show the notification; the shared localStorage data is available across tabs.
- Messages and profile/history are also persisted in localStorage.

## Notes
Authentication, NGO verification, map data and matching are intentionally simulated for a hackathon frontend prototype. Browser geolocation uses the normal permission API when available.
