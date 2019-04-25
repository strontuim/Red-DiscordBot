.. v3.1.0 Changelog

================
v3.1.0 Changelog
================

-----
Audio
-----

 * Add Spotify support (`#2328`_)
 * Play local folders via text command (`#2457`_)
 * Change pause to a toggle (`#2461`_)
 * Remove aliases (`#2462`_)
 * Add track length restriction (`#2465`_)
 * Seek command can now seek to position (`#2470`_)
 * Add option for dc at queue end (`#2472`_)
 * Emptydisconnect and status refactor (`#2473`_)
 * Queue clean and queue clear addition (`#2476`_)
 * Fix for audioset status (`#2481`_)
 * Playlist download addition (`#2482`_)
 * Add songs when search-queuing (`#2513`_)
 * Match v2 behavior for channel change (`#2521`_)
 * Bot will no longer complain about permissions when trying to connect to user-limited channel, if it has "Move Members" permission (`#2525`_)
 * Fix issue on audiostats command when more than 20 servers to display (`#2533`_)
 * Fix for prev command display (`#2556`_)
 * Fix for localtrack playing (`#2557`_)
 * Fix for playlist queue when not playing (`#2586`_)
 * Track search and append fixes (`#2591`_)
 * DJ role should ask for a role (`#2606`_)

----
Core
----

 * Delete cooldown messages when expired (`#2469`_)
 * ``redbot --version`` will now give you current version of Red (`#2567`_)

------
Config
------

 * Updated Mongo driver to support large guilds (`#2536`_)
 * Introduced ``init_custom`` method on Config objects (`#2545`_)
 * We now record custom group primary key lengths in the core config object (`#2550`_)
 * Migrated internal UUIDs to maintain cross platform consistency (`#2604`_)

----------
discord.py
----------

----------
Downloader
----------

 * ``[p]cog install`` will now tell user that cog has to be loaded (`#2523`_)
 * Fixed bug, that caused Downloader to include submodules on cog list (`#2590`_)
 * ``[p]cog uninstall`` allows to uninstall multiple cogs now (`#2592`_)
 * ``[p]cog uninstall`` will now remove cog from installed cogs even if it can't find the cog in install path anymore (`#2595`_)

---
Mod
---

 * Admins can now decide how many times message has to be repeated before ``deleterepeats`` removes it (`#2437`_)

-------------
Setup Scripts
-------------

 * ``redbot-setup`` now uses the click CLI library (`#2579`_)
 * ``redbot-setup convert`` now used to convert between libraries (`#2579`_)
 * Backup support for Mongo is currently broken (`#2579`_)

-----
Tests
-----

 * Test for ``trivia`` cog uses explicitly utf-8 encoding for checking yaml files (`#2565`_)

------
Trivia
------

 * Fix of dead image link for Sao Tome and Principe in ``worldflags`` trivia (`#2540`_)

-----------------
Utility Functions
-----------------

 * ``Tunnel`` - Spelling correction of method name - changed ``files_from_attatch`` to ``files_from_attach`` (old name is left for backwards compatibility) (`#2496`_)
 * ``Tunnel`` - fixed behavior of ``react_close()``, now when tunnel closes message will be sent to other end (`#2507`_)

.. _#2328: https://github.com/Cog-Creators/Red-DiscordBot/pull/2328
.. _#2437: https://github.com/Cog-Creators/Red-DiscordBot/pull/2437
.. _#2457: https://github.com/Cog-Creators/Red-DiscordBot/pull/2457
.. _#2461: https://github.com/Cog-Creators/Red-DiscordBot/pull/2461
.. _#2462: https://github.com/Cog-Creators/Red-DiscordBot/pull/2462
.. _#2465: https://github.com/Cog-Creators/Red-DiscordBot/pull/2465
.. _#2469: https://github.com/Cog-Creators/Red-DiscordBot/pull/2469
.. _#2470: https://github.com/Cog-Creators/Red-DiscordBot/pull/2470
.. _#2472: https://github.com/Cog-Creators/Red-DiscordBot/pull/2472
.. _#2473: https://github.com/Cog-Creators/Red-DiscordBot/pull/2473
.. _#2476: https://github.com/Cog-Creators/Red-DiscordBot/pull/2476
.. _#2481: https://github.com/Cog-Creators/Red-DiscordBot/pull/2481
.. _#2482: https://github.com/Cog-Creators/Red-DiscordBot/pull/2482
.. _#2496: https://github.com/Cog-Creators/Red-DiscordBot/pull/2496
.. _#2507: https://github.com/Cog-Creators/Red-DiscordBot/pull/2507
.. _#2513: https://github.com/Cog-Creators/Red-DiscordBot/pull/2513
.. _#2521: https://github.com/Cog-Creators/Red-DiscordBot/pull/2521
.. _#2523: https://github.com/Cog-Creators/Red-DiscordBot/pull/2523
.. _#2525: https://github.com/Cog-Creators/Red-DiscordBot/pull/2525
.. _#2533: https://github.com/Cog-Creators/Red-DiscordBot/pull/2533
.. _#2536: https://github.com/Cog-Creators/Red-DiscordBot/pull/2536
.. _#2540: https://github.com/Cog-Creators/Red-DiscordBot/pull/2540
.. _#2545: https://github.com/Cog-Creators/Red-DiscordBot/pull/2545
.. _#2550: https://github.com/Cog-Creators/Red-DiscordBot/pull/2550
.. _#2556: https://github.com/Cog-Creators/Red-DiscordBot/pull/2556
.. _#2557: https://github.com/Cog-Creators/Red-DiscordBot/pull/2557
.. _#2565: https://github.com/Cog-Creators/Red-DiscordBot/pull/2565
.. _#2567: https://github.com/Cog-Creators/Red-DiscordBot/pull/2567
.. _#2579: https://github.com/Cog-Creators/Red-DiscordBot/pull/2579
.. _#2586: https://github.com/Cog-Creators/Red-DiscordBot/pull/2586
.. _#2590: https://github.com/Cog-Creators/Red-DiscordBot/pull/2590
.. _#2591: https://github.com/Cog-Creators/Red-DiscordBot/pull/2591
.. _#2592: https://github.com/Cog-Creators/Red-DiscordBot/pull/2592
.. _#2595: https://github.com/Cog-Creators/Red-DiscordBot/pull/2595
.. _#2604: https://github.com/Cog-Creators/Red-DiscordBot/pull/2604
.. _#2606: https://github.com/Cog-Creators/Red-DiscordBot/pull/2606