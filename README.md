﻿![Image](clockwork-logo.png)

Clockwork is a collection of custom nodes for the [Dynamo](http://www.dynamobim.org) visual programming environment. It contains many Revit-related nodes, but also lots of nodes for various other purposes such as list management, mathematical operations, string operations, unit conversions, geometric operations (mainly bounding boxes, meshes, planes, points, surfaces, UVs and vectors) and paneling. Currently it consists of some 370+ nodes of which a large portion was previously published in a number of separate packages. My reasoning is that keeping all nodes in a single package will make updates easier and reduce package dependencies. I had never set out to build so many custom nodes – somehow it just happened.

If you like the package, please vote in support of it in Dynamo's package search tool. 

##Installation
Installation is simple - just use Dynamo's built-in package manager and search for ```Clockwork```. If you have used some of my previous 0.6.3 packages, please remember to uninstall *all* of them (find a complete list [here](https://github.com/CAAD-RWTH/ClockworkForDynamo/wiki/0.6.3-Packages-to-Uninstall)). Also, always make sure you have the correct version of Clockwork installed that corresponds to your installed version of Dynamo.

##Versions
- Clockwork for Dynamo 0.8.2: [0.82.2](https://github.com/CAAD-RWTH/ClockworkForDynamo/wiki/Version-History#0822)
- Clockwork for Dynamo 0.7.x: [0.75.47](https://github.com/CAAD-RWTH/ClockworkForDynamo/wiki/Version-History#07547) - not supported any more
- Clockwork for Dynamo 0.6.3: [0.63.3](https://github.com/CAAD-RWTH/ClockworkForDynamo/wiki/Version-History#0633) - not supported any more

##Renamed, recategorized and deprecated nodes
During migration from one Dynamo versuion to the next, I regularly recategorize and rename a lot of nodes. These changes are documented in an [excel sheet](https://github.com/CAAD-RWTH/ClockworkForDynamo/raw/master/NodeList.xls) that contains a list of all nodes within the package. Nodes with [pending issues](https://github.com/CAAD-RWTH/ClockworkForDynamo/issues) are highlighted in yellow.
If you are missing a specific node, please consult the [list of deprecated nodes](https://github.com/CAAD-RWTH/ClockworkForDynamo/wiki/Deprecated-Nodes).

##Updates
Since Dynamo's package manager currently does not (yet) have an update notification infrastructure in place, you may want to follow me on [twitter](https://twitter.com/a_dieckmann) for update notifications.

##Known Issues
On this repository you can find a [list of known issues and planned enhancements](https://github.com/CAAD-RWTH/ClockworkForDynamo/issues). Should you find that one of the nodes in this package does not work (or could work better with improved functionality), please let me know by creating a new issue in that section. Also, if you happen to come across a built-in node that does exactly the same as one of the Clockwork nodes, please let me know so I can remove that particular node from the package - I am not trying to duplicate existing functionality.

##Material on this repository

This repository contains the following:
- Directory [package_samples](package_samples) contains simple examples for most of the nodes in Clockwork. I use them for occasional testing, but they should also help explain how to use each node. I have started to migrate all the samples to 0.7.x, but this process is not yet complete. If you cannot find a sample for a particular node, have a look at the 0.6.3 samples instead (they are, however, sorted according to their previous packages).
- Directory [workflow_samples](workflow_samples) contains some sample workflows that I have published online somewhere before. I have also started to include some of the examples that I use for teaching Dynamo as well as some material presented at conferences. Almost all of these are available for Dynamo 0.7.x (as well as 0.6.3).
- Directory [nodes](nodes) is the actual repository of the custom nodes that I use for versioning nodes in between publishing package updates to Dynamo's package manager - which means you will sometimes find nodes in here that haven't made it onto the package manager yet.
- Directory [issues](issues) contains sample files for issues raised on the [Dynamo GitHub site](https://github.com/DynamoDS/Dynamo).

##Help to improve Clockwork
If you're interested in contributing to Clockwork, just submit a [pull request](https://github.com/CAAD-RWTH/ClockworkForDynamo/pulls). It's not that hard - [some folks](https://github.com/CAAD-RWTH/ClockworkForDynamo/graphs/contributors) have already done it. 
