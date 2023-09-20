# Telecore
simple library for telegram :|

# Repo Link
```
https://github.com/Zrexer/telecore
```

# How Install & Import
install:
`pip install telecore`

import:
`from telecore.telecore import TeleCore`

# Simple Work
    # Method: sendMessage
        from telecore.telecore import TeleCore

        token = ""
        chat = ""
        app = TeleCore(token)

        data = app.sendMessage(chat, "hello world")
        print(data)

