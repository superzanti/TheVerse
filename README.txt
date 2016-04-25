BASIC:

Run minecraft by double clicking x_Start where x is your operating system.

When you first run minecraft you will be asked to log in.

Once logged in look at the bottom right, make sure the profile is set to 'TheVerse'

Click play. Enjoy!

ADVANCED (PLEASE READ EVEN IF YOU'RE NOT DOING IT):

If you want to toy with a few of the advanced settings click 'Edit Profile' 

In the JVM arguments you want to change -XmX4G to however much ram you're willing to give minecraft. I'm giving it 4 gigabytes. For 6 gigabytes you'd type -Xmx6G.

Now set Xms to half of that value. Then set Xmn to a fourth of the Xmx value.

Finally the last entry says -XX:ParallelGCThreads=4

Change this number to how many threads your processor has. For 16 (my computer) type:

-XX:ParallelGCThreads=16

Now you can follow the basic instructions and connect to the server. To make minecraft run optimally you should configure optifine. To do that, after you connect click "esc" then "Options..." then "Video Settings..."

Here are some settings that will make it look good on almost any computer:
Graphics: Fancy
Smooth Lighting: Minimum
Smooth Lighting Level: 100%
GUI Scale: Auto
Brightness: Moody
Fog: Fast
3d Anaglyph: OFF
Render Distance: 12 Normal+
Max Framerate: VSync (all the way to the left)
View Bobbing: ON
Advanced OpenGL: Fancy
Clouds: ON
Fog Start: 0.8

In "Details...":
Clouds: Default
Trees: Default
Water: Default
Sky: ON
Sun & Moon: ON
Depth Fog: ON
Translucent Blocks: Fast
Cloud Height: OFF
Grass: Default
Rain & Snow: Fast
Stars: ON
Show Capes ON
Held Item Tooltips: ON
Dropped Items: Default

click done.
In "Animations...":
click "All ON"
change Particles to 'Decreased'

click done.
In "Quality...":
MipMap Levels: 3 (any higher doesn't do anything with our texturepack)
Anisotropic Filtering: OFF
Clear Water: OFF
Better Grass: OFF
Custom Fonts: ON
Swamp Colors: ON
Connected Textures: Fancy
Mipmap Type: NEarest
Custom Sky: OFF
Random Mobs: ON
Better Snow: OFF
Custom Colors: ON
Smooth Biomes: ON
Natural Textures: OFF

click done.
In "Performance...":
Smooth FPS: ON
Load Far: OFF
Chunk Updates: 1
Fast Math: ON
Fast Render: ON
Smooth World: ON
Preloaded Chunks: OFF
Dynamic Updates: ON
Lazy Chunk Loading: ON

click done.
In "Other..."
Lagometer: OFF
Weather: ON
Fullscreen: OFF
Autosave: 3min
Debug Profiler: OFF
Time: Default
Fullscreen Mode: Default

Click done, done, done, and back to game!
Note, the game runs faster if you click f11 and make it fullscreen, but don't change that option in optifine otherwise the game may have trouble starting.