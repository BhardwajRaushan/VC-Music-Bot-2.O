<h1 align="centre">Bot-Musicv2 🎧

### Bot musik untuk memutar musik di grup obrolan suara telegram.

<h3>Requirements 📝</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.8+ or Higher
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

### Get STRING_SESSION from here:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-green)](https://replit.com/@fjgaming212/String-1#main.py)


### Commands 🛠

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/video <song name>` - download videos you want quickly

#### Admins Only 👷‍♂️
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/musicplayer on` - to disable music player in your group
- `/musicplayer off` - to enable music player in your group
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status

### Sudo User ✅
- `/pmpermit on | off` turn on/off the assistant pmpermit
- `/userbotleaveall` - order the assistant to leave all groups
- `/gcast` - send a broadcast message
- `/rmd` - remove all downloaded file

### pm-permit 💬
- `.yes` - approve user for sending message to assistant
- `.no` - disapprove user for sending message to assistant

### 🔎 Support Inline Search

### Heroku Deployment 💜
Cara mudah untuk meng-host bot ini, gunakan ke Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/fjgaming212/Bot-Musicv2)

## Railway Deployment 🚄
For deployment on railway you can see the full of [Necessary Variables Here](https://github.com/Tonic990/VirtualMusic/blob/main/example.env), make sure you fill all of it.

[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/fjgaming212/Bot-Musicv2&envs=SESSION_NAME,BOT_TOKEN,BOT_USERNAME,BOT_NAME,GROUP_SUPPORT,ASSISTANT_NAME,OWNER_NAME,OWNER_ID,BG_IMAGE,BOT_IMG,UPDATES_CHANNEL,API_ID,API_HASH,PMPERMIT,SUDO_USERS,DURATION_LIMIT,)

### Deploy On VPS 💙

- `sudo apt update && apt upgrade -y`
- `sudo apt install git curl python3-pip ffmpeg -y`
- `pip3 install -U pip`
- `curl -sL https://deb.nodesource.com/setup_16.x | bash -`
- `sudo apt-get install -y nodejs`
- `npm i -g npm`
- `git clone https://github.com/KennedyProject/KennedyXMusic` # Clone your repo.
- `cd KennedyXMusic`
- `pip3 install -U -r requirements.txt`
- `cp example.env .env` #Use vim to edit ENVs
- `vim .env` #Fill up your ENVs ( Steps press `i` to enter in insert mode then edit the file. Press `Esc` to exit the editing mode then type `:wq!` and press `Enter` key to save the file.)
- `python3 main.py` # Run the bot

### Credits 🕊️
- [Kennedy](https://github.com/KennedyProject) Dev
- [RojSerBest](https://github.com/rojserbest) CallsMusic Developer
- [Levina](https://github.com/levina-lab) Veez Project

### Support & Developer 🛵
<a href="https://t.me/Rizzz_Support"><img src="https://img.shields.io/badge/Join-Channel%20Support-red.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/FJ_GAMING"><img src="https://img.shields.io/badge/Developer%20Bot-white.svg?style=for-the-badge&logo=Telegram"></a>
