<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://github.com/walkxcode/dashboard-icons/blob/main/png/jellyfin.png?raw=true" width="200" alt="Nest Logo" /></a>
</p>

  <br/>
  <h1 align="center">Jellyfin Discord Bot</h1>

  <p align="center">A simple <a href="https://discord.com" target="_blank">Discord</a> bot that enables you to broadcast<br/>your <a href="https://jellyfin.org/" target="_blank">Jellyfin Media Server</a> music collection to voice channels.<br/>It's Open Source and can easily be hosted by yourself!</p>

<p align="center">
  <small>Thanky you <a href="https://github.com/KGT1/jellyfin-discord-music-bot/">KGT1</a> for starting this project!<br/>This is a fork of their original repository and re-uses some of their code.</small>
</p>


<br/>
<hr/>
<br/>


## ✨ Features

- Leighweight and extendable using the [Nest](https://github.com/nestjs/nest) framework
- Easy usage with Discord command system (eg. ``/play``, ``/pause``, ...)
- Fast and validated configuration using environment variables
- Typesafe code for quicker development and less bugs
- Supports ``Music``, ``Playlists`` and ``Albums`` from your Jellyfin instance

## 📌 About this project
This project was originally started by [KGT1 on Github](https://github.com/KGT1/jellyfin-discord-music-bot/) in 2020. I came accross this project in late 2021, when wanted to enjoy my music on Discord. I never got it to run as I wanted it to. Since the original project was created under the MIT license, I decided to make a fork in 2022 with my own version. Although this project re-uses some code of the original project, it has been completly rewritten in other parts using NestJs and features now a module-based approach.

## ⛔ Limitations

- Bot does not support shards. This means, you cannot use it in multiple servers concurrently.
- Displaying media covers or images in Discord (Jellyfin is self hosted, and other users woudln't be able to see those images)
- Streaming any video content in voice channels (See [this issue](https://github.com/discordjs/discord.js/issues/4116))

## 🚀 Installation

Please check out the Wiki section in the repository for installation instructions:

https://github.com/manuel-rw/jellyfin-discord-music-bot/wiki



> Docker container comming soon

## 💻 Development

I'm open to any contributions to this project. You can start contributing using the following commands, after executing the installation commands:

## 👤 Credits
- https://tabler-icons.io/ (MIT)
- https://docs.nestjs.com/ (MIT)
- https://discord.js.org/ (Apache 2.0)