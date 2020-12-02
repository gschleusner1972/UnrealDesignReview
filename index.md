---
//typora-root-url: ./
---

## Unreal Design Review for AEC (WIP)

### Why?

The design process in AEC has been generating 3D models for many years.  These models come from BIM tools like Revit, ArchiCAD or BricsCAD BIM or modelers like Sketchup or Rhino.    Its always been a challenge to easily merge these models in a way enables designers to compare options, review materials, generate analysis or do simple things like early clash detection.  

There are tools made for clash detection, separate tools for exploring materials, still others for generating  analysis.   These tools go largely under utilized in the design process because no platform has made it easy to export data, assemble models and at the same time bring together disparate tools to view, review, clash, analyze etc.   

### Enter Unreal

In recent years Unreal engine and the tooling to support better AEC workflows have advanced to the point where its now possible to start to build such a tool(s). 

#### Datasmith

Datasmith enables easy translation of model data into Unreal.  This includes materials and geometry, but also properties and attributes like parameters, layers, descriptions from the modeling tools etc.  With this data its possible to enable data driven tools.  Like searching for all "Columns" and clashing them with walls or simply setting a color by layer.

<img src="/LayerColor2.gif" alt="LayerColor2" style="zoom:80%;" />



With the other features around Datasmith in active development that will make it even easier to keep a game updated for a project and thus enabling other kinds tools to be build on top of Unreal.

#### Dataprep

#### Point Cloud Support

#### Pixel Streaming

#### Collaboration

<img src="/SectionGif.gif" alt="SectionGif" style="zoom:67%;" />





A
