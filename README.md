# Twiddler

This repo is an exercise to build Twitter clone using JavaScript, HTML/CSS and jQuery.

The file ```data_generator.js``` creates some data that represents Twitter users and their tweets. It is the data expected from a Twitter account with a few followers. More tweets appear over time. The code in this file:
- Creates two global variables, ```users``` and ```streams```
  - ```users```is an array of strings (all the usernames the account is following)
  - ```streams``` is an object with two properties, ```users``` and ```home```
  - ```streams.home``` is an array of all tweets from all the users you're following
  - ```streams.users``` is an object with properties for each user. (```streams.users.shawndrost``` has all of ```shawndrost```'s tweets)
 - Kicks off a perioddic process that puts more data in ```streams```
 
 Complete requirements within ```index.html```. The generated tweets will be displayed in reverse chronological order.

---

### Minimum Requirements
- [x] Show the user new tweets. (Show them automatically as they're created, or create a button that displays new tweets)
- [x] Display the timestamps of when the tweets were created. This timestamp should reflect the actual time the tweets were created, and should not be hardcoded
- [x] Design the interface to be user-friendly and visually pleasing
- [x] Allow the user to click on a username to see that user's timeline

### Advanced
- [ ] Show when the tweets were created in a human-friendly way (e.g. "10 minutes ago"). Find and use a library for this
- [ ] Allow the user to tweet
