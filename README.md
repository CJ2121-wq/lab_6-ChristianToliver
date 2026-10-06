# Lab 6 - Three.js Lighting

## Activity 1: Ambient Light

### 1. What is ambient light?
Ambient light provides general illumination to the entire scene without coming from one specific direction.

### 2. What happens when ambient light intensity increases?
As the ambient light intensity increases, the entire cube becomes brighter, including the darker faces.

### 3. Which intensity produces the brightest scene?
An intensity of 1.0 produces the brightest scene.

### 4. Does ambient light create highlights or shadows?
No. Ambient light provides even illumination and does not create strong directional highlights or shadows.


## Activity 2: Directional Light

### 1. Which faces of the cube become brighter?
The faces pointing toward the directional light become brighter.

### 2. Which faces become darker?
The faces pointing away from the directional light become darker.

### 3. Why does changing the light position affect visibility?
Changing the light position changes which surfaces receive the most light, so different faces become brighter or darker.

### 4. Which direction produces the strongest lighting effect?
The (1, 0, 0) direction produced the strongest visible lighting effect for my cube.


## Activity 3: Colored Lights

### 1. Which color creates the highest contrast?
Blue created a high amount of contrast against the black background.

### 2. Which color appears brightest?
Yellow appeared the brightest because it was easy to see against the dark background.

### 3. Why do dark areas remain dark even when the light color changes?
Dark areas remain dark because those faces are not receiving as much direct light.

### 4. Which color feels the most realistic?
Yellow felt the most realistic because it looked similar to warm natural or indoor lighting.

### 5. Which color creates the most dramatic effect?
Red created the most dramatic effect because it gave the cube a more intense appearance.


## Activity 4: Animated Light

### 1. Why do the highlights move across the cube?
The highlights move because the directional light changes position over time.

### 2. Why do some faces become brighter over time?
Some faces become brighter as they rotate toward the moving light source.

### 3. Why does the cube appear different as it rotates?
The cube appears different because each face changes its angle relative to the light as the cube rotates.

### 4. How would animated lighting improve a video game scene?
Animated lighting could make a video game scene feel more active and realistic by creating effects such as moving lights, fires, or changing environmental lighting.


## Activity 5: Disco Cube

For the Disco Cube, I used a rotating cube, a moving directional light, changing light colors, and ambient lighting. The combination made the cube continuously change appearance as it rotated.


## Activity 6: Purple Light

### 1. What color code did you use?
I used `0xff00ff` for the purple light.

### 2. Does your purple light appear exactly how you expected?
The purple light appeared close to what I expected, although the brightness changed depending on which face of the cube was facing the light.


## Activity 7: Random Color Light Show

### 1. How did you generate random colors?
I used `Math.random()` to generate random color values and changed the directional light color every second.

### 2. Which colors looked best?
The brighter colors such as purple, blue, red, and yellow looked best because they were easier to see against the black background.

### 3. Did any colors make the cube difficult to see?
Yes. Some darker random colors made the cube more difficult to see against the black background.


## Activity 8: Point Light

### 1. How is a Point Light different from a Directional Light?
A Point Light shines outward from one location, while a Directional Light sends light in one direction across the scene.

### 2. Which light type resembles a light bulb?
A Point Light resembles a light bulb.

### 3. Which light type resembles sunlight?
A Directional Light resembles sunlight.

### 4. What happens when the Point Light is moved closer to the cube?
The cube becomes more strongly illuminated when the Point Light is moved closer.

### 5. What happens when it is moved farther away?
The lighting effect becomes weaker when the Point Light is moved farther away.


## Activity 9: Multiple Point Lights

### 1. Which color dominates the scene?
The white light dominated most of the scene, but the blue light was clearly visible on the opposite side of the cube.

### 2. What happens when lights overlap?
When the lights overlap, their lighting effects combine on the same surfaces.

### 3. Does the object look more realistic with multiple lights?
Yes. Multiple lights made the cube look more detailed because different faces received different amounts and colors of light.


# Reflection Questions

## 1. What is ambient lighting?
Ambient lighting provides general illumination to all objects in a scene without coming from a specific direction.

## 2. What is directional lighting?
Directional lighting sends light in a specific direction and is useful for simulating a distant light source such as the sun.

## 3. What is point lighting?
Point lighting comes from a specific position and spreads outward in different directions, similar to a light bulb.

## 4. Why do we need normals for lighting calculations?
Normals tell the program which direction a surface is facing. This helps determine how much light should affect each surface.

## 5. Why do some faces of an object appear brighter than others?
Some faces appear brighter because they are facing more directly toward the light source, while other faces receive less light.

## 6. How does moving a light source affect a scene?
Moving a light source changes which parts of an object receive the most light, causing highlights and darker areas to move.

## 7. How does changing light color affect realism and mood?
Changing the light color can make a scene feel warmer, colder, calmer, or more dramatic depending on the color being used.

## 8. Why does Three.js make lighting easier than raw WebGL?
Three.js makes lighting easier because it provides built-in light types such as AmbientLight, DirectionalLight, and PointLight instead of requiring all of the lighting calculations to be created manually.

## 9. Which light type did you find most useful?
I found the Point Light most useful because it was easy to position near the cube and it clearly showed how light from a specific location affects an object.

## 10. What was the most interesting thing you learned during this lab?
The most interesting thing I learned was how changing the position, color, and type of a light can completely change the appearance of the same object.
