# Design-Simple-WebPage-with-CSS-Properties
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        #registration-form {
            width: 300px;
            margin: 50px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            text-align: left;
            margin: 10px 0 5px;
        }

        input,
        select,
        button {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="radio"] {
            margin: 8px 5px 8px 0;
        }

        button {
            background-color: #4caf50;
            color: #fff;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }

        input[type="reset"] {
            background-color: #f44336;
            color: #fff;
            cursor: pointer;
        }

        input[type="reset"]:hover {
            background-color: #d32f2f;
        }
    </style>
</head>
<body>

    <div id="registration-form">
        <h2>User Registration</h2>
        <form>
            <label for="userid">User ID:</label>
            <input type="text" id="userid" name="userid" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>

            <label for="dob">DOB:</label>
            <input type="date" id="dob" name="dob" required>

            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <!-- Add more options as needed -->
            </select>

            <button type="submit">Register Now</button>
            <input type="reset" value="Clear All">
        </form>
    </div>

</body>
</html>
