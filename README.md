SomeStorageMod [![Licence](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
===============

**Currently not stable and under heavy development!**  
Considering AE2 does not plan to update anytime soon for 1.9 (or 1.8.9) we have decided to give out take on it. Things are a little different however, so this is NOT a "clone". Even some of the core concepts are different.

###Development
You can see our current roadmap [here](https://trello.com/)

## Clone
The following steps will ensure your project is cloned properly.  
1. `git@github.com:AgileMods/SomeStorageMod.git`  
2. `cd SomeStorageMod`

## Setup
__Note:__ If you do not have [Gradle] installed then use ./gradlew for Unix systems or Git Bash and gradlew.bat for Windows systems in place of any 'gradle' command.

__For [Eclipse]__  
  1. Run `gradle setupDecompWorkspace eclipse --refresh-dependencies`  
  2. Now open up Eclipse and point the project directory to the `eclipse` folder

__For [IntelliJ]__  
  1. Run `gradle setupDecompWorkspace idea --refresh-dependencies`  
  3. Click File > Import Module and select the **MateriaMuto.iml** file.

## Building
__Note:__ If you do not have [Gradle] installed then use ./gradlew for Unix systems or Git Bash and gradlew.bat for Windows systems in place of any 'gradle' command.

In order to build MateriaMuto you simply need to run the `gradle` command. You can find the compiled JAR file in `./build/libs` labeled similarly to 'MateriaMuto-x.x.x.jar'.

## Contributing
Are you a talented programmer looking to contribute some code? We'd love the help!
* Open a pull request with your changes, following our [guidelines](CONTRIBUTING.md).
* Please follow the above guidelines for your pull request(s) to be accepted.
