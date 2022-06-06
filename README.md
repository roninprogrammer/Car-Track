# Car-Track
Cartrack Mobile Application Challenge. 

## Feature  
Screens:
Splash Screen:
mock up users with username, password, country and insert into the database via “SQLITE database + Room module”, we will use for login UI.
The password should not be store as plaintext, and must be secure enough and contain upper case, lower case, numeric, special char like $, %, min length 7 chars. Username should not contain space special chars.


Login UI (Validation of inputs is a must):

2.1 Username: not contain special chars and min 7 chars
2.2. Password: must contain upper case, lower case, numeric, special chars, min 7 chars.
2.3. Country selector: Required.
2.4. Remember Login: user can select this to remember the login state. Once remembered, means if app is killed and launch again, app should skip the login and go to the user list UI.
2.4. Others: Show error when validate / login failed.



User List:
3.1 . Only shows when user is logged in or redirect user to login screen.
3.2. Request data from https://jsonplaceholder.typicode.com/users 
retrofit, RXJava / Coroutine is a must.

3.3. Save the response into SQLite, and display the user list data.
3.4. Tap on the list item will go to the User details page.
3.5. Master Details page style is a must.
3.6. Show a logout button to logout, clear the login state and redirect to the Login UI.


User Details:
4.1. Implementing the Google map API 
If Google map is not available, u can consider Openstreet Map API
(https://github.com/osmdroid/osmdroid/wiki/How-to-use-the-osmdroid-library-(Kotlin)).
4.2. Show the user’s location on map.
4.3. Show “My current location”, which is device’s location.
4.4. Default zoom to Singapore.
4.5. Show user’s details on screen.
4.6. Only Shows when user is logged in or redirect user to login screen.

