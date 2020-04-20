.. Channel Manager documentation master file, created by
   sphinx-quickstart on Fri Apr 17 11:37:56 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Voice Channel Manager Discord Bot
===========================================

.. toctree::
   :caption: Table of Contents
   :maxdepth: 2
   :hidden:

   getting_started
   setup

Overview
--------
The Voice Channel Manager Bot is a bot that manages voice channels in Discord servers. It helps to prevent large lists of
voice channels in a servers' channel list by automatically creating channels when none is available, and removing
channels when they are not needed. In addition, the Voice Channel Manager Bot can create "Game Rooms," which base the
channel name on the game that the users in the channel are playing, and allow members of the server to create their own
custom voice channels.

| Feel free to join the Discord if you have any questions or need help setting up the bot!
| `https://discord.gg/Kqv2kQT <https://discord.gg/Kqv2kQT>`_


Auto Voice Groups
~~~~~~~~~~~~~~~~~
Auto Voice Groups allow server managers to keep their voice channel lists clear of clutter. When you set up a Voice
Channel Group, the Voice Channel Manager Bot creates the initial channel. When users join the channel a new one is
created, and when they leave it is removed.

.. image:: _static/auto_voice_group.gif
  :width: 800
  :alt: Auto Voice Group

Game Rooms
~~~~~~~~~~
Game Rooms are channels that are tailored to the type of game that a user is playing. The voice channel gets renamed
based on what the majority of players are playing in the channel. Like Auto Voice Groups, new channels are created
when a user joins a Game Room so that there is always a free channel.

.. image:: _static/game_room.gif
  :width: 800
  :alt: Game Room

Temporary Voice Channel
~~~~~~~~~~~~~~~~~~~~~~~
Temporary Voice Channels give users of a server the freedom to create their own custom named channel. To keep things tidy,
the channels are deleted once all users have left the channel.

.. image:: _static/temp_room.gif
  :width: 800
  :alt: Temp Room
