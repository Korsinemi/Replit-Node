# Replit-Node
A script to update Node on Replit


Installation

1. Copy this scripts inside the ``scripts`` section on package.json
```
"node-update": "npm i --save-dev node@latest && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH",
"node-clean": "rm -rf node_modules && rm package-lock.json && npm cache clear --force && npm cache clean --force && npm i",
"replit-node": "npm run node-update && npm run node-clean"
```
- It looks like this:

![Image xD](https://raw.githubusercontent.com/Furrycality/Replit-Node/main/1.png)

2. On shell execute ``npm run replit-node``
3. Success now you have the last version of NodeJS on ur Replit, you only need to do this one time

- Cooming soon npm updater, stay tuned
