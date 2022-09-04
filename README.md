# TTGamesPatcher

For the longest time now we've had to rely on pirated copies of EXEs for the LEGO games which do not run extracted, which has been unreliable at best. A former user (Masquerade) was working on cracking the DAT-DRM and had figured it out but left before patching all games. However, they left their method and it is so simple that I managed to whip this patcher up in about 30 minutes. The patcher takes the game executable and, well... patches it.

How to use:
   Either drag the executable onto `TTGamesPatcher.exe` or type the executable as a parameter in the command line.

The patcher will patch the game and write itself back into the original executable, a copy of the old executable will be saved as `[game]_old.exe`. The patcher will not touch any Steamworks or GOG Galaxy integration.
