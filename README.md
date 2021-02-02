# Event Manager
This project is a part of The Odin Project's Ruby course.

Objective:
- This is an exercise/tutorial in file serialization in Ruby.

Outline:
- The program reads data from a CSV file. The data is a list of attendees of an event with relevant information such as, phone numbers, zipcodes, registration dates ect..
- Program parses data: Zipcodes and phone numbers are cleaned and formatted.
- Zipcodes are used to get information on political representatives. Google's civic info API is used.
- Registration date and time isalso handled by the program (Get data on best time of day for registration or best day of week)
- Program generates thank you notes based on ERB template and outputs an HTML file as the thank you note for each of the attendees. Each thank you note contains information that is inserted dynamically based on specific attendee information.