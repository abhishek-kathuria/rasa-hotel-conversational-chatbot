# rasa hotel conversational chatbot

# Objective
To build a simple chatbot for a hotel. </br>
The chatbot should be able to the following basic functionalities </br> <br>
-Book room <br>
-Request Room Cleaning <br>
-Handle FAQs <br>
-Handle Greetings

# Prerequisites:
Python <br>
Rasa 2.0

# Setup:

-Clone this repo <br>
-cd into the directory <br>
-Install rasa 2.0 <br>
-Run command "rasa train"  <br>
-Run command "rasa shell" to interact with the chatbot in the terminal  <br>

# Sample Use Case
## Book Room

**User**: I want to book a room.

**Bot**: Select the number of rooms you want to book
- Button 1 - 1 
- Button 2 - 2

**User**: (Clicks on Button 2)

**Bot**: Select from one of the room types
- Button 1 - Simple 
- Button 2 - Deluxe

**User**: (Clicks on Button 1)

**Bot**: Your room(s) have been booked. Number of Simple rooms booked : 2

(Clicking on button 2 is handled similarly)
