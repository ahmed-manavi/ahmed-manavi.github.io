---
permalink: /
title: "Ahmed Manavi Alam"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="lead">
Hi, I'm Ahmed. I'm a PhD candidate in Electrical and Computer Engineering at NC State University, currently working as a Graduate Research Assistant, and previously a Machine Learning and DSP Research Engineering Intern at Bose Corporation.
</p>

<p class="lead">
My research centers on developing machine learning models for intelligent sensing systems, including physics-inspired models for radio-frequency interference detection, radar &amp; audio signal processing, and room acoustics. Over 6+ years, I've authored more than 25 technical publications, contributed to NASA- and NSF-funded research projects, and gained hands-on industry experience through two research engagements at Bose Corporation.
</p>

<ul class="tag-list">
<li class="tag">Machine Learning</li>
<li class="tag">RFI Detection &amp; Mitigation</li>
<li class="tag">Digital Signal Processing</li>
<li class="tag">Time-Frequency Analysis</li>
<li class="tag">Software-Defined Radio</li>
<li class="tag">Spectrum Coexistence</li>
<li class="tag">Integrated Sensing &amp; Communication</li>
<li class="tag">Radar / Array Signal Processing</li>
<li class="tag">GNSS-R &amp; Passive Radar</li>
<li class="tag">UAS &amp; Satellite Remote Sensing</li>
<li class="tag">Precision Agriculture</li>
<li class="tag">Room Acoustics</li>
<li class="tag">Spatial Audio</li>
</ul>

<ul class="highlight-list">
<li><strong>25+</strong> technical publications, including 6 IEEE journals</li>
<li><strong>NASA SMAP</strong> project, Award No. 80NSSC25K7061 ($493,000)</li>
<li><strong>NSF SWIFT-SAT</strong> project, Award No. 2332661 ($750,000)</li>
<li><strong>NSF</strong> Spectrum Coexistence project, Award No. 2030291 ($516,000)</li>
<li>Two research engagements at <strong>Bose Corporation</strong>, ML &amp; audio DSP</li>
<li>Taught <strong>24</strong> course sections to 460+ students at DIU</li>
<li>Advised <strong>15</strong> undergraduates across 5 capstone projects</li>
<li>NC State <strong>Mentored Teaching Fellow</strong>, co-taught ECE 301</li>
<li>IEEE reviewer: JSTARS, TGRS, TRS, TAES; session chair, IGARSS 2023</li>
<li>GRSS volunteer, AGU 2024; Graduate Student Member, IEEE</li>
</ul>

---

## News

<div class="news-card">
<ul class="news-list">
{% assign recent_posts = site.posts | sort: "date" | reverse %}
{% for post in recent_posts limit:6 %}
<li><span class="news-date">[{{ post.date | date: "%Y/%m" }}]</span><span><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></span></li>
{% endfor %}
</ul>
</div>
<p class="section-more"><a href="{{ base_path }}/year-archive/">See all news &rarr;</a></p>

---

## Selected Publications

<div class="pub-preview-grid">
  <div class="pub-preview-item">
    <a href="{{ base_path }}/publication/2025-rfinet"><img src="{{ base_path }}/images/over_rfi_net_final.png" alt="RFI-Net"></a>
    <div>
      <a class="pub-preview-title" href="{{ base_path }}/publication/2025-rfinet">RFI-Net: Enhancing Passive Sensing through Deep Learning Based Time-Frequency Domain RFI Detection and Mitigation</a>
      <p class="pub-preview-venue">IEEE Transactions on Geoscience and Remote Sensing, 2026</p>
    </div>
  </div>
  <div class="pub-preview-item">
    <a href="{{ base_path }}/publication/2024-access-spectrum-coexistence"><img src="{{ base_path }}/images/5G_radiometer_overall.jpg" alt="Spectrum coexistence testbed"></a>
    <div>
      <a class="pub-preview-title" href="{{ base_path }}/publication/2024-access-spectrum-coexistence">A Physical Testbed and Open Dataset for Passive Sensing and Wireless Communication Spectrum Coexistence</a>
      <p class="pub-preview-venue">IEEE Access, 2024</p>
    </div>
  </div>
  <div class="pub-preview-item">
    <a href="{{ base_path }}/publication/2024-hrspecnet"><img src="{{ base_path }}/images/Auto-UNET.png" alt="HRSpecNet"></a>
    <div>
      <a class="pub-preview-title" href="{{ base_path }}/publication/2024-hrspecnet">HRSpecNET: A Deep Learning-Based High-Resolution Radar Micro-Doppler Signature Reconstruction for Improved HAR Classification</a>
      <p class="pub-preview-venue">IEEE Transactions on Radar Systems, 2024</p>
    </div>
  </div>
</div>
<p class="section-more"><a href="{{ base_path }}/publications/">See all publications &rarr;</a></p>

---

## Education

**Ph.D., Electrical Engineering**, North Carolina State University, Raleigh, NC *(Expected October 2026 · CGPA 4.00/4.00)*  
Dissertation: *Spectrum Coexistence Between Active Technologies and Passive Sensing Systems* · Advisor: Dr. Ali Gurbuz

**M.S., Electrical and Computer Engineering**, Mississippi State University, Starkville, MS *(April 2024 · CGPA 4.00/4.00)*  
Thesis: *Radio Frequency Interference Detection and Mitigation in Microwave Radiometers with Deep Learning* · Advisor: Dr. Ali Gurbuz

**B.S., Electrical and Electronic Engineering**, Bangladesh University of Engineering and Technology (BUET), Dhaka, Bangladesh *(June 2019)*  
Advisor: Dr. Nahid-Al-Masood

---

## Experience

**Machine Learning and DSP Research Engineering Intern**, Bose Corporation, Framingham, MA *(May 2026 – Aug 2026)*

**Graduate Research Assistant**, IMPRESS Lab, North Carolina State University *(Jan 2025 – May 2026)*

**Audio ML & DSP Research Co-op**, Bose Corporation, Framingham, MA *(Jul 2024 – Dec 2024)*

**Graduate Research Assistant**, IMPRESS Lab, Mississippi State University *(Aug 2021 – Jun 2024)*

**Machine Learning Intern**, GRI, High Performance Computing Collaboratory, Starkville, MS *(Jun 2023 – Aug 2023)*

**Lecturer**, Electrical and Telecommunication Engineering, Daffodil International University, Dhaka, Bangladesh *(Sep 2019 – Jul 2021)*
