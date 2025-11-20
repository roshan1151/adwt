slip 1
-------------------------------------------------------
<!DOCTYPE html>
<html>
<head>
    <style>
        Body {
            font-family: Arial, sans-serif;
        }
        H1 {
            Font-size: 6pt;
            Color: black;
        }
        Form {
            Background-color: lightblue;
        }
    </style>
</head>
<body>
    <h1><b>Project Management</b></h1>
    <form action=””> <label for=”projectname”>Project Name:</label>
        <input type=”text” id=”projectname” name=”projectname”><br><br>
        <label for=”assignedto”>Assigned to:</label>
        <input type=”text” id=”assignedto” name=”assignedto”><br><br>
        <label for=”startdate”>Start Date:</label>
        <input type=”date” id=”startdate” name=”startdate”><br><br>
        <label for=”enddate”>End Date:</label>
        <input type=”date” id=”enddate” name=”enddate”><br><br>
        <label for=”priority”>Priority:</label>
        <select id=”priority” name=”priority”>
            <option value=”high”>High</option>
            <option value=”average”>Average</option>
            <option value=”low”>Low</option>
        </select><br><br>
        <label for=”description”>Description:</label>
        <textarea id=”description” name=”description” rows=”4” cols=”50”></textarea><br><br>
        <input type=”submit” value=”Submit”>
        <input type=”submit” value=”clear”>
    </form>
</body>
</html>
---------------------------------------------------------------------------  
slip 2
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Container Example</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Column 1</h5>
                        <p class="card-text">Content for column 1.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Column 2</h5>
                        <p class="card-text">Content for column 2.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Column 3</h5>
                        <p class="card-text">Content for column 3.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Bootstrap JS (Optional, for certain components) -->
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
---------------------------------------------------------------------------  
slip 3
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <title>Image Thumbnails</title>
</head>
<body>
    <div class="container mt-5">
        <h2 class="mb-4">Image Thumbnails</h2>
        <div class="row">
            <!-- Image 1 -->
            <div class="col-md-4">
                <div class="thumbnail">
                    <img src="path/to/image1.jpg" alt="Image 1" class="img-fluid">
                    <div class="caption">
                        <h4>Image 1</h4>
                    </div>
                </div>
            </div>
            <!-- Image 2 -->
            <div class="col-md-4">
                <div class="thumbnail">
                    <img src="path/to/image2.jpg" alt="Image 2" class="img-fluid">
                    <div class="caption">
                        <h4>Image 2</h4>
                    </div>
                </div>
            </div>
            <!-- Image 3 -->
            <div class="col-md-4">
                <div class="thumbnail">
                    <img src="path/to/image3.jpg" alt="Image 3" class="img-fluid">
                    <div class="caption">
                        <h4>Image 3</h4>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
---------------------------------------------------------------------------  
slip 4
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Table Example</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <!-- Container with margin-top (mt-5) -->
        <h2 class="mb-4">User Information Table</h2>
        <table class="table">
            <!-- Bootstrap Table -->
            <thead>
                <!-- Table Header -->
                <tr>
                    <th scope="col">First Name</th>
                    <th scope="col">Last Name</th>
                    <th scope="col">Email ID</th>
                </tr>
            </thead>
            <tbody>
                <!-- Table Body -->
                <tr>
                    <td>John</td>
                    <td>Doe</td>
                    <td>john.doe@example.com</td>
                </tr>
                <tr>
                    <td>Jane</td>
                    <td>Smith</td>
                    <td>jane.smith@example.com</td>
                </tr>
                <!-- Add more rows as needed -->
            </tbody>
        </table>
        <!-- End of Bootstrap Table -->
    </div>
    <!-- End of Container -->
    <!-- Bootstrap JS (Optional, for certain components) -->
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
---------------------------------------------------------------------------  
slip 5
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List of Persons</title>
    <style>
        table {
            border-collapse: collapse;
            width: 50%;
            margin: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
        }
        th,
        td {
            border: 1px solid #ddd;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h2>List of Persons</h2>
    <table>
        <thead>
            <tr>
                <th>Srno</th>
                <th>Person Name</th>
                <th>Age</th>
                <th>Country</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>John Doe</td>
                <td>30</td>
                <td>USA</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Jane Smith</td>
                <td>25</td>
                <td>Canada</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Bob Johnson</td>
                <td>35</td>
                <td>UK</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
---------------------------------------------------------------------------  
slip 7
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Text Effect</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .three-d-text {
            font-size: 3em;
            font-weight: bold;
            color: #3498db;
            text-shadow: 4px 4px 0 #2980b9, 7px 7px 0 #2c3e50;
            transition: transform 0.3s ease-in-out;
        }
        .three-d-text:hover {
            transform: translate(3px, 3px);
        }
    </style>
</head>
<body>
    <div class="three-d-text">Hover me!</div>
</body>
</html>
---------------------------------------------------------------------------  
slip 9
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input,
        select {
            width: 100%;
            padding: 10px;
            margin-bottom: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4caf50;
            color: #fff;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <form action="#" method="post">
        <h2>Student Registration Form</h2>
        <label for="fullName">Full Name:</label>
        <input type="text" id="fullName" name="fullName" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="dateOfBirth">Date of Birth:</label>
        <input type="date" id="dateOfBirth" name="dateOfBirth" required>
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <label for="course">Select Course:</label>
        <select id="course" name="course" required>
            <option value="computerScience">Computer Science</option>
            <option value="engineering">Engineering</option>
            <option value="biology">Biology</option>
            <!-- Add more options as needed -->
        </select>
        <label for="searchCollege">Search for College:</label>
        <input type="search" id="searchCollege" name="searchCollege">
        <label for="comments">Additional Comments:</label>
        <textarea id="comments" name="comments" rows="4"></textarea>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
---------------------------------------------------------------------------  
slip 10
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Transition Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            background-color: #4caf50;
            color: #fff;
            border-radius: 4px;
            transition-property: background-color, color;
            transition-duration: 0.6s;
            transition-delay: 0.1s;
        }
        button:hover {
            background-color: #fe3618;
            color: #e0e0e0;
        }
    </style>
</head>
<body>
    <button>Hover Me</button>
</body>
</html>
---------------------------------------------------------------------------  
slip 11
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            height: 100vh;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        main {
            display: flex;
            flex: 1;
        }
        nav {
            width: 200px;
            background-color: #f0f0f0;
            padding: 10px;
            box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
        }
        nav a {
            display: block;
            margin-bottom: 10px;
            text-decoration: none;
            color: #333;
        }
        article {
            flex: 1;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Company Name</h1>
    </header>
    <main>
        <nav>
            <a href="#" onclick="showDepartment('department1'); return false;">Department 1</a>
            <a href="#" onclick="showDepartment('department2'); return false;">Department 2</a>
            <a href="#" onclick="showDepartment('department3'); return false;">Department 3</a>
            <!-- Add more departments as needed -->
        </nav>
        <article id="department-info">
            <!-- Department information will be displayed here -->
        </article>
    </main>
    <script>
        function showDepartment(department) {
            // You can replace the following line with an AJAX request to fetch department information from the server
            const departmentInfo = getDepartmentInfo(department);
            // Display department information in the third frame (article)
            document.getElementById('department-info').innerHTML = departmentInfo;
        }
        function getDepartmentInfo(department) {
            // Simulated department information, replace this with actual data
            const departmentData = {
                department1: 'Information for Department 1',
                department2: 'Information for Department 2',
                department3: 'Information for Department 3',
                // Add more departments as needed
            };
            return departmentData[department] || 'Department information not available.';
        }
    </script>
</body>
</html>
---------------------------------------------------------------------------  
slip 12
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        form {
            max-width: 600px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input,
        select,
        textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        textarea {
            resize: vertical;
            height: 100px;
        }
        button {
            background-color: #4caf50;
            color: #fff;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button[type="reset"] {
            background-color: #f44336;
        }
    </style>
</head>
<body>
    <form id="customerRegistrationForm">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="contactNo">Contact Number:</label>
        <input type="tel" id="contactNo" name="contactNo" pattern="[0-9]{10}" required>
        <small>Enter a 10-digit phone number.</small>
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <label for="preferredDays">Preferred Days of Purchasing:</label>
        <input type="text" id="preferredDays" name="preferredDays">
        <label for="favoriteItem">Favorite Item:</label>
        <select id="favoriteItem" name="favoriteItem">
            <option value="clothing">Clothing</option>
            <option value="electronics">Electronics</option>
            <option value="homeAppliances">Home Appliances</option>
            <option value="groceries">Groceries</option>
        </select>
        <label for="suggestions">Suggestions:</label>
        <textarea id="suggestions" name="suggestions"></textarea>
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
    </form>
</body>
</html>
---------------------------------------------------------------------------  
slip 13
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fictional Tech Product</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        nav {
            background-color: #555;
            color: #fff;
            padding: 10px;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 15px;
        }
        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        aside {
            float: right;
            width: 30%;
            padding: 20px;
            background-color: #ddd;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            clear: both;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fictional Tech Product</h1>
    </header>
    <nav>
        <a href="#features">Features</a>
        <a href="#specs">Specifications</a>
        <a href="#buy">Buy Now</a>
    </nav>
    <section id="features">
        <h2>Features</h2>
        <p>This fictional tech product comes with amazing features to enhance your
            experience.</p>
        <ul>
            <li>Wireless Connectivity</li>
            <li>Long Battery Life</li>
            <li>High-Resolution Display</li>
            <li>Advanced Security</li>
        </ul>
    </section>
    <section id="specs">
        <h2>Specifications</h2>
        <p>Check out the technical specifications of our product:</p>
        <ul>
            <li>Processor: Quad-core, 2.0 GHz</li>
            <li>Memory: 8 GB RAM</li>
            <li>Storage: 256 GB SSD</li>
            <li>Operating System: TechOS</li>
        </ul>
    </section>
    <section id="buy">
        <h2>Buy Now</h2>
        <p>Purchase this amazing product today!</p>
    </section>
    <aside>
        <h2>Special Offer</h2>
        <p>For a limited time, get a 20% discount on your purchase. Use code: TECH20.</p>
    </aside>
    <footer>
        <p>&copy; 2023 Fictional Tech Company | Contact us at info@fictionaltech.com</p>
    </footer>
</body>
</html>
---------------------------------------------------------------------------  
slip 14
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Plan Booking Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        form {
            max-width: 400px;
            margin: auto;
        }
        label {
            display: block;
            margin-bottom: 8px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-bottom: 12px;
            box-sizing: border-box;
        }
        input[type="checkbox"] {
            width: auto;
            margin-right: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button[type="reset"] {
            background-color: #f44336;
        }
    </style>
</head>
<body>
    <form id="travelForm">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="address">Address:</label>
        <input type="text" id="address" name="address" required>
        <label for="contact">Contact No.:</label>
        <input type="tel" id="contact" name="contact" required>
        <label>Gender:</label>
        <label for="male">Male</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="female">Female</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="season">Preferred Season:</label>
        <label for="spring">Spring</label>
        <input type="checkbox" id="spring" name="season" value="spring">
        <label for="summer">Summer</label>
        <input type="checkbox" id="summer" name="season" value="summer">
        <label for="autumn">Autumn</label>
        <input type="checkbox" id="autumn" name="season" value="autumn">
        <label for="winter">Winter</label>
        <input type="checkbox" id="winter" name="season" value="winter">
        <label for="locationType">Location Type:</label>
        <select id="locationType" name="locationType" required>
            <option value="" disabled selected>Select Location Type</option>
            <option value="beach">Beach</option>
            <option value="mountain">Mountain</option>
            <option value="city">City</option>
            <option value="countryside">Countryside</option>
        </select>
        <div style="text-align: center; margin-top: 20px;">
            <button type="submit">Submit</button>
            <button type="reset">Reset</button>
        </div>
    </form>
    <script>
        document.getElementById('travelForm').addEventListener('submit', function (e) {
            e.preventDefault(); // Prevent the default form submission
            // You can add code here to handle the form submission, e.g., sending data to a server
        });
    </script>
</body>
</html>
---------------------------------------------------------------------------  
slip 15
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang=”en”>
<head>
    <meta charset=”UTF-8”>
    <meta name=”viewport” content=”width=device-width, initial-scale=1.0”>
    <title>Registration Form</title>
    <link rel=”stylesheet” href=https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css>
</head>
<body>
    <div class=”container”>
        <div class=”row”>
            <div class=”col-md-6 offset-md-3”>
                <h4>Registration Form</h4>
                <form>
                    <div class=”form-group”>
                        <label for=”firstname”>First Name</label>
                        <input type=”text” class=”form-control” id=”firstname” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”lastname”>Last Name</label>
                        <input type=”text” class=”form-control” id=”lastname” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”department”>Department / Office</label>
                        <select class=”form-control” id=”department” required>
                            <option>IT</option>
                            <option>Sales</option>
                            <option>HR</option>
                            <option>Marketing</option>
                        </select>
                    </div>
                    <div class=”form-group”>
                        <label for=”username”>Username</label>
                        <input type=”text” class=”form-control” id=”username” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”password”>Password</label>
                        <input type=”password” class=”form-control” id=”password” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”confirm-password”>Confirm Password</label>
                        <input type=”password” class=”form-control” id=”confirm-password” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”email”>E-Mail</label>
                        <input type=”email” class=”form-control” id=”email” required>
                    </div>
                    <div class=”form-group”>
                        <label for=”contact”>Contact No.</label>
                        <input type=”text” class=”form-control” id=”contact” required>
                    </div>
                    <button type=”submit” class=”btn btn-primary”>Submit</button>
                </form>
            </div>
        </div>
    </div>
    <script src=https://code.jquery.com/jquery-3.5.1.slim.min.js></script>
    <script src=https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js></script>
    <script src=https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js></script>
</body>
</html>
---------------------------------------------------------------------------  
slip 16
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <h2>Contact Us</h2>
        <form>
            <div class="mb-3">
                <label class="form-label">Name</label>
                <input type="text" class="form-control" required>
            </div>
            <div class="mb-3">
                <label class="form-label">Email</label>
                <input type="email" class="form-control" required>
            </div>
            <div class="mb-3">
                <label class="form-label">Message</label>
                <textarea class="form-control" rows="4" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
            <button type="reset" class="btn btn-secondary">Reset</button>
        </form>
    </div>
</body>
</html>
---------------------------------------------------------------------------  
slip 17
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Example</title>
    <style>
        .box {
            border: 2px solid #000;
            padding: 10px;
            background-color: yellow;
            width: 300px;
        }
        .box div {
            margin: 5px 0;
            background-color: yellow;
            padding: 5px;
            border: 2px solid #000;
        }
        .Outerbox {
            width: 400px;
            height: 200px;
            display: flex;
            border: 2px solid #000;
            background-color: orange;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="Outerbox">
        <div class="box">
            <div>M.Sc Computer Science</div>
            <div>Academic Year 2023-24</div>
        </div>
        <div>
</body>
</html>
---------------------------------------------------------------------------  
slip 18
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2D Transformation Example</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        img {
            transform-origin: center center;
            transition: transform 0.5s ease-in-out;
        }
    </style>
</head>
<body>
    <img id="transformImage" src="https://picsum.photos/200" alt="Transformed Image" width="200">
    <script>
        const transformImage = document.getElementById('transformImage');
        // Apply combined transformations after 1 second
        setTimeout(() => {
            transformImage.style.transform = 'rotate(45deg) scale(1.5) translate(50px, 50px)';
        }, 1000);
    </script>
</body>
</html>
---------------------------------------------------------------------------  
slip 21
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input {
            width: 100%;
            padding: 8px;
            margin-bottom: 12px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="reset"] {
            background-color: #f44336;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-left: 10px;
        }
        .required {
            color: red;
        }
        .message {
            margin-top: 10px;
            padding: 10px;
            background-color: #e7f3fe;
            border: 1px solid #4e7dcb;
            border-radius: 4px;
            display: none;
        }
        input:required {
            border: 2px solid red;
        }
    </style>
</head>
<body>
    <form id="registrationForm">
        <label for="firstName">First Name<span class="required">*</span>:</label>
        <input type="text" id="firstName" name="firstName" required>
        <label for="lastName">Last Name<span class="required">*</span>:</label>
        <input type="text" id="lastName" name="lastName" required>
        <label for="email">Email<span class="required">*</span>:</label>
        <input type="email" id="email" name="email" required>
        <label for="password">Password<span class="required">*</span>:</label>
        <input type="password" id="password" name="password" required>
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
        <div class="message" id="successMessage">Registration Successful!</div>
        <div class="message" id="errorMessage">Error submitting the form. Please try again.</div>
    </form>
    <script>
        const registrationForm = document.getElementById('registrationForm');
        const successMessage = document.getElementById('successMessage');
        const errorMessage = document.getElementById('errorMessage');
        registrationForm.addEventListener('submit', function (e) {
            e.preventDefault(); // Prevent the default form submission
            // You can add code here to handle the form submission, e.g., sending data to a server
            // For demonstration purposes, show a success message
            successMessage.style.display = 'block';
            // Clear the form after a delay (in a real scenario, this may be replaced with appropriate logic)
            setTimeout(() => {
                registrationForm.reset();
                successMessage.style.display = 'none';
            }, 3000);
        });
        registrationForm.addEventListener('reset', function () {
            // Reset the success message on form reset
            successMessage.style.display = 'none';
        });
    </script>
</body>
</html>
---------------------------------------------------------------------------  
slip 23
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Display with Rotation</title>
    <style>
        body {
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        #imageContainer {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .imageTile {
            width: 150px;
            height: 150px;
            overflow: hidden;
            border: 1px solid #ddd;
            margin: 5px;
        }
        img {
            max-width: 100%;
            max-height: 100%;
            transform-origin: center center;
            transition: transform 0.3s ease;
        }
        button {
            margin-top: 20px;
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head> 
<body> 
    <div id="imageContainer">
        <!-- Replace "https://via.placeholder.com/150" with the actual URL or path of your image -->
        <div class="imageTile">
            <img src="https://via.placeholder.com/150" alt="Image Tile 1" id="imageTile1">
        </div>
        <div class="imageTile">
            <img src="https://via.placeholder.com/150" alt="Image Tile 2" id="imageTile2">
        </div>
        <div class="imageTile">
            <img src="https://via.placeholder.com/150" alt="Image Tile 3" id="imageTile3">
        </div>
        <!-- Add more image tiles as needed -->
    </div>
    <button onclick="rotateClockwise()">Rotate Clockwise</button>
    <button onclick="rotateAntiClockwise()">Rotate Anti-clockwise</button>
    <script>
        let currentRotation = 0;
        function rotateClockwise() {
            currentRotation += 90;
            rotateImage("imageContainer", currentRotation);
        }
        function rotateAntiClockwise() {
            currentRotation -= 90;
            rotateImage("imageContainer", currentRotation);
        }
        function rotateImage(containerId, angle) {
            const container = document.getElementById(containerId);
            const imageTiles = container.querySelectorAll('.imageTile img');
            imageTiles.forEach(img => {
                img.style.transform = `rotate(${angle}deg)`;
            });
        }
    </script>
</body> 
</html>
---------------------------------------------------------------------------  
slip 25
---------------------------------------------------------------------------
<!DOCTYPE html>
<html>
<head>
    <title>Entry Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #b30000;
            font-size: 18px;
        }
        h1 {
            text-align: center;
            color: #b30000;
            font-size: 40px;
            margin-bottom: 20px;
        }
        .main-container {
            background-color: #b6dbe8;
            border: 2px solid #b30000;
            width: 80%;
        }
        .container {
            width: 60%;
            margin: auto;
        }
        label {
            display: inline-block;
            width: 200px;
            font-weight: bold;
            margin-bottom: 15px;
        }
        input[type="text"],
        input[type="number"],
        textarea,
        select,
        input[type="password"] {
            padding: 5px;
            width: 250px;
            font-size: 16px;
        }
        textarea {
            height: 80px;
        }
        .buttons {
            margin-top: 20px;
            text-align: center;
        }
        input[type="submit"],
        input[type="reset"] {
            padding: 8px 20px;
            margin: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="main-container">
        <h1>ENTRY FORM</h1>
        <div class="container">
            <form>
                <label>Enter your Name :</label>
                <input type="text"><br>
                <label>Enter your Age :</label>
                <input type="number"><br>
                <label>Enter your Address :</label>
                <textarea></textarea><br>
                <label>Sex :</label>
                <input type="radio" name="gender"> Female
                <input type="radio" name="gender"> Male<br><br>
                <label>Nationality :</label>
                <select>
                    <option>(Please select a country)</option>
                    <option>India</option>
                    <option>USA</option>
                    <option>UK</option>
                    <option>Other</option>
                </select><br><br>
                <label>Languages Known :</label>
                (can select more than one)<br>
                <label></label><input type="checkbox"> C<br>
                <label></label><input type="checkbox"> C++<br>
                <label></label><input type="checkbox"> VB<br>
                <label></label><input type="checkbox"> JAVA<br>
                <label></label><input type="checkbox"> ASP<br>
                <label></label><input type="checkbox"> OTHERS<br><br>
                <label>Enter your Password :</label>
                <input type="password"><br><br>
                <div class="buttons">
                    <input type="reset" value="Reset">
                    <input type="submit" value="Submit">
                </div>
            </form>
        </div>
    </div>
</body>
</html>
