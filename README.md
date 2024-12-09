# Dex - Gamifying Ecology 🌿🎮

## Overview
**Dex - Gamifying Ecology** is a gamified, community-based flora sighting application designed to encourage data collection for environmental protection initiatives. Inspired by Pokémon and the Pokédex, this project combines the power of gamification and AI to make ecological data collection engaging and educational.

Users can:
- Capture images of plants.
- Use AI to identify plant species.
- Generate fictional Pokémon characters based on plant characteristics.
- Track sightings, explore a Pokédex-style interface, and compete on leaderboards.

---

## Features
### Core Functionalities
1. **Sign-Up and Login System**: Create and manage user accounts securely.
2. **Flora Identification**: Capture plant images and identify species using AI.
3. **Pokémon Generation**: Generate fictional Pokémon based on plant characteristics.
4. **Pokedex View**: Explore collected Pokémon-like entries.
5. **Leaderboards**: Compete with others to track contributions.
6. **Map View**: Visualize plant sightings on an interactive map.
7. **Export Sightings**: Download location-based data in JSON format.
8. **Card Printouts**: Generate Pokémon-like cards for individual sightings.

### Non-Functional Requirements
- **Strong Security**: Encrypted passwords and session tokens.
- **High Availability**: Reliable and responsive application with 99.8% uptime.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Fast AI Processing**: Efficient generation of plant data and Pokémon details.

---

## Project Architecture
The application is built using:
- **Spring Boot**: Backend framework for API management and database operations.
- **External APIs**: For plant identification, Pokémon generation, and mapping:
  - PlantNet API: Species identification.
  - Google Cloud AI API: Pokémon data generation.
  - OpenAI DALL-E API: Generative art for Pokémon characters.
  - Google Maps API: Map-based visualization of sightings.

### Database Design
The SQL database is designed with 10 interconnected tables to manage users, plant sightings, Pokémon data, and leaderboard rankings.

---

## Repository Structure
```plaintext
├── src/                               # Application source code
├── Documentation/                     # Project-related documentation
├── Final Release/                     # Final running Project
│   ├── Final Report.pdf               # Detailed project summary
│   ├── Project Proposal.pdf           # Initial project proposal
└── README.md                          # Project overview
```

---

## Usage
1. **Sign Up**: Create a new account.
2. **Capture Sightings**: Upload plant images to identify species and generate Pokémon-inspired entries.
3. **View Data**: Explore your Pokedex, leaderboard, or map view to see your contributions.
4. **Export Data**: Download sightings data in JSON format for further analysis or sharing.

For detailed instructions, refer to the [User Guide](./Documentation/Report.pdf).

---

## Future Work
1. **Microtransactions**: Introduce optional in-app purchases for additional features, such as rare Pokémon or enhanced tracking options.
2. **Daily Challenges**: Implement gamified tasks to encourage regular user engagement.
3. **Enhanced AI**: Improve the accuracy and speed of plant identification and Pokémon generation with newer AI models.

---

## Documentation
For more detailed information about the project, please refer to the following documents located in the `Documentation/` folder:

- **[Final Report](./Documentation/Report.pdf)**: Comprehensive overview of the project, including objectives, implementation, and results.
- **[Project Proposal](./Documentation/Proposal.pdf)**: Initial project concept and requirements.

---

## Acknowledgments
We would like to extend our gratitude to everyone who contributed to the success of this project:

- **Team Members**:
  - Daniel Chorev - 510502137
  - Zeeshan Ansari - 510370813
  - William Walker - 520659025
  - Nakul Reddy - 500066919
  - Syed Hamza Kaliyadan - 500585454
- **Supervisors**:
  - University of Sydney Faculty of Engineering

This project was developed as part of the **ELEC5619 - Advanced Software Engineering** course and reflects a collaborative effort to combine software engineering practices with environmental conservation goals.

Special thanks to our academic mentors and peers who provided feedback and support throughout the project development lifecycle.

---
