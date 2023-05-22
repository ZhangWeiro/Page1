<!DOCTYPE html>
<html>
<head>
  <title>Survey Results</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    /* Add your custom CSS styling here */
  </style>
</head>
<body>
  <h1>Survey Results</h1>
  
  <h2>Findings:</h2>
  
  <canvas id="surveyChart" width="400" height="400"></canvas>
  
  <script>
    var ctx = document.getElementById('surveyChart').getContext('2d');
    var surveyData = {
      labels: ['Enjoy NatureCare products', 'Prefer email as primary communication channel', 'Other'],
      datasets: [{
        data: [80, 50, 20],
        backgroundColor: ['#FF6384', '#36A2EB', '#FFCE56']
      }]
    };
    
    var surveyChart = new Chart(ctx, {
      type: 'pie',
      data: surveyData
    });
  </script>
  
  <p>
    Description: The survey results show that 80% of respondents enjoy NatureCare products, and 50% prefer email as their primary communication channel. These findings highlight the significance of NatureCare's product appeal and the importance of email communication for effective customer engagement.
  </p>
</body>
</html>
