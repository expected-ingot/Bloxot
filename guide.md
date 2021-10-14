# Bloxot Guide

Hello there! Bloxot is a builder bot for Blockate.

# Setting up Bloxot

You can find Bloxot in the file "bloxot.txt". Copy that file, and paste it into your Roblox executor. Then, you can write code (REMEMBER TO PUT IT AT THE BOTTOM!)

# Placing Blocks

You can place blocks with the Place() function.
The Place() function has 10 arguments: Coords, Reflectance, CanCollide, Color, LightColor, Transparency, Light, MaterialID, ShapeID, SizeID.
For example, this code would place a white full-sized block at 0 0 0, and print "Placed":
```
if Place("0 0 0/0", 0, true, Color3.fromHex("#FFFFFF"), Color3.fromHex("#FFFFFF"), 0, 0, 1, 1, 1) then 
    print("Placed")
end
```
You can also use other materials (MaterialID), here's a list of them:

1 - Plastic

2 - Brick

3 - Cobblestone

4 - Concrete

5 - CorrodedMetal

6 - DiamondPlate

7 - Fabric

8 - Foil

9 - Granite

10 - Grass

11 - Ice

12 - Marble

13 - Metal

14 - Neon

15 - Glass

16 - Pebble

17 - SmoothPlastic

18 - Sand

19 - Slate

20 - Wood

21 - WoodPlanks

22 - ForceField
