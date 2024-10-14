<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        fieldset {
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>

    <h1>Sample Form</h1>
    <form action="#" method="post">
        
        <!-- Text Input -->
        <label for="textInput">Text Input:</label>
        <input type="text" id="textInput" name="textInput"><br><br>

        <!-- Email Input -->
        <label for="emailInput">Email:</label>
        <input type="email" id="emailInput" name="emailInput"><br><br>

        <!-- Password Input -->
        <label for="passwordInput">Password:</label>
        <input type="password" id="passwordInput" name="passwordInput"><br><br>

        <!-- Color Input -->
        <label for="colorInput">Select a Color:</label>
        <input type="color" id="colorInput" name="colorInput"><br><br>

        <!-- File Input -->
        <label for="fileInput">Upload a File:</label>
        <input type="file" id="fileInput" name="fileInput"><br><br>

        <!-- Checkbox Input -->
        <label for="checkboxInput">Check this box:</label>
        <input type="checkbox" id="checkboxInput" name="checkboxInput"><br><br>

        <!-- Radio Buttons -->
        <fieldset>
            <legend>Choose an Option:</legend>
            <input type="radio" id="option1" name="radioOptions" value="option1">
            <label for="option1">Option 1</label><br>
            <input type="radio" id="option2" name="radioOptions" value="option2">
            <label for="option2">Option 2</label><br>
            <input type="radio" id="option3" name="radioOptions" value="option3">
            <label for="option3">Option 3</label><br>
        </fieldset>

        <!-- Select Dropdown -->
        <label for="selectInput">Choose a selection:</label>
        <select id="selectInput" name="selectInput">
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
        </select><br><br>

        <!-- Textarea -->
        <label for="textareaInput">Your Message:</label><br>
        <textarea id="textareaInput" name="textareaInput" rows="4" cols="50"></textarea><br><br>

        <!-- Range Input -->
        <label for="rangeInput">Select a Range:</label>
        <input type="range" id="rangeInput" name="rangeInput" min="0" max="100" value="50"><br><br>

        <!-- Reset Button -->
        <input type="reset" value="Reset Form">
        
        <!-- Submit Button -->
        <input type="submit" value="Submit Form">
        
    </form>

</body>
</html>
