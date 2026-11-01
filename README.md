# Data4Kids
Data4Kids is a simple, browser-based learning tool for making graphs, picture graphs, and drawings. It is built with plain HTML, CSS, and JavaScript, without a framework or server-side application. The painting area and PDF/image exports use the browser's Canvas API. Picture Graph stickers use Noto Emoji SVG images loaded online from Google Fonts.

## Does Data4Kids store my work online?

No. The app does not send your graph entries or drawings to a database or save them to a website. Unsaved work stays in the currently open browser page and can be lost if the page is refreshed or closed.

- **Save Project** downloads a JSON project file to your device. Use **Open** to load that file later.
- **Save** downloads an export to your device: a PDF for Graph or Picture Graph, and a PNG for Paint.
- **Print** opens the browser's print dialog.
- Picture Graph sticker images load from Google Fonts, so an internet connection is needed for those images. The image requests do not include your graph labels, vote counts, or name.

When hosted online, the hosting provider may log ordinary website visits, such as visitor IP addresses, under its own privacy policy. That is separate from the graph data, which this app does not upload.

## Quick guide

### Graph

1. Choose **Graph**.
2. Add categories and enter a number for each one. Edit the graph title if you like.
3. Choose **Pie**, **Bar**, or **Horizontal**. Use the colour squares to change category colours.
4. Select **Save** to download a PDF containing the graph types, or select the printer button to print.

### Picture Graph

1. Choose **Picture Graph** and select a preset or start with a blank graph.
2. Add choices, select a sticker for each one, and use **+** or **−** to tally votes.
3. Click **Generate Ranking** to display the results ordered by votes.
4. Select **Save** to download a PDF with the picture graph and ranking, or select the printer button to print.

### Paint

1. Choose **Paint** and select a tool and colour.
2. Draw on the canvas. Choose a sticker to place it; scroll the mouse wheel over the canvas to resize the sticker.
3. Select **Save** to download the drawing as a PNG.

### Project files

Enter a name in the top **Name** field if you want it included in exports. To keep an editable copy of the whole project, open the arrow next to **Save** and choose **Save Project**. Use **Open** to load a previously saved JSON project.

## Code and contributions

The page is a static, client-side app made with HTML, CSS, and vanilla JavaScript. Its graphing, picture tallying, painting, and exporting features run in the browser. There is no backend or database in this project.

If this repository is public, anyone can view it and create a GitHub fork, then make changes in their own copy or propose changes to the original repository. **This repository does not currently include a software license.** A public repository can be forked, but without a license there is no explicit permission for others to reuse, modify, or redistribute the code. Add a license, such as MIT if that matches the owner's intent, before describing the code as open source or inviting reuse.
