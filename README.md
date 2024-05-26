<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Admission Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="date"],
        input[type="tel"],
        select {
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            width: 100%;
        }
        input[type="submit"] {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        .form-section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Online Admission Form</h2>
    <form action="#" method="post">
        <div class="form-section">
            <label for="fullname">Full Name</label>
            <input type="text" id="fullname" name="fullname" required>
        </div>
        
        <div class="form-section">
            <label for="fullname">Father's Name</label>
            <input type="text" id="fullname" name="fullname" required>
        </div>
        
        <div class="form-section">
            <label for="fullname">Mother's Name</label>
            <input type="text" id="fullname" name="fullname" required>
        </div>
        
        <div class="form-section">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
        </div>
        
        <div class="form-section">
            <label for="phone">Phone Number 1</label>
            <input type="tel" id="phone" name="phone" required>
        </div>
        
        <div class="form-section">
            <label for="phone">Phone Number 2</label>
            <input type="tel" id="phone" name="phone" required>
        </div>
        
        <div class="form-section">
            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>
        </div>
        
        <div class="form-section">
            <label for="gender">Gender</label>
            <select id="gender" name="gender" required>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
        </div>
        
        <div class="form-section">
            <label for="birth_certificate_number">Birth Certificate Number</label>
            <input type="text" id="birth_certificate_number" name="birth_certificate_number" required>
        </div>
        
        <div class="form-section">
            <label for="birth_place">Place of Birth</label>
            <input type="text" id="birth_place" name="birth_place" required>
        </div>
        
        <div class="form-section">
            <label for="parent_name">Parent's/Guardian's Name</label>
            <input type="text" id="parent_name" name="parent_name" required>
        </div>
        
        <div class="form-section">
            <label for="address">Address</label>
            <input type="text" id="address" name="address" required>
        </div>
        
        <div class="form-section">
            <input type="submit" value="Submit">
        </div>
    </form>
</div>

</body>
</html>
