To add annotations to your images, click the subfolder containing the images you want to work with in the Image Gallery. This will open the images in the folder, and you can start annotating. 

# Overview

The following functionalities are available in the annotation mode (numbers correspond to those in **Figure 10** and **11**) 
1.	[Add an image](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#annotating-multiple-images-simultaneously)
2.	Zoom in or zoom out of an image
3.	Click image numbers to browse the images in the same subfolder on top / click arrows to display the previous or next image  
4.	Undo/redo 
5.	Move individual images
6.	[Draw a shape](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#annotating-multiple-images-simultaneously) (select rectangle, polygon, or ellipse)
7.	Select an annotation
8.	List your annotations
9.	Add or edit [metadata](https://github.com/rsimon/immarkus/wiki/05-Working-with-Metadata)

![Screenshot (484)](https://github.com/rsimon/immarkus/assets/128056738/913bd4fa-8cf8-4447-9ca5-8b0b1e64fb8a)

**Figure 10.** Annotation Mode

![Screenshot (485)](https://github.com/rsimon/immarkus/assets/128056738/63fd251f-c3e7-4746-9164-c0432fca8576)


**Figure 11.** Close-up View of Functionalities in the Annotation Mode


# Drawing Annotations

Decide which part of the image you would like to tag and draw a shape.

1. Click the draw button (#6 in **Figure 3** and **4**) and select one of the three options for drawing shapes (rectangle, polygon, or ellipse).

Then click and drag on the part of the image that you want to annotate. Be sure to click the part of the image you want to annotate before you move the pointer over the image to avoid moving the image.

**Tip:** Double-clicking will end the drawing; this is especially useful when drawing a polygon.

2. When you have finished drawing, you will be asked to add a tag. Choose "Add Tag" and you can [create entities and properties](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#creating-entities-and-properties-in-annotation-mode).

# Creating Entities and Properties in Annotation Mode

To create entities and properties in the annotation mode, follow the steps below.
* You can also create and view entities and properties in the [data model mode](https://github.com/rsimon/immarkus/wiki/03-Designing-a-Data-Model). 

1. In the Image Gallery click a subfolder containing the images with which you want to work. (To locate the Image Gallery, see **Figure 2** in [The Interface](https://github.com/rsimon/immarkus/wiki/02-The-Interface)) This opens the images in the folder.

1. Decide which part of the image you would like to tag and [draw a shape](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#drawing-annotations). 

1. Once you have drawn a shape, you will see the Add Tag and Add Note buttons in the panel on the right. Choose **Add Tag**. A popup window appears (**Figure 3**). 
1.	Click **Create New Entity Class**. 



![Screenshot (487)](https://github.com/rsimon/immarkus/assets/128056738/e9d557b0-6af3-41a8-8a3d-5e7fadadfccc)

**Figure 3.** Creating Entities in Annotation Mode

5.	Click **Entity Class** and name the entity class (e.g. "city_gate”).

    •	You can select the color of each entity on the right panel.

6.	You can define a different **Display Name**. In this case, "city gate.”
7.	Add an **Entity Class Description** that explains the use of this entity class (e.g., a city gate is a passageway through a city wall).  


8.	Add/edit the properties. Click the drop down menu next to **No Properties** (the blue arrow in **Figure 4**)

![Screenshot (488)](https://github.com/rsimon/immarkus/assets/128056738/74052980-2bf6-4b82-884a-3130bdd2a721)

**Figure 4.** Creating Entities and Properties



9.	Click **Add Property**. This opens the property editor as shown in **Figure 5**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 5.** Add Properties

10.	Define the **Property Name**.

11.	Select a data type by clicking the drop-down menu under **Data Type**. Click here for [Property Options](https://github.com/rsimon/immarkus/wiki/03-Designing-a-Data-Model#property-options).


12.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 6.** Selecting a Data Type


13.	After you have added each property, click **Save Property**. 

14.	When you have finished adding properties, click **Save Entity Class**.

# Using External Authorities in Annotations

Using the External Authority property type allows you to associate an entity class with one or more external authority services. You can add multiple authorities per field, and multiple fields per entity class. 

In the property editor, type a name for your property ("place ID" in **Figure 21**) and select the External Authority field type.

![Screenshot (491)](https://github.com/rsimon/immarkus/assets/128056738/8b581e78-bb41-42d5-9664-ebae050103b4)

**Figure 21.** Available Options for External Authorities

As you fill in properties for the annotated entity, the external authority popup displays a search field and the authority service result page below it.  

Click the ↗ icon on the right side of the search field to open the current authority search in a new browser tab. 

To add an id paste the relevant information from the external authority in the corresponding field of the schema.

<img width="723" alt="Screenshot 2024-03-03 at 00 09 36" src="https://github.com/rsimon/immarkus/assets/160752064/517a056d-fef7-42be-813d-7c56c9d0c458">

**Figure 22.** TGAZ Result of "Guangchang County" Using IMMARKUS
	 
# Annotating Multiple Images Simultaneously

You can annotate images side by side by clicking **Add Image** (#1 in **Figures 3** and **4**). You can drag and drop windows to move them around and change their layout.

![Picture11](https://github.com/rsimon/immarkus/assets/128056738/18df8963-93a5-4304-be1b-819c85a2729d)

**Figure 12.** Annotating Multiple Images Simultaneously Using Add Image


