It creates a scheduler that runs the "SMStoDiscord" script every minute. 
The script checks whether there are any incoming messages in the "tool/sms/inbox" folder. 
If so, it sends them in JSON format to the specified Discord webhook. Set the value of the "WEBHOOK" variable to your own link.
