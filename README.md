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
    <title>Index Page</title>

</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
        <li>Item Four</li>
        <li>Item Five</li>
    </ol>
 <!-- External Image from Pexels -->
    <h2>Image</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Pexels Image" width="600">
      <!-- Contacts Table -->
    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Gideon Kimani</td>
            <td>123 pioneer eldoret</td>
            <td>0714263748</td>
            <td>kimanigideon@gmail.com</td>
        </tr>
        <tr>
            <td>Jane chebet</td>
            <td>458-kibuye kisumu</td>
            <td>0765432109</td>
            <td>janechebet@gmail.com</td>
        </tr>
        <tr>
            <td>Mark Lee Otieno</td>
            <td>789-karen nairobi</td>
            <td>0102938475</td>
            <td>kinglee@gmail.com</td>
        </tr>
        <tr>
            <td>Lisa Kwamboka</td>
            <td>321 kapsoya eldoret</td>
            <td>0756473829</td>
            <td>lisakwamboka@gmail.com</td>
        </tr>
        <tr>
            <td>Michael Olunga</td>
            <td>654-arthiriver nairobi</td>
            <td>0765748392</td>
            <td>michael007@gmail.com</td>
        </tr>
    </table>
     <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <fieldset>
            <legend>Personal information</legend>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br><br>
         
   <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
    
   <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter password" required>
            <br><br>
    
   <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
    
   <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male"> Male
            <input type="radio" id="female" name="gender" value="female"> Female
            <input type="radio" id="other" name="gender" value="other"> Other
            <br><br>
    
   <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="Kenya">Kenya</option>
                <option value="Ethiopia">Ethiopia</option>
                <option value="Tanzania">Tanzania</option>
                <option value="Nigeria">Nigeria</option>
                <option value="South africa">South Africa</option>
            </select>
            <br><br>
    
   <label>Interests:</label>
            <input type="checkbox" name="interests" value="coding"> Coding
            <input type="checkbox" name="interests" value="sports"> Sports
            <input type="checkbox" name="interests" value="music"> Music
            <br><br>
        </fieldset>


   <input type="submit" value="Register">
    </form>
    
</body>
</html>

