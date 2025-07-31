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

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
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
