<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Angelo Jay Aleria - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header with Navigation -->
    <header>
        <nav>
            <ul>
                <li><a href="#profile">Profile</a></li>
                <li><a href="#hobbies">Hobbies</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    
    <section id="profile" class="section">
        <div class="profile">
            <img src="profile.jpg" alt="Angelo Jay Aleria" class="circle-image">
            <div class="profile-text">
                <h1>Angelo Jay Aleria</h1>
                <p><strong>Address:</strong> 123 Main Street, City, Country</p>
                <p><strong>Age:</strong> 25</p>
            </div>
        </div>
    </section>

    <!-- Hobbies Section -->
    <section id="hobbies" class="section">
        <h2>Hobbies</h2>
        <ul>
            <li><strong>Coding:</strong> Building interactive websites and applications.</li>
            <li><strong>Reading:</strong> Enjoying books on technology and self-improvement.</li>
            <li><strong>Gaming:</strong> Playing strategy and adventure games.</li>
            <li><strong>Traveling:</strong> Exploring new places and cultures.</li>
        </ul>
    </section>

    <!-- Education Section -->
    <section id="education" class="section">
        <h2>Educational Background</h2>
        <ul>
            <li><strong>Bachelor of Science in Computer Science</strong> - University of Tech (2020-2024)</li>
            <li><strong>High School Diploma</strong> - City High School (2016-2020)</li>
        </ul>
    </section>

    <!-- Footer with Contact Form -->
    <footer id="contact">
        <h2>Contact Me</h2>
        <form id="contactForm">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <label for="comment">Comment:</label>
            <textarea id="comment" name="comment" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </footer>

</body>
</html>


body {
    font-family: 'Times New Roman', serif;
    margin: 0;
    padding: 0;
    background-color: beige;
    color: #333;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    width: 100%;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #ff6347;
}


.section {
    padding: 20px;
    margin: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 90%;
    max-width: 800px;
}


.profile {
    display: flex;
    align-items: center;
    gap: 20px;
}

.circle-image {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #333;
}

.profile-text h1 {
    margin: 0;
    font-size: 2rem;
}

.profile-text p {
    margin: 10px 0 0;
    font-size: 1rem;
    color: #666;
}


#hobbies ul {
    list-style: none;
    padding: 0;
}

#hobbies ul li {
    background-color: #ff6347;
    color: #fff;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
}
#education ul {
    list-style: none;
    padding: 0;
}

#education ul li {
    background-color: #333;
    color: #fff;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
}


footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
    width: 100%;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin-bottom:
    }
