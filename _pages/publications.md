---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

<style>
.publication-list {
  width: 100%;
}

.publication-item {
  display: table;
  width: 100%;
  table-layout: fixed;
  margin-bottom: 20px;
}

.publication-thumbnail {
  display: table-cell;
  width: 100px; /* Fixed width for the thumbnail */
  padding-right: 20px; /* Spacing between image and text */
  vertical-align: top; /* Align the content to the top */
}

.publication-thumbnail img {
  width: 100%;
  height: auto;
}

.publication-info {
  display: table-cell;
  vertical-align: top;
}

.btn {
  text-decoration: none;
  background-color: #007bff;
  color: white;
  padding: 5px 10px;
  border-radius: 5px;
  display: inline-block;
  margin-right: 5px;
  margin-top: 10px;
}

.btn:last-child {
  margin-right: 0;
}
</style>

<div class="publication-list">
  <!-- Publication Entry -->
  <div class="publication-item">
    <!-- Publication Image -->
    <div class="publication-thumbnail">
      <img src="/images/bc_proj.png" alt="Publication Thumbnail">
    </div>
    <div class="publication-info">
      <h3>GEO: Generative Engine Optimization</h3>
      <p>Pranjal Aggarwal, Vishvak Murahari, Tanmay Rajpurohit, Ashwin Kalyan, Karthik R Narasimhan, and 1 more author</p>
      <p>arXiv preprint arXiv:2311.09735, 2023</p>
      <div>
        <a href="link-to-abstract" class="btn">ABSTRACT</a>
        <a href="link-to-bibtex" class="btn">BIB</a>
        <a href="link-to-paper" class="btn">PAPER</a>
      </div>
    </div>
  </div>

  <!-- Repeat the block inside .publication-list for each publication -->
  <div class="publication-item">
    <!-- Publication Image -->
    <div class="publication-thumbnail">
      <img src="/images/sn_proj.png" alt="Publication Thumbnail">
    </div>
    <div class="publication-info">
      <h3>GEO: Generative Engine Optimization</h3>
      <p>Pranjal Aggarwal, Vishvak Murahari, Tanmay Rajpurohit, Ashwin Kalyan, Karthik R Narasimhan, and 1 more author</p>
      <p>arXiv preprint arXiv:2311.09735, 2023</p>
      <div>
        <a href="link-to-abstract" class="btn">ABSTRACT</a>
        <a href="link-to-bibtex" class="btn">BIB</a>
        <a href="link-to-paper" class="btn">PAPER</a>
      </div>
    </div>
  </div>
</div>
