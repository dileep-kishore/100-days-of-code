# #100DaysOfCode Log - Round 1 - Dileep

The log of my #100DaysOfCode challenge. Started on [July 17, Monday, 2017].

## Log

### R1D1 - Thur Jun 21
    Started the `beeminder-sync` app. It's an application that syncs various datasources with beeminder.
    https://github.com/dileep-kishore/beeminder-sync

### R1D2 - Fri Jun 22
    Working on the `Beeminder` class which acts as the interface to the `beeminder` api.

### R1D3 - Sat Jun 23
    Wrote tests for and fixed bugs in the `beeminder` api interface.

### R1D4 - Sun Jun 24
    Package now uses `furl` for url manipulation. Added method to retrieve individual goal information.

### R1D5 - Mon Jun 25
    Package now supports querying and creating datapoints.

### R1D6 - Tue Jun 26
    Completed tests for datapoint creation method. Currently implementing the cli for the `Beeminder` class

#### R1D7 - Wed Jun 27
    Changed configuration file type from `json` to `ini`

#### R1D8 - Thu Jun 28
    Setting up the CLI to manage configuration directory and file

#### R1D9 - Fri Jun 29
    Setting up the CLI to manage application configuration

#### R1D10 - Sat Jun 30
    Added the `BeeSync` class to handle the configuration

#### R1D11 - Sun Jul 01
    Add loading spinners using the `halo` library and sub-commands to update configuration file and talk to the `beeminder` api

#### R1D12 - Mon Jul 02
    Spinners now show success and failure status for various actions
