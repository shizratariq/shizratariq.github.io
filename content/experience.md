---
title: "Experience"
layout: "page"
permalink: "/experience/"
---
<div class="timeline-container">

<div class="timeline-item">
<div class="timeline-content">
<h2>Graduate Research Assistant</h2>
<div class="timeline-meta">
<span class="company">Robotics Perception and Manipulation (RPM) Lab</span>
<span class="date">January 2023 – Present</span>
</div>
<ul>
<li>Developed robotic perception system integrating Segment Anything Model (SAM) with Contact GraspNet</li>
<li>Created pipeline for object identification and optimal grasp point detection</li>
<li>Conducted research on vision-based learning from human demonstrations</li>
<li>Focused on bridging computer vision advancements with practical robotic applications</li>
</ul>
<div class="timeline-description">
<p>Pioneering intuitive robot learning through visual demonstrations. Current research enables robots to acquire manipulation skills from single video examples, mimicking human-like learning patterns. This approach eliminates traditional training constraints and enhances adaptability for unstructured environments.</p>
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-content">
<h2>Software Engineering Intern</h2>
<div class="timeline-meta">
<span class="company">Nilfisk</span>
<span class="date">May 2023 – December 2023</span>
</div>
<ul>
<li>Developed perception algorithms for industrial cleaning robots</li>
<li>Optimized object detection pipelines for dynamic environments</li>
<li>Implemented sensor fusion techniques for improved localization</li>
<li>Contributed to ROS-based navigation stack improvements</li>
</ul>
<div class="timeline-description">
<p>Enhanced robotic vacuum capabilities through software optimizations. Worked on making commercial cleaning robots more autonomous by improving their spatial understanding and decision-making algorithms.</p>
</div>
</div>
</div>

</div>

<style>
.timeline-container {
  position: relative;
  padding-left: 30px;
  margin-left: 20px;
}

.timeline-container::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 2px;
  background: #e0e0e0;
}

.timeline-item {
  position: relative;
  margin-bottom: 2.5rem;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: -29px;
  top: 8px;
  width: 12px;
  height: 12px;
  background: #2c3e50;
  border-radius: 50%;
  z-index: 1;
}

.timeline-content {
  background: #ffffff;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.timeline-meta {
  margin: 0.5rem 0;
  color: #666;
  font-size: 0.9rem;
}

.company {
  display: block;
  font-style: italic;
}

.date {
  display: block;
  color: #888;
}

.timeline-description {
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid #eee;
}

.timeline-content ul {
  padding-left: 1.5rem;
  margin: 1rem 0;
}

.timeline-content li {
  margin-bottom: 0.5rem;
}
</style>
