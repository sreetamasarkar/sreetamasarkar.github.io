---
layout: about
title: about
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic_sreetama.jpg
  image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 10 # leave blank to include all the news in the `_news` folder

# latest_posts:
#  enabled: true
#  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#  limit: 3 # leave blank to include all the blog posts
---
I am a 5<sup>th</sup> year PhD student in the [EESSC lab](https://sites.usc.edu/eessc/) at the [University of Southern California](https://minghsiehece.usc.edu/), advised by [Prof. Peter Beerel](https://viterbi.usc.edu/directory/faculty/Beerel/Peter).

My research focuses on **efficient and trustworthy AI systems**. I develop methods that reduce computation and improve reliability while preserving model quality. My work spans two main directions:

- **Efficiency:** I focus on improving model efficiency by reducing redundant computations: exploiting spatial and temporal redundancy in videos ([MaskVD](https://arxiv.org/pdf/2407.12067)), pruning visual tokens ([RedVTP](https://arxiv.org/abs/2511.12428)), and skipping redundant layers in vision-language models ([FlashVLM](https://openreview.net/forum?id=dT4ijGCYSs)). Most recently, I worked on [cross-model KV cache reuse](https://arxiv.org/pdf/2610.11358) with selective recomputation for prefill latency reduction.

- **Trustworthiness:** I investigate why vision-language models hallucinate and design inference-time interventions to improve visual grounding ([SPIN](https://arxiv.org/abs/2505.16411)). Building on this, I aim to explore multimodal model safety by studying how models distinguish task-relevant evidence from instructions embedded in untrusted images, documents, and videos.

Previously, I earned my Master of Science in Communication Engineering from the [Technical University of Munich](https://www.tum.de/en/) and conducted my master's thesis on robustness-aware model pruning at [BMW](https://www.bmwgroup.com/en.html). I received my BTech in Electronics and Communications Engineering from the National Institute of Technology, Durgapur, India, with a gold medal.

<section class="mentorship-box" aria-labelledby="mentorship-title">
  <h2 id="mentorship-title">mentorship</h2>
  <p>I’m happy to mentor motivated undergraduate and master’s students interested in research on efficient and trustworthy ML systems. If you’re interested, please <a href="mailto:{{ site.data.socials.email | encode_email }}">email me</a> with your CV!</p>
</section>
