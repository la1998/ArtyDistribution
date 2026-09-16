# ArtyDistribution


[![Join the Discord](https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/HuvgnGMZ5K)

## Install

Add this custom repository in Dalamud:

```text
https://raw.githubusercontent.com/la1998/ArtyDistribution/main/repo.json
```

You can add it under:

```text
/xlsettings > Experimental > Custom Plugin Repositories
```

After adding the repository, open `/xlplugins`, search for the plugin name, and install it from the plugin list.

## Plugins

### RollTracker

RollTracker is a private Dalamud plugin for running Truth or Dare style `/random` rounds in Final Fantasy XIV.

It watches chat for configured commands, tracks each player's first valid roll, shows the current round in an ImGui window, and can send the final result back to chat when the round ends.

#### Main Features

- Starts Truth or Dare roll rounds with `!tod`.
- Supports a second-pair round mode with `!tod2`.
- Sends random Truth and Dare prompts with `!truth` and `!dare`.
- Provides editable command help with `!help`.
- Provides a configurable Shells/Discord info command with `!wifi`.
- Supports exact and range-based special roll rules.
- Can automatically turn modules off when leaving housing.
- Can automatically turn modules on again when entering saved housing interiors.
- Can apply Moodles, Honorific titles, or custom macros when selected RollTracker modules are active.

#### Commands

```text
/rt
/rt help
/rt history
/rt on
/rt off
/rt status
/rt reset
/rt end
```

`/rolltracker` also works as an alternative to `/rt`.

## Community

For support, feedback, update notes, and test feedback, join the Discord:

```text
https://discord.gg/HuvgnGMZ5K
```

## Notes


This repository is only the Dalamud distribution repository. It contains the plugin index, packaged plugin builds, and public install information.
