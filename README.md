Welcome Plugin for PocketMine-MP

Description:

The Welcome plugin for PocketMine-MP sends a customizable welcome message to players when they join the server. It also provides additional information to help new players get started, and gives a welcome gift to first-time joiners.

Installation:

1. Download the Welcome plugin from the official PocketMine-MP website or from a trusted source.
2. Place the Welcome plugin file (.phar) in the plugins folder of your PocketMine-MP server.
3. Restart your PocketMine-MP server.

Configuration:

The Welcome plugin can be configured by editing the config.yml file in the plugin's data folder. The following options are available:

welcome-message: The welcome message that is sent to all players when they join the server.
additional-information: A list of additional information that is sent to all players when they join the server.
welcome-gift: The welcome gift that is given to first-time joiners. The format is as follows:

welcome-gift:
  id: <item id>
  damage: <item damage value>
  amount: <item amount>


Usage:

The Welcome plugin does not require any commands or permissions. It will automatically send the welcome message and additional information to all players when they join the server. First-time joiners will also receive the welcome gift.

Support:

If you have any questions or problems with the Welcome plugin, you can create an issue on the plugin's GitHub page: https://github.com/maniApt42/Welcome

Additional Notes:

The Welcome plugin is compatible with PocketMine-MP API 3.0.0 and later.
The welcome message, additional information, and welcome gift can be customized to fit your server's needs.
