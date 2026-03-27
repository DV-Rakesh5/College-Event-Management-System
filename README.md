# College Event Management System


A modern, responsive, and fully functional **College Event Management System** built with HTML, CSS, and Vanilla JavaScript. It features a premium, glassmorphism-based UI design and utilizes `localStorage` for real-time frontend database management without relying on a backend server. 

##  Features

- **Premium Glassmorphism UI**: Beautiful, modern translucent interfaces, dynamic gradients, and smooth scroll animations.
- **User Authentication**: Frontend mock login and sign-up pages (`login.html` & `signin.html`).
- **Dynamic Event Dashboard**: 
  - Showcases upcoming events with their respective fees, dates, and venues.
  - Events include: Alliance Literary Festival, Alliance One, Hackathon, Sports Meet, and Alumni Meet.
- **Event Registration System**:
  - Validated form for users to register using Name & Email.
  - **Payment Integration**: Conditional payment flow drops down for paid events (e.g., Hackathon, Alumni Meet).
- **Admin Dashboard**:
  - Live statistics counter for Total Registrations and Active Events.
  - View real-time attendee lists sorted by event filter.
  - Reset Database feature to clear out registrations.
- **Local Storage Database**: Stores tracking data locally in your browser to simulate a real-time database tracking system.

##  Tech Stack

- **HTML5**: Semantic tags for structuring web content.
- **CSS3**: Modern formatting, Custom Properties (Variables), Flexbox/Grid structuring, and Keyframe Animations.
- **JavaScript (ES6+)**: DOM Manipulation, Event Listeners, and LocalStorage data handling.

## 📂 Project Structure

```text
📁 SEAD
 ┣ 📄 login.html      # User authentication gateway page
 ┣ 📄 signin.html     # User registration page
 ┣ 📄 sead.html       # Main Application (Dashboard, Events, Registration, Stats)
 ┣ 📄 style.css       # Shared stylesheet (if any external overrides exist)
 ┗ 📄 logo.png        # Project background and branding logo
```

##  Getting Started

1. **Clone the repository** (or download the zip):
   ```bash
   https://github.com/DV-Rakesh5/College-Event-Management-System.git
   ```
2. **Open the project**:
   Navigate into the directory and open `login.html` or `sead.html` directly in your favorite browser. No server setup is required.
   
3. **Usage**:
   - Register for an event directly from the **Events** or **Registration** sections in `sead.html`.
   - Choose a paid event to see the simulated payment portal.
   - Scroll up to the **Admin Dashboard** to see the attendee appear instantly.
   - Use the **Reset Database** button to clear your `localStorage` entries for testing.

##  Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
