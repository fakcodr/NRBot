# NRBot

NRBot is an image recognition based bot for NieR Re[in]carnation. It is based on the Airtest framework (Python). It currently only supports English UI. The main goal of NRBot is to automate repetitive content in the game where a simple macro won't suffice.

Installation

Install AirtestIDE.
Extract it to your favorite path.
Download ADB (e.g. from here) and add it to your system path.
Copy settings.default.jsonc to settings.jsonc and update the config. Refer to the comments for instructions.
Make sure you already set up the proper team for the quests in the game.
Usage

Run python NRBot.py <script_name> in this directory. Here, <script_name> can be any of the following:

resetfarming: Farms purple grade items in daily dark lairs by resetting if no drop.
darkdaily: Clears all specified daily dark lairs.
dungeon: Farms specified dark dungeon for memoirs.
arena: Battles in arena.
Example

To farm purple grade items in daily dark lairs, run the following command:

python NRBot.py resetfarming
NRBot will then start farming the dark lairs, resetting if no purple grade item drops. It will continue farming until you stop the script.

Notes

NRBot is still under development. Please report any bugs or suggestions to the author.
NRBot requires AirtestIDE to be installed.
NRBot currently only supports English UI.
License

NRBot is licensed under the MIT License.

Contributing

Contributions to NRBot are welcomed. Please fork the repository and create a pull request with your changes.

Sources
github.com/Anyrainel/NRBot
github.com/Anyrainel/NRBot#:~:text=NRBot%20is%20an%20image%20recognition,simple%20macro%20won't%20suffice.
