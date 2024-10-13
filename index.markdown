---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<style>
  .contents-section {
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
  }
  .contents-section:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
  }
  .contents-title {
    color: #333;
    border-bottom: 2px solid #4a4a4a;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }
  .lecture-list {
    list-style-type: none;
    padding: 0;
  }
  .lecture-list li {
    margin-bottom: 10px;
    opacity: 0;
    animation: fadeIn 0.5s ease forwards;
  }
  .lecture-list li a {
    color: #0066cc;
    text-decoration: none;
    transition: color 0.2s ease;
  }
  .lecture-list li a:hover {
    color: #004080;
  }
  @keyframes fadeIn {
    to { opacity: 1; }
  }
</style>

<div class="contents-section">
  <h2 class="contents-title">Contents</h2>

  <ul class="lecture-list">
    <li>
      <h3><a href="{{ site.baseurl }}/lecture1/">Introduction to Deep Learning</a></h3>
    </li>
  </ul>
</div>
