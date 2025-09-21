Libreland-Client is a mod that uses [BepInEx](https://github.com/BepInEx/BepInEx) to intercept the urls Anyland uses and replaced them with user configurable addresses via the config located under ``BepInEx > config > LibreLand-Server-Urls``, this mod is to be used in tandom with a server running [Echoland](https://github.com/Echoland-AL/echoland). 

Under ``BepInEx > config > LibreLand-Server-User.cfg`` you can assign a Username and Password, by default your username will be your machine name and the password will be ``REPLACEME``, to grab a specfic username you just have to change the ``Username`` field and also the ``Password`` field.

# How to install
1) Download the latest [release](https://github.com/Echoland-AL/libreland-client-mods/releases/latest/download/libreland-client-mods.dll)
2) Download and install [BepInEx](https://github.com/BepInEx/BepInEx) by following their instructions and launch the game, once it's opened close it
3) Place the ``libreland-client-mods.dll`` file into the ``BepInEx > plugins`` folder
4) Launch the game, it should generate configs under ``BepInEx > config`` once it has close the game
5) Modify any settings you want like the ``Url Endpoints`` or ``User settings``
6) Launch and have fun
