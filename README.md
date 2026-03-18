# -the-project-scope-statement.
1. GitHub Repository Description

Repository Name: Tiny-House-Construction
Description:
This repository contains the complete Tiny House Construction Project, including WBS Dictionary, project scope, design files, HTML/CSS templates, and CodeSwing examples. It serves as a structured blueprint for pre-construction, construction, and close-out phases of the project.

2. Folder Structure & README.md

Folder Structure:

Tiny-House-Construction/
│
├── README.md
├── WBS/
│   └── WBS-Dictionary-Tiny-House.md
├── Scope/
│   └── Tiny_House_Project_Scope_Statement.md
├── CodeSwing/
│   └── code_examples.swing
├── HTML/
│   └── index.html
├── CSS/
│   └── style.css
└── Assets/
    └── images/

README.md:

# Tiny House Construction Project

## Overview
This project organizes all resources, designs, and templates for the Tiny House Construction Project. It follows the WBS Dictionary and Project Scope Statement for clarity and efficiency.

## Folder Structure
- **WBS/**: Work Breakdown Structure Dictionary
- **Scope/**: Project Scope Statement
- **CodeSwing/**: CodeSwing project files
- **HTML/**: HTML templates for project documentation or web previews
- **CSS/**: Stylesheets for HTML
- **Assets/**: Images and media

## Usage
1. Review the WBS Dictionary to understand task breakdown.
2. Follow the Project Scope Statement for project boundaries.
3. Open HTML and CSS files for web-based project previews.
4. Load CodeSwing files in CodeSwing IDE for interactive coding.

## Author
[Your Name Here]
3. HTML Template (index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiny House Construction Project</title>
    <link rel="stylesheet" href="../CSS/style.css">
</head>
<body>
    <header>
        <h1>Tiny House Construction Project</h1>
    </header>

    <section id="overview">
        <h2>Project Overview</h2>
        <p>This project organizes all resources, designs, and templates for the Tiny House Construction Project.</p>
    </section>

    <section id="wbs">
        <h2>WBS Dictionary</h2>
        <p>All work packages, owners, dependencies, resources, and timelines are detailed here.</p>
    </section>

    <footer>
        <p>&copy; 2026 Tiny House Project</p>
    </footer>
</body>
</html>
4. CSS Template (style.css)
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

/* Header */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Sections */
section {
    padding: 20px;
    margin: 10px auto;
    max-width: 900px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: #eee;
    margin-top: 20px;
}
5. CodeSwing Template (code_examples.swing)
// Tiny House Project CodeSwing Template
// Interactive JS Example for Project Planning

console.log("Welcome to Tiny House Construction Project");

let tasks = [
    { id: "1.1.1.1", name: "Finalize Floorplan", owner: "Architect", status: "Complete" },
    { id: "1.1.1.2", name: "Execute Construction Contract", owner: "Project Manager", status: "Complete" },
    { id: "1.2.1.1", name: "Pour & Cure Cement", owner: "Crew Lead", status: "In Progress" }
];

tasks.forEach(task => {
    console.log(`Task: ${task.name}, Owner: ${task.owner}, Status: ${task.status}`);
});
