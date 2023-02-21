# Eitaabot
<p align="center">
    <br>
        <img src="https://s2.uupload.ir/files/inshot_20230218_173605494_ss40.jpg" alt="Eitaabot" width="428">
    <br>
    <br>
    <b>Eitaa Bot Library for Python</b>
    <br>
</p>

## Install via pip
```
pip install Eitaabot
```

## Example
Getting channel's information :
```py
from Eitaabot import Bot
print(Bot.get_info("eitta")) # "eitta" is a channel id
```

Sending messages :
```py
from Eitaabot import Bot
bot = Bot("your eitaayar.ir token")
print(bot.send_message("chat id","message text",pin=True))
```


© 2023 Mohammad Saeed Salari
