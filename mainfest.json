<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taekwondo Attendance App</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <!-- Navigation bar -->
    <nav>
        <button class="nav-btn" id="attendance-btn">Attendance</button>
        <button class="nav-btn" id="view-btn">View</button>
        <button class="nav-btn" id="settings-btn">Settings</button>
    </nav>

    <!-- Attendance Page -->
    <section id="attendance-page" class="page">
        <header>
            <input type="text" id="search-bar" placeholder="Search student...">
            <input type="date" id="attendance-date">
        </header>
        <ul id="student-list" class="student-list">
            <!-- Dynamically populated student list will be inserted here -->
        </ul>
        <button class="save-btn" id="save-attendance">Save</button>
    </section>

    <!-- View Page -->
    <section id="view-page" class="page hidden">
        <header>
            <input type="date" id="view-date">
        </header>
        <ul id="view-list" class="student-list">
            <!-- Dynamically populated attendance view -->
        </ul>
    </section>

    <!-- Settings Page -->
    <section id="settings-page" class="page hidden">
        <div class="settings-section">
            <h3>Add New Student</h3>
            <input type="text" id="new-student-name" placeholder="Enter student name">
            <button id="add-student">Add</button>
        </div>
        <div class="settings-section">
            <h3>Edit Student Name(s)</h3>
            <button id="edit-student-btn">Edit Students</button>
            <div id="edit-student-popup" class="popup hidden">
                <ul id="edit-student-list">
                    <!-- Dynamically populated student edit list -->
                </ul>
                <button id="save-edits">Save</button>
                <button id="discard-edits">Discard</button>
            </div>
        </div>
        <div class="settings-section">
            <h3>Export Data</h3>
            <button id="export-data">Export to Excel</button>
        </div>
    </section>

</body>
</html>