---
title: "You can send texts "
date: 2017-09-17T00:51:31-07:00
tags: ["lifehack"]
bigimg: /img/sphere.jpg
draft: true
---
**TL;DR Send text from any sender using Twilio**<br>
(1) Register [Twilio](www.twilio.com) account<br>
(2) Get API keys
(3) Run this Python code

```python
from twilio.rest import Client

# PUT IN YOUR CREDENTIALS BELOW
account_sid = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
auth_token = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"

client = Client(account_sid, auth_token)

client.messages.create(
    to="+12345678",
    from_="FBI",
    body="We're outside your building"))
```

[BILD PÅ SMS FRÅN FBI]




<!--more-->

------

#### Be whoever you want to be (over text)

Ever wanted to trick your friend that the FBI is outside his apartment? Ever wanted to send a fake text from your dad to your sibling? Ever wanted send a booty call from your friend's phone to her lovers?

Look no further!

<br><br><br>
*With love,*<br>
**afo**
