# NRBot

A simple AFK bot for Minecraft Java servers (originally used with an Aternos server), built on [mineflayer](https://github.com/PrismarineJS/mineflayer). It joins the server, walks and looks around at random intervals so it isn't kicked for idling, and reconnects automatically if it gets disconnected.

> This project is **not** related to the NieR Re[in]carnation image-recognition bot of the same name.

## Requirements

- Node.js 14 or newer
- A Minecraft Java server the bot is allowed to join (offline-mode / cracked servers only, since the bot has no Microsoft login)

## Setup

```bash
git clone https://github.com/fakcodr/NRBot.git
cd NRBot
npm install
```

Edit `config.json`:

| Key | Description |
| --- | --- |
| `ip` | Server address, e.g. `yourserver.aternos.me` |
| `port` | Server port (default `25565`) |
| `name` | Username the bot joins with |
| `auto-night-skip` | `true` makes the bot run `/time set day` at night (needs operator permissions) |

## Run

```bash
npm start
```

For hosting on a platform like Heroku, the included `Procfile` runs the bot as a `worker` process.

## Notes

- Only use this on servers where you have permission to run bots.
- Aternos may still shut down idle servers according to its own rules.

## License

ISC
