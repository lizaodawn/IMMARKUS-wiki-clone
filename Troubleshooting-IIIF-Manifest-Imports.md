This guide covers common issues you may encounter when importing IIIF manifests into IMMARKUS. If you see one of the following errors, these steps may help your resolve or diagnose the problem.

### 1. Error: "Failed to fetch. Server may restrict access."

This error indicates that the collection hosting the manifest blocks external access. You can view the IIIF images in the collection's own website, but importing the manifest into external tools like IMMARKUS is restriced.

__What you can do:__

- __Verify the manifest link:__ Ensure you are using an actual manifest URL, not a web page URL. A common mistake is pasting the URL of a page displaying the zoomable image rather than the manifest itself.

- __Test in other viewers:__ Try opening the manifest in alternative viewers like [Universal Viewer](https://universalviewer.io/) or [Theseus Viewer](https://theseusviewer.org/). If the manifest doesn’t load there either, the issue is with the source server, not IMMARKUS.

- __Contact the collection administrators:__ The collection may be inadvertently block external access. Some collections may not be aware they need to explicitly enable a server setting called CORS (Cross-Origin Resource Sharing) to allow access. When contacting them, reference [this IIIF implementation guide](https://iiif.io/guides/guide_for_implementers/#other-considerations) for technical details.

### 2. Error: "The provided input is not a valid URL"

This error appears when the URL is incorrectly formatted. Note that IMMARKUS requires secure HTTPS URls–standard browser security prevents importing content from non-secure HTTP sites.

__What you can do:__

- __Check URL format:__ Ensure the URL starts with `https://`. For example:
  - Correct: `https://example.com/manifest.json`
  - Incorrect: `example.com/manifest.json` or `http://example.com/manifest.json`)
- __Try opening the URL in browser:__ Paste the URL into your browser address bar. If it doesn’t load correctly, the link itself might be broken.

### 3. Manifest Imports Correctly But Images Are Not Loading

Sometimes IMMARKUS imports the manifest successfully, but images appear broken in the overview, and the annotation view fails to load. Note that some image servers respond slowly, and images from certain collections may take longer to display.

__What you can do:__

- __Test in other viewers:__ Open the manifest in [Universal Viewer](https://universalviewer.io/) or [Theseus](https://theseusviewer.org/) and check if the images load there.

- __Try a different network:__ Missing images may indicate firewall restrictions. If possible, connect through a different network (like your mobile data) to determine if your current network is blocked by the collection server's security measures. 

- __Contact the collection:__ If you appear to be blocked, reach out to the collection administrators with the exact URL you're trying to access.  To facilitate unblocking, provide your IP address (which you can find out with services like [whatismyipaddress.com](https://whatismyipaddress.com/)).

### 4. Error: Server responded: HTTP XXX

This error means the collection server couldn't successfully deliver the manifest. The error code provides specific information about the problem:

- `404 Not Found`: The manifest URL doesn't exist on the server.
- `403 Forbidden`: The manifest requires authentication or access is restricted.
- `500 Internal Server Error`: The server encountered an interal problem processing the request.

__What you can do:__

- __Verify the URL:__ Ensure you are using the correct and complete manifest URL.
- __For 500 errors, retry later:__ Server issues are often temporary. Try again after some time.
- __For persistent 403 or 404 errors:__ Contact the collection administrators to verify the manifest's availability and access permissions.

## Need Further Assistance?

If these solutions don't resolve your issue or you encounter an error not listed above, please contact us at [infrastructurelives@kuleuven.be](mailto:infrastructurelives@kuleuven.be). To help us diagnose your problem, please include:

- The exact URL you are trying to import
- The complete error message
- Screenshots illustrating the issue
- A summary of troubleshooting steps you've already attempted
