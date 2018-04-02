# THE GRAND PIANO

FEATURES AND TECHNOLOGIES

My playground is meant to educate the user about the parts of a piano that are responsible for creating its sound. I tried to create a fun and interactive scene targeting everybody regardless of their skill level or experience with playing the piano. In this short text I will tell you about the creation of the playground and how exactly it works.

After deciding on the idea and creating a few rough sketches of what I wanted the final product to look like, I began work on the most time consuming part of the project: the 3D model. Since I've already had some experience with Autodesk's Maya, I used their software for the basic modelling process. My model is based on a concert piano by Steinway & Sons, but the mechanism itself is similar on other grand pianos.
After finishing the basic model I began to create and apply textures to the different parts. To finish it of, I built a lighting setup around the model. These last two steps played a much bigger role in the quality of the scene than I had anticipated, so I spent almost a whole day experimenting with different values and setups. 
After that I started to work on what has to be one of the most fun parts of the project: the animation. It, too, was created using Autodesk Maya and the built-in animation toolkit. The slo-mo animation uses the same project file, just played back at a different frame rate. 
Now that the model and animation were finished, I exported the scene as a Collada-file, which was then converted into a .scn-file for use with SceneKit. After I had built the SceneView and written all the necessary functions to detect touches and playback sounds, it was time for the last important element: recording the actual sounds.
Using GarageBand and an external MIDI keyboard, I recorded a set of sounds for the key with slo-mo disabled and another one with slo-mo enabled. After trying many different styles I decided to use a longer, deeper sample for the latter.
After writing the markup comments and documentation, the project was finished.
