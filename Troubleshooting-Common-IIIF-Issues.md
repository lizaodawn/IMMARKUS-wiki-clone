This page lists some common issues you may encounter when trying to import IIIF manifests into IMMARKUS. If you see one of the following error messages during import, the steps below may help your resolve or diagnose the issue.

#### 1. Error: __Failed to fetch. Server may restrict access.__

This error indicates that the collection hosting the manifest blocks external access. This means you can view the IIIF images in the collection's own website. But it is not possible to import the manifest into an external tool, like IMMARKUS.

__What you can do:__

- __Confirm that the link is to an actual manifest:__ One common cause for this error is when you accidentally paste a web page URL instead of a IIIF manifest URL. Make sure the URL actually points to a valid IIIF Presentation manifest and not, for example, to the web page that displays the zoomable image on the collection website.

- __Check the manifest in other viewers:__ you can try opening the manifest in another viewer like [Universal Viewer](https://universalviewer.io/) or [Theseus Viewer](https://theseusviewer.org/). If the manifest doesn’t load there either, it confirms that the issue is with the server hosting the manifest, not with IMMARKUS.

- __Contact the collection:__ consider reaching out to the collection maintainers and ask them whether they can adjust their settings to allow external access. In our experience, access is often blocked by accident. The relevant setting is a standard on Web servers and blocks by default. Many institutions are not aware that they have to explicitly enable the setting. When contacting them, you can mention CORS (Cross-Origin Resource Sharing) as the possible error cause and point them to [this information page](https://iiif.io/guides/guide_for_implementers/#other-considerations,



