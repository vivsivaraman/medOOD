---
layout: homepage
---

# Summary
<p align="justify">
We focus on producing well-calibrated out-of-distribution (OOD) detectors for safe deployment of medical image classifiers. Synthetic augmentations have become prevalent for inlier/outlier specification, but our research reveals that the synthesis space and augmentation type significantly impact OOD detector calibration. Through empirical studies on medical imaging benchmarks, we demonstrate that our approach of synthesizing latent-space inliers and diverse pixel-space outliers consistently outperforms state-of-the-art methods, improving OOD detection across various open-set recognition settings.
</p>

# Video
<p align="justify">
To be posted
</p>
<!-- {% include add_video.html 
    youtube_link="https://www.youtube.com/embed/2bQwT548NFI" 
%} -->


# Method

{% include add_image.html 
    image="assets/img/approach.png"
    caption="" 
    alt_text="Alt text" 
%}


<div style="font-size:18px">
  <ol type="a">
  <p align="justify">
  <li><strong>Training:</strong> Train the medical image classifier along with the appropriate calibration protocol i.e latent-space inliers & pixel-space outliers.</li>
  <li><strong>OOD Detection:</strong> Use an energy based OOD detector to distinguish between ID and OOD (Modality Shifts / Novel Classes) and compute the performance metrics for e.g., AUROC</li>
  </p>
</ol>
</div>


<!-- {% include add_image.html 
    image="assets/img/website-fig-teaser.png"
    caption="Examples of synthetic data generated using SiSTA. <strong>Please follow the link by clicking the image</strong> to access additional examples for different benchmarks and distribution shifts." 
    alt_text="Alt text" 
    link="https://icml-sista.github.io/"
    height="400"
%} -->



# Empirical Results


{% include add_gallery.html data="results" %}



# Citation

{% include add_citation.html text="@inproceedings{narayanaswamy2023know,
title={Know Your Space: Inlier and Outlier Construction for Calibrating Medical {OOD} Detectors},
author={Vivek Narayanaswamy and Yamen Mubarka and Rushil Anirudh and Deepta Rajan and Andreas Spanias and Jayaraman J. Thiagarajan},
booktitle={Medical Imaging with Deep Learning},
year={2023}}" %}


# Contact
If you have any questions, please feel free to contact us via email: {{ site.contact.emails }}
