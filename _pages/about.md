---
permalink: /
title: "Hello and welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! -->

I am an incoming PhD student at MIT, where I will join the Clinical and Applied Machine Learning ([CAML](https://www.csail.mit.edu/research/clinical-and-applied-machine-learning-group-caml)) Group at CSAIL, advised by Prof. [John Guttag](https://people.csail.mit.edu/guttag/) and Prof. [Adrian Dalca](https://www.mit.edu/~adalca/).

My research objective is to develop fundamental machine learning methods that are grounded in real clinical needs and robust to the data limitations (i.e. heterogeneity and scarcity) inherent in medical settings.

I obtained my BS degree from Vanderbilt University, where I double majored in Computer Science and Mathematics with a minor in Data Science. At Vandy, I was fortunate to be advised by Prof. [Jie Ying Wu](https://engineering.vanderbilt.edu/bio/?pid=jieying-wu) and Prof. [Bennett A. Landman](https://www.vanderbilt.edu/vise/visepeople/bennett-landman/). My undergraduate research focused on biomechanics-based deformable registration for surgical guidance and model generalizability in medical imaging.

<!-- Research Interests
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html). -->


<h2>News</h2>

<div style="position:relative;">
  <ul id="news-list">
    <li>[12/2025] I am selected as one of <strong>8</strong> undergraduate awardees nationwide to receive the <strong>2025–2026 CRA Outstanding Undergraduate Researcher Award</strong>!</li>
    <li>[09/2025] I gave an <strong>oral presentation</strong> at MICCAI 2025 on our paper <a href="https://link.springer.com/chapter/10.1007/978-3-032-05114-1_5">"Augmented Reality-Based Guidance with Deformable Registration in Head and Neck Tumor Resection"</a>!</li>
    <li>[09/2025] I am selected to receive the <strong>MICCAI 2025 NIH Registration Grant</strong>!</li>
    <li>[06/2025] Our paper <a href="https://link.springer.com/chapter/10.1007/978-3-032-05114-1_5">"Augmented Reality-Based Guidance with Deformable Registration in Head and Neck Tumor Resection"</a> has been accepted to <strong>MICCAI 2025</strong>!</li>
    <li>[02/2025] I gave an <strong>oral presentation</strong> at SPIE Medical Imaging 2025 on <a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13408/1340811/Nonrigid-alignment-of-en-bloc-tissue-specimen-to-resection-bed/10.1117/12.3047043.short">"Nonrigid Alignment of En Bloc Tissue Specimen to Resection Bed..."</a>.</li>
    <li>[01/2025] I am selected as an <strong>Honorable Mention</strong> for the <a href="https://cra.org/about/awards/outstanding-undergraduate-researcher-award/"><strong>2024-2025 CRA Outstanding Undergraduate Researcher Award</strong></a>!</li>
    <li>[12/2024] I am honored to be the only undergraduate speaker at the <a href="https://www.vanderbilt.edu/vise/symposium-schedule/">VISE 13th Annual Symposium</a>.</li>
    <li>[10/2024] My paper <a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13408/1340811/Nonrigid-alignment-of-en-bloc-tissue-specimen-to-resection-bed/10.1117/12.3047043.short">"Nonrigid Alignment of En Bloc Tissue Specimen..."</a> has been accepted to SPIE Medical Imaging 2025!</li>
    <li>[10/2024] Our paper <a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13408/3047413/Automated-segmentation-of-central-airway-obstruction-from-endoscopic-video-stream/10.1117/12.3047413.short">"Automated segmentation of central airway obstruction..."</a> has been accepted to SPIE Medical Imaging 2025!</li>
    <li>[07/2024] Our paper "Specimen-to-tumor bed deformable registration..." has been accepted to <a href="https://www.frontiersin.org/books/Medical_Image_Understanding_and_Analysis/12759">MIUA 2024</a>!</li>
    <li>[01/2024] Joined the Machine Automation, Perception, and Learning (MAPLE) Lab advised by Dr. Jie Ying Wu!</li>
  </ul>

  <div id="news-fade" style="
    position:absolute;
    bottom:0px;
    left:0; right:0;
    height:80px;
    background: linear-gradient(to bottom, transparent, white);
    pointer-events:none;
  "></div>
</div>

<div style="text-align:center; margin-top:8px;">
  <a id="news-btn" onclick="toggleNews()" style="cursor:pointer; color:#666; text-decoration:underline; font-size:14px;">
    Show more ▼
  </a>
</div>

<style>
  #news-list {
    max-height: 200px;
    overflow: hidden;
    transition: max-height 0.4s ease;
  }
  #news-list.expanded {
    max-height: 2000px;
  }
</style>

<script>
function toggleNews() {
  var list = document.getElementById("news-list");
  var btn = document.getElementById("news-btn");
  var fade = document.getElementById("news-fade");
  if (list.classList.contains("expanded")) {
    list.classList.remove("expanded");
    btn.textContent = "Show more ▼";
    fade.style.display = "block";
  } else {
    list.classList.add("expanded");
    btn.textContent = "Show less ▲";
    fade.style.display = "none";
  }
}
</script>


<!-- ==================== PUBLICATIONS ==================== -->
<h2> Publications </h2>

<div style="position:relative;">  
  <ul id="pub-list">
    <li>
      <strong>Yang, Q.*</strong>, Li, F.*, et al. 
      <a href="https://link.springer.com/chapter/10.1007/978-3-032-05114-1_5">"Augmented Reality-Based Guidance with Deformable Registration in Head and Neck Tumor Resection."</a>
      <em>MICCAI 2025.</em> <strong>(Oral Presentation, Paper Highlight)</strong>
    </li>
    <li>
      <strong>Yang, Q.</strong>, Acar, A., et al.
      <a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13408/1340811/Nonrigid-alignment-of-en-bloc-tissue-specimen-to-resection-bed/10.1117/12.3047043.short">"Nonrigid Alignment of En Bloc Tissue Specimen to Resection Bed to Enhance Correspondence for Re-Resection Guidance."</a>
      <em>SPIE Medical Imaging 2025.</em> <strong>(Oral Presentation)</strong>
    </li>
    <li>
      Ringel, M., Acar, A., <strong>Yang, Q.</strong>, et al.
      <a href="https://www.frontiersin.org/books/Medical_Image_Understanding_and_Analysis/12759">"Specimen-to-tumor bed deformable registration to inform re-resection in otolaryngologic procedures."</a>
      <em>MIUA 2024.</em>
    </li>
  </ul>
  <div id="news-fade" style="
      position:absolute;
      bottom:0px;
      left:0; right:0;
      height:80px;
      background: linear-gradient(to bottom, transparent, white);
      pointer-events:none;
    "></div>
</div>


<div style="text-align:center; margin-top:8px;">
  <a href="{{ site.baseurl }}/publications/" style="cursor:pointer; color:#666; text-decoration:underline; font-size:14px;">
  See all publications →
  </a>
</div>

<!-- ==================== AWARDS ==================== -->
<h2> Awards & Fellowships </h2>

<div style="position:relative;">
  <ul>
    <li>CRA Outstanding Undergraduate Researcher Award</li>
    <li>MICCAI 2025 NIH Registration Grant</li>
    <li>Stanford SERGE Scholar</li>
    <li>2025 VISE Fellowship ($8000) </li>
  </ul>
  <div id="news-fade" style="
    position:absolute;
    bottom:0px;
    left:0; right:0;
    height:80px;
    background: linear-gradient(to bottom, transparent, white);
    pointer-events:none;
  "></div>
</div>

<div style="text-align:center; margin-top:8px;">
  <a href="{{ site.baseurl }}/awards/" style="cursor:pointer; color:#666; text-decoration:underline; font-size:14px;">
  See all →
  </a>
</div>

<!-- ==================== PRESENTATIONS ==================== -->
<h2>Presentations</h2>

<div style="position:relative;">
  <ul>
    <li>
      <a href="{{ site.baseurl }}/talks/2025-9-27-talk-3"><strong>Oral & Poster Presentation — MICCAI 2025</strong></a>
      , Daejeon, South Korea. Sep 2025.
    </li>
    <li>
      <a href="{{ site.baseurl }}/talks/2025-2-19-talk-2"><strong>Oral Presentation — SPIE Medical Imaging 2025</strong></a>
      , San Diego, CA, USA. Feb 2025.
    </li>
    <li> 
      <a href="{{ site.baseurl }}/talks/2025-12-11-talk-1"><strong>Invited Undergraduate Speaker — VISE 13th Annual Surgery, Intervention, and Engineering Symposium.</strong></a>
      Nashville, TN, USA. Dec 2024.
    </li>
  </ul>
  <div style="
    position:absolute;
    bottom:0px;
    left:0; right:0;
    height:80px;
    background: linear-gradient(to bottom, transparent, white);
    pointer-events:none;
  "></div>
</div>

<div style="text-align:center; margin-top:8px;">
  <a href="{{ site.baseurl }}/talks/" style="cursor:pointer; color:#666; text-decoration:underline; font-size:14px;">
    See all presentations →
  </a>
</div>

<!-- ==================== BLOG ==================== -->
<h2> Selected Blog <a href="/qingyun-yang.github.io/year-archive/" style="font-size:14px; font-weight:normal; margin-left:8px;">See all →</a></h2>

<div style="position:relative;">
  <ul>
    <li>
      <a href="{{ site.baseurl }}/posts/2026/04/PhD/"><strong>My PhD Application Experience: Resources, Lessons, and Honest Advice</strong></a>
    </li>
  </ul>
</div>

<!-- 1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section -->

<!-- Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
