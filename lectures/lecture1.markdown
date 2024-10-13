---
layout: default
title: Lecture 1
permalink: /lecture1/
---

<style>
  .lecture-content {
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
  }
  .lecture-content:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
  }
  .lecture-title {
    color: #333;
    border-bottom: 2px solid #4a4a4a;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }
  .file-list {
    list-style-type: none;
    padding: 0;
  }
  .file-list li {
    margin-bottom: 10px;
    opacity: 0;
    animation: fadeIn 0.5s ease forwards;
  }
  .file-list li a {
    color: #0066cc;
    text-decoration: none;
    transition: color 0.2s ease;
  }
  .file-list li a:hover {
    color: #004080;
  }
  @keyframes fadeIn {
    to { opacity: 1; }
  }
</style>

<div class="lecture-content">
  <h1 class="lecture-title">Intro to deep learning</h1>

  <p>Here are the files for this lecture:</p>

  <ul class="file-list">
    <li><a href="/assets/lectures/lecture1/slides.pdf">Slides (pdf)</a></li>
    <li><a href="/assets/lectures/lecture1/tutorial.zip">Tutorial notebook (zip)</a></li>
    <li><a href="/assets/lectures/lecture1/exercises.ipynb">Exercises (notebook)</a></li>
  </ul>
</div>

