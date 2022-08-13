# 00.Gaddy ~ My projects

## Fastcord
Fastcord is a libary build on top of [Discord.py](https://github.com/Rapptz/discord.py) that simplifies the building of a Discord bot down from **this**:

    @client.event
    
    async def on_message(message):
    
    if message.author == client.user:
	    return
    
    elif message.content.startswith('-Test'):
	    await message.channel.send('This is a Test!')
	    
	else:pass

to **this** :

    Start
    command("-Test")
    msg.send("This ia a Test!")
    Stop

because of this change it´s more like writing Ruby than Python because the User just can write a Bot with just plain English and some Syntax.

