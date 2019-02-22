# ITSPCameraUE4
In this project, I am trying to recreate the ITSP camera in Unreal engine 4

The ITSPCamera is an autonomous actor which has a camera component. 
The ITSPCamera actor follows the player pawn arround the level when activated. 
The ITSPCamera actor has a 'IsActivated' flag, which when set to true, result in activating its camera 
component and setting the players view target to itself.
The camera also checks if there are any POI(point of interest) actors overlapping with the player pawn and if there are any,
the camera will smoothly(hopefully) move between the player pawn and POI according to the player's position.
