//{
//	"clientID": "hl383lDAyfZbbGy+bRDIrA==",
//	"serverToken": "1@IUQfDVc5pX4uvTXtU6uJlQQiOsZvAzvXjEVUdWdXGAlutq6lI2Jw70o3qtIPbQXG3FyBHCmny098fQ==",
//	"clientToken": "gF4K/jty5G6eyLOJ6SMcrEKWCktQVXp4p2aJrP0lOrc=",
//	"encKey": "NSeQd3DlZSo+VrIrjOgR91oUPTtIIYMHOcv2SPJi7Qk=",
//	"macKey": "UnJ8BiJ1oMDaozY+CW2xXsBfsNTuJsUF7n6EN5S83Sc="
//}
# wabot-aq
Simple WhatsApp Bot

### FOR TERMUX USER
```bash
> pkg update && pkg upgrade
> pkg install git -y
> pkg install nodejs -y
> pkg install ffmpeg -y
> pkg install imagemagick -y
> git clone https://github.com/Nurutomo/wabot-aq
> cd wabot-aq
> npm install
```
###### Run
```bash
> node . [<session name>] (session name is optional)
```

---------

### FOR WINDOWS/VPS/RDP USER
* Download And Install Git [`Click Here`](https://git-scm.com/downloads) <br>
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download) <br>
* Download And Install FFMPEG [`Click Here`](https://ffmpeg.org/download.html) (don't forget to path) 
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php) (if nulis want work,  checklist columns 1,2,3,5,6) 
```bash
> git clone https://github.com/Nurutomo/wabot-aq
> cd wabot-aq
> npm install
```
###### Run
```bash
> node index.js
```
--------------

# Arguments `node . [--options] [<session name>]`

## `--self`
Activate self mode (Ignores other)

## `--prefix <prefixes>`
 - `prefixes` are seperated by each character
Set prefix

## `--server`
Used for [heroku](https://heroku.com/) or scan through website

## `--big-qr`
If small qr unicode doesn't support

## `--restrict`
Enables restricted plugins (which can lead your number to be **banned** if used too often)
 - Group Administration `add, kick`

## `--img`
Enable image inspector through terminal

## `--nyimak`
No bot, just print received messages and add users to database

## `--test`
**Development** Testing Mode

--------------

##### Powered By : [`XTEAM`](https://api.xteam.xyz) 
##### Author / Creator : [`Nurutomo`](https://GitHub.com/Nurutomo) 
