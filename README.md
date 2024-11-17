<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internship Application Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Internship Application Tracker</h1>
        <p>Select a category to view applications</p>
    </header>

    <main>
        <section id="categories">
            <h2>Categories</h2>
            <div class="category-list">
                <button onclick="showApplications('Finance')">Finance</button>
                <button onclick="showApplications('Marketing')">Marketing</button>
                <button onclick="showApplications('Engineering')">Engineering</button>
                <button onclick="showApplications('Technology')">Technology</button>
            </div>
        </section>

        <section id="applications">
            <h2>Applications</h2>
            <table id="application-table">
                <thead>
                    <tr>
                        <th>Company</th>
                        <th>Position</th>
                        <th>Opening Date</th>
                        <th>Closing Date</th>
                        <th>Apply Link</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- Applications will be dynamically inserted here -->
                </tbody>
            </table>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
