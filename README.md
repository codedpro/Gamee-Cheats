# Gamee-Cheats

## Overview
Gamee-Cheats is a graphical user interface (GUI) cheat tool designed for the Gamee website. This tool allows users to increase their score in any game available on the Gamee website.

## Features
- Increase your score in Gamee website games.
- User-friendly GUI for easy interaction.
- Telegram contact option to reach out for support.

## How to Use
1. Install dependencies by running the following command in your terminal:
    ```
    pip install -r requirements.txt
    ```
2. Run the Python script:
    ```
    python CodedCheats.py
    ```
3. Enter the Game link, Score, and Time in the provided fields.
4. Click the "Submit" button to apply the cheat.

### Additional Option (exe):
- Alternatively, you can download the exe from the "builds" section and install it on your device.

## Script Details
The Python script uses PySimpleGUI for the GUI and includes the following key functions:
- **get_checksum:** Generates a checksum based on the provided score, playtime, and game URL.
- **get_token:** Retrieves an authentication token from the Gamee API.
- **game_id:** Retrieves the game ID for the given game URL.
- **send_score:** Submits the score, playtime, checksum, and token to the Gamee API.

## Disclaimer
Use this tool responsibly and be aware that cheating in online games may violate terms of service and result in consequences, including account suspension.

## Author
Coded by Coded_Pro. Contact on [Telegram](https://t.me/coded_pro).
