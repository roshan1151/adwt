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
