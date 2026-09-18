# Website and server setup

The `website/` directory contains a self-contained landing page for the Eaglercraft 1.12 server. It does not include a game client. Set `PLAY_URL` in `website/config.js` to an authorized Eaglercraft web client URL before publishing the page.

## Publish the website

The page can be served by any static host or by the optional EaglerWeb plugin referenced by the upstream project. For GitHub Pages, set the Pages source to the `website` directory if your Pages configuration supports a custom folder, or copy these three files to the publishing root.

## Connect to the server

Edit `SERVER_ADDRESS` in `website/config.js` to the public DNS name or IP and port that players should use. The Paper server is configured for port `25565`, supports up to 50 players, and uses the Eaglercraft-compatible offline/proxy setup required by this template.

Keep the client and server files authorized and comply with the licenses of all plugins and assets you deploy.
