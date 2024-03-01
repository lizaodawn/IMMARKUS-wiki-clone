In IMMARKUS you can define a data model consisting of entity classes and properties. A well-designed data model can help ensure that you gather data systematically and tailored to the research questions the annotation process is aimed to address. Data models can also help ensure consistency in collaborative research projects.

**Entity classes** are used to annotate classes of concepts or things (e.g., a city wall, a bridge, a human figure, an animal, a plant); **properties** can be used to record specific details about entity classes (e.g., name, dimension, location, identifier). You can create and view entities and properties both in the [annotation mode](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images) and the [data model mode](https://github.com/rsimon/immarkus/wiki/03-Designing-a-Data-Model).

In the IMMARKUS **hierarchical data model**, you can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. We can also define properties that are particular to child classes.




# Creating Entities and Properties in Annotation Mode

1. In the Image Gallery click a subfolder containing the images with which you want to work. (To locate the Image Gallery, see **Figure 2** in [The Interface](https://github.com/rsimon/immarkus/wiki/02-The-Interface)) This opens the images in the folder.

1. Decide which part of the image you would like to tag and [draw a shape](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#draw-annotations). 

1. After you have drawn a shape, you will see the Add Tag and Add Note buttons in the panel on the right. Choose **Add Tag**. A popup window appears (**Figure 3**). 
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

11.	Select a data type by clicking the drop-down menu under **Data Type**. You can select as many properties as you need to create a schema for your entity class. The following seven data types are currently available:

### Property Options

* **Text** - a basic text field

* **Number** - a numeric field

* **Options** - a list of values to choose from

* **URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

* **Geo-Coordinates** - a latitude/longitude coordinate pair

* **Measurement** – a number combined with a measurement word

* **[External Authority](https://github.com/rsimon/immarkus/wiki/06-External-Authorities)** - external authority services such as TGAZ, CBDB, and Wikipedia.



12.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 6.** Selecting a Data Type


13.	After you have added each property, click **Save Property**. 

14.	When you have finished adding properties, click **Save Entity Class**.



# Creating Parent-Child Entity Classes in the Data Model Mode

In Data Model, you can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. You can also define properties that are particular to child classes. (If you cannot locate the Data Model mode, see the [The Interface](https://github.com/rsimon/immarkus/wiki/02-The-Interface)) 

You can create a child class in the Annotation Mode (see **Figure 7**) and in the Data Model mode.  

1. Click the Create New Entity button 

1. Define **Entity Class** (city_gate) 

1. Define **Display Name** (City gate) 

1. Select the **Parent Class** (in this case the Parent is obj_part) 

![Screenshot (495)](https://github.com/rsimon/immarkus/assets/128056738/68f14260-31e9-4a0b-99e0-93b6fe0a7586)


**Figure 7.** Creating Parent-Child Relationships
<br/><br/>

## Inherited Properties

In **Figure 8**, the child class named "city_gate" inherits all the properties from the parent class named "obj_part".  

In the Properties editor, it looks like this entity does not have any properties (circled in red in **Figure 8**). This means no particular property has been added to this child class. The child class city_gate inherited all the properties from its parent class (circled in blue) as shown on the right panel in **Figure 8**.


![Screenshot (496)](https://github.com/rsimon/immarkus/assets/128056738/fa26f2c4-4600-4f84-9fa7-017c3bf454ff)

**Figure 8.**  The Child Class "city gate" Inherits Properties from its Parent Class "obj_part" 
<br/><br/>

## Viewing Parent-Child Relationships

Classes do not need to have a parent-child relationship. Whether they do depends on your own data design. 

The entity classes for which you have created child classes have a drop-down menu (“>”) on the left (red square in **Figure 9**). 

* Click the drop-down menu to expand the parent class and you will see child classes belonging to the parent class.  

* The properties belonging to or inherited from the parent to the child class are shown on the row of the parent class.  

* On the row of the child class, you can only see the properties specifically added to the child class (see the properties for "location site" parent and "survey area" child in **Figure 9**). 

Classes that do not have children have no drop-down menu (blue square in **Figure 9**).  

![Screenshot (82)](https://github.com/rsimon/immarkus/assets/128056738/7a9f5b76-79c2-4d3f-bf3c-61f41f87dad9)

**Figure 9.** Entity Classes in the Data Model
<br/><br/>

