
# Remaded Discum

### Its not Official Discum Wrapper !
This Wrapper is a Discum Copy With Addons, original one is made by **Merubokkusu**

## Authors

- [@merubokkusu](https://www.github.com/merubokkusu) (Official Author)
- [@bambikuu](https://www.github.com/bambikuu) (Me)




## Installation

How to install Discum-Remaded

```python
  python -m pip install --user --upgrade git+https://github.com/discummer/discum-remaded.git#egg=discum-remaded
```
or
```
  pip install discumremaded
```
    
# Prerequisites
- requests
- requests_toolbelt
- brotli
- websocket_client==0.59.0
- filetype
- ua-parser
- colorama

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

# Table of Contents + Links
- [Authors](#Authors)
- [Installation](#Installation)
- [Prerequisites](#Prerequisites)
- [Contributing](#Contributing)
- [Examples](#Examples)
- [Checklist](#Checklist)
- [Support](#Support)
- [PyPi](https://pypi.org/project/discum-remaded/)
## Examples

```python
import discumremaded   
bot = discumremaded.Client(token='bottoken', log=False)

bot.sendMessage("channelid", "Hello :)")

@bot.gateway.command
def helloworld(resp):
    if resp.event.ready_supplemental: #ready_supplemental is sent after ready
        user = bot.gateway.session.user
        print("Logged in as {}#{}".format(user['username'], user['discriminator']))
    if resp.event.message:
        m = resp.parsed.auto()
        guildID = m['guild_id'] if 'guild_id' in m else None #because DMs are technically channels too
        channelID = m['channel_id']
        username = m['author']['username']
        discriminator = m['author']['discriminator']
        content = m['content']
        print("> guild {} channel {} | {}#{}: {}".format(guildID, channelID, username, discriminator, content))

bot.gateway.run(auto_reconnect=True)
```


# Checklist
- [x] Make Github Repo
- [x] Make More Functions
- [x] Publish Github Repo
- [ ] Upload To PyPi
- [ ] Everything
## Support

For support, email bambikuuu@gmail.com or join our Discord Server.

