# Creating Metadata Schemas

You can create metadata schemas in the Data Model view. The metadata can be recorded at the folder (or sub-folder) level as well as at the individual image level. 
- The [Image Metadata](https://github.com/rsimon/immarkus/wiki/04-Annotating-Image) schema defines how you describe individual __image files__ in your collection.
- The [folder metadata](https://github.com/rsimon/immarkus/wiki/05-Working-with-Metadata#adding-folder-metadata) schema defines how you record information about the __directory folders__ in your collection. This can be useful in case your folders represent sub-collections.

## Adding Folder Metadata

1. Go to the **Folder Metadata** tab and click **New Folder Schema**. 

![Screenshot (498)](https://github.com/rsimon/immarkus/assets/128056738/2210a06d-eedd-482f-b519-16b28e845113)

**Figure 15. Folder Metadata** 
<br/><br/>

2.  Metadata properties are added in the same way as entity classes, with the same [property options](https://github.com/rsimon/immarkus/wiki/t_04-Designing-Data-Model#property-options).  

![Screenshot (499)](https://github.com/rsimon/immarkus/assets/128056738/3ec44d69-8f94-4085-af65-05b2677f9879)

**Figure 16.** Add Folder Metadata
<br/><br/>

3. Add **Property Name** ("title” below) and choose a **Data Type** ("text"). Click **Save Property**. 

![Screenshot (500)](https://github.com/rsimon/immarkus/assets/128056738/b4d6c9f2-2c97-4e69-b3d6-f6109c744b89)

**Figure 17.** Choose Data Type of Folder Metadata

4. Be sure to click **Save Schema** after you are done adding properties.

## Adding Metatdata for Individual Images

The metadata for individual images can be added in the same way as metadata for folders.  

1. Choose **Image Metadata** and Click **New Image Schema**. 

![Screenshot (501)](https://github.com/rsimon/immarkus/assets/128056738/2ed26f55-e180-4815-b7f4-677610b05d77)

**Figure 18.**  Individual Image Metadata
<br/><br/>
2. Define **Property Name** and choose **Data Type**. Click **Save Property**. 

![Screenshot (502)](https://github.com/rsimon/immarkus/assets/128056738/05e9a2e5-e62c-42db-b7d5-5c5e5a467f05)

**Figure 19.** Adding properties in Image Metadata
<br/><br/>


# Recording Metadata

After defining your metadata schemas, you can enter metadata for folders and images in the image gallery. You can also enter image metadata in the annotation mode (but not folder metadata).

## Adding Folder Metadata 

1. Click **Images** on the left sidebar to move to image gallery. Click the three dots at the bottom right of the folder and select **Information**.

1. Select a schema for your metadata on the right panel and enter the metadata for the selected folder. After you are done, be sure to click **Save Metadata**. 

![Screenshot (505)](https://github.com/rsimon/immarkus/assets/128056738/6c55b8bb-5406-40f0-a441-d23aec01e624)

**Figure 20**. Recording Folder Metadata in the Image Gallery
<br/>

## Adding Individual Image Metadata 
1. Click the three dots on the individual image. 
2. Select a schema for your metadata and fill in the properties in the same way as the folder metadata.

![Screenshot (506)](https://github.com/rsimon/immarkus/assets/128056738/35ad3826-6688-4dd1-832c-ddc776168076)

**Figure 21.** Recording Image Metadata in the Image Gallery   
<br/>

## Adding Metadata in the Image Annotation View

You can also enter metadata in the Annotation mode. Click the individual image to enter the annotation view and select the metadata tab in the right sidebar (circled in red in **figure 22**). Select the Schema for your metadata and fill in the properties you defined in the Data Model. 

![Screenshot (507)](https://github.com/rsimon/immarkus/assets/128056738/eaafd13a-7bd8-408e-aaa5-5a512bcce8ba)

**Figure 22.** Record Metadata in the Image Annotation View 


