# Receiving freshping.io notification on Telegram
Use [freshping.io](https://freshping.io) webhook to send notification through Telegram App when website is down

## How to use

Run php composer to install requirement
`composer  install`

Create your [telegram bot](https://core.telegram.org/bots#3-how-do-i-create-a-bot). 

For receiving notification on your telegram account, group or channel, you you need to know those **chat_id**.
Get your **chat_id** from [@FalconGate_Bot](https://github.com/A3sal0n/FalconGate/wiki/Get-Telegram-Chat-ID)

Make copy of config-sample.php as config.php and update it.

Create webhook in your [freshping.io](https://freshping.io) `setting > integrations > Webhook`
