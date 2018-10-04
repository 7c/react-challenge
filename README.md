# WEATHER APP CHALLENGE PROJECT

Feel free to start with this challenge project to show all your skills about react

Technologies we will be covering:
- React as UI
- Redux as State Management
- Axios as ajax requests
- OpenWeatherMap.org as API Endpoint
- React-Router for routing

## API:

We will be working with https://openweathermap.org/ and use their free API. In order to work with them you need to signup to get an `APIKEY`.

Get started documentation is at https://openweathermap.org/appid and we will be working with `Weather Data` API which is at https://openweathermap.org/current . This API is able to query current weather by different properties like ZIP, Coordinate or Name of the city. We will use the Name of the city as the query property. The example API Endpoint is at https://samples.openweathermap.org/data/2.5/weather?q=London,uk&appid=b6907d289e10d714a6e88b30761fae22 

You will receive different properties from that query and it is your task to decide which properties are to visualize from the api response. 


## FEATURES IN DETAIL
- Ability to add unlimited cities by their name to a list, this list will be kept in redux (mandatory), example cities: Miami, London, Berlin, Frankfurt, Istanbul, Ankara
- If city cannot be found show an error
- Ability to remove the city
- Ability to refresh all cities unless they have been refreshed within last 60 seconds (caching)
- Ability to search and shortlist the list of the added cities by searchbox realtime (two-way-binding)
- We will have an `About` and `Home` pages. Home will host the Weather App itself and About view will host simple Text with Name of the App and the version. You need to use react-router to switch between these 2 views/components
- Make sure to have proper directory structure for scalability, hint: Components, Containers, Store, CSS
- This is the essential feature list which is required as minimum. Feel free to add new features or ideas on top of it to show your capabilities.
- Please see https://github.com/7c/react-challenge/assets/Weather_App_Mockup.png as Mockup of the UI. Make sure to center Home and About views and make them responsive

## Deployment

- Please create a github account and upload your work as public github repository. In order to do this you will need to understand basic git commands. Make sure to upload only your work, not the repos you are depending on (hint: .gitignore)

- Add a basic README.md (markdown) file to describe your App and also how to build and start your app
