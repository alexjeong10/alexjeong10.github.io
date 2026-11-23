---
layout: about
title: Home
permalink: /
subtitle:

profile:
  align: left
  image: myphoto.JPG
  image_circular: false
  more_info: >
    <p>
      <a href="mailto:alexjeong10@yonsei.ac.kr">
        alexjeong10@yonsei.ac.kr
      </a>
    </p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

## About Me

Welcome! I am a Master's student in Statistics and Data Science at Yonsei University, advised by Prof. Kibok Lee ([ML lab](https://ml.yonsei.ac.kr/)).

## Research Areas

My research primarily focuses on deep learning. I am interested in understanding the gap between the ideal or optimal states of deep learning models and their actual behaviors!

- Representation Learning
  
- Vision-Language Models (VLMs)
  
- Multimodal Large Language Models (MLLMs)

## Education

**M.S. in Statistics and Data Science, Yonsei University (Present)**

Advisor: Prof. [Kibok Lee](https://ml.yonsei.ac.kr/professor)

**B.S. in Mathematics and Computer Science, Yonsei University (Mar. 2020 – Feb. 2026)**

- _Magna Cum Laude_
- Military Service: Jan. 2021 – Jul. 2022

**Summer Session, University of California, Berkeley (Jul. – Aug. 2024)**

## Academic Experiences

Teaching Assistant

- Statistical Machine Learning (STA3142), Spring 2026

- Computer Vision for Data Science (STA3143), Fall 2026
  

<style>
/* Home: two-column layout */
.post > article {
  display: grid;
  grid-template-columns: 220px minmax(0, 1fr);
  column-gap: 72px;
  align-items: start;
}

/* Left column: photo and email */
.post > article > .profile {
  grid-column: 1;
  float: none !important;
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
}

.post > article > .profile figure,
.post > article > .profile img {
  width: 100%;
}

.post > article > .profile .more-info {
  overflow-wrap: anywhere;
}

/* Right column: text */
.post > article > .clearfix {
  grid-column: 2;
  min-width: 0;
}

/* Section spacing */
.post > article > .clearfix > h2 {
  margin-top: 48px;
  margin-bottom: 20px;
}

.post > article > .clearfix > h2:first-child {
  margin-top: 0;
}

.post > article > .clearfix > h3 {
  margin-top: 28px;
  margin-bottom: 16px;
}

/* Paragraph spacing */
.post > article > .clearfix > p {
  line-height: 1.85;
  margin-bottom: 20px;
}

/* Bullet spacing */
.post > article > .clearfix > ul {
  margin-top: 12px;
  margin-bottom: 28px;
}

.post > article > .clearfix > ul > li {
  margin-bottom: 10px;
  line-height: 1.75;
}

/* Other sections */
.post > article > :not(.profile):not(.clearfix) {
  grid-column: 1 / -1;
}

/* Mobile */
@media (max-width: 767px) {
  .post > article {
    grid-template-columns: 1fr;
    row-gap: 32px;
  }

  .post > article > .profile,
  .post > article > .clearfix {
    grid-column: 1;
  }

  .post > article > .profile {
    max-width: 220px !important;
  }
}
</style>
