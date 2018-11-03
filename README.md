## Postman API

  - create an acount with gmail
  - download postman [application](https://www.getpostman.com/apps)
  - beginner level [videos](https://www.youtube.com/playlist?list=PLM-7VG-sgbtBsenu0CM-UF3NZj3hQFs7E)

#### Postman Features
  
  - ##### Environment
      - Create an environment and name it, what it does is,you can store variables like api keys, user name,passwords you can use them as local and global variables
  - ##### Collections
      - THese are helpful to store repeated requests, we can use output of one request in other requests, by storing the output as environment global/local variables
  - ##### Assertions
      - Essential to check API output's and status code, AUTOMATION is also possible
      
### Google maps (Sending request with API key)
  - go through [this](https://developers.google.com/maps/documentation/geocoding/start)
  - create an api key
  - enable geocoding api
  - in the metric page select dropdown values, it enables the api to use
  - open postman application 
  - In the URL section enter [link](https://maps.googleapis.com/maps/api/geocode/json?address=1600+Amphitheatre+Parkway,+Mountain+View,+CA&key=YOUR_API_KEY)
  - Create an environment variable and name it, you can use pass them as url parameters, address and key 
      Example: Lets say my_api_key = 123 and my_location = hyderabad  you can them as <code>{{my_api_key}}</code><code>{{my_location}}</code>
     
  - It gives us json output, we can change  it either   
  
### Twiter (Sending request with Authorization)
