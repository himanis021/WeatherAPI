# WeatherAPI

Create a test case to check the following 
- Use the weather API to get the weather for New Delhi 
  ○ Get weather in the standard unit (Kelvin) 
  ○ Get weather by changing unit to metric (celsius) 
- See if the values are matching (up to 2% error while converting is ok)

# To Start With:

- Import the json files "WeatherAPI.postman_collection.json" and "Weather_Env.postman_environment.json" both in the Postman.
- Grab the API key of your account from the website:  https://openweathermap.org/api
- Paste the API key in the Environment variable 'app_id' under the Initial Value column.
- Make sure the correct environment is selected before sending the API requests.
- Simply hit the API to see the results and the Status.

# GET     GetWeatherInKelvin 

API:  api.openweathermap.org/data/2.5/weather?q=New Delhi

Authorization   : API Key

  Key   :  <key>
  Value :  {{API key}}
  
Request Params 
  
  q     :  New Delhi
  appid :  {API key}


# GET     GetWeatherByChangingUnitToCelsius

API:  api.openweathermap.org/data/2.5/find?q=New Delhi&units=metric

Authorization   : API Key

  Key   :  <key>
  Value :  {{API key}}
  
Request Params

  q     :  New Delhi
  units :  metric
  
  

# To Run Collection

- Go to the Collections on left sidebar and click on Arrow icon.
- Click on 'Run' button to open the Collection Runner window.
- Also we can open the console to check the logs and the printed messages.
- Select the correct collection and the environment.
- Set the number of Iterations and Delay if required.
- Click on "Run WeatherAPI" button present below.
- Observe the results.


Note: All the test cases are written in the Tests tab. Test Results can be seen after hitting the API in the below section as "Test results".
