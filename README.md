# gTTS-wrapper
gTTS wrapper for Easy transition from Talkey library

# Note
As of 28.1.2020, this library is unmaintained, archived and retired. It will not recieve any updates.

# How to do it
Include this library in same folder as your code.

Download gTTS and PyGame with pip:
```
pip install gtts
pip install PyGame
```

Then, if you have code like this
```
import talkey
tts = talkey.Talkey()
tts.say('Old McDonald had a farm')
```

You have to change it to this:
```
import gTTSwrapper as tts
tts.say('Old McDonald had a farm')
```

It is easy, you have to change only 2 lines of code. This makes it super simple for easy (simple) transition from Talkey library, if you are interested, what's better.

You get also a lot of options, like language or slow tts:
```
import gTTSwrapper as tts
tts.say('Old McDonald had a farm', language="en", slow=True)
```

But for more details, check this links:
- https://github.com/grigi/talkey
- https://github.com/pndurette/gTTS
