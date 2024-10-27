# Weather Reporter 🌦️

This is a simple Python weather application that fetches real-time weather data for any city using the Open-Meteo API. It provides detailed weather information including temperature, wind speed, humidity, precipitation, and more. Additionally, it generates a QR code containing the weather report, which is saved along with the report.

## Features ✨

- 🌍 Fetches real-time weather data based on city input
- 📏 Provides detailed weather information:
  - Temperature (current, max, min)
  - Wind speed
  - Humidity
  - Precipitation
  - Visibility
  - Cloud cover
  - Pressure
  - Dew point
  - Sunrise and sunset times
- 🗂️ Saves weather report in a text file
- 🖼️ Generates a QR code containing the weather report
- 🗂️ Organizes reports in directories based on the current date and time

## Installation 🛠️

1. **Clone the repository**:
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app

4. **Install dependencies**:
```
   pip install requests
   ```

## Usage 🚀

1. **Run the application**:
```
   python weather.py
```

2. **Enter the city name**:
   - The script will fetch and display the weather information.
   - The weather report will be saved in the `Weather_reports_Python` directory.

## Example Output 📊
<pre style="border-radius:20px">
Enter a city: Dhaka
Latitude: 23.7104 
Longitude: 90.40744

Current temperature in Dhaka is 30°C
Wind speed is 10 m/s
Humidity is 70%
Precipitation is 0 mm
Visibility is 10 km
Cloud cover is 50%
Pressure is 1015 hPa
Dew point is 25°C
Max daily temperature is 32°C
Min daily temperature is 28°C
Daily precipitation is 2 mm
Sunrise at 06:00 AM
Sunset at 06:00 PM
</pre>
## QR Code 📷

A QR code containing the weather report will be generated and saved as `weather_report_qr.png` in the respective report directory.

## Contributing 💡

Feel free to fork the repository and submit pull requests. Any contributions and suggestions are welcome!

## Acknowledgements 🙏

- Thanks to [Open-Meteo](https://open-meteo.com/) for providing the weather data API.
- Special thanks to [GoQR.me](https://goqr.me/) for the QR code generation API.

<br><br>
<br>
<br>
NOTE: There's a bug for showing the time of sunrise and sunset, work is going on to fix it.