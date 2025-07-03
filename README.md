<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Chapter 1 Quiz</title>
  <style>
    body {
      font-family: sans-serif;
      max-width: 800px;
      margin: auto;
      padding: 2rem;
      background-color: #f9f9f9;
    }
    h1, h2 {
      text-align: center;
    }
    .question {
      margin-bottom: 2rem;
      padding: 1rem;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .answers label {
      display: block;
      margin: 0.5rem 0;
      cursor: pointer;
    }
    .result {
      margin-top: 2rem;
      padding: 1rem;
      background: #e8f5e9;
      border: 1px solid #66bb6a;
      border-radius: 8px;
    }
    button {
      background: #4caf50;
      color: white;
      border: none;
      padding: 0.8rem 1.2rem;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #45a049;
    }
  </style>
</head>
<body>
  <h1>Chapter 1 Quiz</h1>
  <form id="quizForm">

    <div class="question" data-correct="B">
      <h3>1. Which of the following describes the nature of the workplace in the digital world?</h3>
      <div class="answers">
        <label><input type="radio" name="q1" value="A"> A. It is primarily a single-functional environment.</label>
        <label><input type="radio" name="q1" value="B"> B. It is a highly cross-functional workplace.</label>
        <label><input type="radio" name="q1" value="C"> C. It always follows a strict hierarchical structure.</label>
        <label><input type="radio" name="q1" value="D"> D. It avoids the use of diverse skillsets.</label>
      </div>
    </div>

    <div class="question" data-correct="B">
      <h3>2. When forming a team in digital product development, what is a crucial consideration, given that there is no set rule for team composition?</h3>
      <div class="answers">
        <label><input type="radio" name="q2" value="A"> A. To ensure all team members have the same technical background.</label>
        <label><input type="radio" name="q2" value="B"> B. To assess whom do we need to get the job done, which roles are important, and which skillset helps to succeed with our project or product.</label>
        <label><input type="radio" name="q2" value="C"> C. To exclusively hire external partners for all roles.</label>
        <label><input type="radio" name="q2" value="D"> D. To rely solely on automated processes without human involvement.</label>
      </div>
    </div>

    <div class="question" data-correct="C">
      <h3>3. What is a primary benefit of using a Skill Matrix in a company or team?</h3>
      <div class="answers">
        <label><input type="radio" name="q3" value="A"> A. To determine the financial compensation for each employee.</label>
        <label><input type="radio" name="q3" value="B"> B. To manage customer relationships and feedback.</label>
        <label><input type="radio" name="q3" value="C"> C. To have a quick overview of your teams' ability to solve related tasks and to do an assessment for hiring new people with the right skills.</label>
        <label><input type="radio" name="q3" value="D"> D. To assign specific office spaces to team members.</label>
      </div>
    </div>

    <div class="question" data-correct="B">
      <h3>4. In the context of the RACI Matrix, who is defined as the person who "checks that the work is done, is a success, and all this while following the agreed timeline," stepping in to find solutions in case of delays?</h3>
      <div class="answers">
        <label><input type="radio" name="q4" value="A"> A. Responsible.</label>
        <label><input type="radio" name="q4" value="B"> B. Accountable.</label>
        <label><input type="radio" name="q4" value="C"> C. Consulted.</label>
        <label><input type="radio" name="q4" value="D"> D. Informed.</label>
      </div>
    </div>

    <div class="question" data-correct="B">
      <h3>5. When is the RACI Matrix particularly useful, according to the sources?</h3>
      <div class="answers">
        <label><input type="radio" name="q5" value="A"> A. Only during the final review phase of a project.</label>
        <label><input type="radio" name="q5" value="B"> B. When you have clashing opinions in a meeting, or a decision is unclear and you don't know how to move forward.</label>
        <label><input type="radio" name="q5" value="C"> C. Primarily for documenting individual performance reviews.</label>
        <label><input type="radio" name="q5" value="D"> D. As a tool for automated task assignment.</label>
      </div>
    </div>

    <div class="question" data-correct="C">
      <h3>6. What is Delegation Poker described as, and what is its main purpose?</h3>
      <div class="answers">
        <label><input type="radio" name="q6" value="A"> A. A competitive game played by team leaders to win projects.</label>
        <label><input type="radio" name="q6" value="B"> B. A method to strictly enforce top-down decision-making.</label>
        <label><input type="radio" name="q6" value="C"> C. A method that allows teams to clarify roles in a self-organized manner.</label>
        <label><input type="radio" name="q6" value="D"> D. A system for tracking employee attendance.</label>
      </div>
    </div>

    <div class="question" data-correct="C">
      <h3>7. How do frameworks like Agile, Waterfall, and Hybrid approaches assist interdisciplinary teams?</h3>
      <div class="answers">
        <label><input type="radio" name="q7" value="A"> A. By dictating rigid communication protocols.</label>
        <label><input type="radio" name="q7" value="B"> B. By eliminating the need for any team discussions.</label>
        <label><input type="radio" name="q7" value="C"> C. By giving us a mutual understanding of our process and providing standards of how and when work gets done.</label>
        <label><input type="radio" name="q7" value="D"> D. By automating all project tasks, reducing human error.</label>
      </div>
    </div>

    <div class="question" data-correct="B">
      <h3>8. Which of the following is a core characteristic of the Waterfall method?</h3>
      <div class="answers">
        <label><input type="radio" name="q8" value="A"> A. It is highly flexible and open to continuous change.</label>
        <label><input type="radio" name="q8" value="B"> B. It involves sequential phases that are dependent on each other, are carried out one after the other, and progress falls in one direction.</label>
        <label><input type="radio" name="q8" value="C"> C. It emphasizes collaborative, incremental value delivery.</label>
        <label><input type="radio" name="q8" value="D"> D. It prioritizes individuals and interactions over processes and tools.</label>
      </div>
    </div>

    <div class="question" data-correct="C">
      <h3>9. According to the Agile Manifesto, which aspect is valued <em>more</em> than comprehensive documentation?</h3>
      <div class="answers">
        <label><input type="radio" name="q9" value="A"> A. Processes and tools.</label>
        <label><input type="radio" name="q9" value="B"> B. Contract negotiation.</label>
        <label><input type="radio" name="q9" value="C"> C. Working software.</label>
        <label><input type="radio" name="q9" value="D"> D. Following a plan.</label>
      </div>
    </div>

    <div class="question" data-correct="C">
      <h3>10. What is explicitly stated as one of the benefits that Project Management offers?</h3>
      <div class="answers">
        <label><input type="radio" name="q10" value="A"> A. It guarantees immediate financial returns for all endeavors.</label>
        <label><input type="radio" name="q10" value="B"> B. It eliminates the need for any form of human collaboration.</label>
        <label><input type="radio" name="q10" value="C"> C. It guides us to document our way of working, making decisions, and to measure our outcomes.</label>
        <label><input type="radio" name="q10" value="D"> D. It restricts creativity and innovation in product development.</label>
      </div>
    </div>

    <button type="submit">Submit</button>
  </form>
  <div class="result" id="result" style="display:none;"></div>

  <script>
    document.getElementById('quizForm').addEventListener('submit', function(e) {
      e.preventDefault();
      const questions = document.querySelectorAll('.question');
      let score = 0;
      let output = '<h2>Your Results</h2>';

      questions.forEach((q, i) => {
        const correct = q.dataset.correct;
        const selected = q.querySelector('input:checked');
        const selectedValue = selected ? selected.value : 'None';
        const isCorrect = selectedValue === correct;
        if (isCorrect) score++;
        output += `<p><strong>Question ${i + 1}:</strong> ` +
