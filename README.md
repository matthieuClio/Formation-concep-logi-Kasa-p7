# Kasa – Dynamic lodging listing (JavaScript)

## Project context
This project was developed as part of the **Application Designer & Developer (React-oriented)** training program by OpenClassrooms.  
It's a JavaScript front-end project in the curriculum and focuses on building a dynamic, multi-page web application consuming local JSON data.

The goal was to create a lodging rental platform with multiple views including listings, filters, and a details page using modern JavaScript without frameworks.

## Educational objectives
- Build a dynamic front-end application using JavaScript (ES6+)
- Implement client-side routing
- Generate pages and components dynamically with DOM manipulation
- Consume and display data from a local JSON source
- Handle user navigation between routes
- Apply responsive design and interface logic

## Technologies used
- JavaScript (ES6+)
- HTML5
- CSS3
- DOM manipulation
- Client-side routing (hash/router)
- Git / GitHub
- GitHub Pages (deployment)

## Features
- Responsive listing of lodgings
- Dynamic routing to detail pages
- Display of lodging information, photos, and tags
- Star rating component
- Collapsible sections for description and equipment
- Error page for unknown routes

## Installation and use
No special prerequisites are required.

1. Clone the repository:
```bash
git clone https://github.com/matthieuClio/Formation-concep-logi-Kasa-p7.git
```
Open index.html in a modern browser.

## Architecture
.  
├── index.html  
├── css/  
│   └── style.css  
├── js/  
│   ├── app.js  
│   ├── router.js  
│   ├── components/  
│   │   ├── header.js  
│   │   ├── footer.js  
│   │   ├── card.js  
│   │   └── carousel.js  
├── data/  
│   └── lodgings.json  
├── images/  
└── README.md  


- HTML: Base template and mounting point
- CSS: Responsive layout and design
- JavaScript: Routing, rendering logic, event handling
- JSON data: Lodging dataset for dynamic content

## Areas for improvement
- Add search and filter functionality
- Implement lazy loading of images
- Refactor JavaScript into ES Modules and use bundler
- Add accessibility improvements (ARIA, keyboard)
- Add unit or integration tests

## Author
Project by Matthieu Clio  
Full stack JavaScript web developer
