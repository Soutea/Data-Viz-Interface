# Data-Viz-Interface

This interface is designed with the D3.js library. Please see the documentation for further details about code syntax and functionality: https://github.com/d3/d3/wiki 

## Data
This folder is updated to only consist of json-files, which is the choice of data format used for the visualizations.

- oxygen.json: *A very basic mocked flow from https://www.mockaroo.com/schemas/new*
- db_flow1.json: *A more realistic attempt on a mocked database flow.*
- db_flow2.json: *Another version of a mocked database flow.*

## Graphs
Each file in this folder has code-comments for guiding. In case the code is unfamiliar or difficult to follow, please look at the documentation. In order to preview the graphs (Not a completed styling!), visit https://soutea.github.io/Data-Viz-Interface/ and add the path to the wanted version. For example, if graph_1.html will be viewed, visit https://soutea.github.io/Data-Viz-Interface/Graphs/graph_1.html

- graph_1.html: *This graph has hardcoded values and is based on the data found in oxygen.json*
- graph_2.html: *This graph has hardcoded values and is based on the data found in db_flow2.json*
- graph_generic.html: *This graph has a generic approach and is not available to preview without further customization.*
- graph_animated.html: *This graph is slightly outdated and belongs to an older prototype. Has working transitions, allowing a dynamic toggling.*

## Cloning the interface
Feel free to clone and use the repository as you wish. If another data flow is to be bound, just replace the link to another hosted GitHub-link with the provided data. Remember to re-bound the labels of the new data flow to the scatter points. If the hardcoded version of the interface is to be used, adapt the axes to show the correct time interval. In the case where the generic interface will be used, the axes do not need to be changed and will match accordingly. Note that the generic interface requires jQuery to work. For more information, contact **@Soutea.**
