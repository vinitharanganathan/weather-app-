# weather-app-
#include <iostream>
#include <string>

using namespace std;

class WeatherData {
private:
    string weatherCondition;

public:
    WeatherData(const string& weatherCondition) : weatherCondition(weatherCondition) {}

    string getWeatherDescription() {
        string description;
        if (weatherCondition == "cloudy") {
            description = "Cloudy weather";
        } else if (weatherCondition == "dry") {
            description = "Dry weather";
        } else if (weatherCondition == "rain") {
            description = "Rainy weather";
        
