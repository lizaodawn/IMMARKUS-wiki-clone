IMMARKUS uses a novel browser feature which is currently unavailable on Firefox, Safari and mobile devices. Please use **Chrome** or **Edge** on the desktop to access IMMARKUS.

1. To start working with IMMARKUS, create or locate a folder with JPEG or PNG files on your computer. If you are working exclusively with IIIF sources, select or create an empty folder.

    **NOTE:** IMMARKUS stores data directly on your computer. We recommend that you work with copies of your work folder, and make regular backups of your files in another folder to avoid the loss of data.

2. Go to IMMARKUS [immarkus.xmarkus.org](https://immarkus.xmarkus.org/)

3. Click **Open New Folder** and select the folder that contains your images or the empty folder designated for annotating IIIF sources.  
 
    <img width="578" alt="Screenshot 2024-03-04 at 14 17 54" src="https://github.com/rsimon/immarkus/assets/160752064/aa280af6-768d-40bf-accc-2f0739b7a3e8">

    **Figure 1.** The IMMARKUS Main Page [immarkus.xmarkus.org](https://immarkus.xmarkus.org/)

    If you have already used IMMARKUS, the folder with which you last worked will be displayed next to **Open New Folder** (in **Figure 1** above, the folder "Ming illustrative map") 

4. You will see a popup window asking "Let site edit files?" Click **Edit files** to allow IMMARKUS to edit the files in the selected folder. 

## Working with IIIF Sources

IMMARKUS supports imports from [IIIF (International Image Interoperability Framework)](https://iiif.io/get-started/how-iiif-works/) Presentation Manifests, allowing you to bring images (whether organized in a folder structure or as individual canvases) and their associated metadata from IIIF-compliant collections directly into your workspace. Working with IIIF resources provides several key advantages:

* **efficient image access and handling**: Access high-resolution images and metadata remotely, reducing reliance on local storage. You can view scalable images at various zoom levels without downloading large files and manipulate them directly from the source.

* **the integration of sources from multiple collections**: IIIF enables users to easily integrate image and metadata sources from different collections as they all adopt a shared, interoperable standard.

You can add and save annotations, relationships, and other content added to imported IIIF canvases to your local storage, keeping full control over your work. 

**Want to learn more about IIIF?**  
➡️Visit [Why IIIF?](https://iiif.io/get-started/why-iiif/#:~:text=IIIF%20is%20a%20set%20of%20open%20standards%20for,backed%20by%20a%20consortium%20of%20leading%20cultural%20institutions)  

**Looking for more IIIF resources and tips?**  
➡️Explore [Navigating the IIIF Landscape: A Guide to Finding Images & Manifests](https://liiive.now/blog/2025-02-navigating-the-iiif-landscape/)

**Need quick help working with IIIF resources in IMMARKUS?**  
➡️Check out [Troubleshooting IIIF Manifest Imports](Troubleshooting-IIIF-Manifest-Imports.md).


### Importing IIIF Manifest
Paste the URL to a **IIIF Presentation Manifest** into the dialogue box.

![02-fig2](update-images/02_importing-images_fig2.jpg)  
**Figure 2.** Pasting IIIF Manifest URL to Import

The imported IIIF folders or canvases will have a IIIF icon displayed on their thumbnails (outlined in blue in **Figure 3**). 

![02-fig3](update-images/02_importing-images_fig3.png)
**Figure 3.** IIIF Icons Shown on the Thumbnails of Imported Folders and Canvases

You can work with IIIF canvases in the same way as with local images.

## Image Size
Limit your image size to 10 MB to ensure IMMARKUS can open them. If you are working with images above 10 MB, we recommend converting them to lower quality images for your work in IMMARKUS. 

## Subfolder Organization 
In IMMARKUS it is possible to upload one folder with several subfolders and apply the same data and metadata model to subfolders. We recommend organizing images into subfolders according to shared features (e.g. they belong to the same publication or collection). If you have images from different sources (**Figure 4**) consider storing those from the same source together. You can then fill in the shared bibliographic information for all images in the same subfolder in the [subfolder metadata](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata). The subfolder structure will be visible in the .XLSX export of annotations.

<img width="1100" alt="SUBFOLDERS" src="https://github.com/rsimon/immarkus/assets/128056738/a9fabd17-2042-48b7-ac57-7c9b2ddc1bab">

**Figure 4.** Creating Multiple Folders by Topic (Left) and Subfolders for Each Source (Center)

Folders can have several levels of subfolders, as shown in **Figure 4**, the top folder is named after the theme of the main project (i.e. cartographic ethnography) and contains the data model .JSON file (_immarkus.model.json) that applies to all image files in this folder. The subfolders at the next level are named after sub-themes (i.e. maritime frontier, northern frontier, and southwestern frontier). You can store different metadata information at each level of the subfolder structure if needed. At the next level subfolders are divided by the source title (i.e. sanzhen tushuo_painted_atlas_juan 2) and contain images intended for annotation. At this level you could, for example, store the bibliographic information for the source, which could be applied to all the images in this subfolder (**Figure 4**).

![SUBFOLDERS image 2](update-images/02_importing-images_fig5.png)
**Figure 5.** Subfolder Organization in IMMARKUS
   
</br>

![SUBFOLDERS image 3](update-images/02_importing-images_fig6.png)
**Figure 6.** Subfolder Metadata

## Image and Folder Size

To ensure optimal performance, keep your projects manageable. Limit the number of subfolders and limit the number of images in your subfolders to 100, with a recommended maximum size of 10 MB per image (see [Image Size](https://github.com/rsimon/immarkus/wiki/02-Uploading-Images#image-size) above). Keep in mind that metadata models can be exported and reused in projects (see [Importing Metadata Models](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#importing-data-models-for-metadata)).

