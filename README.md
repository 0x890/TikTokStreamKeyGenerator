# TikTok Live Stream Key Generator for OBS Studio

## Description
This Python script is a valuable tool for content creators looking to broadcast on TikTok's live streaming platform using OBS Studio, an alternative to TikTok LIVE Studio. The script's standout feature is generating a stream key, a capability typically restricted and highly sought after. This stream key enables users to stream via OBS Studio, offering more control and flexibility over their live broadcasts. Additionally, the script provides the base stream URL and a shareable URL for the stream.

## Features
- Retrieve the base stream URL.
- Generate a TikTok stream key.
- Obtain a shareable URL for the TikTok live stream.
- Support for specifying different games by their game tag IDs.
- Option to enable replay generation.
- Option to close the room when the stream ends.
- Option to choose region priority.
- Option to mark the stream as mature content.

## Requirements
- Python 3.6+
- Google Chrome browser
- Game tag ID
- Logged into TikTok LIVE studio at least once
- Have TikTok LIVE studio access


## Finding Game Tag IDs
1. Download and install this extension: [JSON Formatter](https://chromewebstore.google.com/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) (optional but recommended).
2. Visit this url to find [TikTok Live API Game Tag List](https://webcast16-normal-c-useast2a.tiktokv.com/webcast/room/hashtag/list/).
3. Use the id from the list to specify the game tag ID.


## Installation
Ensure you have Python and PIP working.
In the command line, install the required packages using the following command (run the command in the same directory as the script):
```bash
pip install -r requirements.txt
```
or if pip is not working, try:
```bash
python -m pip install -r requirements.txt
```

## Usage
Simply run the script to open the GUI.

### Command Format
```bash
python TikTokStreamKeyGenerator.py
```

Press the login button to login to TikTok. After logging in, you can enter the game tag ID, stream title, and other options. Press the go live button to generate the stream key.

## Output

The script will output:
- **Base stream URL:** The URL needed to connect to the TikTok live stream.
- **Stream key for OBS Studio integration:** Stream key that that you can use in OBS Studio to stream to TikTok.
- **Shareable URL for the live stream:** A URL that can be shared for others to view the live stream.

## FAQ
### I'm getting a "Please login first" error. What should I do?
Swap the url inside TikTokStreamKeyGenerator.py at the line 27.