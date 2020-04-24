.. toctree::
   :caption: Table of Contents
   :maxdepth: 2
   :hidden:

Temporary Voice Channels
========================
Creating a Temporary Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
To create a Temporary Channel, use the ``/temp voice`` command. This command accepts two arguments: ``channelName``
and ``userLimit``. The channelName argument is what you would like to call your temporary channel, while the userLimit
argument sets the number of allowed users for that temporary voice channel.

| Example:
| ``/temp voice "My Custom Channel" 10``
| The above command will create a Temporary Voice Channel called My Custom Channel with a user limit of 10.

.. image:: _static/temp_voice_command.gif
  :width: 800
  :alt: Temp Voice

Locking and Unlocking a Temporary Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
While you are using a Temporary Voice Channel, you can lock and unlock the channel to prevent unwanted users from
entering the channel. To do this, use the ``/temp lock`` command to lock the channel, and ``/temp unlock`` to unlock
the channel.

.. image:: _static/temp_voice_lock_command.gif
  :width: 800
  :alt: Temp Voice
