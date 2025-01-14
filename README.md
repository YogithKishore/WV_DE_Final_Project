This final project is a tarot reading with sensor inputs displayed onto an FHD display screen.

The input uses 2 ultrasonic sensors to detect the distance away an object is from them. Whenever an object is within 0.2 feet away from the sensors, the code recieves an input.
A tarot deck is split into 2 types of cards, major arcana and minor arcana. Major arcana are used to show major events in ones life, and minor arcana show smaller events.
Each sensor is linked up with one of the dictionaries used to store the cards information, one sensor for the major arcana, and one sensor for the minor arcana.
When an object is placed in front of the sensor, the sensors are able to give an input to the code to display a random card from it's corresponding deck on the FHD display screen.

The FHD Display screen is linked to the pi-top which is what allows the code to display the tarot cards to the user.
The tarot cards are made up of 3 main components, a name, a description, and an image directory which is saved somewhere on the pi-top.
In order to randomize the cards, I used embeded dictionaries.
What I mean is each card is a dictionary, the "name" links to the cardsname, the "description" links to the cards description, and the "image" is linked to the image directory.
Each of those cards is then placed in one of two dictionaries, based on major and minor arcana, and are then assigned a number.
Then by randomizing a number when a sensor recieves an input, you can randomly pick a card.
After picking a card, the code uses imports to create a window that displays the card's name, description, and image on the FHD display.

[https://drive.google.com/file/d/1y_EjLaNfwjW5f8i2UImtc1b-Iu9Ve7qz/view?usp=sharing](url)
