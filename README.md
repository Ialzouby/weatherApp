<h1 align="center">☀️ WeatherApp</h1>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdnVwYm96bmlscDM1NHdtc3R4aTFkYjd6cnYwMXB2Nm9qamdhZnJpZyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/WOfGfEQwDzdGcXYmrn/giphy.gif" alt="WeatherApp Logo">
</p>

<p>Welcome to the <strong>WeatherApp</strong> project! This iOS application provides real-time weather information based on the user's current location. Built with SwiftUI and CoreLocation, WeatherApp offers a sleek and intuitive interface for accessing up-to-date weather data.</p>

<h2>✨ Features</h2>

<ul>
  <li><strong>Real-Time Weather Data</strong>: Fetches current weather conditions using the OpenWeather API.</li>
  <li><strong>Location-Based Updates</strong>: Utilizes CoreLocation to determine the user's current location for accurate weather information.</li>
  <li><strong>User-Friendly Interface</strong>: Designed with SwiftUI for a modern and responsive user experience.</li>
</ul>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><strong>Language</strong>: Swift</li>
  <li><strong>Frameworks</strong>: SwiftUI, CoreLocation</li>
  <li><strong>API</strong>: OpenWeather API</li>
  <li><strong>Version Control</strong>: Git</li>
</ul>

<h2>🚀 Installation</h2>

<p>To set up the WeatherApp project locally:</p>

<ol>
  <li><strong>Clone the Repository</strong>:</li>
</ol>

<pre><code>git clone https://github.com/Ialzouby/weatherApp.git
</code></pre>

<ol start="2">
  <li><strong>Open the Project in Xcode</strong>:</li>
</ol>

<pre><code>cd weatherApp
open weatherApp.xcodeproj
</code></pre>

<ol start="3">
  <li><strong>Obtain an OpenWeather API Key</strong>:</li>
</ol>

<p>Sign up at <a href="https://openweathermap.org/api">OpenWeather API</a> to get your free API key.</p>

<ol start="4">
  <li><strong>Configure the API Key</strong>:</li>
</ol>

<p>Create a new file named <code>Secrets.swift</code> in the project directory and add the following:</p>

<pre><code>struct Secrets {
    static let openWeatherAPIKey = "YOUR_API_KEY"
}
</code></pre>

<p>Replace <code>YOUR_API_KEY</code> with the API key obtained in the previous step.</p>

<ol start="5">
  <li><strong>Build and Run the Project</strong>:</li>
</ol>

<p>Select your target device or simulator in Xcode and click the "Run" button to build and launch the application.</p>

<h2>🤝 Contributing</h2>

<p>Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.</p>

<h2>📄 License</h2>

<p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

<p>Happy coding! 😊</p>
