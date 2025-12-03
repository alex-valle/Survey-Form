<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>
    <h1 id="title">Survery Form</h1>
      <p id="description">Thank you for taking time to fill our this survery.</p>
    <body>
      <form id="survey-form"> 
        <label for="name" id="name-label">Name</label>
        <input type="text" id="name" name="name" placeholder="Full Name" required>
        <label for="email" id="email-label">Email</label>
        <input type="email" id="email" name="email" placeholder="example@email.com" required/>
        <label for="number" id="number-label">Age(optional)</label>
        <input type="number" id="number"
        placeholder="Age"
        min="3"
        max="100"/>
        <p>How was your experience?
       <label for"dropdown"></label> 
        <select id="dropdown">
          <option value"poor">Poor</option>
          <option value="satisfactory">Satisfactory</option>
          <option value="good">Good</option>
          <option value="very-good">Very Good</option>
          <option value="excellent">Excellent</option>
        </select>
        <p>Would you recommend freeCodeCamp to a friend?</p>
        <label>
        <input type="radio" name="recommend" value="Yes">Yes</input>
        <input type="radio" name="recommend" value="Maybe">Maybe</input>
        <input type="radio" name="recommend" value="No">No</input>
        </label>
        <p>What would you like to see improved?</p>
        <label>
          <input type="checkbox" id="class" value="front-end-dev">Front End Project</input>
          <input type="checkbox" id="class" value="back-end-projects">Back End Projects</input>
        </label>
        <p>Any additional feedback?</p>
        <textarea>
        </textarea>
        <button type="submit" id="submit">Submit</button>
        
      </form>
    </body>
</html>
