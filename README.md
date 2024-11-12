# python_api_challenge
# World_Weather_Analysis
    Ever wondered why it gets hotter near the equator? This project seeks to unravel this mystery by analyzing weather data. Using Python's requests library, I accessed weather APIs and parsed JSON data to uncover the underlying patterns. The repository is structured into two parts, each housed in its own folder.
    
    In the first part (WeatherPy), I embarked on a global weather exploration. A diverse range of 500+ cities, spanning various distances from the equator, were selected through a random generation of latitude and longitude coordinates. The nearest city for each coordinate pair was identified using Citipy, and weather data was sourced from the OpenWeatherMap API. The collected data is meticulously organized in a CSV file.
    Using the data received from the OpenWeatherMap API, a series of scatter plots were built to visualize the following relationships:
        Temperature (F) vs. Latitude
        Humidity (%) vs. Latitude
        Cloudiness (%) vs. Latitude
        Wind Speed (mph) vs. Latitude
    After each plot, you will find a mini summary about the code and what it is analyzing.
    A linear regression was conducted on each relationship separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
    After each plot, a small explanation of what the linear regression is modeling and of any other interesting relationships is included. Images of all the plots are saved in the output_data folder.

   In the second part (VacationPy), weather data was used to identify ideal vacation destinations. A heatmap, created with Jupyter notebooks, geoViews Python library, and the Geoapify API, visualized humidity levels across all cities. The data was filtered for these specific weather criterias:
        A max temperature lower than 27 degrees but higher than 21
        Wind speed less than 4.5 m/s
        Zero cloudiness 
    Any rows that did not meet these criterias were dropped. Then these destinations were plotted on a heatmap for each city within 10000 meters of the coordinates.


# File Submission:
        This assignment includes the following attchments:
              A WeatherPy folder that contains a jupyter source file and an output data folder.
              A VacationPy folder that contains a jupyter source file and an output data folder.
              A .gitignore file
              A license
              A Readme.md file



# Acknowledgements
        **Internet Search: I utilized Google Search and slack overflow to research coding concepts, algorithms, and best practices.
        **Gemini AI: I leveraged Gemini AI to generate code suggestions, debug errors, and provide explanations for complex code segments.
        **Support Staff: I recieved help from my instructor and class TA during office hours for help with debugging errors and further explanation for complex code segments.
        **Please note: While these tools were invaluable in my development process, the final code is the result of my analysis, testing, and refinement.