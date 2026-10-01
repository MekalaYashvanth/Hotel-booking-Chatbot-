A conversational hotel booking bot built during my AWS cloud internship. Users chat on WhatsApp (via Twilio sandbox) to book a room: the bot collects city, check-in date, nights, room type and guest name, a Lambda function validates the input and generates a booking ID, and DynamoDB stores the booking.

Stack: Amazon Lex, AWS Lambda (Python), DynamoDB, Twilio
Status: Course project running on Twilio's sandbox; bookings are test data.
Known gaps: Confirmation doesn't show nights or total price, no availability check, no cancellations.
