---
layout: main
title: 'SOLIDWORKS macro for automation: guides, examples, library'
description: Beginner friendly guides, code examples and library of VBA and VSTA macros for automation of SOLIDWORKS functionality
lang: en
sections: 
    overview:
        title: SOLIDWORKS VBA and VSTA Macro Overview
        icon_alt: SOLIDWORKS Macro
    vba:
        title: Visual Basic for Applications
        icon_alt: Visual Basic for Application
    recording:
        title: Recording Macros
        icon_alt: Macro recording toolbar
    troubleshooting: 
        title: Troubleshooting
        icon_alt: Troubleshooting SOLIDWORKS VBA and VSTA macros
    library:
        title: Macro Library
        icon_alt: Library of SOLIDWORKS VBA and VSTA macros
        featured:
            - title: Delete All Equations
              url: https://www.codestack.net/solidworks-api/document/delete-model-equations/
              summary: This macro removes all equations from SOLIDWORKS model

            - title: Remove All Colors From Part
              url: https://www.codestack.net/solidworks-api/document/appearance/remove-color/
              summary: Colors can be assigned to multiple entities in the SOLIDWORKS document (component, face, feature, body). And it might be challenging to remove the color from the part. This macro removes all the colors from all levels in SOLIDWORKS part document

            - title: Copy Custom Property From Material To Model
              url: https://www.codestack.net/solidworks-api/document/materials/copy-custom-property/
              summary: Custom materials is a good way to support additional materials with additional properties for your SOLIDWORKS file. Unfortunately custom materials properties cannot be queried from the document BOM tables or annotations. This macro allows copying the material custom properties into SOLIDWORKS custom properties

            - title: Suspend Rebuild Operation
              url: https://www.codestack.net/solidworks-api/document/suspend-rebuild/
              summary: This macro allows to enhance SOLIDWORKS performance by temporarily disabling rebuild operations. This is very useful when sequence of operations needs to be performed in the large model and regeneration of each operations decreases the performance

            - title: Break All External References For Components
              url: https://www.codestack.net/solidworks-api/document/assembly/components/break-external-references/
              summary: Macro breaks all external references for the components in the assembly with single click. This allow to increase performance by disabling external links resolution

            - title: Move To Folder
              url: https://www.codestack.net/solidworks-api/document/assembly/components/move-to-folder/
              summary: This macro provides a single click function to move components selected in the graphics area in new feature folder. This enhances the built-in functionality of SOLIDWORKS allowing the selection of entities in the model view (not only in the feature manager tree)

            - title: Copy File Specific Custom Properties To Configuration Properties
              url: https://www.codestack.net/solidworks-api/data-storage/custom-properties/copy-file-specific-to-configuration/
              summary: Configuration specific property is a way to override the metadata assigned to a part on configuration level. This macro copies the properties and values from file level to configuration level

            - title: Animate Configurations
              url: https://www.codestack.net/solidworks-api/motion-study/animate-configurations/
              summary: This macro create a motion study animation between the configurations. This macro can be used to animate the sheet metal bending in SOLIDWORKS part
              
            - title: Close All Documents Except Active
              url: https://www.codestack.net/solidworks-api/application/frame/close-all-documents-except-active/
              summary: This macro provides a single click way to close all documents except of the active one
---