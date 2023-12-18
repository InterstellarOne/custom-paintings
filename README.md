# Custom Paintings
A guide on how to create custom paintings with KawaMood's Better Paintings datapack
This datapack uses custom player heads in block displays to easily display any texture, which makes custom paintings fairly easy to add, without overriding defaults and with no resource packs.

*Add an image of the paintings with their IDs*

## Prequisites:
- A photo editor like GIMP or Photoshop
- An official copy of Minecraft: Java Edition

## Understanding the templates
This guide includes skin templates for creating custom paintings, and it is important to understand how to use them. 

Each skin, excluding 1x1s, holds four 8x8 tiles pulled from the painting. 
I will be using "painting tile" throughout this guide to refer to 8x8 squares copied from the painting, and I will refer to 8x8 squares of the skins as a "tile"

<img src="https://github.com/InterstellarOne/custom-paintings/blob/main/2x2%20template%20readme.png?raw=true" width="400"/> 
Each of these tiles is marked by a yellow dotted outline, and the red square on each represents which painting tile you should copy on top of it. For example, the left-most tile has the red square in the top left corner, so you would copy the top left 8x8 painting tile, and paste it on the tile in the skin. 

Be aware, these tiles can be rotated, so the red square indicates the direction that the tile is oriented, with the darker part facing upwards.

The final element that can appear in these templates is the double-sided arrow, which is the symbol for flipping the tile in the direction of the arrows. **↔** is horizontal, **↕** is vertical.
## 1x1
[Template](https://github.com/InterstellarOne/custom-paintings/blob/main/1x1/1x1%20template.png?raw=true)
This painting only includes one template, with a different format to the rest. Copy the top left painting tile to the left square, and the top right painting tile to the right square.s.

1. Create a 16x16 painting. Drawing a frame will keep it in line with the built-in paintings and make it contrast better with the walls, but it isn't nessecary. Open both the painting and the template in an image editor such as GIMP or Photoshop. 
2. Unzip the datapack if you haven't already, and navigate to ~/pk-more-paintings/data/pk_mo_pa/functions/core/place/1x1/.
3. Choose whether you want to replace one of the paintings, or create a new one. If you want to replace one, follow the steps in 4a. If you want to add one, follow the steps in 4b. 
4a. Open the painting's .mcfunction of your choice, denoted by a number.
4b. 
- 1. Duplicate a file, such as 01.mcfunction, and rename it to the lowest available number. With no previous modifications, I would rename it to 05.mcfunction. 
- 2. Open the file, and change the number in line 1 to the number you just named the function. Save the file.
- 3. In the same file directory, open random.mcfunction, change the last number on line 4 to the number you set, (No leading zeros) and duplicate the last line of code below itself, replacing the numbers with the one that you set. Save the file.
5. Copy the top two 8x8 painting tiles onto the indicated spaces on the template, then export as something like "painting top.png"
6. Change your minecraft skin to the file you just exported. 
7. Go to https://minecraft-heads.com/custom-heads/heads-generator, and enter your username, and write anything for the head name. Click "Craft Command", then copy the **Value** field.
8. Paste this into the top **value** field in your .mcfunction, replacing what was already inside of the quotation marks.
9. Repeat steps 5-8 for the bottom two squares. Replace "top" in the steps with "bottom" when nessecary.
10. Save the file. You should be done!
## 1x2
[Templates](https://github.com/InterstellarOne/custom-paintings/tree/main/1x2)
Nothing too special about this one, but make sure to flip the indicated tile horizontally, and pay attention to each tile's orientation.

1. Create a 16x32 painting. Drawing a frame will keep it in line with the built-in paintings and make it contrast better with the walls, but it isn't nessecary. Open both the painting and the template in an image editor such as GIMP or Photoshop. 
2. Unzip the datapack if you haven't already, and navigate to ~/pk-more-paintings/data/pk_mo_pa/functions/core/place/1x2/.
3. Choose whether you want to replace one of the paintings, or create a new one. If you want to replace one, follow the steps in 4a. If you want to add one, follow the steps in 4b. 
4a. Open the painting's .mcfunction of your choice, denoted by a number.
4b. 
- 1. Duplicate a file, such as 01.mcfunction, and rename it to the lowest available number. With no previous modifications, I would rename it to 09.mcfunction. 
- 2. Open the file, and change the number in line 1 to the number you just named the function. Save the file.
- 3. In the same file directory, open random.mcfunction, change the last number on line 4 to the number you set, (No leading zeros) and duplicate the last line of code below itself, replacing the numbers with the one that you set. Save the file.
5. Copy the top four 8x8 painting tiles onto the indicated spaces on the template, then export.
6. Change your minecraft skin to the file you just exported. 
7. Go to https://minecraft-heads.com/custom-heads/heads-generator, and enter your username, and write anything for the head name. Click "Craft Command", then copy the **Value** field.
8. Paste this into the top **value** field in your .mcfunction, replacing what was already inside of the quotation marks.
9. Repeat steps 5-8 for the bottom four squares. Replace "top" in the steps with "bottom" when nessecary.
10. Save the file. You should be done!
## 2x1
[Templates](https://github.com/InterstellarOne/custom-paintings/tree/main/2x2)
Nothing too special about this one, but make sure to flip the indicated tile horizontally, and pay attention to each tile's orientation.

1. Create a 32x16 painting. Drawing a frame will keep it in line with the built-in paintings and make it contrast better with the walls, but it isn't nessecary. Open both the painting and the template in an image editor such as GIMP or Photoshop. 
2. Unzip the datapack if you haven't already, and navigate to ~/pk-more-paintings/data/pk_mo_pa/functions/core/place/2x1/.
3. Choose whether you want to replace one of the paintings, or create a new one. If you want to replace one, follow the steps in 4a. If you want to add one, follow the steps in 4b. 
4a. Open the painting's .mcfunction of your choice, denoted by a number.
4b. 
- 1. Duplicate a file, such as 01.mcfunction, and rename it to the lowest available number. With no previous modifications, I would rename it to 07.mcfunction. 
- 2. Open the file, and change the number in line 1 to the number you just named the function. Save the file.
- 3. In the same file directory, open random.mcfunction, change the last number on line 4 to the number you set, (No leading zeros) and duplicate the last line of code below itself, replacing the numbers with the one that you set. Save the file.
5. Copy the top four 8x8 painting tiles onto the indicated spaces on the template, then export.
6. Change your minecraft skin to the file you just exported. 
7. Go to https://minecraft-heads.com/custom-heads/heads-generator, and enter your username, and write anything for the head name. Click "Craft Command", then copy the **Value** field.
8. Paste this into the top **value** field in your .mcfunction, replacing what was already inside of the quotation marks.
9. Repeat steps 5-8 for the bottom four squares. Replace "top" in the steps with "bottom" when nessecary.
10. Save the file. You should be done!

## 2x2
[Templates](https://github.com/InterstellarOne/custom-paintings/tree/main/2x2)
There's four templates for this one. The first template is for the top layer, the second one is the bottom layer, the third is the outside edges, and the fourth is the middle four. Pay attention and make sure to flip the indicated tile horizontally.

1. Create a 32x32 painting. Drawing a frame will keep it in line with the built-in paintings and make it contrast better with the walls, but it isn't nessecary. Open both the painting and the template in an image editor such as GIMP or Photoshop. 
2. Unzip the datapack if you haven't already, and navigate to ~/pk-more-paintings/data/pk_mo_pa/functions/core/place/2x2/.
3. Choose whether you want to replace one of the paintings, or create a new one. If you want to replace one, follow the steps in 4a. If you want to add one, follow the steps in 4b. 
4a. Open the painting's .mcfunction of your choice, denoted by a number.
4b. 
- 1. Duplicate a file, such as 01.mcfunction, and rename it to the lowest available number. With no previous modifications, I would rename it to 09.mcfunction. 
- 2. Open the file, and change the number in line 1 to the number you just named the function. Save the file.
- 3. In the same file directory, open random.mcfunction, change the last number on line 4 to the number you set, (No leading zeros) and duplicate the last line of code below itself, replacing the numbers with the one that you set. Save the file.
5. Copy the top four 8x8 painting tiles onto the indicated spaces on the template, then export.
6. Change your minecraft skin to the file you just exported. 
7. Go to https://minecraft-heads.com/custom-heads/heads-generator, and enter your username, and write anything for the head name. Click "Craft Command", then copy the **Value** field.
8. Paste this into the first **value** field in your .mcfunction, replacing what was already inside of the quotation marks.
9. Repeat steps 5-8 for the second set of four squares. Replace "top" in the steps with "bottom" when nessecary. Paste the value you obtain into the second **value** field.
10. Repeat steps 5-8 for the two other sets of four squares, pasting the values you obtain into the third and forth steps respectively.
11. Save the file. You should be done!
