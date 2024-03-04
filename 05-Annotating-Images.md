To add annotations to your images, click the subfolder containing the images you want to work with in the Image Gallery. This will open the images in the folder, and you can start annotating. 

# Overview

The following functionalities are available in the Annotation Mode (numbers correspond to those in **Figure 14** and **15**) 
1.	[Add an image](https://github.com/rsimon/immarkus/wiki/02-Uploading-Images)
2.	Zoom in or zoom out of an image
3.	Click image numbers to browse the images in the same subfolder on top / click arrows to display the previous or next image  
4.	Undo/redo 
5.	Move (pan) across the image
6.	[Draw a shape](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#drawing-annotations) (select rectangle, polygon, or ellipse)
7.	Select an annotation
8.	List your annotations
9.	Add or edit [metadata](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata)

![Screenshot (520)](https://github.com/rsimon/immarkus/assets/128056738/430a8823-1169-460b-80d1-819568eade75)

**Figure 14.** Annotation Mode

![Screenshot (485)](https://github.com/rsimon/immarkus/assets/128056738/63fd251f-c3e7-4746-9164-c0432fca8576)


**Figure 15.** Close-up View of Functionalities in the Annotation Mode


# Drawing Annotations

Decide which part of the image you would like to tag and draw a shape.

1. Click the draw button (#6 in **Figure 14** and **15**) and select one of the three options for drawing shapes (rectangle, polygon, or ellipse).

Then click and drag on the part of the image that you want to annotate. Be sure to click the part of the image you want to annotate before you move the pointer over the image to avoid moving the image.

**Tip:** Double-clicking will end the drawing; this is especially useful when drawing a polygon.

2. When you have finished drawing, you will be asked to add a tag. Choose "Add Tag" and you can [create entities and properties](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#creating-entities-and-properties-in-annotation-mode).

# Adding Entities and Properties to Image Selections

While annotating images, you can also create or add entities and properties. 
* For creating entities and properties in the data model mode, see [data model mode](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model). 

First, decide which part of the image you would like to tag and [draw a shape](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#drawing-annotations). Once you have drawn a shape, you will see the Add Tag and Add Note buttons in the panel on the right. Choose **Add Tag**. A popup window appears and follow the steps below. 

1.	Click **Create New Entity Class**. 
* If you have already created your data model, the existing entities will appear as shown in **Figure 16**.


<img width="583" alt="Screenshot 2024-03-04 at 18 42 22" src="https://github.com/rsimon/immarkus/assets/160752064/7631a25d-2913-4ff4-9c33-972056b20d5c">



**Figure 16.** Creating Entities in Annotation Mode

2.	Click **Entity Class** and name the entity class (e.g. "gate_tower”).

    •	You can select the color of each entity on the right panel.

3.	You can define a different **Display Name**. (e.g. "gate tower").
4.	Add an **Entity Class Description** that explains the use of this entity class. This is optional and you can skip it if you want.  

5.	You can choose to add your new entity class as a child class of one of your existing entities. Enter the name of the entity class you want to make the parent of your new entity class. (e.g. "obj_part").
* Once you have defined your new entity class as a child class, the properties of its parent class will be displayed in the entity preview. (see the right side of the panel in **Figure 17**)

6. Add/edit the properties. Click the drop down menu next to **No Properties** (circled in blue in **Figure 17**)

<img width="987" alt="Screenshot 2024-03-04 at 18 45 39" src="https://github.com/rsimon/immarkus/assets/160752064/46bf3d50-b73e-41aa-84d9-73ea81a3c7e9">

**Figure 17.** Creating Entities and Properties



6.	Click **Add Property**. This opens the property editor as shown in **Figure 18**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 18.** Adding Properties

7.	Define the **Property Name**.

8.	Select a data type by clicking the drop-down menu under **Data Type**. Click here for [Property Options](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#property-options).


9.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 19.** Selecting a Data Type


10.	After you have added each property, click **Save Property**. 

11.	When you have finished adding properties, click **Save Entity Class**.

## Using External Authorities in Annotations

Using the External Authority property type allows you to associate an entity class with one or more external authority services. You can add multiple authorities per field, and multiple fields per entity class. 

1. In the property editor, type a name for your property ("place ID" in **Figure 20**) and select the External Authority field type.

![Screenshot (491)](https://github.com/rsimon/immarkus/assets/128056738/8b581e78-bb41-42d5-9664-ebae050103b4)

**Figure 20.** Available Options for External Authorities

2. As you fill in properties for the annotated entity, the external authority popup displays a search field and the authority service result page below it.  

3. Click the ↗ icon on the right side of the search field to open the current authority search in a new browser tab. 

4. To add an id paste the relevant information from the external authority in the corresponding field of the schema.

<img width="723" alt="Screenshot 2024-03-03 at 00 09 36" src="https://github.com/rsimon/immarkus/assets/160752064/517a056d-fef7-42be-813d-7c56c9d0c458">

**Figure 21.** TGAZ Result of "Guangchang County" Using IMMARKUS
	 
# Annotating Multiple Images Simultaneously

You can annotate multiple images side by side. 

1. Click **Add Image** (red square in **Figure 22**) and select the image(s) that you want to annotate together.

2. You can drag and drop windows to move them around and change their layout.

![Screenshot (525)](https://github.com/rsimon/immarkus/assets/128056738/37ef3e05-9873-4be7-b7a2-28a167275e6f)


**Figure 22.** Annotating Multiple Images Simultaneously Using Add Image (Red Square)


