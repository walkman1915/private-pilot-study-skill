# private-pilot-study-skill
An Amazon Alexa skill to help those studying to get an FAA private pilot certificate.

## Adding your own app ID
To add your own app ID for use in src/index.js, go to your AWL Lambda function that you're using to run the skill. Under the "Code" tab, look at the bottom of the page where it says "Environment variables". In the blank on the left (Key), type in "APP_ID" (without quotes). In the blank on the right, paste in your app ID (also without quotes) from the Skill Information page on your Amazon Developer Console. Save it and you should be good to go!