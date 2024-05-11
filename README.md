
# ZoneTu

This README provides instructions on how to set up the Live Server extension in Visual Studio Code (VSCode) to easily view and test the website locally. It also covers how to update the text content on the website.

## ToDo List
- Update informational text
- Create splitview cards to reformat ABOUT section
- Refactor portfolio section styles to better resemble a dot map
- Replace/remove portfolio items and add your own
- change color palette to desired taste

## Installing Live Server

Live Server is a VSCode extension that launches a local development server with live reload feature for static & dynamic pages. To install and use it, follow these steps:

1. **Open VSCode**:
   Launch Visual Studio Code on your computer.

2. **Extension Marketplace**:
   Click on the Extensions view icon on the Sidebar or press `Ctrl+Shift+X` to open the Extensions view.

3. **Search for Live Server**:
   Type `Live Server` into the search bar and look for the extension by Ritwick Dey.

4. **Install the Extension**:
   Click on the `Install` button next to the Live Server extension.

5. **Start the Server**:
   Once installed, open your project folder in VSCode. Right-click on your `index.html` file in the Explorer pane and select `Open with Live Server`. Alternatively, you can click on the `Go Live` button in the status bar at the bottom to start the server.

6. **View Your Website**:
   Your default web browser should open automatically, displaying the website running on a local server. The URL should look something like `http://127.0.0.1:5500/index.html`.

## Updating the Website

To update text on the website:

1. **Open Files**:
   Navigate to the HTML or CSS files in the VSCode editor where you wish to make changes.

2. **Edit Text**:
   Locate the areas marked with comments like `<!-- Editable Area -->` and replace the placeholder text with your desired content.

3. **Save Changes**:
   After editing, save the file by pressing `Ctrl+S`.

4. **View Changes**:
   Upon saving the Live Server will automatically reload the page and display your changes. Ensure the server is running to see updates in real-time.