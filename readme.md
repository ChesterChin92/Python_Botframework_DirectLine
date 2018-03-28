Python Bot framework Directline
Example Python for calling Bot Framework via the DirectLine API (v3)

For further details refer to the API documentation here: http://dev.botframework.com

Register your bot on the dev.botframework.com portal
Enable the DirectLine Channel and copy the secret key
Add you key below and run
Usage example

bot = DirectLineAPI('{your-direct-line-secret-here}')
bot.send_message("Hi")
botresponse = bot.get_message()
print botresponse