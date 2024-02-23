---
title: "What is Minerva?"
teaching: 10
exercises: 0
questions:
- "What is Minerva?"
- "What are the 3 main types of Minerva Stories (for the LSP)?"
- "Why do we use Minerva in the LSP (and why you should too)?"
objectives:
- "Explain what Minerva is and its components"
- "Define the 3 types of LSP Minerva Stories"
- "Discuss the role of Minerva in sharing tissue image data"
keypoints:
- "Minerva is the general term for Minerva Author and Minerva Story."
- "Minerva Author is the software tool to create Minerva Story. Minerva Story is a narrative image viewer for web hosting."
- "Minerva turns large image files into smaller ones that can be loaded as needed, allowing interactive and fast viewing in a browser."
- "You can annotate your image data when sharing with Minerva, providing important context to help the audience understand the data"
- "LSP uses Minerva to share large tissue image data, usually but not necessarily from CYCIF."
- "FIX ME a key point about different types of Minerva Stories in the LSP"
---

## What is Minerva

Minerva is a suite of light-weight software tools that enables interactive viewing and fast sharing
of large image data. It comprises Minerva Author, a tool that lets you easily create and annotate
images, and Minerva Story, a narrative image viewer for web hosting.

Minerva is built to support the image data sharing for tissue atlases and digital pathology.

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

2. **You can provide context tailored for your target audience.** Tissue image data is incredibly
   information-dense, especially for those who are not as familiar with your project. The
   introductory text and waypoint description in Minerva Stories allow you to walk your audience
   through the story of your data without physically standing next to them.

3. FIX ME something about sharing different data format? but Minerva only handles OME-TIFF?

We will go over how to leverage these three key qualities of Minerva to share your data FAIR-ly and
effectively in today's tutorial.

## 3 Main Types of Minerva Stories

At the LSP, we group our Minerva Stories into 3 main types. They are the Automated, Curated and
Narrated Minerva Stories. They each have their unique advantages, use cases and required different
amount of time to make. Today, we will practice making one of each type with the same dataset.

### Automated

Automated Stories directly uses the channel display settings Minerva recommends. FIX ME Channel
groups are formed ... by defualt. Minimal input from the author is needed.

> ## Automated Stories can also be made as a part of the MCMICRO workflow
> Check out the [MCMICRO webiste](https://mcmicro.org/overview/#visualization) for more information
> on this (FIX ME - do we have documentation on this? The MCMICRO website currently links to Wiki).
> We will not demonstrate this route in today's tutorial.
{: .callout}

### Curated

Automated Stories can become *Curated* with a few additional steps. Theses steps involve human
review for accuracy, quality and context, ensuring that the data is represented ideally and
understandable to others.

### Narrated

Narrated stories build upon Curated Stories and walk a viewer through the data. The precise purpose
and expectations vary depending on the use case. Common uses cases include a graphical abstract for
a paper, a digital figure, 'eye candy' for a grant or press, or an educational description of the
data.

FIX ME - Insert the style guide chart here?

> ## Activity | What role can Minerva play in your data sharing?
> Think of a situation where you had to share your data with anyone, a collaborator, a colleague,
> a funding agency *etc.*. If you haven't encountered a scenario yet, come up with a hypothetical
> that is meaningful for your project.
> Try to answer the following questions with the knowledge of Minerva and story types you now have:
> 1. What your goals of sharing your tissue image data? Who are your audiences?
> 2. Which type of Minerva Story would you use? Why?
{: .callout}

{% include links.md %}
