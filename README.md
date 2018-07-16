# CS467 "Pavo" team capstone project repository
Team members: Tim Dufala, Brad Beise, Jigar Gor

Phaser 3 Project Template copied from [photonstorm/phaser3-project-template](https://github.com/photonstorm/phaser3-project-template)

### Requirements

We need [Node.js](https://nodejs.org) to install and run scripts.
Will be hosted locally (port 6245) by default, via `webpack-dev-server`.

## Install and run

Run next commands in your terminal:

| Command | Description |
|---------|-------------|
| `vim `[`package.json`](package.json) | Modify --port for your environment. Default is `6245` |
| `npm install` | Install dependencies. |
| `npm start` | Serves up content in background via `forever` <br> `forever list` to monitor running process and see logs. |
| `npm stop`  | Kills all `webpack-dev-server` processes running under `forever` |
