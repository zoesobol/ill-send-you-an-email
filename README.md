# ill-send-you-an-email

Project made using serverless to deploy a python app thats sends emails via SES in a lambda function

# How can I try it?

Just make a curl command like this:

```
curl -X POST -d "name=<your name here>" -d "source=zoesobol98@gmail.com" -d "subject=<subject goes here>" -d "destination=<destination email>" -d "message=<your message here>" https://joj14wtsm1.execute-api.us-east-1.amazonaws.com/dev/send-email
```


## Disclaimer

I'm still on Amazon SES sandbox so you can only send emails to verified email addresses
