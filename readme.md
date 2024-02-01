<h1>About this App:</h1>
<p>
This app scrapes data from a mock music tour website and stores the data in a SQLite
database. When a new event is scraped it is added to the database and an email is sent
to the specified account. If you do not recieve an email for a scraped event check the
database to see if it was already in there. The email function only works for new 
events.

User must fill the "sender", "sender_app_password", and "reciever" variables
located in the Email class.
</p>
