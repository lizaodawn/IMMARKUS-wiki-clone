This guide covers common issues you may encounter when importing IIIF manifests into IMMARKUS. If you see one of the following errors, these steps may help you resolve or diagnose the problem.

### 1. Error: "Failed to fetch. Server may restrict access."

This error indicates that the collection that hosts the manifest may possibly block external access. You can view the IIIF images in the collection's own website, but importing the manifest into external tools like IMMARKUS is restricted.

__What you can do:__

- __Verify the manifest link:__ Ensure you are using the correct manifest URL. A common mistake is pasting the URL of a page displaying the zoomable image rather than the manifest, which may also lead to this error. Note that in some collections, the manifest URL can be a bit hard to find. You may have to scroll down or open an additional dropdown to get to it. We have collected some examples below.

- __Test in other viewers:__ Try opening the manifest in alternative viewers like [Universal Viewer](https://universalviewer.io/) or [Theseus Viewer](https://theseusviewer.org/). If the manifest doesn’t load there either, the issue is with the source server, not IMMARKUS.

- __Contact the collection administrators:__ The collection may have inadvertently blocked external access. Some collection maintainers may not be aware that they need to explicitly enable a server setting called CORS (Cross-Origin Resource Sharing) to allow access. When contacting them, reference [this IIIF implementation guide](https://iiif.io/guides/guide_for_implementers/#other-considerations) for technical details.

__Examples:__ Make sure you import the IIIF manifest URL (green), not the web page URL (red).

![example-yale](https://github.com/user-attachments/assets/8ec48019-b42e-49c7-a0f1-dce45d374646)

![example-oxford](https://github.com/user-attachments/assets/c8b3d359-cf41-4be2-ac45-ffd97999a23c)

![example-loc](https://github.com/user-attachments/assets/5ff2a429-585b-4947-bbf8-07c7d37af3ed)

### 2. Error: "The provided input is not a valid URL"

This error appears when the URL is incorrectly formatted. Note that IMMARKUS requires secure HTTPS URLs–standard browser security will otherwise prevent importing content from non-secure HTTP sites.

__What you can do:__

- __Check URL format:__ Ensure the URL starts with `https://`. For example:
  - Correct: `https://example.com/manifest.json`
  - Incorrect: `example.com/manifest.json` or `http://example.com/manifest.json`
- __Try opening the URL in browser:__ Paste the URL into your browser address bar. If it doesn’t load correctly, the link itself might be broken.

### 3. Manifest Imports Correctly But Images Are Not Loading

Sometimes IMMARKUS imports the manifest successfully, but images appear broken in the overview, and the annotation view fails to load. (Note that some image servers respond slowly, and images from certain collections may take longer to display!)

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
