# alexaodds
alexa skill to run odds
Super quick skill to run odds w/ Alexa
Releasing this under the GPLv3 license.

--
Paste lambda.py into a new AWS Lambda function here:

https://console.aws.amazon.com/lambda/home?region=us-east-1

(NB: make sure to use us-east-1 because it’s the only one that Alexa can use according to the docs)

Then create an Amazon Echo app / Alexa Skills Kit here:

https://developer.amazon.com/edw/home.html#/skills/list

Take the Application Id from the app and paste it into the code where it says FIX-ME PUT APPID HERE

Grab the ARN from the top right and put it in “Endpoint” under the app.

The skill can be invoked by saying "Alexa ask Odds run odds out of {x}" where x is any positive integeer
--


Todo: make code resistant to invalid input, make calling the skill more fluid.
