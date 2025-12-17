# discord-testflight-watcher

Watching for when testflight will be open

## Usage
1. Fork repo
2. Go to Settings > Secrets and variables > Actions > Repository secrets
3. Add a secret named `DISCORD_WEBHOOK` with the value of your webhook url
4. go to `main.js` and find line where `const role = "<@ID>"` and add your role id for pings there
5. profit!
