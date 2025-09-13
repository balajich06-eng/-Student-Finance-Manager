<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Student Finance Manager</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" href="AI-THON.css">
</head>
<body>
  <header>
    <h1>🎓 Student Finance Manager</h1>
    <nav>
      <ul>
        <li>Dashboard</li>
        <li>Expenses</li>
        <li>Goals</li>
        <li>Alerts</li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="card analytics">
      <h2>📈 Predictive Spending Analysis</h2>
      <div class="chart-placeholder">[AI Chart Here]</div>
    </section>

    <section class="card expenses">
      <h2>🧾 Expense Categorization</h2>
      <ul>
        <li>🍕 Food: ₹2,300</li>
        <li>📚 Books: ₹1,200</li>
        <li>🚍 Transport: ₹800</li>
        <li>🏠 Rent: ₹6,000</li>
      </ul>
    </section>

    <section class="card goals">
      <h2>🎯 Financial Goals</h2>
      <p>💻 New Laptop: ₹25,000 / ₹50,000</p>
      <progress value="25000" max="50000"></progress>
    </section>

    <section class="card alerts">
      <h2>🚨 Budget Alerts</h2>
      <p>⚠ You're close to exceeding your monthly food budget!</p>
    </section>
  </main>

  <footer>
    <p>© 2025 FinAI for Students</p>
  </footer>
</body>
</html>
