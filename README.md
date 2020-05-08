# Social Distancing App - 590U A5

### Idea/Motivation
A large population of the public now-a-days have smartphones. Secondly, almost all smartphones of the present day have bluetooth and GPS capabilities. The GPS gives the users' realtime location, whereas the bluetooth can be used to continiuously discover other bluetooth smartphones (which can easily be used as a proxy for other people nearby!) in the near vicinity. Hence, these sensors when used in sync hold immense potential to apply ubiquituous to the problem of social distancing.

Given the above motivation, we can come up with the following idea for the app;

**Use the bluetooth to discover new smartphone devices in close vicinity, while outside home, at constant intervals of time (every 10 to 15mins). Combine this with the realtime location data to identify crowded regions on a map and provide this info to the user in realtime. Lastly, utilize the average count of bluetooth devices seen throughout the day as a logical metric for social distancing.**

### UI/UX Design
The user interface has been explored in detail in the video. I'll just give a short description of the interface and the main buttons here;
- There is just one activity/screen in this app for ease of usability. All important details such as "Nearby People", "Tracking Status" and the current distancing score estimate (*which updates on pressing the "My Score" button*); is displayed on the same screen.
- The majority of the screen is covered with the Google Maps, which is something most smartphone users now-a-days are comforatble working with. The app has access to the Places API, which allows the users to interact freely with the UI.
- The button on the top right of the screen called "Set Home", lets the user set their home coordinates on the map with a green marker.
- The "Track" button on the  bottom left initiates the constant time duty cycle for  bluetooth device scanning. It starts sensing for nearby bluetooth devices every 20 seconds (this duration will be kept around 10 or 15mins in a practical scenario). For the purposes of the demo we are scanning for all devices, but in a real world scenario, we would only scan for smartphones. **The code has commented lines of code that just sense for other bluetooth smartphones.**
- The "Stop" button in the middle 

### Scoring Metric Engineering
### Evaluation
### Highlighting Contribution
### Video Link
