---
title: "MassHunter Profinder"
date: 2021-11-01T17:33:00-07:00
description: "A fast, batch-processing feature extraction software for differential analysis of mass spectrometry data"
fact: "A parallelized C# .NET application for naive and targeted feature extraction."
featured: true
image: "/img/profinder.png"
link: "https://www.agilent.com/cs/library/usermanuals/public/G3835-90027_Profinder_QuickStart.pdf"
tags: ["Agilent", "MassHunter", "mass spectrometry", "feature extraction", "C#"]
weight: 500
sitemap:
  priority: 0.8
---

I had gotten the idea for a batch feature extraction software at [ASMS 2009](https://www.agilent.com/Library/technicaloverviews/Public/5991-3947EN.pdf), where I had presented a poster on a [new untargeted feature extraction methodology](https://www.agilent.com/Library/technicaloverviews/Public/5991-3947EN.pdf) I had developed. After showing the poster at the conference, several customers articulated to me how valuable it would be to have a dedicated batch feature extraction software workflow. I was so excited by the idea that I started writing the prototype for such an application on the airplane ride back! After a few days, after demonstrating the prototype and idea to the metabolomics marketing manager, he commented "you need to definitely hang onto that. This could be the next big thing."

In 2012, driven by a related prototype to improve batch visualization and editing of feature extraction data, I got the green light to productionize what would eventually become MassHunter Profinder. I wore many hats during its one year development, including architect, developer, scientist and Scrum Master. I partnered with an engineer in India, where we effected a 24-hour development cycle to get the job done.

![MassHunter Profinder B.06.00 - the first release in 2013](/img/profinder.png "MassHunter Profinder B.06.00 - circa 2013")

We launched our first release of Profinder at the [2013 ASMS conference](https://www.agilent.com/cs/library/posters/public/ASMS_2013_MP_379_Kitagawa_Novel_Two-Pass_Feature_Extraction_Workflow_for_Statistical_Profiling_of_MS_Data.pdf). I gave a 20 minute presentation with live software demo to 200+ conference attendants at our vendor "Lunch-and-Learn" session. The first version of software we released was buggy but extremely capable and very well received by our customers. Profinder would continue to mature over the years through multiple major versions to become a central part of the 'omics workflow for Agilent.
