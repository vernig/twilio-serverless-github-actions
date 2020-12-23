# Test and deploy Twilio Serverless with GitHub Actions

This repo includes an example of automated test and deployment of a Twilio Serverless environment. 

## How to use it
* Fork the repo 
* In your repo click on Settings and then Secrets
* Create the following secrets 
  * `TWILIO_ACCOUNT_SID`: this is your Twilio account SID or your API key 
  * `TWILIO_AUTH_TOKEN`: this is your Twilio auth token or your API secret 
  * `TWILIO_SMS_API_KEY`: this is an API to send SMS (create one at https://www.twilio.com/console/sms/project/api-keys)
  * `TWILIO_SMS_API_SECRET`: this is the secret for the API key created above
  * `TWILIO_SMS_FROM`: Phone number in your Twilio account to send the SMS from
  * `TWILIO_SMS_TO`: Phone number to send the SMS to
* To test the automated testing, create a Pull Request and see GitHub Actions executing testing
* To test deploymeny, push a commit to `main` branch and see GitHub Actions deploying your Twilio Serverless environment
