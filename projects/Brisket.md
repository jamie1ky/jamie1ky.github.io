---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Brisket"
date: 2025-06-01
published: true
labels:
  - Educational
  - 
  - C++
summary: "I built a BBQ website as part of my System Design class, taking the idea from concept to a working site. Starting with limited coding experience, I learned HTML, CSS, and GitHub version control while designing pages that cover brisket prep, cooking, and serving. Along the way I created diagrams, documented requirements, and overcame challenges with styling, file paths, and deployment. The project not only taught me technical skills but also gave me confidence in managing a full development cycle."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

My BBQ Website was created as a step-by-step guide for cooking brisket, designed to be both practical and easy to navigate. The site includes dedicated pages for preparation, cooking, and serving, with each section breaking down techniques and tips in a straightforward way. I wanted the design to be clean and approachable, so I focused on simple navigation, readable text, and visuals that highlight the cooking process.

Behind the scenes, the project was built using HTML and CSS, with GitHub providing version control and hosting. Along the way, I implemented features like multimedia elements, diagrams, and organized layouts to make the content engaging. What started as a class project became a complete site that combines my interest in technology with my love of BBQ.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
