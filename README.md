# Skybox-Sports-Hall-VR_MSc
A virtual world sports hall project as part of the MSc Virtual Reality course.<br><br>

## Short Description
This virtual environment depicts an open roof sports hall which has been set up for basketball use. The space is intended to be explored, with the added interaction and ability to pick up and throw basketballs – in a to-scale environment. The basketballs have bounce functionality and can be picked up using a VR ray for accessibility. The space has plenty of room to host many users, it uses PBR materials for lifelike rendering and has empty walls for users to illustrate upon.
### Features
* Left Hand Ray Interactable (Red) - Pick up Basketballs with grip button
* Right Hand Teleportation (Blue) - Trigger to teleport
* PBR Rendered Sports Hall
* Interactable basketballs with bounce physics

![Overview Image Of World](https://github.com/jbengey/Skybox-Sports-Hall-VR_MSc/blob/main/Images/cover_image.PNG)

![Overview Image Of World](https://github.com/jbengey/Skybox-Sports-Hall-VR_MSc/blob/main/Images/VR_shot.PNG)
<br><br><br>

## Focus Feature – Custom 3D Assets with PBR Mapping
My first additional feature is the importing of custom handmade 3D assets, that have been unwrapped and textured with PBR materials. Examples of this in my project include the basketball hoops and the basketball court floor. Both Assets are necessary for the theme of my virtual world, and by creating these myself I was able to control the dimensions (Making them accurate to real life) and also introduce texturing to make these assets sit flush into the environment. The use of custom 3D assets is necessary to any virtual reality developer, as relying on premade objects will often leave a sense of discontinuity in a project as well as limiting the imagination and overall usability of a scene. Physically Based Rendering uses additional texture maps to replicate the effects of light and to provide perceived depth to flat geometry; the benefit of this is a much more realistic appearance and allows objects to better represent their real world counterparts. The only negative being the increased weighting (file size) due to many additional texture maps being required.
<br><br>
## Focus Feature – Skybox
The second feature I added was a skybox to replace the default gradient sky. The skybox in Unity provides lighting information but can also help to set the scene for a game or area, for example dark skies can be used to infer a scary/moody type of environment. They are a resource friendly device that can overhaul the atmosphere and feel of a space. 
In my case, this was even more important to implement as I had chosen an open-roof style sports hall – so a default blank sky simply ruined any immersion I tried to invoke. I chose a bright summer sky which has a wide range of contrasting colours, as for me; this made the whole scene pop and come to life. To fully take advantage of the atmosphere provided by the skybox, I have implemented large glass windows in which the user will be able to see the clouds and lighting through when in game. This becomes important given that the windows are at a very similar height to the user’s eyes. The use of a bright skybox also helps to allow every aspect of my world to be explored and for the details implemented to be noticed a lot easier.
<br><br>
![Overview Image Of World](https://github.com/jbengey/Skybox-Sports-Hall-VR_MSc/blob/main/Images/Skybox-1.PNG)
<br><br><br>
## Release Information
Current Version 1.0.0 - [Download](https://github.com/jbengey/Skybox-Sports-Hall-VR_MSc/releases/tag/v1.0.0)
<br><br>
[![DOI](https://zenodo.org/badge/302599083.svg)](https://zenodo.org/badge/latestdoi/302599083)
<br>
### Tested with the following:
* Unity 2019.4.10f1
* Acer Mixed Reality Headset
* NVIDIA GTX 1070
* Intel I7-7700HQ
* 16GB Ram
