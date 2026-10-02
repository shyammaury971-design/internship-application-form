# internship-application-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internship Application Form</title>
</head>

<body>

    <h1>Internship Application Form</h1>
    <p>Please fill in the details below to apply for the internship.</p>

    <form>

        <fieldset>
            <legend>Personal Information</legend>

            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter phone number">
            <br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob">
            <br><br>

            <label>Gender:</label>
            <input type="radio" name="gender" value="male"> Male
            <input type="radio" name="gender" value="female"> Female
            <input type="radio" name="gender" value="other"> Other

        </fieldset>

        <br>

        <fieldset>
            <legend>Education</legend>

            <label for="college">College/University:</label>
            <input type="text" id="college" name="college" placeholder="Enter college name">
            <br><br>

            <label for="degree">Degree:</label>
            <select id="degree" name="degree">
                <option value="">Select Degree</option>
                <option value="btech">B.Tech</option>
                <option value="bsc">B.Sc</option>
                <option value="bca">BCA</option>
                <option value="mtech">M.Tech</option>
                <option value="msc">M.Sc</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <label for="year">Graduation Year:</label>
            <input type="number" id="year" name="year" placeholder="2027">

        </fieldset>

        <br>

        <fieldset>
            <legend>Internship Details</legend>

            <label for="domain">Internship Domain:</label>
            <select id="domain" name="domain">
                <option value="">Select Domain</option>
                <option value="web">Web Development</option>
                <option value="ai">Artificial Intelligence</option>
                <option value="biotech">Biotechnology</option>
                <option value="data">Data Science</option>
                <option value="software">Software Development</option>
            </select>

            <br><br>

            <label>Skills:</label><br>
            <input type="checkbox" name="skill" value="html"> HTML
            <input type="checkbox" name="skill" value="css"> CSS
            <input type="checkbox" name="skill" value="javascript"> JavaScript
            <input type="checkbox" name="skill" value="java"> Java
            <input type="checkbox" name="skill" value="sql"> SQL

            <br><br>

            <label for="resume">Upload Resume:</label>
            <input type="file" id="resume" name="resume">

            <br><br>

            <label for="message">Why do you want this internship?</label><br>
            <textarea id="message" name="message" rows="5" cols="40"
                placeholder="Write your answer here..."></textarea>

        </fieldset>

        <br>

        <input type="checkbox" required>
        I confirm that the information provided is correct.

        <br><br>

        <button type="submit">Submit Application</button>
        <button type="reset">Reset Form</button>

    </form>

</body>
</html>
