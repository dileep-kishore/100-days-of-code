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

#### R1D13 - Tue Jul 03
    Configuration backup and replacement when new configuration is provided

#### R1D14 - Wed Jul 04
    Testing the CLI

#### R1D15 - Thu Jul 05
    Application now sets up new configuration files and directory on first run

#### R1D16 - Fri Jul 06
    Created `setup.py` and confirmed that the functionality implemented so far works as expected.

#### R1D17 - Sat Jul 07
    Having trouble testing `click.prompt` using `pytest`. Testing the base `BeeSync` class instead

#### R1D18 - Sun Jul 08
    Got the basic CLI set up. Now onto creating the database backend and connections to store data from api requests

#### R1D19 - Mon Jul 09
    Add logging to application

#### R1D20 - Tue Jul 10
    Logging configuration continued

#### R1D21 - Wed Jul 11
    Finally logging configuration working. Still have to implement log calls throughout the application

#### R1D22 - Thu Jul 12
    Completed setting up logging for the `Beeminder` class. Thinking about how to structure the cli for the api.

#### R1D23 - Sat Jul 14
    The `beeminder` subcommand works! Can create and retrieve datapoints

#### R1D24 - Wed Jul 18
    Update the CLI and API to ensure that the `Halo` spinners are entirely handled in the API classes
