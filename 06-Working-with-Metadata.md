# Creating a Metadata Schema

You can create a metadata schema in the Data Model view. You can record metadata at the folder (or sub-folder) level as well as at the individual image level. 
- The [Image Metadata Schema ](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#adding-a-metadata-schema-for-individual-images) defines how you describe individual __image files__ in your collection.
- The [Folder Metadata Schema](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#adding-a-folder-metadata-schema) defines how you record information about the __directory folders__ in your collection. This can be useful if your folder contains images from the same book, artwork, or publication, so that you do not have to enter in the same metadata information for each individual image in the sub-folder.



## Adding a Folder Metadata Schema

1. In the Data Model view, go to the **Folder Metadata** tab and click **New Folder Schema**. 

<img width="1189" alt="Screenshot 2024-03-03 at 01 02 00" src="https://github.com/rsimon/immarkus/assets/160752064/f49ff713-296c-4ce9-8bd5-d4dff7c76882">


**Figure 23**. Examples of Folder Metadata Schemas
<br/><br/>

2.  Metadata categories are added in the same way as properties for entity classes with similar [property options](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#property-options).  

<img width="837" alt="Screenshot 2024-03-03 at 00 39 13" src="https://github.com/rsimon/immarkus/assets/160752064/2e5a7224-4522-412d-bced-84a3339a2852">


**Figure 24.** Adding a Schema for Folder Metadata
<br/><br/>

3. Add a metadata field under **Property Name** ("genre”) and choose a **Data Type** ("Options"). Click **Save Property**. 

<img width="955" alt="Screenshot 2024-03-03 at 00 48 39" src="https://github.com/rsimon/immarkus/assets/160752064/e2e8674c-d19c-4a2c-9002-ad259a922d65">

**Figure 25.** Setting a Data Type in a Folder Metadata Schema

4. Be sure to click **Save Schema** after you are done adding properties (bottom blue box in **figure 26**).

<img width="614" alt="Screenshot 2024-03-03 at 01 09 37" src="https://github.com/rsimon/immarkus/assets/160752064/fe127aa5-443e-4320-9cbb-38c91206466b">


**Figure 26.** Saving a Folder Metadata Schema

## Adding a Metadata Schema for Individual Images

A metadata schema for individual images can be added in the same way as metadata schemas for folders.  

1. Choose **Image Metadata** and click **New Image Schema**. 

<img width="917" alt="Screenshot 2024-03-03 at 01 21 41" src="https://github.com/rsimon/immarkus/assets/160752064/faf265e2-0fc3-4a05-b4e9-864496725378">

**Figure 27.**  Creating a Metadata Schema for Individual Images
<br/><br/>
2. Define **Property Name** and choose **Data Type**. Click **Save Property**. 

<img width="819" alt="Screenshot 2024-03-03 at 01 25 49" src="https://github.com/rsimon/immarkus/assets/160752064/af4a0c0d-1b18-4645-80a3-2c8693ba4af5">


**Figure 28.** Setting a Data Type in a Metadata Schema for Individual Images
<br/><br/>


# Recording Metadata

After defining your metadata schemas, you can enter metadata for folders and images in the Image Gallery. You can also enter image metadata in the annotation mode (but not folder metadata).

## Recording Folder Metadata in the Image Gallery 

1. Click **Images** on the left sidebar to move to the Image Gallery. Click the three dots at the bottom right of the folder and select **Information**.

1. Select a schema for your metadata on the right panel and enter the metadata for the selected folder. After you are done, be sure to click **Save Metadata**. 

![Screenshot (529)](https://github.com/rsimon/immarkus/assets/128056738/acb11fe8-c8d3-4ea8-918f-90e88594f4b9)

**Figure 29**. Recording Folder Metadata in the Image Gallery
<br/>

## Recording Individual Image Metadata in the Image Gallery 
1. Click the three dots on the individual image. 
2. Select a schema for your metadata and fill in the properties in the same way as for the [folder metadata](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#recording-folder-metadata-in-the-image-gallery).

![Screenshot (533)](https://github.com/rsimon/immarkus/assets/128056738/6fe34242-8b76-4a4d-a6f1-8c863e3d12c6)

**Figure 30.** Recording Image Metadata in the Image Gallery   
<br/>

## Recording Metadata in Annotation Mode

You can also enter metadata for individual images in the annotation mode. Click the individual image to enter the annotation view and select the metadata tab in the right panel (red square in **Figure 31**). Select the schema for your metadata and fill in the properties you defined under metadata in the Data Model view. 

![Screenshot (537)](https://github.com/rsimon/immarkus/assets/128056738/b3835a3f-a305-4b1a-bca3-a924f04790c2)

**Figure 31.** Recording Image Metadata in the Annotation Mode


