# in-class-activities
## Devlogs
### W1
The camera becomes a game object that is not tied to the cat anymore. When the cat is moved, the camera does not move with it and stays where it started.
https://randomroll14.itch.io/gdim-31-w1-assignment

### W2
1. r, g, and b are floats because they are number variables with decimals.
2. The _bounce variable is an int because it's a number that does not have a decimal. It's just increasing by 1 every time.
3. It said that it can't implicitly change the variable from a double to a float. This meant that the '0.1' was a double while 'g' was a float, so I had to add the f in front of the 0.1.

### W3

Activity 1 (Answers to three questions):
Table 14:
1. Output is a string, inputs are a float and bool respectively.
2. Output is a void, input is a float.
3. Output is a bool, input is a float.

Activity 2 (Metaphor for components and classes):
Components are like a video game character, classes are the spells they can use, the member variables are the stats of the spell, and the methods are the effects of the spell.

Activity 3 (Devlog question):
It's an exponential multiplier so if it bounces a bunch of times then it will multiply into the stratosphere.

### W4

Activity 1 (Collision Discussion):
Table 14:
1. The cat and soccer ball had rigidbodies because they should be able to hit each other and bounce off walls. The goal should be a trigger because it should check when the ball enters it.
2. The cat rotated really funnily which messed up the camera that was attached to it so all I had to do was lock the x and z rotations.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 