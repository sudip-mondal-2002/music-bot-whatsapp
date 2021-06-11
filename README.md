# music-bot-whatsapp

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://www.gyan.dev/ffmpeg/builds/)
* Any text editor
## Link to tutorial video
<a href="https://www.youtube.com/watch?v=00XkvNImLsg"> Youtube video </a>
# Installation

## 📝 Cloning this repo

```cmd
> git clone https://github.com/sudip-mondal-2002/music-bot-whatsapp.git
> cd music-bot-whatsapp
```

## 🛠️ Installing the FFmpeg
* Download one of the available versions of FFmpeg by clicking [this link](https://www.gyan.dev/ffmpeg/builds/).
* Extract the file to `C:\` path.
* Rename the extracted folder to `ffmpeg`.
* Run Command Prompt as Administrator.
* Run this command:

```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```

It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've FFmpeg installed, verify that it's working by running this command to see version number (may need to restart Command Prompt):
```cmd
> ffmpeg -version
```

## 🔍 Installing the dependencies
```cmd
> npm install
```

## 🆗 Running the bot
Regular node:
```cmd
> npm start
```

Scan the QR code in the terminal using whatsapp web scanner in your whatsapp
