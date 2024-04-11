---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

<br>

<style>
  @media (max-width: 768px) {
    /* Adjust table layout for small screens */
    .publication-table, .publication-table td, .publication-table tr {
      display: block;
      width: 100%;
    }
    /* Hide table headers on small screens */
    .publication-table thead tr {
      display: none;
    }
    /* Make images responsive */
    .publication-table td img {
      max-width: 90%;
      height: auto;
      margin: 0 auto; /* Center-align the image */
    }
    /* Style publication info for small screens */
    .publication-table td:not(:first-child) {
      padding: 10px 5%;
    }
  }

  /* Styles for all screen sizes */
  .publication-table {
    width: 100%;
    border-collapse: collapse;
    border: none;
  }
  .publication-table td {
    border: none;
  }
  .publication-buttons .btn {
    text-decoration: none;
    background-color: #007bff;
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
    display: inline-block;
    margin-right: 5px;
  }
</style>

<!-- Publications Table -->
<table class="publication-table">
  <!-- Repeat this block for each publication -->
  <tr style="background-color: #FFFFFF;">
    <!-- Image Column -->
    <td style="padding: 20px 0; text-align: center;">
      <img src="/images/bc_proj.png" alt="Publication Thumbnail">
    </td>
    <!-- Publication Info Column -->
    <td>
      <h3 style="margin: 0;">Unveiling Voices: Identification of Concerns in a Social Media Breast Cancer Cohort via Natural Language Processing</h3>
      <p style="margin: 5px 0; color: #555;"><b>Swati Rajwal</b>, Avinash Kumar Pandey, Zhishuo Han, Abeed Sarker</p>
      <p style="margin: 5px 0; color: #555;">CL4HEALTH Workshop within LREC-COLING, 2024</p>
      <div class="publication-buttons">
        <a href="https://github.com/swati-rajwal/BreastCancer_tweets_project" target="_blank" class="btn">PAPER</a>
        <a href="https://github.com/swati-rajwal/BreastCancer_tweets_project" target="_blank" class="btn">CODE</a>
      </div>
    </td>
  </tr>
  <tr><td colspan="2" style="padding: 10px; background-color: transparent;"></td></tr>
  <!-- End of publication block -->
</table>
