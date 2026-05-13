---
author: safa bamatraf
title: "Inspirations of Umayyad Architecture"
layout: base
header-image: images/mshatta-arches.webp
header-image: center 30%
thumbnail: images/mshatta-arches.webp
summary: Umayyad architecture is a relfection of their early ruling methods.
---

# Monasteries: The More Sophisticated Type of Webpage

This essay demonstrates **intermediate ScrollStory features**—building on what you learned in Seedling by adding scrollyboxes, carousels, and more sophisticated visual storytelling. As you scroll, we'll point out what makes this more advanced than a Seedling essay.

**What makes this a "Sapling" essay?** It includes everything from Seedling (headings, images, footnotes, pull quotes) plus immersive components: text overlaying background images, image carousels for comparisons, and more dynamic pacing. This is where ScrollStories start feeling cinematic.

The text below includes both explanations and filler content to show how these components work in practice.


## Building on Seedling Basics
{% include images/figure.html
class="right"
width="48%"
caption="Right-aligned images still work exactly like Seedling. You already know this pattern. [Source](https://commons.wikimedia.org/wiki/File:Khiva_town_of_The_Silk_Road_(%D0%9A%D0%B0%D1%80%D0%B0%D0%B2%D0%B0%D0%BD,_%D0%98%D1%87%D0%B0%D0%BD_%D0%9A%D0%B0%D0%BB%D0%B0,_%D0%A5%D0%B8%D0%B2%D0%B0).jpg)"
image-path="images/ota-gate-khiva2.jpg"
%}

Everything from Seedling still works here: images with captions, footnotes, section headings.[^note1] The Sapling template doesn't replace what you learned—it **adds** to it.

[^note1]:Footnotes continue to work exactly as before. All your Seedling skills carry forward.

This layered approach is intentional. Master the basics, then add complexity incrementally. You're not learning a whole new system; you're expanding your toolkit with a few powerful new components.[^randomthing]

[^randomthing]:Put your source information here.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus pretium, nibh vel posuere pretium, neque ipsum maximus libero, ac maximus quam ante sit amet dolor. Integer pharetra semper sem sed sagittis. Curabitur mauris tortor, elementum non felis id, hendrerit efficitur metus.


## Your First Scrollybox
Here's what makes Sapling different: keep scrolling and watch what happens next. You're about to see text appear **over** a background image, creating an immersive reading experience.

{% include scrollybox/bg.html
  image-path="images/ota-gate-khiva2.jpg"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' A sculpture in Khiva offers a romaticized view of the Silk Road trade network.'
%}


## Juxtapose: Before/After Comparisons
Below you'll see a **juxtapose component**—an interactive slider that lets readers compare two images by dragging a handle left and right. Perfect for before/after, then/now, or any two related images.

{% include images/juxtapose.html
image1="images/ota-gate-demo-brown.png"
image2="images/ota-gate-demo-gray.png"
caption="Two shades of color on the Ota Gate."
%}

**Why use juxtapose?** When you want readers to actively explore the relationship between two images. The interactive slider invites engagement—readers control what they see and how much of each image.

**Use cases:**
- Historical photos showing change over time
- Different views of the same location
- Comparing historical documents or maps
- Revealing differences that might be subtle

Praesent sed vehicula velit, vel hendrerit neque. Vivamus scelerisque sed nunc nec congue. Curabitur sapien risus, finibus id tincidunt iaculis, porta et ipsum.

---

## Bibliography

- Lastname, Firstname. “Title of the Article.” *Title of the Journal* 9, no. 9 (1999): 999–999.
- Lastname, Firstname. *Title of the Book*. Publisher Press, 1999.