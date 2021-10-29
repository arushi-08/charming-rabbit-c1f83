---
title: Hate Speech Detection in Hindi-English Code-mixed Text
subtitle: Accepted Work in IPM (SCI Journal)
date: '2019-05-10'
thumb_image: images/freehatespeech.jpg
thumb_image_alt: 'White, black, and red shoe sole'
image_alt: 'White, black, and red shoe sole'
seo:
  title: Project Title 1
  description: This is the project 1 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 1
      keyName: property
    - name: 'og:description'
      value: This is the project 1 description
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 1
    - name: 'twitter:description'
      value: This is the project 1 description
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: project
---
**Abstract:** Social media has become a bedrock for people to voice their opinions worldwide. Due to the greater sense of freedom with the anonymity feature, it is possible to disregard social etiquette online and attack others without facing severe consequences, inevitably propagating hate speech. The current measures to sift the online content and offset the hatred spread do not go far enough. One factor contributing to this is the prevalence of regional languages in social media and the paucity of language flexible hate speech detectors. The proposed work focuses on analyzing hate speech in Hindi-English code-switched language.

This work explores transformation techniques to capture precise text representation. To contain the structure of data and yet use it with existing algorithms, I develop MoH or Map Only Hindi, which means "Love" in Hindi. MoH pipeline consists of language identification, Roman to Devanagari Hindi transliteration using a knowledge base of Roman Hindi words. Finally, it employs the fine-tuned Multilingual Bert and MuRIL language models. I conducted several quantitative experiment studies on three datasets and evaluated performance using Precision, Recall, and F1 metrics. The first experiment studies MoH mapped text's performance with classical machine learning models and shows an average increase of 13% in F1 scores. The second compares the proposed work's scores with those of the baseline models and offers a rise in performance by 6%. Finally, the third reaches the proposed MoH technique with various data simulations using the existing transliteration library. Here, MoH outperforms the rest by 15%. Our results demonstrate a significant improvement in the state-of-the-art scores on all three datasets.





