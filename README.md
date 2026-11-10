# Lumen
 Had issues finding dedicated study applications for pc so made one that has all the functions of YPT whilst living on yourpc, no need for an internet connection to log your study hours. Lumen combines a Pomodoro timer and a stopwatch, and keeps a record of your study time so you can see how much you've put in each month and across the year.

Built with [Electron](https://www.electronjs.org/).

## Features

- **Pomodoro timer** – work in focused intervals with breaks in between.
- **Stopwatch** – track open-ended study sessions when a fixed interval doesn't fit.
- **Monthly stats** – see how much you studied over the month.
- **Yearly stats** – look back over your study time across the whole year.

## Getting started

### Requirements

- [Node.js](https://nodejs.org/) (includes npm)

### Install and run

```bash
git clone https://github.com/pk-left/lumen.git
cd lumen
npm install
npm start
```

## Project structure

```
lumen/
├── main.js        # Electron main process: creates the app window
├── renderer/      # The app's interface (HTML, CSS, JavaScript)
└── package.json   # Dependencies and scripts
```

## Author

Built by **PK**
GitHub: [@pk-left](https://github.com/pk-left)
