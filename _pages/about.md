---
layout: about
title: About
permalink: /
subtitle: >
  M.S. Student · <a href="https://www.cs.tsinghua.edu.cn/csen/">Department of Computer Science and Technology</a> · <a href="https://www.tsinghua.edu.cn/en/">Tsinghua University</a>

profile:
  align: right
  image: profile-black-cat.png
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  :root {
    --global-theme-color: #58aeda;
    --global-hover-color: #318fbd;
  }
  html { scroll-behavior: smooth; }
  h2 { scroll-margin-top: 5rem; }
  #publications {
    clear: both;
    padding-top: 0.75rem;
  }
  .publications .abbr figure {
    margin: 0;
  }
  .publications .abbr picture {
    display: flex;
    width: 100%;
    aspect-ratio: 4 / 3;
    align-items: center;
    justify-content: center;
    background: var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 0.25rem;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.16), 0 2px 10px rgba(0, 0, 0, 0.12);
  }
  .publications .abbr img.preview {
    display: block;
    width: auto !important;
    height: auto !important;
    max-width: 100%;
    max-height: 100%;
    aspect-ratio: auto;
    object-fit: contain;
    background: transparent;
    border: 0;
    box-shadow: none !important;
  }
  .social .contact-icons {
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: center;
    gap: 1.15rem;
    font-size: 2.4rem;
  }
  .social .contact-icons a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    color: var(--global-text-color) !important;
    line-height: 1;
  }
  .social .contact-icons a:hover {
    color: var(--global-theme-color) !important;
  }
  footer {
    background: var(--global-bg-color) !important;
    color: var(--global-text-color-light) !important;
    border-top: 1px solid var(--global-divider-color);
  }
</style>

I am currently an M.S. student in the Department of Computer Science and Technology at Tsinghua University, advised by [Shi-Min Hu](https://cg.cs.tsinghua.edu.cn/shimin.htm) and [Tai-Jiang Mu](https://cg.cs.tsinghua.edu.cn/people/~mtj/). I received my B.E. from the same department in 2026.

My research interests include long-sequence modeling, model architecture, and generative models.

If you are interested in my research or would like to collaborate, please feel free to reach out.

<h2 id="publications">Publications</h2>

<div class="publications">
{% bibliography %}
</div>

<p><small><sup>*</sup> Equal contribution.</small></p>

<h2 id="education">Education</h2>

<div class="table-responsive">
  <table class="table table-sm table-borderless">
    <tbody>
      <tr>
        <th scope="row" style="width: 20%">2026–Present</th>
        <td><strong>M.S.</strong>, <a href="https://www.cs.tsinghua.edu.cn/csen/">Department of Computer Science and Technology</a>, <a href="https://www.tsinghua.edu.cn/en/">Tsinghua University</a></td>
      </tr>
      <tr>
        <th scope="row">2022–2026</th>
        <td><strong>B.E.</strong>, <a href="https://www.cs.tsinghua.edu.cn/csen/">Department of Computer Science and Technology</a>, <a href="https://www.tsinghua.edu.cn/en/">Tsinghua University</a></td>
      </tr>
    </tbody>
  </table>
</div>

<h2 id="experiences">Experiences</h2>

<div class="table-responsive">
  <table class="table table-sm table-borderless">
    <tbody>
      <tr>
        <th scope="row" style="width: 20%">2026</th>
        <td><strong>Research Intern</strong>, Tencent AMS</td>
      </tr>
      <tr>
        <th scope="row">2024–2025</th>
        <td><strong>Research Intern</strong>, ShengShu Technology</td>
      </tr>
    </tbody>
  </table>
</div>

<h2 id="awards-honors">Awards &amp; Honors</h2>

<div class="table-responsive">
  <table class="table table-sm table-borderless">
    <tbody>
      <tr>
        <th scope="row" style="width: 20%">2024</th>
        <td><strong>Second Prize</strong>, Style Transfer Image Generation Track, 4th Jittor Artificial Intelligence Challenge (1st on the A Leaderboard; 2nd on the B Leaderboard).</td>
      </tr>
      <tr>
        <th scope="row">2020</th>
        <td><strong>Gold Medal (5th Place Nationwide)</strong>, 34th Chinese Chemistry Olympiad (Final).</td>
      </tr>
    </tbody>
  </table>
</div>
