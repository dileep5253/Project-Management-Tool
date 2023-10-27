# Project-Management-Tool
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Management Tool</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Project Management Tool</h1>
    </header>

    <main>
        <section id="project-details">
            <h2>Project Details</h2>
            <p>Project Name: Social Media Integration</p>
            <p>Description: A framework of social media sites for user communication.</p>
        </section>

        <section id="user-communication">
            <h2>User Communication</h2>
            <div id="message-board">
                <!-- User messages and communication will be displayed here -->
            </div>
            <div id="message-input">
                <input type="text" placeholder="Type your message...">
                <button id="send-message">Send</button>
            </div>
        </section>

        <section id="task-assignment">
            <h2>Task Assignment</h2>
            <ul id="task-list">
                <!-- Task list will be displayed here -->
            </ul>
            <div id="task-input">
                <input type="text" placeholder="Task description...">
                <select id="assignee">
                    <option value="user1">User 1</option>
                    <option value="user2">User 2</option>
                    <!-- Add more user options here -->
                </select>
                <button id="assign-task">Assign Task</button>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Project Management Tool</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
