# Test and deploy Twilio Serverless with GitHub Actions

This repo includes an example of automated test and deployment of a Twilio Serverless environment. 

## How to use it
* Fork the repo 
* In your repo click on Settings and then Secrets
* Create two secrets 
  * `ACCOUNT_SID`: this is your Twilio account SID or your API key 
  * `AUTH_TOKEN`: this is your Twilio auth token or your API secret 
* To test the automated testing, create a Pull Request and see GitHub Actions executing testing
* To test deploymeny, push a commit to `main` branch and see GitHub Actions deploying your Twilio Serverless environment