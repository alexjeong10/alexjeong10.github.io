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

Welcome! I am a Master's student in Statistics and Data Science at Yonsei University, advised. Prior to that, I received my Bachelor's degree from Yonsei University, double majoring in Mathematics and Computer Science (Graduated with Honors, Top 3% of the College).

## Research Areas

My research primarily focuses on deep learning. I am interested in understanding the gap between the ideal or optimal states of deep learning models and their actual behaviors. Recently, I have been working on Vision-Language Models (VLMs) and Multimodal Large Language Models (MLLMs). My earlier research focused on deep learning under long-tailed distributions.


<style>
/* Home: two-column layout */
.post > article {
  display: grid;
  grid-template-columns: 240px minmax(0, 1fr);
  column-gap: 64px;
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

/* Right column: all text */
.post > article > .clearfix {
  grid-column: 2;
  min-width: 0;
}

/* Other sections, if enabled */
.post > article > :not(.profile):not(.clearfix) {
  grid-column: 1 / -1;
}

/* Mobile */
@media (max-width: 767px) {
  .post > article {
    grid-template-columns: 1fr;
    row-gap: 24px;
  }

  .post > article > .profile,
  .post > article > .clearfix {
    grid-column: 1;
  }

  .post > article > .profile {
    max-width: 240px !important;
  }
}
</style>
