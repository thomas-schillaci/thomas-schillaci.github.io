---
title: Our paper has been accepted to the IEEE RA-Letters!
categories:
  - Machine Learning
  - Research
tags:
  - Reinforcement Learning
  - Robotics
  - Deep Learning
  - ROS
  - Tensorflow
excerpt: 
  The first paper I contributed has been accepted to the IEEE RA-L and will be presented at ICRA 2021!
---

{% capture fig_img %}
![Decoration image]({{ '/assets/images/heron.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption style="margin: auto;">The Heron dashing around the Symphonie lake</figcaption>
</figure>

The first paper I contributed to has been accepted to the IEEE Robotics and Automation Letters.
<br/>
*How to Train Your HERON* [\[1\]](#first_li) is available on <a href="https://ieeexplore.ieee.org/document/9376100">IEEE Xplore</a> and <a href="https://arxiv.org/abs/2102.10357">arXiv</a>.

In addition to being published in the IEEE RA-Letters, our paper will be presented at the International Conference on Robotics and Automation (ICRA) in 2021.

My contribution consists of the state of the art in Reinforcement Learning, the choice and justification of our agent (Dreamer) in the context of our research, and the related works in perception-based control.

<style>
  .reference_ul {
    list-style-type: none;
  }
  .reference_li::before {
    margin-left: -30px;
    margin-right: 6px;
  }
  #first_li::before {
    content: '[1]';
  }
  #second_li::before {
    content: '[2]';
  }
</style>

<ul class="reference_ul">
  <li class="reference_li" id="first_li">A. Richard, S. Aravecchia, T. Schillaci, M. Geist and C. Pradalier, "How to Train Your HERON," in IEEE Robotics and Automation Letters, vol. 6, no. 3, pp. 5247-5252, July 2021, doi: 10.1109/LRA.2021.3065278.</li>
</ul>
