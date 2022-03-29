These are just some things I want to talk about in general.
# Requests - Use sessions
```py
import requests

with requests.Session() as Session:
  Session.get("discord.com")
```

# Async
[Async isn't going to magically speed up your code.](https://calpaterson.com/async-python-is-not-faster.html)
