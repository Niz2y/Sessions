If you are going to use requests, for fucks sake please use Sessions.
# Sessions
```py
import requests

with requests.Session() as Session:
  Session.get("discord.com")
```
