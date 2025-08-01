**Initial Prototype "derbi_map_5"**
This map is an initial prototype, meaning that it was used for usability testing and the heuristic evaluation portions of the study. This map represents the percent of land area covered by tree canopy in each census tract (Urbana and Champaign, IL). 
## Description
This is an interactive map that shows tree canopy coverage per census block in Champaign and Urbana. There are outlines of each geoid, and the borders of these two towns. Although the user can zoom in and out, tree canopy data (shading and hovering feature) is only shown in Urbana and Champaign.
When a geoid is hovered over, the tree canopy coverage percentage is shown.
There is a red- to- green color scheme with shaded areas (as opposed to "dots"). There is also a legend, title, caption, and zoom feature. 
- Title: Percent(%) of Land Area Covered by Tree Canopy in Each Census Tract (Urbana and Champaign, IL)
- Caption: Tree canopy is the layer of leaves and branches that cover the ground from above. Neighborhoods with at least 40% tree canopy are considered to have ideal coverage—providing cooler temperatures, cleaner air, and a more comfortable place to live. The map represents how different census tracts meet that goal, with enough trees to support both community health and the environment.
- Legend Canopy Groups- Less than 10% (Poor), 10-19%, 20-29%, 30-39%, 40- 100% (Excellent)

The user's location is shown through a blue pin point with the users profile icon inside. The map was made using the leaflet package.
## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
macOS 15.5 (24F74)
R version 4.5.0 (2025-04-11)
RStudio version 2025.05.0+496 (2025.05.0+496)
leaflet 2.2.2
sf 1.0.21
dplyr 1.1.2
htmltools 0.5.8.1
base64enc 0.1.3
htmlwidgets 1.6.4


# My environment
R version 4.3.1
RStudio version 2023.06.1
leaflet 2.2.2
sf 1.0-14
dplyr 1.1.2


### Installing
The data is from https://www.treeequityscore.org/methodology?tab=data-download. I used the shp file only and uploaded the data to the shared box drive: All Files> Capstone Student> Tree Canopy Visualizations> il_tes.shp

I inserted a png image as the marker representing the user's location. Here is where the image is uploaded on/from box: All Files> Capstone Student> Tree Canopy Visualizations> Link to google drive folder with visualization contents.gdoc (click link provided in document)> PNGs for icons and pie charts> derbicustommarkerblue.png


### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```
Executing Program
How to run the program:
1.Open RStudio.
2.Create a new R script file.
3. Copy the full code from: All Files > Capstone Student > Tree Canopy Visualizations > Link to google drive folder with visualization contents.gdoc > Current Visualization > derbi_map_5
4.Paste the code into your new script in RStudio.
5. Update file paths in the code if needed:
For the shapefile:
st_read("/Users/yourusername/path/to/il_tes.shp")
file = "/Users/yourusername/path/to/derbicustommarkerblue.png"
6. Run the entire script.
7. The interactive Leaflet map will appear in the Viewer pane.
8. To save the map as an HTML file, ensure the following line runs: saveWidget(leaflet_map, "derbi_map_5.html", selfcontained = TRUE)


## Help

Any advise for common problems or issues.
If the map doesn’t display properly or an object returns as NULL, double-check the following:

-Paths to shapefile and image marker are correct and accessible.
-All required libraries are installed.
-To install missing libraries: install.packages(c("leaflet", "sf", "dplyr", "htmltools", "base64enc", "htmlwidgets"))


command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
