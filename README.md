# FREE FACEBOOK LIKES - DJ LIKER
<div align="center">
  <img src="https://github.com/RozhakXD/DJ-Liker/assets/65714340/3317ffe1-5302-478c-bf53-4b6ea4ca6970">
  <br>
  <br>
  <p>
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/rozhakxd/DJ-Liker">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/rozhakxd/DJ-Liker">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=shields">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/rozhakxd/DJ-Liker">
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/rozhakxd/DJ-Liker">
    <img alt="Maintenance" src="https://img.shields.io/maintenance/no/2024">
  </p>
  <h4> Free Facebook Likes Using Termux ! </h4>
</div>

##

### What is DJ Liker?
DJ Liker is a modern tools that automates Facebook reactions to your posts, bypasses reCAPTCHA using the Multi-Bot API, and is easy to use and configure. With this tools, you can increase likes on your posts. Every 15 minutes you will get 30 reactions.

### Termux command?
First you must have the [Termux](https://f-droid.org/repo/com.termux_118.apk) to run this script and for how to use it can be seen on [**Youtube**](https://youtu.be/6to2jcOC7tw). Then you enter this command into termux!
```
$ apt update -y && apt upgrade -y
$ pkg install git python-pip
$ git clone https://github.com/RozhakXD/DJ-Liker
$ cd "DJ-Liker"
$ python -m pip install -r requirements.txt
$ python Run.py
```

```
$ cd "$HOME/DJ-Liker" && git pull
$ python Run.py
```

##

### Why login failed?
The error when logging in is caused by a problem with your Facebook cookie, because it has been hit by a checkpoint or has expired. You can also solve this problem by changing the User-Agent in the header with your browser's User-Agent so that it doesn't get checkpointed when logging in.

### When do likes arrive?
Likes should arrive on your post in less than 5 minutes, if they don't arrive within 5 minutes, maybe there are no users on the service or you entered the wrong post link. Not only this, you also have to ensure that the public likes your posts.

We recommend running the service during the day, so it's quick to bypass recaptcha.

### Change API Key?
- Open Termux and navigate to the `Penyimpanan` directory using the cd command: `cd Penyimpanan`
- Open the `Key.json` file using nano: `nano Key.json`
- Update the key with your new key value, making sure to format it correctly.
- Press `Ctrl+X` to exit, then press `Y` to save the changes.

### Your post not public?
There is a problem if an error occurs when sending a like because the post is not public, if this happens then you must use the url `https://m.facebook.com/` do not use a url other than this because it can cause the like to fail to be sent.

### Captcha bypass error?
Before using this service you have to change `Key.json` with the apikey that you have and if you have changed it but the error still occurs maybe your credit has run out or the key has expired.

##
```python
print("Thank You!")
```
##
