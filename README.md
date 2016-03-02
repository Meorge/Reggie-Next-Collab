# Reggie-Next-Collab
Sorry this is such a mess, but here's the old code RoadrunnerWMC found from when we were working on Collaboration for Reggie Next. To run it you'll need to install the Python package Dweepy, plus all of the typical Reggie Next requirements.

TODO:
- Currently to listen for events the program uses the threading module. We should change it to use QThread with signals.
- We should find a different way to send actions than simply acting whenever an action is completed (should be done in a different thread). maybe the other thread could be activated from the main thread upon actions?


~ Meorge
