# DripBot
DripBot is a Discord Bot that sends periodic messages to the user, reminding them to drink water. The bot asks users for their age and weight to determine the required number of ounces to drink. Next, the bot asks users when they wake up and go to bed, which determines the intervals at which the messages will be sent. If users don't respond to the message within time, the bot sends a text message. It's intended to be a useful tool for teenagers to become more hydrated.

As shown in the video, all someone has to do is send a message and the bot will send the user some options. Then, the user will input his/her name and age
and weight and the bot will calculate how much water that person has to drink per day. The user will also enter what time they wake up and what time they 
sleep. Based on this, the user will send periodic messages to the user reminding them to drink water. If the user does not respond to the message in time,
the bot will then send a text to the user's phone number using the Twilio API to remind them to drink water. 

This project won "Best Use of the Twilio API" at Bitcamp, a hackathon hosted by the University of Maryland, College Park. 
