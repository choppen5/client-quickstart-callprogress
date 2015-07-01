#Twilio Client quicker-starter.

Based on Twilio Client quickstart https://github.com/choppen5/twilio-client-quicker-starter 

This repository uses [Twilio Call Progress events](https://www.twilio.com/blog/2015/05/introducing-call-progress-events-flexibly-track-and-control-your-outbound-calls.html) in addition to the Twilio Client tutorial.  

It uses Pusher to update the client UI on state change. 

#Install

Pre requisties/config setup - you need the following environment variables (including a Twilio account and a Pusher account)
- caller_id   = ENV['twilio_caller_id']
- account_sid = ENV['twilio_account_sid']
- auth_token  = ENV['twilio_auth_token']
- appsid      = ENV['twilio_app_id']
- pusherkey   = ENV['pusher_key']
- pushersecret= ENV['pusher_secret']

You can also use the Heroku button to deploy: [Heroku Button](https://blog.heroku.com/archives/2014/8/7/heroku-button). 


# Info on Call Progress events

Now when the Twilio Client dials, it includes events about 'initiated ringing answered completed' calls, which will be reflected in the UI.







