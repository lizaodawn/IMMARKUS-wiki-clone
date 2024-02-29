In IMMARKUS, the data model is based on the concepts of entity classes and properties. 

In short, we use **entity classes** to annotate specific concepts or things (e.g., a city wall); and we use **properties** to record specific details about entity classes (e.g., the name, dimension, and location). You can create and view entities and properties both in the [annotation mode](https://github.com/rsimon/immarkus/wiki/04-Annotating-Image) and the [data model mode](https://github.com/rsimon/immarkus/wiki/04-Annotating-Image).

In the **hierarchical data model**, we can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. We can also define properties that are specific to child classes.




# Creating Entities and Properties in Annotation Mode

To create entities in the image gallery, click the subfolder containing the images you want to work with. (If you cannot find the image gallery, see **figure 2** in the [Interface Overview](https://github.com/rsimon/immarkus/wiki/02-Interface-Overview)) This will open the images in the folder.

1. In the Image Gallery, decide which part of the image you would like to tag and [draw a shape](https://github.com/rsimon/immarkus/wiki/t_05-Annotating-Image#draw-annotations). 

1. After you have drawn a shape, you will see the Add Tag and Add Note buttons in the sidebar on the right. Choose **Add Tag** and it will open a popup window like one shown in **figure 5**. 
1.	Click **Create New Entity Class**. 



![Screenshot (487)](https://github.com/rsimon/immarkus/assets/128056738/e9d557b0-6af3-41a8-8a3d-5e7fadadfccc)

**Figure 5.** Create Entities in Annotation Mode

4.	Click on **Entity Class** and name the entity class (e.g. "city_gate.”)

    •	You can select the color of each entity on the right panel.

5.	You can define a different **Display Name**. In this case, "city gate.”
6.	Add an **Entity Class Description** that explains how to use this entity class (e.g., instances of city gates in the image).  


7.	Add/edit the properties. Click the drop down menu next to **No Properties** (the blue arrow in **figure 6**)

![Screenshot (488)](https://github.com/rsimon/immarkus/assets/128056738/74052980-2bf6-4b82-884a-3130bdd2a721)

**Figure 6.** Create Entities and Properties



8.	Click **Add Property**. This opens the property editor as shown in **figure 7**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 7.** Add Properties

9.	Add a property. Define **Property Name**.

10.	Now select a data type by clicking the drop-down menu under **Data Type**. You can select as many properties as you need to create a schema for your entity class. The following seven data types are currently available:

### Property Options

* **Text** - a basic text field

* **Number** - a numeric field

* **Options** - a list of values to choose from

* **URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

* **Geo-Coordinates** - a latitude/longitude coordinate pair

* **Measurement** – a number combined with a measurement word

* **[External Authority](https://github.com/rsimon/immarkus/wiki/07-External-Authorities)** - external authority services such as TGAZ, CBDB, and Wikipedia.



11.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 8.** Choose Data Type


11.	After you have added each property, click **Save Property**. 

12.	When you are finished adding properties, click **Save Entity Class**.



# Creating Parent-Child Entity Classes in the Data Model Mode

In the data model, we can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. We can also define properties that are specific to child classes. (If you cannot find the data model, see the [Interface Overview](https://github.com/rsimon/immarkus/wiki/t_03-Interface-Overview)) 

You can create a child class in annotation mode (see **figure 12**) and in the Data Model. Click the Create New Entity button and: 

1. Define **Entity Class** (city_gate) 

1. Define **Display Name** (City gate) 

1. Choose the **Parent Class** (in this case the Parent is obj_part) 

![Screenshot (495)](https://github.com/rsimon/immarkus/assets/128056738/68f14260-31e9-4a0b-99e0-93b6fe0a7586)


**Figure 12.** Create Child- Parent Relationships
<br/><br/>

## Inherited Properties

In **figure 13**, the child class named "city_gate" inherits all the properties from the parent class named "obj_part".  

In the Properties editor, it looks like this entity does not have any properties (circled in red in **figure 13**). This means no specific property has been added to this child class. The child class city_gate inherited all the properties from its parent class (circled in blue) as shown on the right sidebar in **figure 13**.


![Screenshot (496)](https://github.com/rsimon/immarkus/assets/128056738/fa26f2c4-4600-4f84-9fa7-017c3bf454ff)

**Figure 13.**  The Child Class "city gate" Inherits Properties from its Parent Class "obj_part" 
<br/><br/>

## View Parent-Child Relationship

Classes do not need to have a parent-child relationship. Whether they do depends on your own data design. 

The entity classes for which you have created child classes have a drop-down menu (“>”) on the left (red square in **figure 14**). 

* Click the drop-down menu to expand the parent class and you will see child classes belonging to the parent class.  

* The properties belonging to or inherited from the parent to the child class are shown on the row of the parent class.  

* On the row of the child class, you can only see the properties specifically added to the child class (see the properties for "location site" parent and "survey area" child on **figure 14**). 

Classes that do not have children have no drop-down menu (blue square on **figure 14**).  

![Screenshot (82)](https://github.com/rsimon/immarkus/assets/128056738/7a9f5b76-79c2-4d3f-bf3c-61f41f87dad9)

**Figure 14.** Entity Classes in the Data Model
<br/><br/>

