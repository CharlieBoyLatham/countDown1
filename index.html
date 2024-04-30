<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Countdown App</title>
</head>
<body>
  <h1>Countdown App</h1>
  <div>
    <label for="start-date">Start Date:</label>
    <input type="date" id="start-date">
    <input type="time" id="start-time">
  </div>
  <div>
    <label for="end-date">End Date:</label>
    <input type="date" id="end-date">
    <input type="time" id="end-time">
  </div>
  <div>
    <p>Remaining Time: <span id="remaining-time"></span></p>
    <p>Time Elapsed: <span id="elapsed-time"></span></p>
    <p>Percentage Complete: <span id="percentage-complete"></span>%</p>
    <p>Percentage Remaining: <span id="percentage-remaining"></span>%</p>
  </div>

  <script>
    // Function to calculate and update countdown
    function updateCountdown() {
      const startDate = new Date(document.getElementById('start-date').value + 'T' + document.getElementById('start-time').value);
      const endDate = new Date(document.getElementById('end-date').value + 'T' + document.getElementById('end-time').value);

      const currentTime = new Date();
      const diff = endDate.getTime() - currentTime.getTime();
      const secondsRemaining = Math.floor(diff / 1000);

      if (secondsRemaining <= 0) {
        document.getElementById('remaining-time').textContent = 'Expired';
        document.getElementById('percentage-complete').textContent = 100;
        document.getElementById('percentage-remaining').textContent = 0;
        clearInterval(interval);
      } else {
        const days = Math.floor(secondsRemaining / (60 * 60 * 24));
        const hours = Math.floor((secondsRemaining % (60 * 60 * 24)) / (60 * 60));
        const minutes = Math.floor((secondsRemaining % (60 * 60)) / 60);
        const seconds = secondsRemaining % 60;
        document.getElementById('remaining-time').textContent = `${days}d ${hours}h ${minutes}m ${seconds}s`;

        const elapsedSeconds = (currentTime.getTime() - startDate.getTime()) / 1000;
        const elapsedDays = Math.floor(elapsedSeconds / (60 * 60 * 24));
        const elapsedHours = Math.floor((elapsedSeconds % (60 * 60 * 24)) / (60 * 60));
        const elapsedMinutes = Math.floor((elapsedSeconds % (60 * 60)) / 60);
        const elapsedSecondsRemain = Math.floor(elapsedSeconds % 60);
        document.getElementById('elapsed-time').textContent = `${elapsedDays}d ${elapsedHours}h ${elapsedMinutes}m ${elapsedSecondsRemain}s`;

        const totalDuration = endDate.getTime() - startDate.getTime();
        const elapsedTimeMillis = elapsedSeconds * 1000;
        const percentage = (elapsedTimeMillis / totalDuration) * 100;
        document.getElementById('percentage-complete').textContent = percentage.toFixed(4);
        document.getElementById('percentage-remaining').textContent = (100 - percentage).toFixed(4);
      }
    }

    // Update countdown every second
    const interval = setInterval(updateCountdown, 1000);
  </script>
</body>
</html>
