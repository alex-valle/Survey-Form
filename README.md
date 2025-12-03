<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
</head>
<body>
    <h1>Survey Form</h1>
    <p>Thank you for taking time to fill out this survey.</p>
    
    <form action="#" method="post">  <!-- Add action for form submission (even dummy for now) -->
        <label for="name">Name</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="age">Age (optional)</label><br>
        <input type="number" id="age" name="age" min="1" max="120"><br><br>
        
        <fieldset>  <!-- Groups the rating question -->
            <legend>How was your experience?</legend>
            <input type="radio" id="poor" name="experience" value="Poor">
            <label for="poor">Poor</label><br>
            <input type="radio" id="satisfactory" name="experience" value="Satisfactory">
            <label for="satisfactory">Satisfactory</label><br>
            <input type="radio" id="good" name="experience" value="Good">
            <label for="good">Good</label><br>
            <input type="radio" id="very-good" name="experience" value="Very Good">
            <label for="very-good">Very Good</label><br>
            <input type="radio" id="excellent" name="experience" value="Excellent">
            <label for="excellent">Excellent</label><br><br>
        </fieldset>
        
        <fieldset>  <!-- Groups the recommendation -->
            <legend>Would you recommend freeCodeCamp to a friend?</legend>
            <input type="radio" id="yes" name="recommend" value="Yes">
            <label for="yes">Yes</label><br>
            <input type="radio" id="maybe" name="recommend" value="Maybe">
            <label for="maybe">Maybe</label><br>
            <input type="radio" id="no" name="recommend" value="No">
            <label for="no">No</label><br><br>
        </fieldset>
        
        <label>What would you like to see improved? (Check all that apply)</label><br>
        <input type="checkbox" id="frontend" name="improvement" value="Front End Projects">
        <label for="frontend">Front End Projects</label><br>  <!-- Fixed plural for consistency -->
        <input type="checkbox" id="backend" name="improvement" value="Back End Projects">
        <label for="backend">Back End Projects</label><br><br>
        
        <label for="comments">Any additional feedback?</label><br>
        <textarea id="comments" name="comments" rows="5" cols="50" placeholder="Enter your thoughts here..."></textarea><br><br>
        
        <button type="submit">Submit</button>
    </form>
</body>
</html>
