# Survey-
<! index html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Questionnaire Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f9;
      margin: 0;
      padding: 0;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    form {
      background: white;
      max-width: 700px;
      margin: 2rem auto;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 1rem;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 1.5rem;
      padding: 0.7rem 1.5rem;
      background: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    button:hover {
      background: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>Questionnaire Form</h1>
    <p>Please fill out all questions carefully</p>
  </header>

  <form action="https://formspree.io/f/mzzbbbyw" method="POST">
    <label for="name">1. Full Name:</label>
    <input type="text" id="name" name="Name" required>

    <label for="email">2. Email Address:</label>
    <input type="email" id="email" name="Email" required>

    <label for="age">3. Age:</label>
    <input type="number" id="age" name="Age" required>

    <label for="gender">4. Gender:</label>
    <select id="gender" name="Gender" required>
      <option value="">-- Select --</option>
      <option value="Male">Male</option>
      <option value="Female">Female</option>
      <option value="Other">Other</option>
    </select>

    <label for="education">5. Education Level:</label>
    <select id="education" name="Education">
      <option value="">-- Select --</option>
      <option value="Primary">Primary</option>
      <option value="Secondary">Secondary</option>
      <option value="College">College</option>
      <option value="University">University</option>
    </select>

    <label for="employment">6. Employment Status:</label>
    <select id="employment" name="Employment">
      <option value="">-- Select --</option>
      <option value="Employed">Employed</option>
      <option value="Unemployed">Unemployed</option>
      <option value="Student">Student</option>
      <option value="Other">Other</option>
    </select>

    <label for="country">7. Country of Residence:</label>
    <input type="text" id="country" name="Country">

    <label for="experience">8. How satisfied are you with our service?</label>
    <select id="experience" name="Satisfaction">
      <option value="">-- Select --</option>
      <option value="Very Satisfied">Very Satisfied</option>
      <option value="Satisfied">Satisfied</option>
      <option value="Neutral">Neutral</option>
      <option value="Dissatisfied">Dissatisfied</option>
      <option value="Very Dissatisfied">Very Dissatisfied</option>
    </select>

    <label for="improve">9. What should we improve?</label>
    <textarea id="improve" name="Improvement" rows="3"></textarea>

    <label for="recommend">10. Would you recommend us to a friend?</label>
    <select id="recommend" name="Recommend">
      <option value="">-- Select --</option>
      <option value="Yes">Yes</option>
      <option value="No">No</option>
    </select>

    <label for="comments">11. Additional Comments:</label>
    <textarea id="comments" name="Comments" rows="4"></textarea>

    <button type="submit">Submit</button>
  </form>
</body>
</html>
