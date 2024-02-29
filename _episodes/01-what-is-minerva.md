---
title: "What is Minerva?"
teaching: 10
exercises: 0
questions:
- "What is Minerva?"
- "Why do we use Minerva in the LSP?"
objectives:
- "Explain what Minerva is"
- "Discuss why is Minerva used in sharing tissue image data"
keypoints:
- "Minerva is the general term for Minerva Author and Minerva Story."
- "Minerva Author is the software tool to create Minerva Story. Minerva Story is a narrative image viewer for web hosting."
- "Minerva turns large image files into smaller ones that can be loaded as needed, allowing interactive and fast viewing in a browser."
- "You can annotate your image data when sharing with Minerva, providing important context to help the audience understand the data"
- "LSP uses Minerva to share large tissue image data, usually but not necessarily from CYCIF."
---

## What is Minerva

Minerva is a suite of light-weight software tools that enables interactive viewing and fast sharing
of large image data. It comprises Minerva Author, a tool that lets you easily create and annotate
images, and Minerva Story, a narrative image viewer for web hosting.

Minerva is built to support the image data sharing for tissue atlases and digital pathology. LSP uses Minerva to share large tissue image data, usually but not necessarily from CYCIF.

## Why Minerva?

You may ask why do we need another software tool to show people my image data?

Sharing your data can mean a different set of goals at different stages of our research and as the
audience changes.

If you need to show a whole slide tissue image to a coworker who sits in the same office, it is easy
to call them over to look at the already loaded image on your OMERO account. You might provide
minimal explanation if they have been following your project closely, or you may offer more verbal
context and point out areas of interest if they are new to your data. Imaging sharing the same
tissue image with someone at a different institute, there are many more barriers in place, like
obtaining credientials, long buffering time for large images, lack of guidance as they view the
image etc. Minerva is the solution to these challenges:

1. **Minerva lets you share large images fast** - for the viewer, there's no download needed and
   minimal loading time when you zoom and pan around the image.

2. **You can provide context tailored for your target audience.** - Tissue image data is incredibly
   information-dense, especially for those who are unfamiliar with your project. The
   introductory text and waypoint description in Minerva Stories allow you to walk your audience
   through your data anytime and anywhere.
   
3. **No need for specialized software to open proprietary file formats** - Minerva Stories can be viewed directly in your browser. 
   Minerva takes OME-TIFF images and converts them into JPEGs to be viewed. In the LSP, most our images are in alreayd OME-TIFFs. If you are working with different image formats, [BioFormats](https://www.openmicroscopy.org/bio-formats/) can convert other them into OME-TIFFs.

We will go over how to leverage these three key qualities of Minerva to share your data FAIR-ly and
effectively in today's tutorial.

{% include links.md %}
