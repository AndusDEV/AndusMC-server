AndusMC-server

A fork of Tuinity, for a better server performance.

Tuinity
==

Fork of [Paper](https://github.com/PaperMC/Paper) aimed at improving server performance at high playercounts.

## Building

Requirements:
- You need `git` installed, with a configured user name and email. 
   On windows you need to run from git bash.
- You need `maven` installed
- You need `jdk` 8+ installed to compile (and `jre` 8+ to run)
- Anything else that `paper` requires to build

If all you want is a paperclip server jar, just run `./tuinity jar`

Otherwise, to setup the `Tuinity-API` and `Tuinity-Server` repo, just run the following command
in your project root `./tuinity patch` additionally, after you run `./tuinity patch` you can run `./tuinity build` to build the 
respective api and server jars.

`./tuinity patch` should initialize the repo such that you can now start modifying and creating
patches. The folder `Tuinity-API` is the api repo and the `Tuinity-Server` folder
is the server repo and will contain the source files you will modify.

## License
The PATCHES-LICENSE file describes the license for api & server patches,
found in `./patches` and its subdirectories except when noted otherwise.

Everything else is licensed under the MIT license, except when note otherwise.
See https://github.com/starlis/empirecraft and https://github.com/electronicboy/byof
for the license of material used/modified by this project.

### Note

The fork is based off of aikar's EMC framework found [here](https://github.com/starlis/empirecraft)
