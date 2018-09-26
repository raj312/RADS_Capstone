# RADS Capstone Project
Manage Meetings Alexa Skill

Create an alexa skill to enable users to book, cancel or edit meetings using Voice user interfaces. 
NodeJS is used as the server side technology and the code will be hosted on lambda which is a serverless architecture, provided by Amazon
The skill is an Amazon skill and therefore it wil be available for use on Amazon echo devices

Basic Interaction of book meeting:

User: Alexa, ask manage meetings to book me a room for tomorrow at 2pm

Alexa: How long do you want the meeting to be?

User: 2 hours

Alexa: (Will ask for any required missing slots like subject or attendees) and then confirm with the user.

User: Yes

The device sends the request to our code which then processes this request, books the meeting and returns an appropriate response mentioning meeting booked.

Note: Meeting is booked on outlook calender
