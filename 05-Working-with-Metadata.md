# Creating a Metadata Schema

You can create a metadata schema in the Data Model view. You can record metadata at the folder (or sub-folder) level as well as at the individual image level. 
- The [Image Metadata](https://github.com/rsimon/immarkus/wiki/05-Working-with-Metadata#adding-metatdata-for-individual-images) schema defines how you describe individual __image files__ in your collection.
- The [Folder Metadata](https://github.com/rsimon/immarkus/wiki/05-Working-with-Metadata#adding-folder-metadata) schema defines how you record information about the __directory folders__ in your collection. This can be useful in case your folders represent sub-collections.

## Adding Folder Metadata

1. In the Data Model view, go to the **Folder Metadata** tab and click **New Folder Schema**. 

![Screenshot (498)](https://github.com/rsimon/immarkus/assets/128056738/2210a06d-eedd-482f-b519-16b28e845113)

**Figure 13**. Schemas for Folder Metadata 
<br/><br/>

2.  Metadata categories are added in the same way as properties for entity classes with similar [property options](https://github.com/rsimon/immarkus/wiki/03-Designing-Data-Model#property-options).  

![Screenshot (499)](https://github.com/rsimon/immarkus/assets/128056738/3ec44d69-8f94-4085-af65-05b2677f9879)

**Figure 14.** Adding a Schema for Folder Metadata
<br/><br/>

3. Add a metadata field under **Property Name** ("title”) and choose a **Data Type** ("text"). Click **Save Property**. 

![Screenshot (500)](https://github.com/rsimon/immarkus/assets/128056738/b4d6c9f2-2c97-4e69-b3d6-f6109c744b89)

**Figure 15.** Setting a Data Type in a Folder Metadata Schema

4. Be sure to click **Save Schema** after you are done adding properties.

## Adding Metadata for Individual Images

A metadata schema for individual images can be added in the same way as metadata schemas for folders.  

1. Choose **Image Metadata** and click **New Image Schema**. 

![Screenshot (501)](https://github.com/rsimon/immarkus/assets/128056738/2ed26f55-e180-4815-b7f4-677610b05d77)

**Figure 16.**  Schemas for Individual Image Metadata
<br/><br/>
2. Define **Property Name** and choose **Data Type**. Click **Save Property**. 

![Screenshot (502)](https://github.com/rsimon/immarkus/assets/128056738/05e9a2e5-e62c-42db-b7d5-5c5e5a467f05)

**Figure 17.** Adding Properties in Image Metadata
<br/><br/>


# Recording Metadata

After defining your metadata schemas, you can enter metadata for folders and images in the image gallery. You can also enter image metadata in the annotation mode (but not folder metadata).

## Recording Folder Metadata in the Image Gallery 

1. Click **Images** on the left sidebar to move to image gallery. Click the three dots at the bottom right of the folder and select **Information**.

1. Select a schema for your metadata on the right panel and enter the metadata for the selected folder. After you are done, be sure to click **Save Metadata**. 

![Screenshot (505)](https://github.com/rsimon/immarkus/assets/128056738/6c55b8bb-5406-40f0-a441-d23aec01e624)

**Figure 18**. Recording Folder Metadata in the Image Gallery
<br/>

## Recording Individual Image Metadata in the Image Gallery 
1. Click the three dots on the individual image. 
2. Select a schema for your metadata and fill in the properties in the same way as the folder metadata.

![Screenshot (506)](https://github.com/rsimon/immarkus/assets/128056738/35ad3826-6688-4dd1-832c-ddc776168076)

**Figure 19.** Recording Image Metadata in the Image Gallery   
<br/>

## Recording Metadata in Annotation Mode

You can also enter metadata for individual images in the annotation mode. Click the individual image to enter the annotation view and select the metadata tab in the right panel (circled in red in **Figure 20**). Select the schema for your metadata and fill in the properties you defined under metadata in the Data Model view. 

![Screenshot (507)](https://github.com/rsimon/immarkus/assets/128056738/eaafd13a-7bd8-408e-aaa5-5a512bcce8ba)

**Figure 20.** Recording Image Metadata in Annotation Mode


