# fiftyone-Voxel-Edit-Label-plugin
It contains the Edit label attributes plugin for the voxel tool fiftyone

# Label attribute editor
This plugin allows you to edit the attributes of selected labels in the FiftyOne App.


# Installation
fiftyone plugins download https://github.com/ehofesmann/edit_label_attributes

Refer to the main README for more information about managing downloaded plugins and developing plugins locally.

# Run Example
After installing this plugin, you can try the example yourself on the quickstart dataset.

import fiftyone as fo
import fiftyone.zoo as foz

dataset = foz.load_zoo_dataset("quickstart")
session = fo.launch_app(dataset)

Click on the first image to expand it in the sample modal, select one of the labels, then click the Edit label button.
