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

#### R1D25 - Thu Jul 19
    Create `tox` and `travis-ci` configuration to set up CI/CD

#### R1D26 - Mon Jul 23
    Add `travis-ci`, `pyup` and `readthedocs` setup to the project

#### R1D27 - Tue Jul 24
    Fixed tests and changed the configuration file used for the tests

#### R1D28 - Wed Jul 25
    Add flags to disable cli spinners for tests. Fix travis and readthedocs configurations

#### R1D29 - Thu Jul 26 21:36:50 EDT 2018
    CLI now supports creation and retieval of datapoints from beeminder goals. Progress is displayed using `Halo` spinners, every event and api call is logged

#### R1D30 - Fri Jul 27
    Created a gif recording of the working app

#### R1D31 - Sun Jul 29
    Updated the gif recording for the README

#### R1D32 - Tue Jul 31
    Debating whether a database backend is necessary

#### R1D33 - Thu Aug 02
    Update badges and start adding functionality for multiple output format (table, json)

#### R1D34 - Fri Aug 03
    Finally recorded a good `gif` of the application in action. Also I have a much better idea of how I want to design the interface (custom user functions/scripts for the app)

#### R1D35 - Sat Aug 04
    Make output prettier and create sane defaults for subcommands

#### R1D36 - Sun Aug 05
    Isolate test configuration to tmpdir. Started working on the query and output options for the CLI

#### R1D37 - Mon Aug 06
    Fix format of api responses. Working on --query option to filter output

#### R1D38 - Wed Aug 08
    Started working on a stochastic simulation algorithm package for Python

#### R1D39 - Thu Aug 09
    Fixed broken tests. Implemented CD with pypi and travis.

#### R1D40 - Fri Aug 10
    Completed 'query' option to query response of api. Have a look at https://stedolan.github.io/jq/

#### R1D41 - Sat Aug 11
    Fix documentation and start working on `--output` option

#### R1D42 - Mon Aug 13
    Change pytest default traceback and add tests for the `query` function

#### R1D43 - Tue Aug 14
    Implement 'output' option to format the api response as either prettified 'json' or 'table'

#### R1D44 - Wed Aug 15
    Didn't have time to do much. Still working on converting the json response to a prettified 'table' format.

#### R1D45 - Thu Aug 16
    Didn't get much done. Just updated the `query` option to return a dictionary instead of a list.

### R1D46 - Mon Aug 20
    Forked and customized `vim-anywhere` to work with termite and neovim. Still trying to get it to work with tdrop!

### R1D47 - Tue Aug 21
    Learning `Cython` to speed up a Python-numpy implementation of the Gillespie algorithm
