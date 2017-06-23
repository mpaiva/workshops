##### Ironhack UX Bootcamp

# Sketch App Workshop

---

## Before you begin
1. **[Download Sketch](https://www.sketchapp.com/static/download/sketch.zip)** - Students should have the Student License ready
2. **[Install Google Web-Fonts](https://github.com/qrpike/Web-Font-Load)** - Follow Github instructions
3. **[Install San Francisco](https://drive.google.com/open?id=0B1I5ivkqdP2jUUJENm1nRGVoVXM)** as it will be needed for the iOS 10 toolkit

---

## Getting started
1. Open the [Ironhack - Sketch Workshop.sketch](Ironhack - Sketch Workshop.sketch) file.

2. The sketch file contains **pages** and **layers** properly named to assist you guiding this class.

3. As the instructor, it is highly encouraged that you follow this guidelines prior to the workshop, to ensure all the steps are clear and easy to follow.

4. Please ensure that all students have the Sketch App installed and ready to begin.

5. Last, but not least - This workshop was created based on the [Official Documentation](https://www.sketchapp.com/learn/documentation/01-introduction/). Please review and follow this documentation to ensure consistency in the order and nomenclature.


## Instructor's Guide
--- 
##### Page: `01 - Introduction` | Artboard: `cover`
---

Open the file on the screen 10-5 min before the session begins, to allow the students to get ready and research on their own.

- Select page: `01 - Introduction`
- Select artboard `cover` and hit `Cmd+2`

--- 
##### Page: `01 - Introduction` | Artboard: `intro`
---

- While everyone gets ready, probe how many students have heard or used Sketch.  

---

## 1. Introduction

--- 
##### Page: `01 - Introduction` | Artboard: `intro`
---

### What is Sketch?

- Vector Drawing Application intended for screen design
- Has a heavy biased towards user interface design
- Outputs pixel-based graphics, but it is not a pixel-based tool
- A vector-based tool with an infinite size canvas
- Create artboards for different screens;
- Pages for different workflows;
- Multiple fills for a single layer;
- Allow us to design different screens and states for a single application;
- Making it so easy to have every aspect of an application, conveniently in front of us, in a single document;
- Design screens indepentently from resolution;
- Export a single design for multiple devices and platforms;
- Vector-drawing application with Infinitely Scalable, Infinitely Precise;
- Strong API that allows community of designers and developer to create and share plugins that make will make you and your team very efficient and save you hundreds of hours;

--- 
##### Page: `01 - Introduction` | Artboard: `raster-vector`
---

### Raster vs. Vector
Zoom in close to each shape to compare the edges.

- raster graphics are made up of pixels
- vector graphics are made up of math
- squares are fine, circles and angled shapes suffer
- raster graphics has its use in photography
- bottom line is that if you will be editing, scaling, moving objects around, it's better to work with vector objects.

--- 
##### Page: `01 - Introduction` | Artboard: `interface`
---

### Interface Tour

- Sketch interface was designed to be streamlined and minimal.
- No floating panels;
- each document gets its own window
- all the tools are contained in each respective window
- **Toolbar** across the top
  - Secondary (right) click to customize
- **Layers List** holds all objects
  - At the bottom we have a **search filter - more later**
- **Inspector** is the most important part of the UI
	- It contains all the tools and properties that we need
	- If I select a vector, text or bitmap the inspector shows me the tool based on the selected object
- At last, we have a primary design surface, **The Canvas**

---

### The Anatomy of a Sketch Document  

**The Canvas** - or Pages - is completely unconstrained, there's a tool to assist with creating boundaries for your design area, **but before...** Let's understand on the canvas for a moment:

- Let's hit `Ctrl+R` to show the **Rulers**
- The primary unit of measurement in Sketch is the `pixel`
- Starting at `0,0` negative pixels up and to the left

**How large is the canvas in Sketch?** > Answer: **Infinite**

- So as you design you dont have to worry about running out of space
- But you do need to worry about the size of the screen you are design for, which is why we have **Artboards**
- On the top left corner, you should see the `Insert` button;
- Select the **Artboard** tool or hit `letter A`
- On the right hand side, you'll find a list of popular screen sizes
- Let's select an `iPhone 7` artboard
- It's not uncommon to design all your screens in a single canvas with multiple artboards
- But sometime, you just want separate your screens by workflows or user stories
- `Pages` allow us to organize our screens design accordingly
- I can add as many pages I want
- I can drag or I can drop artboards from one page to another

---

### Save and Autosave 

- Autosave is a controversial feature
  - If I change something and close a document, Sketch doesn't ask me if I want to save the document, it simply saves it for me;
  - If I make a mistake, it autosave my mistakes
  - But the cool thing is that it saves my mistakes in different versions;
  - And we can access those via the `File` menu > `Revert to` then `Browser all versions...`
  - It brings up a miniture version of the Time Machine
  - You can browse your versions and even copy objects from it.
  - Sketch autosaves feature works per document.
- The **best practice** that I recommend is that you create your own versions, using `Save as...`
  - Go to `File` menu then hold down the `Option` key to access the `Save as..` option.

---

## 2. Layer Basics

--- 
##### Page: `02 - Layers` | Artboard: `layer-types`
---

### Types of Layers
- Text, Image and Shape layers
- Group of objetcs (components) they a glued together
- Group Section for organizational purposes (can be selected)
- Check `Click-through when selecting`

---

### Interacting with Objects

- `Bounding box` around any object
- bounding boxes have `handles` for scaling purposes
- by holding `shift` key you constrain the movement of the mouse
- by holding `command` key turns handles into `rotating` tool
- by holding `command + shift` constraints the angles by 15 degrees
- by holding `option` key scales `from center`
- by holding `option + selecting + dragging` **duplicates**

speaking of selecting...

- `select + shift` adds to selection
- alignment guides support manual placement
- `drag + shift` selects any object touched by the lasso
- `drag + option` selects only objects entirely inside the lasso area
- distributing > vertically / horizontally
- aligning > hor / ver / ctr / right / left
- `select + option` allows picking layer behind
- `select + shift` also deselect an object

---

### Easy Precision and Math 

- select 3 objects
- `width` and `height` 1px at a time
- Keyboard `nudging shortcuts`
 - `Shift + arrow` nudges by 10px
 - it nudges the right and bottom edges only
- Math operations inside the inspector fields
- selecting and dragging the `inspector labels`   

---

### Guides and Grids
- `Ctrl + G` to show grid
- Grid Settings
- Smart guides
  - select and object
  - hold `option`
  - mouse over other object to see distance
- Ruler guides
- Remove guides

---

### Hiding, Locking, and Grouping Layers

- Selecting overlaping shapes `select + option`
- hiding shapes`Shift + Cmd + H`
- locking shapes `Shift + Cmd + L`
- grouping shapes `Cmd + G`
- ungrouping shapes `Shift + Cmd + G`

---

## 3. Shapes

--- 
##### Page: `03 - Shapes` | Artboard: `adding-shapes`
---

### Adding Shapes
- **R - Rectangle** `shift` to constrain
- **O - Oval** `alt option` to build from center
- **U - Rounded Rectangle** - inspector `radius` property
- **Star and Polygon** (From the + Button)
- **Radius and Points** - 
- **L - Line** - To add a line
- **Arrow** (From the + Button) 

--- 
##### Page: `03 - Shapes` | Artboard: `editing-shapes`
---

### Editing Shapes
Draw a rectangle shape and hit `Return` to get into editing mode

- `Straight` points - drag the selected point around
- `Mirrored` - symetric control handles to create **smooth** curves
- `Disconnected` - independent straight points
- `Asymetric` - independent curved points
- `Double click` to toggle between straight and mirrored points
- **Note - if you use straight points**, you'll get the bonus of the `Corners` slider
- Just below, you can select if you want the points to land on a `full pixel edge`
- Small `select points` button
- `Add a control point` by clicking on the path of a line

--- 
##### Page: `03 - Shapes` | Artboard: `drawing-shapes`
---

### Drawing Vector Shapes 

- V - `Vector` allows us to create custom paths and shapes
- `Click` to add straight lines
- `Click, Hold and Drag` to add mirrored points
- `Command` key will allow us to play with `Asymetric` control points
- `Close Path` by simply clicking on the origin point
- P - `Pencil` tool a a free-hand line drawer

--- 
##### Page: `03 - Shapes` | Artboard: `boolean-operations`
---

### Boolean Operations 

#### Finish the Footbal 
- `Union` - Football laces
- `Intersect` - Football

#### Moon
- `Subtract` - Moon

#### DVD on TV Screen
- `Difference` - DVD/TV - Deletes what's overlaping. Union doesn't work because of t=other boolean instructions in complex groups.

#### Build a Rocket

- PART A - `Intersect` Rocket Body
- PART A - `Flatten` Rocket Body
- PART B - `Subtract` Tail
- PART B - `Flatten` Tail
- PART A+B - `Union` Rocket + Tail
- PART C - `Subtract` Tip - and voilá!

--- 
##### Page: `03 - Shapes` | Artboard: `masking`
---

### Masking  

- **Outline Mask**
  - Oval shape on the bottom
  - Select two layers
  - Mask with selected shape
  - Creates a group containing bitmap and shape
  - shape is renamed `mask`
  - Draw rectangle `inside` the group
  - Select `ignore the underlying mask`
  - Rectangle shows inside the masked group

- **Alpha Mask**
  - The `gradient opacity` dictactes the mask
  - We will talk about `Gradients` in the next session
  - Copy masked group
  - We can use a gradient to be `fade out`
  - Select the `mask` shape
  - Then go to `Layer > Mask Mode > Alpha Mask`
  - Select `Fill`, then `Gradient`

--- 
##### Page: `03 - Shapes` | Artboard: `adding-shapes`
---

### Resizing vs Scaling
- `Borders` and `Shadows` need special attention when designing shapes
- Sketch treats `borders and shadows` differently if an layer is `resized` or `scaled`
  - resize circle to `250px`
  - scale circle to `250px`
- Sometime, resizing and keeping the border-witdh intact makes sense - i.e. `button`
- If you are designing `line icons`, I'd recommend using `boolean` shapes
- Often times, we use UI kits that need to be resized for whatever reason
- See iPhone 5 keyboard


--- 
##### Page: `03 - Shapes` | Artboard: `grid-tool`
---

### Make Grid 
- The `Make Grid` tool under the `Arrange` menu is very helpful for a number of repetitive situations.
- Follow settings on artboard.

---

## 4. Styling

--- 
##### Page: `04 - Styling` | Artboard: `fills-borders`
---

### Fills
 
- Select Large Rectangle and change `Fill` color
- For Color picker hit `Control + C`
- `saturation` is vertical, `brightness` is horizontal
- top slider is `hue`
- on the bottom you have the `alpha` slider to control transparency
- Click on `HSB` or `RGB` to toggle color modes
- Global Color palette - Add your Corporate colors here. Other commonly used framework colors like Google's Material Design and Twitter's Bootstrap.
- Document Palette - create palettes specific to the document
- click the `+` sign to add a color to your palettes

---

- OS X Dock Commands
  - Hide Dock `option + command + D`
  - Slide Separator to resize Dock
- `Linear Gradient`
- `Radial Gradient`
- `Angular Gradient`
- `Image Fill` - patter, texture, image
- `Noise Fill` - footbal green grass

---

- Sketch has `Multiple Fills`
- Click the `+ sign` to add a fill
- Drag up and down to `arrange fills`
- Turn `on/off fills`
- To delete fill, simply drag the fill off the inspector panel

---

### Blending Modes and Opacity 

- Blend modes don't export well as SVG and PDF, so becareful on how you choose to use and export your assets.
- Use blending modes only to give a bitmap some effect

---

### Borders

- Sketch can apply borders on masks
- Gradient on borders
- Position (center, inside, outside)
- `cog` icon gives you access to end-point and gap options

--- 
##### Page: `04 - Styling` | Artboard: `shadows`
---

### The Magic of Shadows

- Multiple shadows
- Inner Shadow
- Gausian Blur

---

### Borrowing Style
- `Option + Command + C` to copy style
- `Option + Command + V` to paste style

---
##### Page: `04 - Styling` | Artboard: `shared-styles`
---

### Shared Styles
- DRY - Don't Repeat Yourself! Create Shared Styles.

---

### Text Styles

- Text Styles exist on a per-document basis. 
- You cannot share them between documents but they are available among all Pages and Artboards in your document.
- To create a Text Style, select a text layer, and choose `Layer` › `Create Shared Style` from the menu. 

### Basics of Text Editing
- Typeface vs Font-family
- `shift + enter` for line break

### Area Text and Styling
- No Shared Character Styles

### Text on a Path and Outlines

- To create this effect, you will need a text layer, and a shape layer whose path you want the text to sit on. This layer must appear underneath the text layer in the Layer List.

- With the text layer selected, choose Type › Text on Path from the menu, then move your layer towards the vector shape. It should ‘snap’ as you drag it into place.

- To stop a text layer snapping to a path, simply re-order its position in the Layer List, or choose Type › Text on Path again to unselect the setting.

---

## 5. Exporting
To share your designs, either choose `File › Export…` from the menu, or click the `Export` item in the toolbar. 

### Exporting Artboards 
To mark any layer, group, or Artboard as an exportable layer in Sketch, make sure it is selected, and click the “Make Exportable” button at the bottom of the Inspector.

When a layer has been marked as ‘exportable’, a new view will appear in the place of the button. It‘s here where you can adjust and define the settings for export. Anything you select will be applied when the layer is exported.

Clicking on the add button in the “Export” title will add another scale to your export. The default values will be automatically determined by the previous settings, but this means Sketch will export a different version of the image, as defined.

#### Size
The default size is `1x`, which will export your layer at the actual size it was created. If you’re designing for mobile, you may want to export something at double the size you created it, in this case `2x`. There’s no limit to how much you can multiply by, and you can even scale down in the case of `0.5x`. If designing for Android devices specifically, then you can export to a custom size.

Aside from just multiplying the scale, you can also export to a particular width, or height. For example, to export a layer from its original size to **128 pixels wide**, simply type `128w`. `128h`  would be used to export to **128 px tall**.

#### Suffix

The suffix text box works in conjunction with the size control. If you have more than one export scale defined, then at least one suffix is required to append onto the end of the exported file’s name to tell them apart.

Typically, objects exported at a `2x` scale will have the suffix of “**@2x**” as this meets the naming conventions required by Apple when designing for their operating systems.

#### Format

The format button allows you to choose which file format you would like to export to via the pop-up menu.

---

### Exporting Layers and Slices 

Exporting a layer by itself means that no other elements on the Canvas will be exported with it, and its size will be defined by the layer’s bounds. If there’s a layer on top or a background below it, neither of those will be included in the export.

Marking layers as exportable has its uses, but it doesn’t cover all cases. This is where slices can come into effect.

It’s possible to create a slice straight from an exportable layer. Simply click the Slice button in the “Export” title and a new slice layer will be created around the object containing the defined settings.

---


# End of Sketch Overview
Next Class we'll cover the Best practices, plugins and Team Workflow.
