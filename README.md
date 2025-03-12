# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.
## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form
>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact and Registration</title>
    <link rel="stylesheet" href="styles.css"> <!-- Optional: Link to external CSS -->
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h1>Ordered List of Items</h1>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Sample Image</h2>
    <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image" width="600">

    <!-- Table of Contacts -->
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
                <td>joseph karuri</td>
                <td>123 Nairobi, City</td>
                <td>(254) 456-7890</td>
                <td>karuri712@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 moshi, City</td>
                <td>(255) 654-3210</td>
                <td>karuri712@gmail.com</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>789 thika, City</td>
                <td>(254) 123-4567</td>
                <td>emily@gmail.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>321 kisumu, City</td>
                <td>(254) 987-6543</td>
                <td>michael@gmail.com</td>
            </tr>
            
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br>

        <!-- Date Field -->
        <label for="date">Date of Birth:</label>
        <input type="date" id="date" name="date" required>
        <br>

        <!-- Dropdown -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select Gender</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <br>

        <!-- Radio Buttons -->
        <fieldset>
            <legend>Newsletter Subscription:</legend>
            <label>
                <input type="radio" name="newsletter" value="yes" required> Yes
            </label>
            <label>
                <input type="radio" name="newsletter" value="no"> No
            </label>
        </fieldset>
        <br>

        <!-- Checkboxes -->
        <fieldset>
            <legend>Interests:</legend>
            <label>
                <input type="checkbox" name="interests" value="sports"> Sports
            </label>
            <label>
                <input type="checkbox" name="interests" value="music"> Music
            </label>
            <label>
                <input type="checkbox" name="interests" value="reading"> Reading
            </label>
        </fieldset>
        <br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>

