---
date: 2021-06-16
title: "Report: AI in Orthodontics"
linkTitle: Orthodontics
tags: ["report", "reu", "ai", "health"]
description: "In this effort we are analyzing X-ray images in AI and identifying cavitites"
author: Whitney, McNair
github_url: https://github.com/cybertraining-dsc/su21-reu-363/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---


[![Check Report](https://github.com/cybertraining-dsc/su21-reu-363/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-363/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-363/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-363/actions)
Status: final, Type: Report


Whitney McNair, [su21-reu-363](https://github.com/cybertraining-dsc/su21-reu-363), [Edit](https://github.com/cybertraining-dsc/su21-reu-363/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

In this effort we are analyzing X-ray images in AI and identifying cavitites

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** ai, orthodontics, x-rays. 

## 1. Introduction

Dental field technology capability has increased over the past 25 years, and has helped reduce time, cost, medical errors, and dependence on human expertise. Intelligence in orthodontics can learn, build, remember, understand and recognize designs from techniques used in correcting the teeth like retainers. Dental field can create alternatives, adapt to change and explore experiences with sub-groups of patients. AI has taken part of the dental field by accurately and efficiently processing the best data from treatments. For smart use of Health Data, machine learning and artificial intelligence are expected to promote further development of the digital revolution in (dental) medicine, like x-rays, using algorithms to simulate human cognition in the analysis of complex data. The performance is better, the higher the degree of repetitive pattern and the larger the amount of accessible data[^5].

## 2. Data Sets

We found a dataset on a kaggle website that is about dental images. The data was collected by Mr. Parth Chokhra. The name of the dataset is Dental Images of kjbjl. The dataset did not have metadata and an explanation of how they collected the data. The data set supports how x-rays of teeth in dentistry becomes artificial intelligence. The Dental Images of kjbjl dataset was used in AI already using autoencoders. Autoencoders are an freely artificial neural network (located in the nervous system) that learns how to accurately encode data and reconstruct the data back from the reduced encoded depiction to a representation that is closes to the original. For some challenges with Orthodontics data sets with privacy, size, avalibility were surprisingly hard to find than we thought.

## 3. Figures

Below we observed actual dental x-rays. These dental x-rays images below came from Parth Chorkhra on kaggle.com [^1]. The images are patient x-rays taken by Parth in his dental imagery data set. In the images we can see the caps and nerves of the teeth. Using these x-rays, we may can also find cavities if there are some. We can also identify other issues with patients teeth by taking and using x-rays.

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-363/raw/main/project/images/figure-1.jpg)

**Figure 1:** First x-ray

![Figure 2](https://github.com/cybertraining-dsc/su21-reu-363/raw/main/project/images/figure-2.jpg)

**Figure 2:** Second x-ray

![Figure 3](https://github.com/cybertraining-dsc/su21-reu-363/raw/main/project/images/figure-3.jpg)

**Figure 3:** Third x-ray

## 4. Example of a AI algorighm in Orthodontics

On a separate kaggle website, we found a code for DENTAL PANORAMIC KNN [^5]. The kaggle site shows dental codes taken place in Orthodontics.

## 5. Benchmark
 
Here is an algorithm/code from one of the researchers we found. are using to study the performance of their algorithms or code.
 
Lateral and frontal facial images of patients who visited the Orthodontic department (352 patients) were employed as the training and evaluation data. An experienced orthodontist examined all the facial images for each patient and identified as many clinically used facial traits during the orthodontic diagnosis process as possible (e.g., deviation of the lips, deviation of the mouth, asymmetry of the face, concave profile, upper lip retrusion, presence of scars). A sample patient’s image, a list of sample assessments (i.e., labels), and the multi-label data used in the work by Murata et al. are shown in Figure 4.
 
![Figure 4](https://github.com/cybertraining-dsc/su21-reu-363/raw/main/project/images/figure-4.jpg)

**Figure 4:** Sample patient’s image and a list of sample assessments (i.e., labels) including the region of interest, evaluation, etc. In a previous study by Murata et al., they employed labels representing only the facial part (mouth, chin, and whole face), distorted direction (right and left), and its severity (severe, mild, no deviation).
 
## 6. Conclusion

Artificial intelligence is rapidly expanding into multiple facets of society. Orthodontics may be one of the fastest branches of dentistry to adapt AI for three reasons. First, patient encounters during treatment generate many types of data. Second, the standardization in the field of dentistry is low compared to other areas of healthcare. A range of valid treatment options exists for any given case. Using AI and large datasets (that include diagnostic results, treatments, and outcomes), one can now measure the effectiveness of different treatment modalities given very specific clinical findings and conditions. Third, orthodontics is largely practiced by independent dentists in their own clinics. Despite the promise of AI, the volume of orthodontic research in this field is relatively low. Further, the clinical accuracy of AI must be improved with an increased number and variety of cases. Before AI can take on a more important role in making diagnostic recommendations, the volume and quality of research data will need to increase[^5].

## 7. Acknowledgments

Dr. Gregor von Laszewski, Carlos and Yohn guided me throughout this process.
 
## 8. References

[^1]: Chokhra, P. (2020, June 29). Medical image dataset. Kaggle. <https://www.kaggle.com/parthplc/medical-image-dataset>

[^2]: EMBRACING NOVEL TECHNOLOGIES IN DENTISTRY AND ORTHODONTICS. (n.d.). <https://deepblue.lib.umich.edu/bitstream>

[^3]: DivyaSwarup, DeepakSingh, SinghSwarndeep, AhmadNaeem, SahaiRicha .Artificialintelligence(A.I.) Inorthodontics. JournalofScience ,2017 ;7(9) :304 -307

[^4]: S. Murata, C. Lee, C. Tanikawa and S. Date, "Towards a Fully Automated Diagnostic System for Orthodontic Treatment in Dentistry," 2017 IEEE 13th International Conference on e-Science (e-Science), 2017, pp. 1-8, doi: 10.1109/eScience.2017.12.

[^5]: Hasnitadita. (2021, July 10). DENTAL panoramic knn. Kaggle. <https://www.kaggle.com/hasnitadita/dental-panoramic-knn>

[^6]: The challenge of eHealth data in Orthodontics. Define_me. (n.d.). <https://www.ajodo.org/article/S0889-5406(20)30801-5/fulltext>
