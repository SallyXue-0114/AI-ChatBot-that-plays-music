# AI-ChatBot-that-plays-music
I would also call it an Idol Chatting Bot, because you can chat with your idol through this bot, and also listen to their songs! ✨

# Installation
1. Make sure you have your Discord bot and get a token. You can follow this tutorial:

    https://realpython.com/how-to-make-a-discord-bot-python/

2. Clone and navigate to chatbot directory.

3. Install the required packages/dependacies.

```
pip install -r requirements.txt
```

4. Run the python server. Be sure to replace "YOUR-DISCORD-TOKEN" in bot.py and music.py with your actual token.
```
python bot.py
```

# How to use
1. This bot currently only support "Greetings" and "Goodbye" intents. However, you can go to intents.json and change the "patterns" and "responses" to phrases of your choice! Once the bot recognizes that the sentence you ask includes certain patterns, it would replies with the phrases in "responses".
2. If you enter "songs", the bot would start the song searching service. Here's the commands:

    !play : It would randomly choose a song from the videos you provided (in music.py line 16, currently I only include one song, but you can add     other songs you like! Make sure it is an youtube video link), and play that song in the voice channel. Note that you need to wait for the video to download.

    !pause : pause the song.

    !resume: resume the paused song.

    !stop : stop playing that song.

    !leave: the bot would leave the voice channel.

# References
Discord music bot: https://github.com/afazio1/robotic-nation-proj/tree/master/projects/discord-bot

AI MealBot: https://github.com/anasselhoud/AI-ChatBot

Thank you so much! Also thanks sosp2022 for giving me the very first project experience! 🐱
