
# Box music

This Script is extremly simple however you need to setup your spotify, and you need RFID sensors.

The script captures the RFID card and from the id it plays the specific music that you wish.
Box music is inspired by the stylus record player.
## Demo of Box Music

https://user-images.githubusercontent.com/68626539/155424480-f65923aa-f782-4c8c-be30-6b8357dfaf69.mp4

## Features

- having the futuristic feeling
- the feeling of future on your palms
- enjoying the music that you love, by using a physical key
- showing your friends how cool you are
- learning how to use raspberry pi boards and how to write python


## Running Box Music

To run box music, run the following commands in your raspberry pi

```bash
  python test.py
  python script.py
```

You have to run the test.py first to get the id of your cards and paste them in your script.py file and if you want change the songs you need to change the urls.

Don't forget you need a spotify developer account and you need to enter the redirect url to get the .cache file.
You need a raspberry pi and a RFID sensor with at least one or two cards (I had 9 and I entered all of their ids in the app and I'm using them).


## Installation

Install Box music requirements

```bash
  pip install -r requirements.txt
```
    
## Created by Who????!

Created By AlPHA With ❤️
