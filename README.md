These are just some things I want to talk about in general.
# Requests - Please, for fucks sake, use Session()
```py
import requests

with requests.Session() as Session:
  Session.get("discord.com")
```

# Async - Faster?
[Async isn't going to speed up your code.](https://calpaterson.com/async-python-is-not-faster.html)
