# Moodie Webpage

**Moodie** is a simple HTML/CSS based web-page project that supports your digital product from the “Moodie” concept you built: letting users select curated playlists based on their emotional state.  
This webpage serves as a front-end showcase and user-interface prototype of that idea.

---

## Table of Contents  
- [Project Motivation](#project-motivation)  
- [Features](#features)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Technologies](#technologies)  
- [Contributing](#contributing)  
- [License](#license)

---

## Project Motivation  
You created *Moodie* to help improve mental wellness by aligning music with emotional states, and this web-page brings that concept to the web, allowing a user to select a mood and see a visual and interactive representation of that mood.  
It serves both as a prototype and a foundation for further development (e.g., adding backend/data, playlist integration, accessibility features).

---

## Features  
- A clean, responsive landing page (`index.html`).  
- Dedicated pages/views for a variety of moods (e.g., “Anxious”, “Chill”, “Happy”, “Sad”, etc.).  
- Visual assets (icons/images) corresponding to each mood.  
- A consistent stylesheet (`style.css`) that handles the visual presentation.  
- Simple navigation and mood-based structure to demonstrate the core user flow.

---

## Getting Started  
### Prerequisites  
- A web browser (Chrome, Firefox, Safari, etc.)  
- (Optional) A local static server if you want to test features e.g., `live-server`, `http-server`, or similar.

### Installation / Setup  
1. Clone the repository to your local machine:  
   ```bash  
   git clone https://github.com/chellexra/moodie-webpage.git

**2. Navigate into the project directory:**
cd moodie-webpage  

**3. Open index.html in your browser to view the project.**

Or if using a static server:

npx http-server .  

Then go to http://localhost:8080 (or whichever port).

Usage

Open the landing page (index.html).

Select or click a mood of interest.

Navigate to the mood-specific page to see visuals/icons and content tailored to that emotional state.

From here you may integrate further-connections like playlist links, audio previews, data analytics, or user personalization.

moodie-webpage/
├── icons/                 # Mood icons and asset images  
├── images/                # Other image assets  
├── index.html             # Landing page  
├── style.css              # Global stylesheet  
├── moodie.html            # Secondary page / main mood picker  
├── anxious-page.html      # Mood “Anxious”  
├── chill-page.html        # Mood “Chill”  
├── happyPage.html         # Mood “Happy”  
├── sad-page.html          # Mood “Sad”  
├── emb …                  # etc. other mood pages  
└── tech.html              # Technology or about page  

Note: filenames may vary slightly — please refer to the folder listing in the repository for exact names.

**Technologies**

**HTML5** for structure and markup.

**CSS3** for styling and layout.

No runtime frameworks (vanilla static pages) — which keeps it lightweight and easy to host anywhere.

Designed with accessibility and visual clarity in mind (future work may include keyboard navigation, ARIA labels, etc.).


