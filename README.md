<p align="center">
  <img height="226px" width="151px" src="https://github.com/becurrie/titandash/blob/master/img/flame.png"/>
</p>
<h1 align="center">Titandash</h1>
<h3 align="center">TapTitans 2 Bot/Progression Application</h3>
<p align="center">
  <img src="https://badge.fury.io/gh/becurrie%2Ftitandash.svg">
  <a href="https://titanda.sh"><img src="https://img.shields.io/badge/site-titanda.sh-lightgrey"></a>
  <a href="https://github.com/becurrie/titandash/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/becurrie/titandash"></a>
</p>

## Getting Started
Take a look at the [wiki](https://github.com/becurrie/titandash/wiki) for information about setting up and configuring the dependencies and requirements needed to start the dashboard and initiate a new bot instance.

You can also visit our homepage, [here](https://titanda.sh) for more information!

## Features
### Bootstrapper
- Perform automatic updates as they are released directly from this page within the web application.
- Automate the following processes through the bootstrapper:
  - Updating titandash to the newest version.
  - Install python requirements taken from the `requirements.txt` file.
  - Install all node packages from the `package.json` file.
  - Perform the database caching command to ensure it's setup properly.
  - Collect static files into the static directory.
  - Perform dependency checks (`tesseract`, `redis`, `node`).
- Display helpful error messages when any of the above processes fail.

### Dashboard
- Main dashboard screen providing real-time updates and the ability to start, pause or stop the bot and view information about the current session.
- Choose a specific window (emulator) to target when initializing a bot.
- Generate multiple instances of a bot and start bots for multiple emulator sessions.
- View a real time view of the current in game screen.
- View all log records associated with the current bot session.
- Countdowns until specific functionality takes place.
- View all sessions that have taken place and review logs/duration/prestiges that happened while a session was active.
- View all raid results instances and view data about damage done and who dealt damage.
- Create multiple configurations that can be swapped out quickly when needed (farming, tournaments, push).
- Review all current statistics taken from the game, as well as statistics related to the bot.
- View all prestiges and review additional information (average stage, average duration).
- View all artifact statistics and whether or not you currently own each one.
- Choose different themes for the dashboard (including dark theme).

### System Tray
- Open Dashboard.
- Open Bootstrapper.
- Open Github Repository.
- Exit Application.

### Bot
- Activate chosen in game skills on a specified cooldown, with the option to wait for a specific skill before activating others.
- Activate specific functions using keyboard shortcuts.
- Automatically level up the sword master, skills and heroes in game with a specific intensity (clicks).
- Automatically prestige after a threshold has been reached (stage, percent of max stage, max stage, time limit).
- Automatically parse out clan raid results from in game.
- Automatically take breaks in game after random intervals of game time.
- Receive text notifications when your raid attacks timer has reset and the titan can be attacked.
- Upgrade or ignore specific artifacts or tiers after a prestige.
- Participate in tournaments when they are available (enter/collect rewards).
- Hatch and collect any eggs when they become available.
- Collect in game ads (VIP/Watch).
- Collect daily achievements when they are completed (Watch daily ad).
- Collect milestones in game when they are completed.
- Collect daily rewards when they are available.

### Quickstart
- Ensure you've installed and configured dependencies present in the [wiki](https://github.com/becurrie/titandash/wiki/Dependencies).
- Run the `setup.bat` file to setup your virtual environment, python requirements, database migrations and static files.
- Run `titandash.bat` to start the server and application.

## Requirements
- Windows 10
- [Python 3.7](https://www.python.org/downloads/release/python-370/)
- [Node/NPM](https://nodejs.org/en/)
- [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract)
- [Redis Server](https://redislabs.com/)
- [Nox Android Emulator](https://www.bignox.com/)

## Development
Thanks for taking the time to check out this project. If you have any suggestions, 
you can create a new issue about it or create a pull request with your changes!

## Discord
You can also join our discord channel, [here](https://discord.gg/XJqfVEx) to stay up to date with all the newest features being worked on and make
feature requests here if you want.
