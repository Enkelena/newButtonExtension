# newButtonExtension
The extension adds a new button to the Firefox toolbar. When the user clicks the button, 
we display a popup enabling them to choose an animal. Once they choose an animal,
 we'll replace the current page's content with a picture of the chosen animal.

It's a simple extension, but shows many of the basic concepts of the WebExtensions API:

* adding a button to the toolbar
* defining a popup panel using HTML, CSS, and JavaScript
* injecting content scripts into web pages
* communicating between content scripts and the rest of the extension
* packaging resources with your extension that can be used by web pages

### Testing
* Open "about:debugging" in Firefox, click "Load Temporary Add-on", and select your manifest.json file.
 You should then see the extension's icon appear in the Firefox toolbar
Open a web page, then click the icon, select a beast, and see the web page change:

