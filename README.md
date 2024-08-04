
# CleanMOTD Plugin

## Overview

This is a free BungeeCord/Spigot plugin that is a light, simple but complete motd manager plugin that overrides the default BungeeCord motd system, to make it more capable while being light and good performant.

There are some plugins that makes lot of heavy actions when players ping the server, this one instead keeps everything safe, light and clean.

You can use this plugin installed with another MOTD plugin to improve performance. CleanMotD will automatically give priority to the other plugin if you disable the "motd" option in CleanMotD.

This plugin was mainly made for ArkFlame Network, but i published it because it will help people and the development of the plugin by finding bugs, getting new ideas, etc...

## Features

- **Flexible Configuration**
- **Multiple Random MOTDs**
- **JustOneMore MaxPlayers**
- **Advanced FakePlayers System**
- **Customizable Player Sample List**
- **Customizable Protocol Version Name**
- **Packet Use with ProtocolLib**
- **Minimal Performance Impact**

## Commands

- `/cleanmotd help` - Shows the available commands.
- `/cleanmotd reload` - Reloads the configuration.

## Permissions

- `cleanmotd.admin` - Permission to use commands.

## Installation

1. Stop your server.
2. Download and place the plugin .jar file into your plugins folder.
3. Start your server to generate configuration files.
4. Customize the configurations as needed and reload the plugin.

## Building from Source

To build CleanMOTD from the source, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/2lstudios-mc/CleanMOTD.git
    cd CleanMOTD
    ```

2. Build the plugin using Gradle:
    ```sh
    ./gradlew build
    ```

3. The built .jar file will be located in the `build/libs` directory.

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m "Description of changes"
    ```
4. Push to your branch:
    ```sh
    git push origin feature-branch
    ```
5. Open a pull request on GitHub.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you see fit.

## Links

- [GitHub Repository](https://github.com/2lstudios-mc/CleanMOTD)
- [SpigotMC Resource Page](https://www.spigotmc.org/resources/2ls-cleanmotd-the-ligthest-motd-plugin.58268/)

