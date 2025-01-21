# REST-API-CLIENT

**COMPANY: CODETECH IT SOLUTIONS**

**NAME: Patil Mayuresh Pratap**

**INTERN ID:CT08ICW**

**DOMAIN:JAVA**

**BATCH DURATION:December 30th, 2024 to January 30th, 2025**

**MENTOR NAME:NEELA SANTOSH**

**Libraries Used**

**org.json.simple.JSONArray:** This is a part of the JSON Simple library, which allows you to parse and handle JSON arrays. In the code, it is used to extract location data from the Geocoding API response (i.e., the array of results returned by the search query).

**org.json.simple.JSONObject:** This represents a JSON object, which is a collection of key-value pairs. The JSONObject class is used to parse and handle the weather data and geolocation data.

**org.json.simple.parser.JSONParser:** The JSONParser is used to parse a JSON response into a JSONObject or JSONArray. This is used when parsing the responses from both the geolocation API and the weather API.

**Use of libraries**
The JSON Simple library allows the program to handle JSON objects and arrays returned from the APIs. For example, the location data returned by the geocoding API is parsed into a JSONArray, and the first element of the array is extracted into a JSONObject. Similarly, the weather data is also parsed as a JSONObject.

**java.net.HttpURLConnection:** This is a standard Java library used to send HTTP requests. It is used to send GET requests to the API endpoints and handle the responses. The program calls getResponseCode() to check whether the request was successful and reads the response using an InputStream.

**java.util.Scanner:** Scanner is used to read the user input from the console. It is also used to read the response data from the HTTP API responses. This class allows the program to fetch the response body and store it as a string for further processing.

**java.io.IOException:** This is a standard Java exception thrown when an I/O operation (e.g., reading from or writing to a file or network connection) fails. It is used in this code to catch potential errors related to network connections or input/output operations (e.g., if there's an issue fetching the API response or reading it).

**java.net.URL:** URL is used to represent a URL and to open a connection to it via HttpURLConnection. It is used to specify the URLs to which the HTTP requests are sent.

