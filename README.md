# Click-Care
<br/>
This app was built as a solution for the ZS Prize healthcare Hackathon
<br/>
Click Care is an app prototype designed to combine healthcare and AI using smart watch.
<br/>
The main idea of this app is tracking the vitals of the people using the data received from the smart watch of the user and linking each person with the nearest registered hospital.
<br/>
The app provides the user with an SOS emergency button which the user can access in case of any emergency. The app is linked with a number of hospitals. Once the SOS button is pressed, our ML model scans the live location of the user and finds the nearest registered hospital from that location. A notification is sent to the hospital where the hospital sends ambulance to the location and accepts the emergency based on their bed availibility. In case the hospital capacity is full then the notification is sent to the next nearest hospital and the same process is repeated. In the time being, a doctor is assigned to the person who checks the previous medical records of the patient updated in the app.
<br/>
This app when installed also has the feature of sending the notification based on live vital tracking. For example the app tracks heart rate, temperature and other vitals. Our ML model trains the live data on multiple fields and once they cross the optimal limit the above procedure is repeated. The app user also gets the facility to access the SOS button from their smart watch as well.
<br/> 
