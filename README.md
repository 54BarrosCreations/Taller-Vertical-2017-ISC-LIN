# final-page (index.html)
---------------------------------------------------------------------------------------------------------------------------------------------
Introduction:

This project analize the needs of the customers according to the "Hospital Puerta de Hierro" services.

Looking fot the comfort of the users, we thought in a speech-to-text dynamic in the web page.
This speech-to-text dynamic is to give a faster and efficient service.

FIrst we started to create the web page in html using javascript, editing the css format and another tools to apply it for "Hospital Puerta de Hierro".

Then we use MongoDB to create the database of the doctors to link them with the users in the web page according to their prefferences, searching for all the doctors that are available in order to the opperation that the client is looking for.

---------------------------------------------------------------------------------------------------------------------------------------------
Steps:

                   ---------------------------------------------------[user]--------------------------------------------
                   |                               |                (Questions)                        |               |
                   |                               |                        |                          |               |
 [Which medical procedure do you need?] [Date for medical procedure] [Require transportation?] [Requiire a hotel?] [Register]
          
Using this questions, we register all the answers on the database to search for the best options to the client for his trip.
---------------------------------------------------------------------------------------------------------------------------------------------
Instructions:

User: Start looking the web page to see the about the hospital, contacts, partner/clients and then when the user start the survey need to answer the questiosn using speech to text, that will help to search the best option for the trip and the doctors that are vailable to do what the client want. FInally they just need to compelte the format to the hospital.

Developers: The information that is stored in the javascript file by speech-to-text will be send to the mongoDB that will catch the information to resend the best options for the user, using a server like intermediary to make this work.

---------------------------------------------------------------------------------------------------------------------------------------------
Future improvements:

	*)Improve the database with all the doctors that are registered in Hospital Puerta de Hierro.
	*)Improve graphical interface with Virtual Reality.
	*)Improve sorting algorithm to make a faster searching.
