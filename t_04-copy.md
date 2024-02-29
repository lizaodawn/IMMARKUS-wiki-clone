To add annotations, in the image gallery, click the subfolder containing the images you want to work with. This will open the images in the folder, and you can start annotating. 

# Overview

The following functionalities are available in annotation mode (see numbers in **figures 3** and **4**) 
1.	[Add image](https://github.com/rsimon/immarkus/wiki/t_04-Annotation-Mode#annotate-multiple-images-on-the-same-screen)
2.	+/- (zoom in/out of the image)
3.	Move through the images in the same subfolder
4.	Undo/redo buttons
5.	Move between annotations
6.	[Draw shape](https://github.com/rsimon/immarkus/wiki/t_04-Annotation-Mode#draw-annotations) (choose among rectangle, polygon, and ellipse)
7.	Selection (select an annotation)
8.	List (list of annotations)
9.	[Metadata](https://github.com/rsimon/immarkus/wiki/t_06-Recording-Metadata#recording-folder-metadata-in-the-image-gallery) (add or edit metadata)

![Screenshot (484)](https://github.com/rsimon/immarkus/assets/128056738/913bd4fa-8cf8-4447-9ca5-8b0b1e64fb8a)

**Figure 3.** Annotation Mode

![Screenshot (485)](https://github.com/rsimon/immarkus/assets/128056738/63fd251f-c3e7-4746-9164-c0432fca8576)


**Figure 4.** Close-up View of Functionalities in Annotation Mode


# Draw Annotations

Decide which part of the image you would like to tag and draw a shape.
Click the draw button (number 6 in **figures 3** and **4**). You can choose one of the three options for drawing shapes (rectangle, polygon, and ellipse), then click and drag on the part of the image that you want to annotate. Be sure to click the part of the image you want to annotate before you move the pointer over the image to avoid moving the image.

**Tip:** Double-click will end the drawing (this is useful for drawing a polygon).
	 

# Creating Entities and Properties in Annotation Mode

After you have finished drawing, you will see the Add Tag and Add Note buttons in the sidebar on the right. Choose **Add Tag** and it will open a popup window like one shown in **figure 5**. 

In IMMARKUS, the data model is based on the concepts of entity classes and properties. In short, we use **entity classes** to annotate specific concepts or things (e.g., a city wall); and we use **properties** to record specific details about entity classes (e.g., the name, dimension, and location).
You can create and view entities and properties in the Annotation mode. First, we will create entities.

1.	Click **Create New Entity Class**. 

![Screenshot (487)](https://github.com/rsimon/immarkus/assets/128056738/e9d557b0-6af3-41a8-8a3d-5e7fadadfccc)


**Figure 5.** Create Entities in Annotation Mode

2.	Click on **Entity Class** and name the entity class (e.g. "city_gate.”)

    •	You can select the color of each entity on the right panel.
3.	You can define a different **Display Name**. In this case, "city gate.”
4.	Add an **Entity Class Description** that explains how to use this entity class (e.g., instances of city gates in the image).  
5.	Add/edit the properties. Click the drop down menu next to **No Properties** (the blue arrow in **figure 6**)

![Screenshot (488)](https://github.com/rsimon/immarkus/assets/128056738/74052980-2bf6-4b82-884a-3130bdd2a721)

**Figure 6.** Create Entities and Properties

6.	Click **Add Property**. This opens the property editor as shown in **figure 7**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 7.** Add Properties

7.	Add a property. Define **Property Name**.

8.	Now select a data type by clicking the drop-down menu under **Data Type**. You can select as many properties as you need to create a schema for your entity class. The following seven data types are currently available:

     •	**Text** - a basic text field

     •	**Number** - a numeric field

     •	**Options** - a list of values to choose from

     •	**URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

     •	**Geo-Coordinates** - a latitude/longitude coordinate pair

     •	**Measurement** – a number combined with a measurement word

     •	**[External Authority](https://github.com/rsimon/immarkus/wiki/t_04-Annotation-Mode#add-external-authorities)** (follow the link)

9.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 8.** Choose Data Type


10.	After you have added each property, click **Save Property**. 

11.	When you are finished adding properties, click **Save Entity Class**.

## Add External Authorities

Using the External Authority property type allows you to associate an entity class with one or more external authority services. You can add multiple authorities per field, and multiple fields per entity class. 
In the property editor, type a name for your property ("place ID" in **figure 9**) and select the External Authority field type.

![Screenshot (491)](https://github.com/rsimon/immarkus/assets/128056738/8b581e78-bb41-42d5-9664-ebae050103b4)

**Figure 9.** External Authorities

As you fill in properties for the annotated entity, the external authority popup displays a search field and the authority service result page below it.  Click the ↗ icon on the right side of the search field to open the current authority search in a new browser tab. The links to external authorities need to be copy-and-pasted in the relevant field of the schema.

![Screenshot (494)](https://github.com/rsimon/immarkus/assets/128056738/cbaf8a8d-f7f1-4c35-b1c0-d40803e49cd3)

**Figure 10.** Wikipedia Search Result of "Yangzhou" Using IMMARKUS

# Annotate Multiple Images on the Same Screen

You can annotate images side by side by clicking **Add Image**. In this mode, you can annotate multiple images at the same time. You can drag and drop windows to move them around and change their layout.

![Picture11](https://github.com/rsimon/immarkus/assets/128056738/18df8963-93a5-4304-be1b-819c85a2729d)

**Figure 11.** Annotate Multiple Images Using Add Image


