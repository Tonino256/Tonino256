- 👋 Hi, I’m @Tonino256
- 👀 I’m intere![Screenshot_20231121-165517](https://github.com/Tonino256/Tonino256/assets/150787608/3aa32993-21f2-41b2-bd34-493078a170e9)
sted in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me . WhatsApp..

<!---
Tonino256/Tonino256 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--
  "name": "hermit-md",
  "description": " Whatsapp bot.",
  "keywords": [
    "whatsapp bot"
  ],
  "repository": "https://github.com/A-d-i-t-h-y-a-n/hermit-md",
  "stack": "container",
  "env": {
    "SESSION_ID": {
      "description": "session id",
      "required": true,
      "value": ""
    },
    "SUDO": {
      "description": "owner number of the bot",
      "required": true,
      "value": "null"
    },
    "MODE": {
      "description": "mode public or private",
      "required": true,
      "value": "private"
    },
    "ALWAYS_ONLINE": {
      "description": "show bot number last seen as online",
      "required": false,
      "value": "false"
    },
    "HEROKU_APP_NAME": {
      "description": "Heroku app name, same as above entered",
      "required": true
    },
    "HEROKU_API_KEY": {
      "description": "Heroku account api key, https://dashboard.heroku.com/account",
      "required": true
    },
    "LOG_MSG": {
      "description": "Show whatsapp msgs in log",
      "required": false,
      "value": "false"
    },
    "PREFIX": {
      "description": "prefix for bot. all so can be null or false multi prefix",
      "required": true,
      "value": "."
    },
    "BOT_INFO": {
      "description": "botname;ownername;ownernumber;image url",
      "required": true,
      "value": "ʜᴇʀᴍɪᴛ;ᴀᴅɪᴛʜyᴀɴ;972528277755;https://i.imgur.com/pbNNWfM.jpeg"
    },
    "STICKER_DATA": {
      "description": "sticker package name",
      "required": true,
      "value": "ʜᴇʀᴍɪᴛ;ᴀᴅɪᴛʜyᴀɴ"
    },
    "AUDIO_DATA": {
      "description": "audio package name",
      "required": true,
      "value": "ʜᴇʀᴍɪᴛ;ᴀᴅɪᴛʜyᴀɴ;https://i.imgur.com/pbNNWfM.jpeg"
    },
    "READ_MSG": {
      "description": "Read all messages",
      "required": false,
      "value": "false"
    },
    "AUTO_STATUS_VIEW": {
      "description": "automatic read status",
      "required": false,
      "value": "false"
    },
    "REJECT_CALL": {
      "description": "automatic reject call",
      "required": false,
      "value": "false"
    },
    "WARN": {
      "description": "warn count",
      "required": false,
      "value": "4"
    },
    "SONG_THUMBNAIL": {
      "description": "show youtube video thumbnail in song cmd",
      "required": false,
      "value": "false"
    },
    "ERROR_MESSAGE": {
      "description": "get error alert",
      "required": false,
      "value": "true"
    }
  },
  "addons": [
    {
      "plan": "heroku-postgresql"
    }
  ]
>
