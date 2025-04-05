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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="HTML5 Advanced Elements Example" />
  <title>Advanced HTML5 Elements</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Advanced HTML5 Elements and Forms</h1>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
      <li>First Item</li>
      <li>Second Item</li>
      <li>Third Item</li>
      <li>Fourth Item</li>
      <li>Fifth Item</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/33537/pexels-photo-33537.jpeg" alt="Beautiful Landscape" width="600" />
  </section>

  <!-- Table of 5 Contacts -->
  <section>
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
          <td>John Doe</td>
          <td>123 Elm Street</td>
          <td>123-456-7890</td>
          <td>johndoe@email.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Oak Avenue</td>
          <td>987-654-3210</td>
          <td>janesmith@email.com</td>
        </tr>
        <tr>
          <td>Mark Johnson</td>
          <td>789 Pine Road</td>
          <td>555-123-4567</td>
          <td>markjohnson@email.com</td>
        </tr>
        <tr>
          <td>Emily Davis</td>
          <td>101 Maple Drive</td>
          <td>555-987-6543</td>
          <td>emilydavis@email.com</td>
        </tr>
        <tr>
          <td>Michael Brown</td>
          <td>202 Birch Lane</td>
          <td>555-321-9876</td>
          <td>michaelbrown@email.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="POST">

      <!-- Name Field -->
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required />

      <!-- Email Field -->
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required />

      <!-- Password Field -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter a password" required />

      <!-- Date Field -->
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required />

      <!-- Dropdown for Gender -->
      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>

      <!-- Radio Buttons for Subscription -->
      <fieldset>
        <legend>Subscribe to Newsletter:</legend>
        <input type="radio" id="yes" name="newsletter" value="yes" required />
        <label for="yes">Yes</label>
        <input type="radio" id="no" name="newsletter" value="no" />
        <label for="no">No</label>
      </fieldset>

      <!-- Checkboxes for Interests -->
      <fieldset>
        <legend>Select Your Interests:</legend>
        <input type="checkbox" id="coding" name="interests" value="coding" />
        <label for="coding">Coding</label>
        <input type="checkbox" id="sports" name="interests" value="sports" />
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music" />
        <label for="music">Music</label>
      </fieldset>

      <!-- Submit Button -->
      <input type="submit" value="Register" />
    </form>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 HTML5 Forms & Elements</p>
  </footer>

</body>
</html>
