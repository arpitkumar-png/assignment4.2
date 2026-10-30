HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Application Form</title>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="job-application.html">Apply for Job</a></li>
            </ul>
        </nav>
        <h1>Career Portal — Job Application</h1>
        <p>Join our growing tech team! Please fill out the application form below.</p>
    </header>

    <main>
        <!-- Job Application Form Section -->
        <section>
            <form action="#" method="POST">

                <!-- Example of a Disabled Field -->
                <div>
                    <label for="app-status">Application Status:</label><br>
                    <input type="text" id="app-status" name="app-status" value="Accepting Submissions" disabled>
                </div>
                <br>

                <!-- Full Name -->
                <div>
                    <label for="fullname">Full Name:</label><br>
                    <input type="text" id="fullname" name="fullname" placeholder="Alex Morgan" required>
                </div>
                <br>

                <!-- Email -->
                <div>
                    <label for="email">Email Address:</label><br>
                    <input type="email" id="email" name="email" placeholder="alex.morgan@example.com" required>
                </div>
                <br>

                <!-- Phone -->
                <div>
                    <label for="phone">Phone Number:</label><br>
                    <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required>
                </div>
                <br>

                <!-- Date of Birth (Date Input) -->
                <div>
                    <label for="dob">Date of Birth:</label><br>
                    <input type="date" id="dob" name="dob" required>
                </div>
                <br>

                <!-- Portfolio URL (URL Input) -->
                <div>
                    <label for="portfolio">Portfolio Website URL:</label><br>
                    <input type="url" id="portfolio" name="portfolio" placeholder="https://github.com/username">
                </div>
                <br>

                <!-- Preferred Job Role (Dropdown / Select) -->
                <div>
                    <label for="job-role">Preferred Job Role:</label><br>
                    <select id="job-role" name="job_role" required>
                        <option value="" disabled selected>-- Select a Role --</option>
                        <option value="frontend">Front-End Developer</option>
                        <option value="backend">Back-End Developer</option>
                        <option value="fullstack">Full-Stack Developer</option>
                        <option value="uiux">UI/UX Designer</option>
                    </select>
                </div>
                <br>

                <!-- Preferred Shift (Radio Buttons with the same name) -->
                <div>
                    <label>Preferred Shift:</label><br>
                    <input type="radio" id="shift-morning" name="preferred_shift" value="morning" required>
                    <label for="shift-morning">Morning Shift (9 AM - 5 PM)</label><br>
                    
                    <input type="radio" id="shift-evening" name="preferred_shift" value="evening">
                    <label for="shift-evening">Evening Shift (1 PM - 9 PM)</label><br>
                    
                    <input type="radio" id="shift-night" name="preferred_shift" value="night">
                    <label for="shift-night">Night Shift (Flexible / Remote)</label>
                </div>
                <br>

                <!-- Technical Skills (Checkboxes) -->
                <div>
                    <label>Technical Skills:</label><br>
                    <input type="checkbox" id="skill-html" name="skills" value="html">
                    <label for="skill-html">HTML5 & CSS3</label><br>

                    <input type="checkbox" id="skill-js" name="skills" value="javascript">
                    <label for="skill-js">JavaScript (ES6)</label><br>

                    <input type="checkbox" id="skill-git" name="skills" value="git">
                    <label for="skill-git">Git & GitHub</label><br>

                    <input type="checkbox" id="skill-python" name="skills" value="python">
                    <label for="skill-python">Python</label>
                </div>
                <br>

                <!-- Cover Letter (Textarea) -->
                <div>
                    <label for="cover-letter">Cover Letter:</label><br>
                    <textarea id="cover-letter" name="cover_letter" rows="5" cols="40" placeholder="Tell us why you are a great fit for this position..." required></textarea>
                </div>
                <br>

                <!-- Submit Button -->
                <div>
                    <button type="submit">Submit Application</button>
                </div>

            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Career Portal. All rights reserved.</p>
    </footer>

</body>
</html>