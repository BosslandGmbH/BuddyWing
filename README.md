# BuddyWing
[BuddyWing](http://buddywing.com/) is the bot for Star Wars: The Old Republic. This repository contains the open-source components that power the bot. More details can be found in the [BuddyWing forum section](https://www.thebuddyforum.com/buddy-wing-forum/).

Refer to the [issue tracker](https://github.com/BosslandGmbH/BuddyWing/issues) for reporting issues with BuddyWing, even outside of the scope of the components that are available within the repository. 

This repository will not contain the full source code. Only specific components in which community contributions actually make sense will be open sourced. This includes profile tags, bot bases, but excludes process interaction, navigation, and otherwise proprietary code.

## How to engage and contribute
The best way to get started is by simply trying things out with the bot, and [reporting things](https://github.com/BosslandGmbH/BuddyWing/issues) that either don't work, or you would like to see function differently. We strongly encourage users to discuss issues, and optionally propose solutions to said problems.

Should an issue affect one of the open-source parts of the BuddyWing code base, feel free to fork the code, make changes, test them, and submit a [pull request](https://github.com/BosslandGmbH/BuddyWing/pulls).

When submitting an issue or a pull request, please take the following into consideration:

* If submitting a pull request, nsure your pull request is accompanied by an issue on the [issue tracker](https://github.com/BosslandGmbH/BuddyWing/issues) and describe how your PR addresses this issue. Note that you do not necessarily have to be assigned to the issue to submit pull requests, every submission is welcome.
* Make sure your pull request builds. To help with this, we provide _AppVeyor_ build integration which automatically builds all pull requests. PRs that don't build can unfortunately not be merged.
* Make sure your code follows the [Microsoft coding conventions and naming guidelines](https://msdn.microsoft.com/en-us/library/ff926074.aspx). While we're not _that_ strictly enforcing a specific coding paradigm, we do prefer the code to be somewhat uniform.

## Builds
Pull requests and branches in the main repository are built whenever a change is detected. On top of that, a daily build of BuddyWing runs every night at 00:00 CET.

## License
Code license is currently pending.

## Related projects
* [BuddyWing.DefaultCombat](https://github.com/BosslandGmbH/BuddyWing.DefaultCombat) - The default combat routine shipped with BuddyWing
