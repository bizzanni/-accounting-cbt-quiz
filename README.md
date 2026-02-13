# -accounting-cbt-quiz
Quiz
‎ <!DOCTYPE html>
‎<html>
‎<head>
‎<meta charset="UTF-8">
‎<title>KWASU Accounting CBT Quiz</title>
‎<style>
‎body {
‎    font-family: Arial, sans-serif;
‎    background: #f4f6f8;
‎    padding: 20px;
‎}
‎.quiz-box {
‎    background: #fff;
‎    max-width: 800px;
‎    margin: auto;
‎    padding: 20px;
‎    border-radius: 10px;
‎}
‎h2 {
‎    text-align: center;
‎}
‎.question {
‎    margin-bottom: 15px;
‎}
‎button {
‎    padding: 10px 20px;
‎    font-size: 16px;
‎    cursor: pointer;
‎    margin-top: 15px;
‎}
‎.timer {
‎    font-size: 18px;
‎    color: red;
‎    text-align: center;
‎    margin-bottom: 15px;
‎}
‎</style>
‎</head>
‎<body>
‎
‎<div class="quiz-box">
‎<h2>KWASU 100L Accounting CBT Quiz</h2>
‎<div class="timer" id="timer">Time Left: 30:00</div>
‎<form id="quizForm">
‎
‎<!-- Questions -->
‎<div class="question">
‎<p>1. Accounting is mainly concerned with:</p>
‎<input type="radio" name="q1" value="A"> A. Recording financial transactions<br>
‎<input type="radio" name="q1" value="B"> B. Selling goods<br>
‎<input type="radio" name="q1" value="C"> C. Buying assets<br>
‎<input type="radio" name="q1" value="D"> D. Hiring workers
‎</div>
‎
‎<div class="question">
‎<p>2. Which of the following is a liability?</p>
‎<input type="radio" name="q2" value="A"> A. Cash<br>
‎<input type="radio" name="q2" value="B"> B. Furniture<br>
‎<input type="radio" name="q2" value="C"> C. Bank loan<br>
‎<input type="radio" name="q2" value="D"> D. Stock
‎</div>
‎
‎<div class="question">
‎<p>3. The accounting equation is:</p>
‎<input type="radio" name="q3" value="A"> A. Assets = Capital – Liabilities<br>
‎<input type="radio" name="q3" value="B"> B. Assets = Capital + Liabilities<br>
‎<input type="radio" name="q3" value="C"> C. Capital = Assets + Liabilities<br>
‎<input type="radio" name="q3" value="D"> D. Assets + Capital = Liabilities
‎</div>
‎
‎<div class="question">
‎<p>4. Drawings will:</p>
‎<input type="radio" name="q4" value="A"> A. Increase capital<br>
‎<input type="radio" name="q4" value="B"> B. Reduce capital<br>
‎<input type="radio" name="q4" value="C"> C. Increase profit<br>
‎<input type="radio" name="q4" value="D"> D. Increase liabilities
‎</div>
‎
‎<div class="question">
‎<p>5. Which book records daily cash transactions?</p>
‎<input type="radio" name="q5" value="A"> A. Journal<br>
‎<input type="radio" name="q5" value="B"> B. Ledger<br>
‎<input type="radio" name="q5" value="C"> C. Cash Book<br>
‎<input type="radio" name="q5" value="D"> D. Trial Balance
‎</div>
‎
‎<div class="question">
‎<p>6. An asset is:</p>
‎<input type="radio" name="q6" value="A"> A. What the business owes<br>
‎<input type="radio" name="q6" value="B"> B. What the owner owes<br>
‎<input type="radio" name="q6" value="C"> C. What the business owns<br>
‎<input type="radio" name="q6" value="D"> D. What customers pay
‎</div>
‎
‎<div class="question">
‎<p>7. Expenses are recorded in order to:</p>
‎<input type="radio" name="q7" value="A"> A. Increase assets<br>
‎<input type="radio" name="q7" value="B"> B. Reduce profit<br>
‎<input type="radio" name="q7" value="C"> C. Increase capital<br>
‎<input type="radio" name="q7" value="D"> D. Increase liabilities
‎</div>
‎
‎<div class="question">
‎<p>8. When goods are bought for cash, which account is credited?</p>
‎<input type="radio" name="q8" value="A"> A. Purchases<br>
‎<input type="radio" name="q8" value="B"> B. Cash<br>
‎<input type="radio" name="q8" value="C"> C. Capital<br>
‎<input type="radio" name="q8" value="D"> D. Stock
‎</div>
‎
‎<div class="question">
‎<p>9. Capital introduced into a business will:</p>
‎<input type="radio" name="q9" value="A"> A. Increase liabilities<br>
‎<input type="radio" name="q9" value="B"> B. Increase assets<br>
‎<input type="radio" name="q9" value="C"> C. Reduce assets<br>
‎<input type="radio" name="q9" value="D"> D. Reduce income
‎</div>
‎
‎<div class="question">
‎<p>10. Profit is calculated as:</p>
‎<input type="radio" name="q10" value="A"> A. Sales – Expenses<br>
‎<input type="radio" name="q10" value="B"> B. Expenses – Sales<br>
‎<input type="radio" name="q10" value="C"> C. Assets – Liabilities<br>
‎<input type="radio" name="q10" value="D"> D. Capital – Drawings
‎</div>
‎
‎<div class="question">
‎<p>11. Depreciation is:</p>
‎<input type="radio" name="q11" value="A"> A. Increase in asset value<br>
‎<input type="radio" name="q11" value="B"> B. Reduction in asset value<br>
‎<input type="radio" name="q11" value="C"> C. Sale of asset<br>
‎<input type="radio" name="q11" value="D"> D. Repair of asset
‎</div>
‎
‎<div class="question">
‎<p>12. Trial balance is prepared to:</p>
‎<input type="radio" name="q12" value="A"> A. Calculate profit<br>
‎<input type="radio" name="q12" value="B"> B. Prepare balance sheet<br>
‎<input type="radio" name="q12" value="C"> C. Check arithmetical accuracy<br>
‎<input type="radio" name="q12" value="D"> D. Record transactions
‎</div>
‎
‎<div class="question">
‎<p>13. Which of the following is NOT a user of accounting information?</p>
‎<input type="radio" name="q13" value="A"> A. Managers<br>
‎<input type="radio" name="q13" value="B"> B. Government<br>
‎<input type="radio" name="q13" value="C"> C. Creditors<br>
‎<input type="radio" name="q13" value="D"> D. Drivers
‎</div>
‎
‎<div class="question">
‎<p>14. Goods taken by owner for personal use is called:</p>
‎<input type="radio" name="q14" value="A"> A. Capital<br>
‎<input type="radio" name="q14" value="B"> B. Purchases<br>
‎<input type="radio" name="q14" value="C"> C. Drawings<br>
‎<input type="radio" name="q14" value="D"> D. Sales
‎</div>
‎
‎<div class="question">
‎<p>15. Which of these is a fixed asset?</p>
‎<input type="radio" name="q15" value="A"> A. Stock<br>
‎<input type="radio" name="q15" value="B"> B. Cash<br>
‎<input type="radio" name="q15" value="C"> C. Furniture<br>
‎<input type="radio" name="q15" value="D"> D. Debtors
‎</div>
‎
‎<div class="question">
‎<p>16. Which of the following is a source document?</p>
‎<input type="radio" name="q16" value="A"> A. Ledger<br>
‎<input type="radio" name="q16" value="B"> B. Trial Balance<br>
‎<input type="radio" name="q16" value="C"> C. Receipt<br>
‎<input type="radio" name="q16" value="D"> D. Balance Sheet
‎</div>
‎
‎<div class="question">
‎<p>17. Double entry system means:</p>
‎<input type="radio" name="q17" value="A"> A. Two transactions in one account<br>
‎<input type="radio" name="q17" value="B"> B. One transaction in one account<br>
‎<input type="radio" name="q17" value="C"> C. One transaction affects two accounts<br>
‎<input type="radio" name="q17" value="D"> D. Two transactions affect two journals
‎</div>
‎
‎<div class="question">
‎<p>18. Which account is debited when cash is paid for rent?</p>
‎<input type="radio" name="q18" value="A"> A. Cash<br>
‎<input type="radio" name="q18" value="B"> B. Capital<br>
‎<input type="radio" name="q18" value="C"> C. Rent<br>
‎<input type="radio" name="q18" value="D"> D. Liability
‎</div>
‎
‎<div class="question">
‎<p>19. If assets are ₦500,000 and liabilities are ₦200,000, capital is:</p>
‎<input type="radio" name="q19" value="A"> A. ₦300,000<br>
‎<input type="radio" name="q19" value="B"> B. ₦700,000<br>
‎<input type="radio" name="q19" value="C"> C. ₦200,000<br>
‎<input type="radio" name="q19" value="D"> D. ₦500,000
‎</div>
‎
‎<div class="question">
‎<p>20. Which account is debited when cash is received?</p>
‎<input type="radio" name="q20" value="A"> A. Capital<br>
‎<input type="radio" name="q20" value="B"> B. Income<br>
‎<input type="radio" name="q20" value="C"> C. Cash<br>
‎<input type="radio" name="q20" value="D"> D. Liability
‎</div>
‎
‎<button type="button" onclick="submitQuiz()">Submit Quiz</button>
‎<p id="score"></p>
‎</form>
‎</div>
‎
‎<script>
‎// Timer Countdown (30 minutes)
‎let timeLeft = 30 * 60; // 30 minutes
‎const timerElement = document.getElementById("timer");
‎
‎const timerInterval = setInterval(() => {
‎    let minutes = Math.floor(timeLeft / 60);
‎    let seconds = timeLeft % 60;
‎    if(seconds < 10) seconds = '0' + seconds;
‎    timerElement.innerHTML = `Time Left: ${minutes}:${seconds}`;
‎    if(timeLeft <= 0) {
‎        clearInterval(timerInterval);
‎        alert("Time is up! Submitting your quiz.");
‎        submitQuiz();
‎    }
‎    timeLeft--;
‎}, 1000);
‎
‎// Correct answers
‎const answers = {
‎    q1:"A", q2:"C", q3:"B", q4:"B", q5:"C",
‎    q6:"C", q7:"B", q8:"B", q9:"B", q10:"A",
‎    q11:"B", q12:"C", q13:"D", q14:"C", q15:"C",
‎    q16:"C", q17:"C", q18:"C", q19:"A", q20:"C"
‎};
‎
‎function submitQuiz() {
‎    let score = 0;
‎    for (let q in answers) {
‎        let selected = document.querySelector(`input[name=${q}]:checked`);
‎        if(selected && selected.value === answers[q]) score++;
‎    }
‎    document.getElementById("score").innerHTML = `Your Score: ${score} / 20`;
‎    clearInterval(timerInterval);
‎}
‎</script>
‎
‎</body>
‎</html> 
