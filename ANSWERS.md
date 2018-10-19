<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?
   Sessions are a simple way for us to store data for individual users against a unique session ID. This can be used to persist state information between page requests.
2. What does bcrypt do to help us store passwords in a secure manner.
   it hashes the password a number of times (the dev gets to choose) before storing it into the DB. This is useful because then the password isnt saved as plain text.
3. What does bcrypt do to slow down attackers?
   it adds salt, which is a way to "sprinkle" in random data to our hashes so that it increases the security of our hash.
4. What are the three parts of the JSON Web Token?
