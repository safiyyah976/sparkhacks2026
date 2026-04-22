
# LoopedIn

# Campus Club Discovery & Sponsor Connection Platform

Built in 48 hours at UIC's SparkHacks 2026 — connecting students, organizations, and sponsors all in one place.

Finding clubs at a big university shouldn't be a guessing game, and securing sponsors for your org shouldn't depend on who you know. LoopedIn was born out of our own experiences as students joining and leading campus organizations at UIC, where we noticed two recurring problems: students struggle to discover clubs that match their interests, and student organizations struggle to connect with sponsors and vendors for their events.

LoopedIn is a centralized web platform that solves both. Students can browse and save clubs they love, organizations can showcase what they need, and sponsors can discover orgs that align with their interests — all from a single hub!

# Features

Club Discovery — Browse student organizations with descriptions, interest tags, and vibes that help you find your community.
Favorites Dashboard — Heart any club to pin it to your personal ❤️ Your Clubs panel for easy reference.
Smart Search & Filtering — Filter clubs by interests, themes, or collaboration needs to find the right fit fast.
Sponsor & Vendor Board — Clubs can post what they need for events, and sponsors can browse and connect based on aligned interests.
Club Registration — Register a new organization through an in-app modal form (demo mode — saved locally).
Responsive Two-Panel UI — Discover panel and personal dashboard live side by side in an intuitive, clean layout.

## Demo

- ❤️ Your Clubs panel: view and manage hearted clubs.
- 🔍 Discover panel: explore clubs by tags, search, or themes.
- Vendor listings: see club requests and potential collaborations.
- Register a new club locally via the modal form.

## Installation

1. Clone the repository: git clone https://github.com/yourusername/loopedin.git
2. Navigate to the project folder:  cd loopedin
3. Install dependencies: npm install
4. Start the development server: npm start
5. Open your browser and visit http://localhost:3000

## Tech Stack

- Frontend: React
- Styling: Inline CSS / CSS modules
- State management: React useState, useMemo, useEffect
- Data persistence: localStorage (for demo)
- Other: JSON dataset for clubs (clubs.json)

## Project Structure

loopedin/
├── public/
│   ├── images/              # Static image assets
│   ├── background2.png      # App background image
│   └── vite.svg
├── src/
│   ├── assets/              # Additional static assets
│   ├── components/          # Reusable React components
│   ├── App.jsx              # Main app logic: search, filtering, UI rendering
│   ├── App.css              # Global styles and responsive layout
│   ├── clubs.json           # Seed dataset for demo clubs
│   ├── requests.json        # Club event/vendor request data
│   ├── vendors.json         # Vendor/sponsor seed data
│   ├── index.css            # Base styles
│   └── main.jsx             # React entry point
├── index.html
├── vite.config.js
└── README.md

- App.js – main app logic, search, filtering, and UI rendering.
- clubs.json – seed dataset for demo clubs.
- components/ – reusable components (ClubTile, Modal, NewClubForm, TagRow).
- App.css – global styles and responsive layout.

# Getting Started

Prerequisites:

- Node.js (v16 or higher)
- npm

Installation:

1. Clone the repository: git clone https://github.com/yourusername/loopedin.git
2. Navigate into the project folder: cd loopedin
3. Install dependencies: npm install
4. Start the development server: npm start
5. Open browser and visit provided link

# Contributions
LoopedIn is currently a demo, but we are open to contributions!

Try:
- Adding new clubs or features
- Improving UI or styling
- Implementing backend support

# Contacts
- Zoya Farooqui - zfaro2@uic.edu - ZoyaF1
- Saima Ashrafi - sashr@uic.edu - saimaash14
- Safiyyah Ahmed - sahme213@uic.edu - safiyyah976
- Mishal Siddiqui - msidd82@uic.edu - mishalsidd

# Acknowledgments
Thank you to the SparkHacks 2026 organizing team and sponsors:
UIC Engineering Computer Science · UIC Engineering Makerspace · 8451° · Grainger · CME Group · Aedify.AI
Special thanks to all the SparkHacks mentors, fellow competitors, and workshop hosts!
