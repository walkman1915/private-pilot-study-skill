# private-pilot-study-skill
An Amazon Alexa skill to help those studying to get an FAA private pilot certificate.

## Adding your own app ID
To add your own app ID in src/index.js, create a file called "keys.js" and put it inside the "src" directory. Inside "keys.js", you should include the code:
'''javascript
module.exports = {
	APP_ID: "YOUR_APP_ID_HERE";
}
'''
