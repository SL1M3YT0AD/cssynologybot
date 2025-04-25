# cssynologybot
Small Aggressor Script to notify you via Synology Chat when a new beacon checks in.

## Installation
1. Create a Synology chat channel that you wish your Bot to post to (or use an existing channel)
2. Create a Synology webhook in profile (top right) -> Integration -> Incoming Webhooks -> New webhook
3. Copy the webhook url and edit bot.cna with the webhook URL and server name (name of the server beacons are connecting back to)
5. Execute the .cna script and make sure that the script is running indefinitely 

## Example Execution
```
tmux new-session -d -s bot-session /pathtocobalt/cobaltstrike/client/agscript 127.0.0.1 1337 BOT <pass> <path to script>
```

