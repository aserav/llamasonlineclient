# Llama's Online Client - Permanent Discord VC Presence V1

A Python script to keep a Discord user account permanently online in a voice channel with a custom presence.

Its not perfect but its pretty damn efficient for V1 <- 


Easily Level Up Or Afk Your Accounts In Servers! 

## Features

- Connects to a specified voice channel using a user token
- Custom activity (Playing, Streaming, Listening, Watching) & Custom status (online, idle, dnd, invisible)
- Auto-reconnect 
- Stores token and last-used server/channel for convenience
- Clean, colorized terminal interface

## Requirements

- Python 3.8 or higher
- Modules: `aiohttp`, `websockets`

Install dependencies:

```bash
pip install aiohttp websockets
Usage
Run the script:

bash
Copy
Edit
python llamasonlineclient.py
Follow the prompts to:

Enter your Discord user token

Enter server and voice channel IDs

Configure your presence (activity + status)

```

## Preview 1
![Preview 1](https://raw.githubusercontent.com/aserav/llamasonlineclient/main/preview1.png)

## Preview 2
![Preview 2](https://raw.githubusercontent.com/aserav/llamasonlineclient/main/preview2.png)

