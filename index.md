## Welcome to My GitHub Page

I will periodically update this page with new projects to showcase my abilities to work with various technologies, databases, data structures, and algorithms.

## About Me

I'm a Computer Science student, in my capstone course, at Southern New Hampshire University. I am focusing my efforts to transitioning into a Software Engineering position when I transition out of the Navy in August.

### Code Snippets

As I decide on snippets to add to my page, I will showcase them here.

### Python Function to Make API Call for Weather Data

```python
# Make api call to return weather data
def get_weather():
    global complete_url
    
    response = requests.get(complete_url) # GET request

    weather_data = response.json() # Json object of response

    if weather_data["cod"] != "404":
        temperature = to_farenheit(weather_data["main"]["temp"]) # api response in kelvin
        weather_description = weather_data["weather"][0]["description"]
	    humidity = weather_data["main"]["humidity"]
		
	else:
		temperature = False
		weather_description = False
		humidity = False
        
    return temperature, weather_description, humidity
```

