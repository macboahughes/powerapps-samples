---
page_type: sample
languages:
- powerapps-comma
products:
- power-apps
- powerapps
- canvas
name: Image Slider Component
description: This component library features a customizable image slider which can be used to display set of images.
urlFragment: powerapps-imageslider
ms.date: 09/01/2022
author: sagar vishwakarma
ms.author: pnp
level: beginner
ms.prod: power-apps
---

# Image Slider Component Library

## Summary

This component library features a customizable image slider which can be used to display set of images one by one.

![Image Slider bar in animation](./assets/image-slider.gif)  

## Applies to

* [Microsoft Power Apps](https://docs.microsoft.com/powerapps/)

## Compatibility

![Power Apps Source File Pack and Unpack Utility 0.20](https://img.shields.io/badge/Packing%20Tool-0.20-green.svg)
![Premium License](https://img.shields.io/badge/Premium%20License-Not%20Required-green.svg "Premium Power Apps license not required")
![Experimental Features](https://img.shields.io/badge/Experimental%20Features-No-green.svg "Does not rely on experimental features")
![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg "Does not use on-premise connectors")
![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-Not%20Required-green.svg "Does not use custom connectors")

## Authors

Solution|Author(s)
--------|---------
Image Slider | [Sagar Vishwakarma](https://github.com/sagar7046) 

## Version history

Version|Date|Comments
-------|----|--------
1.0|September 01, 2022|Initial release

## Features

This sample features a image slider component library which can be used inside a canvas app which takes the following inputs:

* Images: Collection of images in some specified data format which you can get from sample.json file.
* ActionButtonColor: Color of the navigation buttons
* ActionButtonBackgroundColor: Background color of the navigation buttons

## Prerequisites

None

## Data Sources

None

## Minimal Path to Awesome

* [Download](./solution/expandable-navigation.msapp) the `.msapp` from the `solution` folder
* Use the `.msapp` file using **File** > **Open** > **Browse** within Power Apps Studio.
* Save and Publish

## Using the Source Code

You can also use the [Power Apps CLI](https://docs.microsoft.com/powerapps/developer/data-platform/powerapps-cli) to pack the source code by following these steps::

* Clone the repository to a local drive
* Pack the source files back into `.msapp` file:

  ```bash
  pac canvas pack --sources pathtosourcefolder --msapp pathtomsapp
  ```

  Making sure to replace `pathtosourcefolder` to point to the path to this sample's `sourcecode` folder, and `pathtomsapp` to point to the path of this solution's `.msapp` file (located under the `solution` folder)
* Use the `.msapp` file using **File** > **Open** > **Browse** in Power Apps Studio.

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## Support

While we don't support samples, if you encounter any issues while using this sample, you can [create a new issue](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug-report.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=question.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/powerapps-samples/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=suggestion.yml&sample=expandable-navigation&authors=@luisefreese&title=expandable-navigation%20-%20).

## For more information

* [Companion blog post about this sample](https://www.m365princess.com/blogs/build-powerapps-progressbar-component/)
* [Overview of creating apps in Power Apps](https://docs.microsoft.com/powerapps/maker/)
* [Power Apps canvas apps documentation](https://docs.microsoft.com/powerapps/maker/canvas-apps/)
