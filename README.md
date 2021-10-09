# w9d3-weather-api

[🔗 Slides](https://techtalentsouth.slides.com/ttscurriculum/open-weather-api-java?token=wsT0wXR_)  
[🔗 Spring config](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.5.5&packaging=jar&jvmVersion=11&groupId=com.tts&artifactId=w9d3-weather-app&name=w9d3-weather-app&description=Weather%20app%20built%20on%20Open%20Weather%20Map%20API&packageName=com.tts.w9d3-weather-app&dependencies=devtools,h2,data-jpa,lombok,thymeleaf,web)

## Requirements

Please turn in what you have completed for Tuesday's Weather API project. The homework prompts below are **NOT REQUIRED!**

Modify the app so that it displays a list of the 10 most recent searches. Here is a summary of the changes you'll need to make:

    1. Add the necessary database settings to application.properties.
    2. Create a model/entity to store zip codes in the database.
    3. Create a zip code repository.
    4. Inject the zip code repository into the weather service.
    5. Any time the getForecast method is called in the weather service, add the zip code to the database.
    6. Create a weather service method to get the (up to 10) most recent searches.
    7. In both of the weather controller methods, call the new service method and add the the list of zip codes to the model.
    8. In both of the weather controller methods, call the new service method and add the the list of zip codes to the model.
    9. In the html page, add code to display the recent searches in a table.

Use the weather description in the API response to dynamically change the background on the page. You will have to get images from unsplash.com for each possible weather scenario.
