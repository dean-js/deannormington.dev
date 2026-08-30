---
layout: main
title: About Me | Dean Normington
description: "Bradford-based web developer and Shopify builder with a background in customer service. Read about my training, my NCFE Level 3 cybersecurity studies, and how I chose hands-on e-commerce work over the traditional college route."
---

<section class="page-section about-section">
  <h1>About Me</h1>
  <p class="about-story-header"><strong>My Story</strong></p>

<p class="about-bio">I'm Dean, a web developer and Shopify builder based in Bradford. True passion always finds a way back: after stepping away from software development as a teenager, and later realising law wasn't the right fit alongside other personal commitments, I pivoted back to tech with a clear head and a renewed focus.</p>

<p class="about-bio">Before any of that, I spent time in customer service, and it's not a footnote. Knowing what it's like to be on the other end of a support ticket shapes how I build and how I work with people, just as much as the code does. Since then I've built on that with NCFE Level 3 Cyber Security studies, self-taught web development fundamentals, and a growing set of practical projects.</p>

<p class="about-bio">When a hands-on e-commerce role came up this year, I chose it over the traditional college route: real systems, real customers, and real Shopify work from day one, rather than waiting on a qualification to open that door. Formal study is still on the table further down the line; for now, I'm building my skills where the work is. The goal is straightforward: grow into a developer who can build and support sites and stores for small businesses, the way I'd want to be supported myself.</p>
  <h2>My Journey at a Glance</h2>
<div class="education-timeline">
  {% for item in site.data.education %}
    <div class="timeline-block">
      <div class="timeline-dot"></div>
      <div class="timeline-card">
        <span class="timeline-date">{{ item.year }}</span>
        <h3>{{ item.title }}</h3>
        <span class="timeline-institution">{{ item.institution }}</span>
        <p>{{ item.description }}</p>
      </div>
    </div>
  {% endfor %}
</div>

  <h2>My Learning Path</h2>
  <div class="learning-path">
    <div class="learning-item">
      <h3>Customer Service &amp; Communication</h3>
      <ul>
        <li>Real customer service experience, not just client-facing polish</li>
        <li>Technical writing</li>
        <li>Plain, effective communication with clients and users</li>
      </ul>
    </div>
    <div class="learning-item">
      <h3>Courses &amp; Studies</h3>
      <ul>
        <li>Cybersecurity Practices Level 3 (Online Short Course), Think Employment (June&ndash;August 2026)</li>
        <li>NCFE Level 3 in Cybersecurity Systems (2026)</li>
        <li>Law (LLB) with Foundation Year (made the change back to tech)</li>
        <li>ICT Level 3 (BTEC) (2018)</li>
        <li>ICT (GCSE) (2017)</li>
      </ul>
    </div>
    <div class="learning-item">
      <h3>Certifications</h3>
      <ul>
        <li>Shopify Certification (in progress)</li>
        <li>FreeCodeCamp</li>
        <li>TryHackMe</li>
        <li>W3Schools</li>
        <li>Cisco Online Academy</li>
      </ul>
    </div>
    <div class="learning-item">
      <h3>Technical Skills</h3>
      <p>Independent coding practice, foundational programming milestones, and hands-on Shopify e-commerce work.</p>
      <ul>
        <li>Shopify store setup &amp; theme customisation</li>
        <li>JavaScript fundamentals</li>
        <li>Northcoders entry prep &amp; coding challenge problems</li>
      </ul>
    </div>
    <div class="learning-item">
            <h3>Extracurricular Activities</h3>
            <ul>
                <li>Personal projects</li>
                <li>TryHackMe rooms</li>
                <li>Home lab setup</li>
            </ul>
        </div>

    </div>

</section>
