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

2. When you have finished drawing, you will be asked to add a tag. Choose "Add Tag" and you can [add entities and properties](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#adding-entities-and-properties-to-image-selections).

# Adding Entities and Properties to Image Selections

After you have drawn a shape, you can also add or create entities and properties by following the steps below:

1. Decide which part of the image you would like to tag and [draw a shape](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#drawing-annotations). Once you have drawn a shape, you will see the Add Tag and Add Note buttons in the panel on the right. Select **Add Tag** and a popup window appears.

2. If you have already created a data model, the existing entities will appear along with any other entities you created before as shown in **Figure 16**. You can reuse these entities and their properties to annotate the image selection. You can also search through your entities to locate the one needed if you have created many.

* For creating entities and properties in the Data Model mode, see [Data Model Mode](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model). 

<img width="583" alt="Screenshot 2024-03-04 at 18 42 22" src="https://github.com/rsimon/immarkus/assets/160752064/7631a25d-2913-4ff4-9c33-972056b20d5c">



**Figure 16.** Adding or Creating Entities in Annotation Mode

3.	If you have not yet defined a data model or if you would like to add a new parent or child entity class to annotate the image selection, click **Create New Entity Class** and name the entity class (e.g. "gate_tower”). You can select the color of each entity on the right panel. Follow the steps below to complete the creation of a new entity class. This new class will be automatically added to the Data Model view.

4.	You can define a different **Display Name**. (e.g. "gate tower").
5.	You can choose to add your new entity class as a child class of one of your existing entities. In the **Parent Class** field, type the name of the entity class that you want to make the parent of your new entity class (e.g. "obj_part").
6.  Once you have defined your new entity class as a child class, the properties of its parent class will be displayed in the entity preview. (see the right side of the panel in **Figure 17**). You can read more about inherited properties [here](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#inherited-properties)

7. Add an **Entity Class Description** that explains the use of this entity class. This field is optional.  

8. Add/edit the properties. Click the drop down menu next to **No Properties** (circled in blue in **Figure 17**)

<img width="987" alt="Screenshot 2024-03-04 at 18 45 39" src="https://github.com/rsimon/immarkus/assets/160752064/46bf3d50-b73e-41aa-84d9-73ea81a3c7e9">

**Figure 17.** Creating Entities and Properties



9.	Click **Add Property**. This opens the property editor as shown in **Figure 18**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 18.** Adding Properties

10.	Define the **Property Name**.

11.	Select a data type by clicking the drop-down menu under **Data Type**. Click here for [Property Options](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#property-options).


12.	In this case, the data type of "number of floors" is **Number**. You can also add a description of the property in **Property Description**.

<img width="996" alt="Screenshot 2024-03-04 at 18 57 19" src="https://github.com/rsimon/immarkus/assets/160752064/ab407e36-688d-4636-afa3-1362a034bdc6">

**Figure 19.** Selecting a Data Type


13.	After you have added each property, click **Save Property**. 

14.	When you are done adding properties, click **Save Entity Class**.

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

# Adding a Note

You can add a note to a selected part of your image. This is useful if you want to make a note about the image for future use, but do not want to include that information in the annotations.

Select a part of your image and [draw a shape](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#drawing-annotations). 
You will see the Add Tag and Add Note buttons in the panel on the right. 

<img width="980" alt="Screenshot 2024-03-04 at 19 58 06" src="https://github.com/rsimon/immarkus/assets/160752064/06f05864-0886-4c2c-bbd5-d65bf5580b25">

**Figure 22.** Adding a Note to a Selected Image Part

Click **Add Note**. Be sure to click **Save** after writing your note.

You can also add a note to any image selection that you have already annotated. Select the annotation, and then scroll down to the bottom and click the **Add Note** button. This is useful if you want to add a note unrelated to existing properties or want to add extra information for future reference.

<img width="985" alt="Screenshot 2024-03-04 at 20 07 25" src="https://github.com/rsimon/immarkus/assets/160752064/d2f2c4f6-61cb-4fb4-a398-5714e0990f93">

**Figure 23.** Adding a Note to a Selection of an Image with an Existing Tag
	 
# Annotating Multiple Images Simultaneously

You can annotate multiple images side by side. 

1. Click **Add Image** (red square in **Figure 24**) and select the image(s) that you want to annotate together.

2. You can drag and drop windows to move them around and change their layout.

![Screenshot (525)](https://github.com/rsimon/immarkus/assets/128056738/37ef3e05-9873-4be7-b7a2-28a167275e6f)


**Figure 24.** Annotating Multiple Images Simultaneously Using Add Image (Red Square)


