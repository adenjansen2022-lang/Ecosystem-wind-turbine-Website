# Farm4Wind

Farm4Wind is a static educational website about wind energy and wind farming, built as a WPR181 project. It teaches visitors about renewable energy through structured lessons, tests their knowledge with quizzes, and points them to further resources.

## Features

- **Home page** – landing page introducing the site and its purpose
- **Lessons** – six lessons covering:
  1. Introduction to renewable energy
  2. What is wind energy
  3. Benefits of wind farming
  4. Economic benefits
  5. Challenges and limitations
  6. Future of wind energy
- **Quizzes** – six quizzes (one per lesson) so visitors can test what they've learned
- **Resources** – a page of further reading/reference material
- **Contact** – a contact page with site email and social links
- Consistent header navigation (with a Quizzes dropdown) and footer across every page

## Tech stack

- HTML5
- CSS3 (single stylesheet, CSS Grid-based layout)
- No JavaScript frameworks or build tools — plain static site

## Project structure

```
WPR181 Project final website/
├── README.md
└── HTML/
    ├── homepage.html          # Home page
    ├── lessons.html           # Lessons landing/overview page
    ├── LessonHome.html        # Lessons hub
    ├── lesson1.html – lesson6.html   # Individual lesson pages
    ├── quizzes.html           # Quizzes landing page
    ├── Quiz1.html – Quiz6.html       # Individual quiz pages
    ├── Resources.html         # Further resources
    ├── Contact.html           # Contact page
    ├── CSS/
    │   ├── styles.css                 # Main stylesheet
    │   ├── homepageBackground.jpg
    │   ├── contactBackground.jpg
    │   └── transition.jpg
    └── Images/                # Logo and all page/lesson imagery
```

## Getting started

No build step or server is required — this is a static HTML/CSS site.

1. Clone or download this repository.
2. Open `HTML/homepage.html` in your browser.
3. Navigate the site using the top navigation bar (Home, Lessons, Quizzes, Resources, Contact).

Alternatively, serve the `HTML` folder with any static file server, e.g.:

```bash
cd "HTML"
python3 -m http.server 8000
```

Then visit `http://localhost:8000/homepage.html`.

## Notes

- All internal links are relative, so the folder structure above should be kept intact for navigation and images/stylesheets to resolve correctly.
- Lesson content includes in-text citations to academic sources referenced during research for the project.

## License

This project was created for academic purposes (WPR181). No license has been specified — please check with the author before reusing content.
