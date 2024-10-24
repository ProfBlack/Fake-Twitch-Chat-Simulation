# Fake Twitchly

**Fake Twitchly** is a fun, customizable fake Twitch chat simulator. You can generate fake chat messages, assign usernames random colors, import messages from text files, and even use stickers. Perfect for live streams, video content, or game showcases!

## Features

- **Randomized Usernames with Colors:** Each user gets a random color to make the chat more lively.
- **Customizable Messages:** Bulk import messages or import from a `.txt` file.
- **Stickers:** Automatically adds random stickers to messages (🔥, 😂, etc.).
- **Configurable Chat Speed:** Easily adjust chat speed intervals in the config.
- **Notification System:** A notification appears when the chat starts.

## Demo Messages For You TO use:

https://pastebin.com/jncVSNGA -- 🧑 Users (generated with AI)
https://pastebin.com/hhGYGfqP -- 🤑 Messages (generated with random message generators)


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/harsizcool/fake-twitch-chat-simulation.git
    cd fake-twitch-chat-simulation
    ```

2. Open `index.html` in your browser.

## Usage

### Bulk Import

- Paste usernames and messages into their respective text boxes, one per line.
- Click "Bulk Import" to load them into the system.

### File Import

- To import messages from a text file, click "Choose File" and select your `.txt` file containing the messages (one message per line).

### Start Chat

- Press the "Start Chat" button to start the chat simulation. A notification will appear to confirm the start.

### Configuration

You can easily configure variables in the `script.js` file under the **Configuration Section**:

- **chatSpeedMin/Max:** Adjust the speed at which messages appear (in milliseconds).
- **maxMessagesDisplayed:** Set the maximum number of messages displayed in the chat at a time.
- **randomColors:** Add or modify colors for usernames.
- **allowedStickers:** Customize the set of stickers that can appear with messages.

```javascript
const config = {
    chatSpeedMin: 1000, // Minimum chat message interval in milliseconds (1 second)
    chatSpeedMax: 4000, // Maximum chat message interval in milliseconds (4 seconds)
    maxMessagesDisplayed: 100, // Maximum number of messages displayed in the chat box before clearing
    randomColors: ['#FF5733', '#33FF57', '#3375FF'], // Array of random colors for usernames
    allowedStickers: ['🔥', '😂', '👍', '💯', '🎉'], // Allowed stickers in messages
};


```

## Recommended Settings:

- To get that fast twitch chat feel, set your chatspeedMin and Max to (120 - 250)

- to get a slower feel, set it to (404 - 1200)

- to get an XQC level fast chat set it to (30 - 70)
