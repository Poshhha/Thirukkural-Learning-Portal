# Thirukkural Learning Portal (திருக்குறள் மையம்)

An interactive Tamil-language educational website developed to support a primary-school teacher in delivering Thirukkural lessons to students at SJKT Mahizhamboo. It organizes learning material for Years 4, 5 and 6 in an accessible web format, combining verses, explanations, audio and links to interactive activities.

**Live Website:** https://portal-thirukkural.netlify.app/  
**GitHub:** https://github.com/Poshhha/Thirukkural-Learning-Portal

## Features

- **Year-based lessons:** Separate pages for Year 4, Year 5 and Year 6.
- **Tamil learning content:** Selected Thirukkural verses with Tamil meanings and explanations.
- **Audio playback:** Recorded readings with interactive audio controls.
- **Interactive learning:** Links to educational games and activities hosted on platforms such as Wordwall, Educaplay and Genially.
- **Student exercises:** Links to activities and response forms provided through Google Forms.
- **School information:** A homepage containing school background and expandable information sections.
- **Responsive interface:** Layout and styling designed to work across desktop and smaller screens.

## Technology Stack

- **HTML5** — page structure and lesson content
- **CSS3** — responsive layout, styling and visual effects
- **JavaScript (vanilla)** — interactive cards and audio controls
- **Netlify** — static website hosting
- **Google Forms / Wordwall / Educaplay / Genially** — linked third-party learning activities (not custom-built platform engines)

This version is a static website; it does not require a custom backend or database.

## Project Structure

```text
Thirukkural-Learning-Portal/
├── index.html            # Homepage and school information
├── year4.html            # Year 4 learning content
├── year5.html            # Year 5 learning content
├── year6.html            # Year 6 learning content
├── style.css             # Shared styles
├── four.mp3              # Year 4 audio
├── five.mp3              # Year 5 audio
├── six.mp3               # Year 6 audio
└── images/               # Images used by the website
```

## How to View Locally

1. Download the repository as a ZIP from GitHub and extract it.
2. Keep the HTML, CSS, audio files and `images/` folder together, preserving their relative paths.
3. Open `index.html` in a web browser.
4. Use the navigation to explore the Year 4, Year 5 and Year 6 sections.

Online activities and external forms require internet access.

## Purpose

The project was created as a practical teaching resource to make Thirukkural content easier to present and explore through a browser. It emphasizes Tamil-language accessibility, multimedia learning and interactive student engagement.

## Notes and Acknowledgments

School information and educational content were prepared for an educational context. Images, audio, verses, and linked third-party services retain their respective ownership and terms. External quizzes and forms are linked resources, not systems developed within this repository.
