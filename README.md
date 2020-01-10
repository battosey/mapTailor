## Welcome to Map Tailor!

**Download** the [latest version 1.0.1](https://raw.githubusercontent.com/battosey/mapTailor/master/releases/MapTailor_v1-0-1.zip) and get started. _[[Changelog]](#changelog)_

![](https://i.imgur.com/GnciMzt.png)![](https://github.com/battosey/mapTailor/raw/master/example/zoom-map-example.gif)

Map Tailor is a helper tool to create zoomable, interactive maps out of already existing images (e.g. created by [Wonderdraft](https://www.wonderdraft.net/)) that can be displayed on a website.

![](https://media.giphy.com/media/jP4LdxgEuC3VjFnnO9/giphy.gif)

[Demo video](https://www.youtube.com/watch?v=rI9y5wnLEGs) | [Example map](https://map-tailor-example.netlify.com/)

Check out the [wiki](https://github.com/battosey/mapTailor/wiki) to see the detailed **documentation** of all the features.

### Support or Contact
Having trouble with Map Tailor? Join the [Discord Server](https://discord.gg/AUXDqn3) and we’ll help you sort it out.

## Quick How-To
1. Drag&drop image files into [Map Tailor](https://github.com/battosey/mapTailor/wiki/Main-Window)
2. Adjust their size in the [image details window](https://github.com/battosey/mapTailor/wiki/Image-Details-Window). You can open the image details for an image by clicking on it in the listbox on the left
3. Play around with the values and don't forget to hit "Apply" (or simply press the enter key) to apply the changes to the image
4. You can also open the [image matching window](https://github.com/battosey/mapTailor/wiki/Image-Matching-Window) for a map image in the [image details](https://github.com/battosey/mapTailor/wiki/Image-Details-Window)
5. [Export](https://github.com/battosey/mapTailor/wiki/Export) your map
6. Upload your exported files to your webserver
7. Done!

[What's planned for the future?](https://github.com/battosey/mapTailor/projects)

<a name="changelog"/>

## Changelog v1.0.1
### New Features
* Added "Check for updates on launch" option that is enabled by default
* Added possibility to only export html
* Added possibility to close the export settings dialog without discarding setting changes
* You can now export tiles as jpg
* You can now choose to not overwrite exsting files when exporting
* Added a "Reset View" button that resets the preview map to its original view
### Improvements
* Slightly improved performance when exporting a lot of tiles
* Preview map viewport is no longer saved in the project (that did not make a lot of sense...)
* Windows "pling" sound is now played when export is finished
* Disabled the export button when nothing can be exported
* A prompt is now shown when exporting HTML to ensure if the user really wants to overwrite an existing file
* Added some comments with examples of markers and shapes to the exported HTML file
### Bugfixes
* Fixed "Min/Max Zoom Level" fields in main window not influencing the zoom of the preview map
