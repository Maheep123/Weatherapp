<!DOCTYPE html>
<html>
<head>
  <title>Weather Reminder</title>
  <style>
    body { font-family: Arial; text-align: center; padding: 20px; }
    h1 { color: #0077cc; }
  </style>
</head>
<body>
  <h1>🌦️ Weather in Surrey, BC</h1>
  <p id="weather">Loading...</p>

  <script>
    const apiKey = "d1b3236d48bc9012b0ac6019870ba6bb";
    const lat = 49.1044;
    const lon = -122.8011;
    let lastCondition = "";

    async function getWeather() {
      const url = `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${apiKey}&units=metric`;
      const res = await fetch(url);
      const data = await res.json();
      const condition = data.weather[0].main;

      document.getElementById("weather").innerText = `Now: ${condition}, ${data.main.temp}°C`;

      if (lastCondition && condition !== lastCondition) {
        alert(`🔔 Reminder: Weather changed from ${lastCondition} to ${condition}`);
      }

      lastCondition = condition;
    }

    getWeather();
    setInterval(getWeather, 30 * 60 * 1000); // Every 30 minutes
  </script>
</body>
</html>

