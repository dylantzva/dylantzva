<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hey Mrs K.Phekani, Fill this in for me Bae?</title>
    <style>
        body {
            background-color: #f8e8ff; /* Light Purple */
            text-align: center;
            font-family: Arial, sans-serif;
            color: red;
        }
        .container {
            margin-top: 50px;
            background: #ffe4e1; /* Light Pink */
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
        }
        button, input, select {
            background: white;
            color: red;
            border: 2px solid red;
            padding: 10px;
            margin: 5px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Hey Ms K. Radebe, Fill this in for me Bae??</h2>
        <form onsubmit="return handleSubmit(event)">
            <label>Q1 - How was your day? (1-10)</label><br>
            <input type="number" min="1" max="10" required><br><br>

            <label>Q2 - Did you enjoy your day without me?</label><br>
            <button type="button" onclick="alert('Good answer! 😘')">No</button>
            <button type="button" onclick=" alert('Try again, maybe click NO??')">Yes</button> 
            <br><br>

            <label>Q3 - Do you miss me?</label><br>
            <button type="button" onclick="alert('You know i missssss miss miss you more')">Yes</button>
            <button type="button" onclick="alert('You Hate ME!!! 😭')">No</button>
            <br><br>

            <label>Q4 - Do you want a hug?</label><br>
            <button type="button" onclick="alert('Okay then im on my way there princess!')">Yes</button>
            <button type="button" onclick=" alert('Try again, maybe click NO??')">No</button> 
            <br><br>

            <label>Q5 - Did you enjoy your Valentines today?</label><br>
            <button type="button" onclick="alert('That makes me happy, even though i wasnt with youuuu :{ ❤️')">Yes</button>
            <button type="button">No</button> <!-- Does nothing -->
            <br><br>

            <label>Q6 - Do you know that I love you?</label><br>
            <button type="button" onclick="alert('I love you so soooooo much! ❤️')">Yes</button>
            <button type="button" onclick="alert(' I think you are lying about this')">No</button>
            <br><br>

            <button type="submit">Submit</button>
        </form>
    </div>

    <script>
        function handleSubmit(event) {
            event.preventDefault();
            alert('Thank you for filling this out, Mon Cheriiiii, now call me! ❤️');
        }
    </script>
</body>
</html>
