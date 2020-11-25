# backEnd-Take-Home-Test

# Setup
1. Unzip the folder
2. Run `npm install`
3. Please change slot size if needed. In `.env` file.
4. Run `npm start` to start the server


# API's
1. Park a car
 Ex: `localhost:4000/api/car/park/:carNumber`
 
2. Unpark the car
 Ex: `localhost:4000/api/car/un-park/:slotNumber`
 
3. Get the Car/Slot Information
 Ex: `localhost:4000/api/car/details/:carNumber or slotNumber`
 
4. Show all slot details
 Ex: `localhost:4000/api/car/show-all-slots-details`
 
 
 
 
 ### NOTE: Since we are not passing any request data on body, I have made all the API method as `GET`.  So you can test it on browser as well. Not required postman since we have no `POST, PUT, PATCH etc`
