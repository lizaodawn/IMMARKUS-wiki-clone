This page lists some common issues you may encounter when trying to import IIIF manifests into IMMARKUS. If you see one of the following error messages during import, the steps below may help your resolve or diagnose the issue.

### 1. Error: Failed to fetch. Server may restrict access.

This error indicates that the collection hosting the manifest blocks external access. This means you can view the IIIF images in the collection's own website. But it is not possible to import the manifest into an external tool, like IMMARKUS.

__What you can do:__

- __Confirm that the link is to an actual manifest:__ One common cause for this error is when you accidentally paste a web page URL instead of a IIIF manifest URL. Make sure the URL actually points to a valid IIIF Presentation manifest and not, for example, to the web page that displays the zoomable image on the collection website.
- __Check the manifest in other viewers:__ You can try opening the manifest in another viewer like [Universal Viewer](https://universalviewer.io/) or [Theseus Viewer](https://theseusviewer.org/). If the manifest doesn’t load there either, it confirms that the issue is with the server hosting the manifest, not with IMMARKUS.
- __Contact the collection:__ Consider reaching out to the collection maintainers and ask them whether they can adjust their settings to allow external access. In our experience, access is often blocked by accident. The relevant setting is a standard on Web servers and blocks by default. Many institutions are not aware that they have to explicitly enable the setting. When contacting them, you can mention CORS (Cross-Origin Resource Sharing) as the possible error cause and point them to [this information page](https://iiif.io/guides/guide_for_implementers/#other-considerations)

### 2. Error: The provided input is not a valid URL

This error occurs when the URL you entered is not properly formatted, for example if you forget to include `https://` at the beginning of the URL. Note that IMMARKUS will also show this error if you enter a URL starting with `http://` instead of `https://`. Because IMMARKUS is hosted on a secure HTTPS-Address, standard browser security mechanisms prevent import of content from non-secure HTTP sites.

__What you can do:__

- __Double-check the URL:__ Make sure that the URL starts with `https://`. For example:
  - Correct: `https://example.com/manifest.json`
  - Incorrect: `example.com/manifest.json` (missing `https://`)
- __Try opening the URL in your browser:__ Paste the URL into your browser address bar. If it doesn’t open correctly, there might be an issue with the link itself.

### 3. Error: Server responded: HTTP XXX

If you see this error, it means that the collection server could not successfully return a manifest for this URL. The number in the error message (like 404, 500, or 403) identifies the problem more specifically. Some common codes include:

- `404 Not Found`: The manifest URL was not found on the server.
- `403 Forbidden`: Access to the manifest is blocked because it requires a log-in.
- `500 Internal Server Error`: Something went wrong on the server hosting the manifest.

__What you can do:__

- __Check the URL:__ Make sure the manifest URL is correct and exists on the server.
- __Try again later:__ Sometimes, server issues are temporary. If you’re seeing a 500 error, try loading the manifest again later.
- __Contact the collection:__ If you keep seeing a 403 or 404 error and the URL looks correct, the issue might be with the permissions or availability of the manifest. Contact the collection maintainers for help.

## Need More Help?

If none of these solutions work for you, or if you experience an error not listed above, please reach out to us at [infrastructurelives@kuleuven.be](mailto:infrastructurelives@kuleuven.be). When you contact us, please include the following information to help us understand your issue:

- The exact URL you are trying to import.
- The error message you are seeing.
- Screenshots showing the problem, if applicable.
- Any steps you have already tried.

