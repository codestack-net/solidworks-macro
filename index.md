---
layout: master
title: 'SOLIDWORKS macro for automation: guides, examples, library'
description: Beginner friendly guides, code examples and library of VBA and VSTA macros for automation of SOLIDWORKS functionality
image: /solidworks-macro.svg
lang: en
permalink: "/"
---
# SOLIDWORKS VBA and VSTA Macro Overview

![SOLIDWORKS Macro](solidworks-macro.svg)

This resource is managed by [Code Stack](https://www.codestack.net) and dedicated to providing easy-to-follow beginner friendly guides for automation of your SOLIDWORKS routine with VBA and VSTA macros.

SOLIDWORKS macro is the most popular way for complimenting SOLIDWORKS functionality via SOLIDWORKS API.

SOLIDWORKS enables macro creation in 3 popular programming languages:

* VBA - the most common language for writing macros. This language is based on popular Visual Basic. Macro is saved in *.swp or *.swb format and it is both executable and source code.
* C# and VB.NET - powered by Microsoft's Visual Studio for Applications (VSTA) technology. This option enables writing the powerful object-oriented macros in the .NET technology. Macro project is saved as *.csproj or *.vbproj projects. Macro executable is a compiled *.dll with referenced SOLIDWORKS interops.

For more information visit [Macro Types](https://www.codestack.net/solidworks-api/getting-started/macros/types/) page.

## Visual Basic for Applications

Visual Basic for Applications (VBA) is the most popular language for writing SOLIDWORKS macros. It has a similar syntax to the macro in other applications, such as MS Word, Excel or other CAD Systems. Current version of VBA supported in macros is 7.0.

Follow the [Visual Basic](https://www.codestack.net/visual-basic/) link for detailed tutorials and code examples.

## Recording Macros

Macro recording is a simplest way to start exploring of SOLIDWORKS macro functions. Majority of commands executed by SOLIDWORKS can be recorded as a macro command. This enables the possibility to explore SOLIDWORKS API calls and parameters.

Both VBA and VSTA macro can be recorded. Follow [Recording Macros](https://www.codestack.net/solidworks-api/getting-started/macros/recording/) article for a detailed guide of recording the macros.

## Troubleshooting

Although macro is a software which is written using programming language, it is usually managed by engineers and administrators with beginner level of programming. So troubleshooting the macro to fix the error can be a frustrating routine.

Follow the [Macros Troubleshooting: Issues And Resolutions](https://www.codestack.net/solidworks-api/troubleshooting/macros/) section for the list of solutions for the most common macro errors, such as:

* Run-time Error '91': Object variable or With block variable not set
* Run-time error '424': Object required
* Run-time error '13': Type mismatch
* Inconsistent Selections in SOLIDWORKS document
* SOLIDWORKS file title and extension

and much more...

## Macro Library

### Delete All Equations

This macro removes all equations from SOLIDWORKS model.

[Get Macro](https://www.codestack.net/solidworks-api/document/delete-model-equations/)

### Remove All Colors From Part

Colors can be assigned to multiple entities in the SOLIDWORKS document (component, face, feature, body). And it might be challenging to remove the color from the part. This macro removes all the colors from all levels in SOLIDWORKS part document.

[Get Macro](https://www.codestack.net/solidworks-api/document/appearance/remove-color/)

### Copy Custom Property From Material To Model

Custom materials is a good way to support additional materials with additional properties for your SOLIDWORKS file. Unfortunately custom materials properties cannot be queried from the document BOM tables or annotations. This macro allows copying the material custom properties into SOLIDWORKS custom properties.

[Get Macro](https://www.codestack.net/solidworks-api/document/materials/copy-custom-property/)

### Suspend Rebuild Operation

This macro allows to enhance SOLIDWORKS performance by temporarily disabling rebuild operations. This is very useful when sequence of operations needs to be performed in the large model and regeneration of each operations decreases the performance.

[Get Macro](https://www.codestack.net/solidworks-api/document/suspend-rebuild/)

### Break All External References For Components

Macro breaks all external references for the components in the assembly with single click. This allow to increase performance by disabling external links resolution.

[Get Macro](https://www.codestack.net/solidworks-api/document/assembly/components/break-external-references/)

### Move To Folder

This macro provides a single click function to move components selected in the graphics area in new feature folder. This enhances the built-in functionality of SOLIDWORKS allowing the selection of entities in the model view (not only in the feature manager tree).

[Get Macro](https://www.codestack.net/solidworks-api/document/assembly/components/move-to-folder/)

### Copy File Specific Custom Properties To Configuration Properties

Configuration specific property is a way to override the metadata assigned to a part on configuration level. This macro copies the properties and values from file level to configuration level.

[Get Macro](https://www.codestack.net/solidworks-api/data-storage/custom-properties/copy-file-specific-to-configuration/)

### Animate Configurations

This macro create a motion study animation between the configurations. This macro can be used to animate the sheet metal bending in SOLIDWORKS part.

[Get Macro](https://www.codestack.net/solidworks-api/motion-study/animate-configurations/)

### Close All Documents Except Active

This macro provides a single click way to close all documents except of the active one.

[Get Macro](https://www.codestack.net/solidworks-api/application/frame/close-all-documents-except-active/)

For more macros visit the [Macro Library](https://www.codestack.net/solidworks-tools/) link.