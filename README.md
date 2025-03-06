<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Industrial Visit Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 500px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: auto;
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        .note {
            text-align: center;
            font-size: 14px;
            color: blue;
            margin-bottom: 20px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-top: 10px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .submit-btn {
            background-color: #28a745;
            color: white;
            font-size: 16px;
            font-weight: bold;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
        }
        .submit-btn:hover {
            background-color: #218838;
        }
        .footer {
            text-align: center;
            font-size: 14px;
            color: #555;
            margin-top: 20px;
            padding-top: 10px;
            border-top: 1px solid #ccc;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Govt. EFA Gorkhi H.S School</h1>
        <h2>Vocational Education Industrial Visits</h2>
        <p class="note">Please present at school with your consent form and submit it to the student who is collecting.</p>
        <h2>Industrial Visit Registration Form</h2>
        
        <form action="mailto:shrivastavavaibhav53@gmail.com" method="post" enctype="text/plain">
            <h3>Enter Name as per ID Card</h3>
            <label for="name">Name:</label>
            <input type="text" id="name" name="Name" required>

            <label for="class">Class:</label>
            <select id="class" name="Class" required>
                <option value="" disabled selected>Select Class</option>
                <option value="9th">9th</option>
                <option value="10th">10th</option>
                <option value="11th">11th</option>
                <option value="12th">12th</option>
            </select>

            <label for="section">Section:</label>
            <select id="section" name="Section" required>
                <option value="" disabled selected>Select Section</option>
                <option value="A">A</option>
                <option value="B">B</option>
                <option value="C">C</option>
                <option value="D">D</option>
                <option value="E">E</option>
                <option value="F">F</option>
            </select>

            <label for="roll">Roll No. (Max 12 digits):</label>
            <input type="number" id="roll" name="Roll_No" required maxlength="12" oninput="validateRollNo(this)">

            <label for="subject">Subject:</label>
            <select id="subject" name="Subject" required>
                <option value="" disabled selected>Select Subject</option>
                <option value="IT/ITes">IT/ITes</option>
                <option value="Electronic Hardware">Electronic Hardware</option>
                <option value="AI">AI</option>
            </select>

            <label for="guardian">Guardian's Name:</label>
            <input type="text" id="guardian" name="Guardian_Name">

            <label for="contact">Contact Number (10 digits only):</label>
            <input type="tel" id="contact" name="Contact_Number" required pattern="[0-9]{10}" title="Enter a valid 10-digit phone number">

            <label for="email">Email:</label>
            <input type="email" id="email" name="Email">

            <input type="submit" value="Submit" class="submit-btn">
        </form>

        <div class="footer">
            <p><strong>Trainer:</strong> Ms. Shivani Tripathi</p>
            <p><strong>Seniors:</strong><br>
            Aditya Singh Parmar (12th E)<br>
            Vaibhav Shrivastava (12th E)<br>
            Shivam Kushwah (12th E)</p>
        </div>
    </div>

    <script>
        function validateRollNo(input) {
            if (input.value.length > 12) {
                input.value = input.value.slice(0, 12);
            }
        }
    </script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Industrial Visit Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 500px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: auto;
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        .note {
            text-align: center;
            font-size: 14px;
            color: blue;
            margin-bottom: 20px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-top: 10px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .submit-btn {
            background-color: #28a745;
            color: white;
            font-size: 16px;
            font-weight: bold;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
        }
        .submit-btn:hover {
            background-color: #218838;
        }
        .footer {
            text-align: center;
            font-size: 14px;
            color: #555;
            margin-top: 20px;
            padding-top: 10px;
            border-top: 1px solid #ccc;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Govt. EFA Gorkhi H.S School</h1>
        <h2>Vocational Education Industrial Visits</h2>
        <p class="note">Please present at school with your consent form and submit it to the student who is collecting.</p>
        <h2>Industrial Visit Registration Form</h2>
        
        <form action="mailto:shrivastavavaibhav53@gmail.com" method="post" enctype="text/plain">
            <h3>Enter Name as per ID Card</h3>
            <label for="name">Name:</label>
            <input type="text" id="name" name="Name" required>

            <label for="class">Class:</label>
            <select id="class" name="Class" required>
                <option value="" disabled selected>Select Class</option>
                <option value="9th">9th</option>
                <option value="10th">10th</option>
                <option value="11th">11th</option>
                <option value="12th">12th</option>
            </select>

            <label for="section">Section:</label>
            <select id="section" name="Section" required>
                <option value="" disabled selected>Select Section</option>
                <option value="A">A</option>
                <option value="B">B</option>
                <option value="C">C</option>
                <option value="D">D</option>
                <option value="E">E</option>
                <option value="F">F</option>
            </select>

            <label for="roll">Roll No. (Max 12 digits):</label>
            <input type="number" id="roll" name="Roll_No" required maxlength="12" oninput="validateRollNo(this)">

            <label for="subject">Subject:</label>
            <select id="subject" name="Subject" required>
                <option value="" disabled selected>Select Subject</option>
                <option value="IT/ITes">IT/ITes</option>
                <option value="Electronic Hardware">Electronic Hardware</option>
                <option value="AI">AI</option>
            </select>

            <label for="guardian">Guardian's Name:</label>
            <input type="text" id="guardian" name="Guardian_Name">

            <label for="contact">Contact Number (10 digits only):</label>
            <input type="tel" id="contact" name="Contact_Number" required pattern="[0-9]{10}" title="Enter a valid 10-digit phone number">

            <label for="email">Email:</label>
            <input type="email" id="email" name="Email">

            <input type="submit" value="Submit" class="submit-btn">
        </form>

        <div class="footer">
            <p><strong>Trainer:</strong> Ms. Shivani Tripathi</p>
            <p><strong>Seniors:</strong><br>
            Aditya Singh Parmar (12th E)<br>
            Vaibhav Shrivastava (12th E)<br>
            Shivam Kushwah (12th E)</p>
        </div>
    </div>

    <script>
        function validateRollNo(input) {
            if (input.value.length > 12) {
                input.value = input.value.slice(0, 12);
            }
        }
    </script>

</body>
</html>
