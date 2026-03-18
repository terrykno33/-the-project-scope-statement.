# -the-project-scope-statement.
Provide an example of a selected section of the project scope statement.
this is exactly the kind of thing CodeSwing is great for. We’ll turn your assignment into a clean, interactive mini “project dashboard” using HTML + CSS (and optional JS later if you want).

🧱 1. Folder Structure (Create This First)

Inside your repository, set it up like this:

tiny-house-project/
│
├── index.html
├── style.css
├── script.js (optional for later)
│
├── /assets
│   ├── gantt.png (if you add image later)
│
└── /docs
    └── project.docx (your Word file if you export it)

👉 In VS Code:

Right-click → New Folder / New File

Or use terminal:

mkdir tiny-house-project
cd tiny-house-project
mkdir assets docs
touch index.html style.css script.js
🖥️ 2. CodeSwing Setup

If you're using CodeSwing:

Open the folder

Open index.html

CodeSwing will auto-render the UI as you build it

📄 3. HTML (Main Project Dashboard)

Paste this into index.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tiny House Project</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <h1>Tiny House Construction Project</h1>
    <p><strong>Project Manager:</strong> Your Name</p>
    <p><strong>Timeline:</strong> Jan 2 – Jan 21, 2025</p>

    <section>
        <h2>Purpose</h2>
        <p>
            Design and construct a fully functional, code-compliant tiny house,
            including structural build and MEP rough-in.
        </p>
    </section>

    <section>
        <h2>Scope</h2>

        <h3>In Scope</h3>
        <ul>
            <li>Architectural plans</li>
            <li>Foundation work</li>
            <li>Framing & roofing</li>
            <li>Siding</li>
            <li>MEP rough-in</li>
        </ul>

        <h3>Out of Scope</h3>
        <ul>
            <li>Interior decoration</li>
            <li>Landscaping</li>
            <li>Smart systems</li>
        </ul>
    </section>

    <section>
        <h2>Deliverables</h2>
        <ul>
            <li>Approved design</li>
            <li>Completed foundation</li>
            <li>Framed structure</li>
            <li>Installed roof & siding</li>
            <li>MEP system</li>
        </ul>
    </section>

    <section>
        <h2>Budget</h2>
        <table>
            <tr><th>Category</th><th>Cost</th></tr>
            <tr><td>Design</td><td>$800</td></tr>
            <tr><td>Foundation</td><td>$5,500</td></tr>
            <tr><td>Framing</td><td>$2,000</td></tr>
            <tr><td>Roofing</td><td>$2,500</td></tr>
            <tr><td>Siding</td><td>$2,300</td></tr>
            <tr><td>MEP</td><td>$6,000</td></tr>
            <tr><td>Inspection</td><td>$1,200</td></tr>
            <tr><th>Total</th><th>$21,500</th></tr>
        </table>
    </section>

    <section>
        <h2>Gantt Timeline</h2>
        <div class="gantt">
            <div class="task" style="width:20%">Finalize Floorplan</div>
            <div class="task" style="width:20%">Contract</div>
            <div class="task" style="width:30%">Foundation</div>
            <div class="task" style="width:20%">Framing</div>
            <div class="task" style="width:20%">Roof</div>
            <div class="task" style="width:20%">Siding</div>
            <div class="task" style="width:30%">MEP</div>
        </div>
    </section>

</div>

</body>
</html>
🎨 4. CSS Styling (Makes It Look Professional)

Paste into style.css:

body {
    font-family: Arial, sans-serif;
    background: #f4f6f8;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: auto;
    background: white;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h1 {
    color: #2c3e50;
}

h2 {
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 10px;
    text-align: left;
}

th {
    background-color: #3498db;
    color: white;
}

.gantt {
    margin-top: 20px;
}

.task {
    background: #2ecc71;
    color: white;
    padding: 8px;
    margin: 5px 0;
}
🚀 5. What You Just Built

This gives you:

A visual project dashboard

Clean academic structure

A basic Gantt-style visualization

Something you can demo in class (huge bonus)

🔥 Next Level (If You Want)

I can upgrade this into:

Real interactive Gantt chart (drag + timeline)

Export to PDF button

Editable fields (like a real PM tool)

React version (portfolio-worthy project 🔥)
