<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Learning CSS</li>
            <li>Mastering JavaScript</li>
            <li>Web Development Best Practices</li>
            <li>Building Projects</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/30081518/pexels-photo-30081518/free-photo-of-serene-greenhouse-with-lush-botanical-pathway.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Beautiful landscape" width="600">
    </section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Alex Kiptoo</td>
                    <td>Nairobi</td>
                    <td>074567890</td>
                    <td>keteralex29@gmail.com</td>
                </tr>
                <tr>
                    <td>Ivan Tum</td>
                    <td>Eldoret</td>
                    <td>07654321</td>
                    <td>ivan26@gmail.com</td>
                </tr>
                <tr>
                    <td>Taylor Tarus</td>
                    <td>Nakuru</td>
                    <td>0122334455</td>
                    <td>taylor26@gmail.com</td>
                </tr>
                <tr>
                    <td>vincent kibungei</td>
                    <td>Athi River</td>
                    <td>0744332211</td>
                    <td>vinny12@gmail.com</td>
                </tr>
                <tr>
                    <td>Sarah cheptoo</td>
                    <td>Greenfield</td>
                    <td>077889900</td>
                    <td>sarahlee@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>
        <h2>Registration Form</h2>
        <form action="/submit" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select><br><br>

            <label>Subscribe to Newsletter:</label><br>
            <input type="radio" id="subscribeYes" name="subscribe" value="yes">
            <label for="subscribeYes">Yes</label><br>
            <input type="radio" id="subscribeNo" name="subscribe" value="no">
            <label for="subscribeNo">No</label><br><br>
        
            <label for="terms">I agree to the Terms and Conditions:</label>
            <input type="checkbox" id="terms" name="terms" required><br><br>

            <input type="submit" value="Register">
        </form>
    </section>

    <section>
        <h2>Multimedia</h2>

        <audio controls>
            <source src="audio/song.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio><br><br>

        <video width="320" height="240" controls>
            <source src="video/sample.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>
</body>
</html>
