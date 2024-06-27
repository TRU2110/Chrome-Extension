# Chrome-Extension<br>

✨**Project Overview**<br>
This Chrome extension, named "Dad Jokess", displays a new joke fetched from the Dad Joke API each time the extension icon is clicked. It leverages HTML for the structure, and JavaScript to fetch the joke data. The joke is displayed in a popup window when the extension is activated.<br>

✨**Project Files**<br>
_manifest.json:_ Configuration file that describes your extension's properties and permissions.<br>
_popup.html:_ HTML file that defines the popup's user interface.<br>
_script.js:_ JavaScript file to fetch and display the joke from the Dad Joke API.<br>
_logo.png:_ Icon file for your extension.<br>

**1. manifest.json**<br>
The manifest.json file is the blueprint of your Chrome extension. It provides essential metadata and permissions required for your extension to function properly.<br>

**Explanation:**<br>
name: The name of the extension displayed in Chrome's extension manager.<br>
version: The version number of the extension. It's useful for tracking updates.<br>
manifest_version: Specifies the version of the manifest file format. 3 is the latest version as of now.<br>
action: Defines the popup and icon for the extension.<br>
default_popup: The HTML file (popup.html) that will be shown in the popup window when the extension icon is clicked.<br>
default_icon: The icon image (logo.png) that represents your extension.<br>
icons: Provides different icon sizes for various display contexts.<br>
128: The path to a 128x128 pixel icon.<br>
permissions: Lists the permissions your extension needs.<br>
activeTab: Allows the extension to access the current tab’s content when the extension icon is clicked.<br>

**2. popup.html**<br>
The popup.html file is the structure of the popup interface that appears when the extension icon is clicked.<br>

**3. script.js**<br>
The script.js file contains the JavaScript that fetches a joke from the Dad Joke API and updates the HTML content.<br>

**4. logo.png**<br>
This is an optional file representing your extension's icon. It should be placed in the root of your project directory. You can provide different sizes for different display contexts in the manifest.json file.<br>

✨**How to Load and Test Your Extension**<br>
1 Open Chrome and go to chrome://extensions/.<br>
2 Enable Developer Mode by toggling the switch at the top right corner.<br>
3 Click "Load unpacked" and select your project directory.<br>
4 Your extension will appear in the extensions list.<br>
5 Click the extension icon in the Chrome toolbar to open the popup and see the joke.<br>

✨**Conclusion**<br>
You’ve successfully created a Chrome extension that fetches and displays dad jokes from the Dad Joke API. This project demonstrates how to integrate web technologies with Chrome extension APIs, providing a practical example of fetching and displaying data dynamically.<br>
