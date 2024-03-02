```markdown
# Cops vs Robbers Game Mode
```
## Copyright

```plaintext
Copyright (c) [2024] [Liam Ridley]

All rights reserved. 

The software and its associated documentation files (the "Software") are proprietary and confidential. You may not copy, modify, merge, publish, distribute, sublicense, sell, or create derivative works based on the Software without express written permission from the copyright holder.

To obtain permission, please contact [@ncl_liammmmm on Discord or business@cloudworksmanager.co.uk].

Unauthorized use, reproduction, or distribution of the Software or any portion of it may result in severe civil and criminal penalties, and will be prosecuted to the maximum extent possible under law.

By using this software, you agree to abide by these terms and conditions.

Cost: £14.99
```

## Description

This is a Cops vs Robbers game mode plugin for FiveM. It includes features such as team assignment, objectives, and rewards.

## Installation

### Prerequisites

Make sure you have the following installed before proceeding:

- [FiveM](https://fivem.net/)
- [ESX Framework](https://github.com/esx-framework/es_extended)
- [Cops VS Robbers](https://eternal-v.tebex.io/category/custom-fivem-stuff)

### Steps

1. Clone this repository to your server's resources folder:

   ```bash
   1. git clone https://github.com/nclliammmmm/cops-vs-robbers-esx.git
   2.	Add the following line to your server.cfg file: ensure cops-vs-robbers
   3.	Configure the plugin settings in config.lua if needed.
   4.	Restart your FiveM server.
   5.	Start the game mode in the server console or in-game: start cops-vs-robbers
   6.	Enjoy the Cops vs Robbers game mode!
 
## Configuration

To customize the Cops vs Robbers game mode, follow these configuration steps:

1. Open the `config.lua` file located in the `resources/cops-vs-robbers` directory.

2. Adjust the settings based on your preferences. Here are some configurable options:

   - `RobbersRewardAmount`: The amount of money rewarded to each robber team member at the end of the round.
   - `CopsRewardAmount`: The amount of money rewarded to each cop team member at the end of the round.
   - `GameCost`: The cost to play the game, in your desired currency (£14.99 as default).

   Example:

   ```lua
   Config.RobbersRewardAmount = 500
   Config.CopsRewardAmount = 1000
   Config.GameCost = 14.99
   ```
   
3.	Save the config.lua file.
4.	Restart your FiveM server to apply the changes.
   
## Usage

To start the Cops vs Robbers game mode on your FiveM server, follow these steps:

1. Make sure you have successfully installed and configured the Cops vs Robbers game mode by following the [Installation](#installation) and [Configuration](#configuration) steps.

2. In your server console or in-game, use the following command to start the game:

   ```bash
   start cops-vs-robbers

This command initiates the game mode, setting up teams, objectives, and rewards.

	3.	Once the game mode is started, players will receive notifications in the game chat regarding their objectives and the game rules.
	4.	Players can participate in the Cops vs Robbers game by paying the specified game cost (£14.99 as default) to enter.
	5.	Enjoy the Cops vs Robbers game mode with your community!

## License

This software is proprietary and confidential. See the [Copyright Notice](#copyright) for details.

## Contact

For inquiries or permission requests, please contact Liam Ridley at @ncl_liammmmm on Discord or liamridley121@gmail.com
