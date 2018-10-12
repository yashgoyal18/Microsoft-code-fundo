# Microsoft-code-fundo++

## Natural Disaster Management App using Visual Studio

- **Functionality 1 (Pre-Disaster):** Check the daily weather report on the app which will inform you about the temperature, humidity, rainfall, wind speed, etc. and will inform you whether these conditions are in safe zone or there is a possibility of  some natural disaster (like flood due to continuous to heavy rainfall over a period of time and flooding of nearby river).
  - **Implementation:** The app will predict based on the collected dataset of natural disaster occurred in that region in past few years and applying classification model to it (whether given weather conditions lead to some natural disaster or not).
  - **Extension:** In case of possibility of any approaching flood, by analyzing the geography of the region using Google Map API and gradient descent algorithm, the direction of flow of the excess water and expected time of water to hit the region can be calculated.
  
- **Functionality 2 (During Disaster):** 
  - Users will get real-time alerts of the natural disaster through app notifications and SMS on their smartphones. 
      - **Implementation**: App will be getting live data from National Weather Service to provide early alert to the users. 
      - **Extension**: Social media feeds like facebook and twitter posts can be constantly analyzed using NLP (Natural Language Processing) to check any presence of some posts regarding any natural disaster. If found such posts, the photos and corresponding location data can be made available to the user on the app for live updates. 
  - Interested volunteers can register themselves on the app so that they will be informed about the people seeking help nearby and about location of relief camp and relief material like food, clothing, medical first aid, sanitation, money, etc.
      - **Implementation**: The maintainence of list of people in help, their medical condition and their location using Microsoft Azure database. Volunteers can add people who are in help or remove people who have been saved. Also, a record has to be maintained for available resources in any relief camps and their requirements.
  - People stranded or in help can check location of volunteers, relief camps, safe route to move etc. nearby and also seek help through sending SOS signal through the app.
  - During registration of a user on the app, several details of the user can kept in record like his address, contact no. of relatives, bank account details so that flood relief amount can be transfered directly without delay.
  
- **Functionality 3 (Post-Disaster):** 
  - The report of the occured disaster will be created by the app consisting of all weather conditions, economic and life losses, severeness of the disaster, areas of improvement for disaster management.
  - The users can give feedback about the relief program, their grievances, improvements, etc., can share photos, posts related to disaster.
  - The data regarding the disaster is saved in the database for better prediction next time.
