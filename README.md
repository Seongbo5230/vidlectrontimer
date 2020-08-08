# vidlectrontimer

A video timer app using electron

---
### Installing electron
`nvm install 14.7.0`
`nvm use --delete-prefix v14.7.0`
`npm init`
`npm install --save electron`

### Running electron
`"electron": "electron ."` inside `package.json`
Then, in CLI, run `npm run electron` -> `electron` here is referring to `electron` in `package.json` (line 7)

### `breaking app.on('ready', () => {});`
- `app` the thing we're listening to
- `ready` the event we're listening for
- `() => {}` the function to run when an event occurs
