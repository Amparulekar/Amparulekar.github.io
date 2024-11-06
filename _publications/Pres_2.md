---
title: "A Computer Vision Pipeline for Laryngoscopic Image Standardization through Histogram Matching"
collection: publications
ispaper: "no"
permalink: /publication/6
excerpt: 'A preprocessing pipeline for larynogoscopic videos that includes removal of unusable frames, illumination correction, specularity removal and finally color transfer to a target intensity distribution.'
date: 2024-05-16
venue: 'Poster presented in the 145th American Laryngological Association meet (COSM), Chicago'
slidesurl: 'https://medcvr.utm.utoronto.ca/ala2024-histogrammatching.html'
citation: 'Parulekar A., Wiercigroch J., Kahrs L. A. and Lin R. J. (2024). A Computer Vision Pipeline for Laryngoscopic Image Standardization through Histogram Matching.'
---

Objectives: Endoscopic light and recording towers can create inconsistent lighting and color variation during laryngoscopies, posing obstacles for current diagnosis and treatment planning. We propose a computer vision pipeline for standardizing laryngoscopic pictures, which would allow for better treatment planning, consistent data collecting, and comparison across examinations and visits. 

Methods: Twenty movies of 14 patients were captured using two laryngoscopes with halogen and strobe lighting. Stills from these videos were retrieved and combined with publically available laryngoscopic images. Following preprocessing, photos were divided into bins based on color similarity, and two intensity thresholds were set for each bin to improve dark pixels and over-illuminated areas. Histogram matching was utilized to turn the photos into the target pixel intensity distribution by comparing them to the average histogram from a specific bin. The correlation between each image and the target histogram was measured before and after histogram matching to assess color transformation. 

Results: Image enhancement and histogram matching improved the correlation for 471 of the 504 photos altered, indicating a better connection with the target histogram. The pipeline normalized our own data correlations so that 96% of photos were within the required bin range. 

Conclusion: Our pipeline enhanced image quality and standardized the pixel intensity distribution across light sources and laryngoscopes. Standardizing laryngoscopic images has the potential to improve diagnosis and treatment planning in clinical routines or to create standardized datasets for artificial intelligence tasks. 
