# p2pdesk

For LAN remote control, similar to TeamViewer and AnyDesk.

## Initialize

```bash
npm install
```

## Start the server side (controlled side)

First install ffmpeg.

For linux (ubuntu) systems.

```bash
sudo apt install ffmpeg
```

For windows systems.：

Download ffmpeg https://ffmpeg.zeranoe.com/builds/, unzip it and put ffmpeg.exe under the current path.

Finally, start the server by executing the following command.

```bash
node server.js
```

## Start the client (console)

For linux (ubuntu) systems.

```bash
node client.js <server-ip>
```
For windows systems.

Download the windows client: <https://github.com/keyou/peerdesk-windows/releases>

