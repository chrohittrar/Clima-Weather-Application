# Clima: Weather App for iOS

## Introduction

Clima is a simple and intuitive weather app for iOS, built using Swift. Stay informed about the current weather conditions and forecasts with a sleek and user-friendly interface.

## Features

- **Real-time Weather Data:** Get accurate and up-to-date weather information.
- **Location-based Forecast:** Automatically fetches weather details based on your location.
- **Search Functionality:** Search for weather information in any location around the world.
- **Detailed Weather Info:** View detailed weather conditions including temperature, humidity, wind speed, and more.

## Screenshots

<img src = "https://github.com/chrohittrar/Clima-Weather-App/assets/109714993/7e0a3f46-6dad-4167-8615-637294815698" width = "230" height = "500" />
<img src = "https://github.com/chrohittrar/Clima-Weather-App/assets/109714993/cf4679fe-046c-4754-934d-186808466b28" width = "230" height = "500" />
<img src = "https://github.com/chrohittrar/Clima-Weather-App/assets/109714993/4a4e0924-ca43-40a7-aa3e-14df1f29128c" width = "230" height = "500" />
<img src = "https://github.com/chrohittrar/Clima-Weather-App/assets/109714993/d2b542f3-0455-4da1-8380-dde8a61e328c" width = "230" height = "500" />
<img src = "https://github.com/chrohittrar/Clima-Weather-App/assets/109714993/49590672-91b5-43f5-ba2a-31a9faaa93bb" width = "230" height = "500" />


## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/chrohittrar/Clima-Weather-App.git
   ```

2. Open the project in Xcode.

3. Build and run the app on the iOS simulator or a physical device.

## Dependencies

- Alamofire: Swift-based HTTP networking library for making API requests.
- SwiftyJSON: Simplifies JSON parsing in Swift.
- CoreLocation: Framework for obtaining the device’s location.
- MVC Model: Used MVC(Model, View, Controller) for easy understanding and to make code readable.
- Extension: Used SwiftyExtension in Protocol and Delegates for reducing complexcities from the Code.

## API Key

Clima uses OpenWeatherMap API to fetch weather data. Obtain your API key by creating an account on [OpenWeatherMap](https://openweathermap.org/) and replace the placeholder in `WeatherManager.swift`:

```swift
private let apiKey = "8a8d993d7bb8ed2d2df936b5232a7503"
```


## Acknowledgments

- Thanks to OpenWeatherMap for providing the weather data API.
- Icon made by App Icon Generator from https://www.appicon.co/

Feel free to explore and enhance Clima to make it even better! If you encounter any issues or have suggestions, please create an [issue](https://github.com/your-username/clima-weather-app/issues).
