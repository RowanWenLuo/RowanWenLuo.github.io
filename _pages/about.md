---
permalink: /
title: ""
excerpt: ""
redirect_from: 
  - /about/
  - /about.html
---

<section class="hero" id="about-me" aria-label="Introduction">
  <div class="hgroup">
    <p class="eyebrow">Ph.D. Student · Computational Linguistics</p>
    <h1>{{ site.author.name }}</h1>
    <p class="lede">Ph.D. student at the Institute of Computational Linguistics, School of Computer Science, <a href="https://english.pku.edu.cn/" target="_blank" rel="noopener">Peking University</a>, advised by Prof.&nbsp;Houfeng&nbsp;Wang.</p>
    <div class="tokens" aria-label="Research focus: hallucination, factuality, interpretability">
      <span class="tok" data-gloss="detecting and mitigating hallucination in generative models" style="--p:.98"><i class="ix">[0]</i>hallucination<span class="bar"><i></i></span><span class="p">p = 0.98</span></span>
      <span class="tok" data-gloss="improving factuality in long-form generation" style="--p:.95"><i class="ix">[1]</i>factuality<span class="bar"><i></i></span><span class="p">p = 0.95</span></span>
      <span class="tok" data-gloss="mechanistic interpretability of LLM internals" style="--p:.92"><i class="ix">[2]</i>interpretability<span class="bar"><i></i></span><span class="p">p = 0.92</span></span>
    </div>
    <div class="chips">
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">GitHub</a>{% endif %}
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}">Email</a>{% endif %}
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Scholar</a>{% endif %}
      {% if site.author.dblp %}<a href="{{ site.author.dblp }}" target="_blank" rel="noopener">DBLP</a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}" target="_blank" rel="noopener">ORCID</a>{% endif %}
    </div>
  </div>
  <div class="portrait">
    <img src="{{ site.author.avatar }}" alt="{{ site.author.name }}" width="148" height="148">
  </div>
</section>

<section id="about" aria-labelledby="h-about">
  <h2 class="eyebrow" id="h-about">About</h2>
  <div class="prose">
    <p>My research focuses on building reliable and trustworthy large generative models, with a particular emphasis on <span class="hl">hallucination</span>, <span class="hl">factuality</span>, and <span class="hl">mechanistic interpretability</span>. I am broadly interested in developing AI systems that are more truthful, interpretable, and aligned with human expectations.</p>
    <p>Feel free to reach out if you are interested in collaboration or have related research ideas.</p>
  </div>
</section>

<section id="publications" aria-labelledby="h-pubs">
  <h2 class="eyebrow" id="h-pubs">Publications<span class="count">13 entries</span></h2>
  <div class="tabs" role="group" aria-label="Filter publications">
    <button class="tab" data-filter="all" aria-pressed="true">All · 13</button>
    <button class="tab" data-filter="first" aria-pressed="false">First-author · 5</button>
    <button class="tab" data-filter="co" aria-pressed="false">Co-author · 8</button>
  </div>
  <div class="publist">

    <!-- ====== 2026 ====== -->

    <article class="pub" data-role="first">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2026</span><span class="role">First author</span></div>
        <h3><a href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">Only Say What You Know: Calibration-Aware Generation for Long-Form Factuality</a></h3>
        <p class="au"><span class="me">Wen Luo</span>, Guangyue Peng, Liang Wang, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge oral">ACL 2026 · Oral</span><span class="role">First author</span></div>
        <h3><a href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener">Two Pathways to Truthfulness: On the Intrinsic Encoding of LLM Hallucinations</a></h3>
        <p class="au"><span class="me">Wen Luo</span>, Guangyue Peng, Wei Li, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ICML 2026</span></div>
        <h3><a href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener">Measuring and Mitigating Post-hoc Rationalization in Reverse Chain-of-Thought Generation</a></h3>
        <p class="au">Guangyue Peng, Zongchao Chen, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <!-- ====== 2025 ====== -->

    <article class="pub" data-role="first">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span><span class="role">First author</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.1320/" target="_blank" rel="noopener">Odysseus Navigates the Sirens’ Song: Dynamic Focus Decoding for Factual and Diverse Open-Ended Text Generation</a></h3>
        <p class="au"><span class="me">Wen Luo</span>, Feifan Song, Wei Li, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.acl-long.1320/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025 Findings</span></div>
        <h3><a href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">Encode Errors: Representational Retrieval of In-Context Demonstrations for Multilingual Grammatical Error Correction</a></h3>
        <p class="au">Guangyue Peng, Wei Li, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025 Findings</span></div>
        <h3><a href="https://aclanthology.org/2025.findings-acl.655/" target="_blank" rel="noopener">Well Begun is Half Done: Low-resource Preference Alignment by Weak-to-Strong Decoding</a></h3>
        <p class="au">Feifan Song, Shaohang Wei, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.findings-acl.655/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">Learn to Memorize: Scalable Continual Learning in Semiparametric Models with Mixture-of-Neighbors Induction Memory</a></h3>
        <p class="au">Guangyue Peng, Tao Ge, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge spotlight">NeurIPS 2025 · Spotlight</span></div>
        <h3><a href="https://arxiv.org/abs/2505.12891" target="_blank" rel="noopener">TIME: A Multi-level Benchmark for Temporal Reasoning of LLMs in Real-World Scenarios</a></h3>
        <p class="au">Shaohang Wei, Wei Li, Feifan Song, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2505.12891" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.839/" target="_blank" rel="noopener">FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation</a></h3>
        <p class="au">Wei Li, Xin Zhang, Zhongxin Guo, Shaoguang Mao, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.acl-long.839/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">NAACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.naacl-long.251/" target="_blank" rel="noopener">Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction</a></h3>
        <p class="au">Wei Li, <span class="me">Wen Luo</span>, Guangyue Peng, Houfeng Wang</p>
        <a class="src" href="https://aclanthology.org/2025.naacl-long.251/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2025</span></div>
        <h3><a href="https://arxiv.org/abs/2510.09535" target="_blank" rel="noopener">Mitigating Overthinking through Reasoning Shaping</a></h3>
        <p class="au">Feifan Song, Shaohang Wei, Baoxin Gao, Yiwei Wang, <span class="me">Wen Luo</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2510.09535" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <!-- ====== 2024 ====== -->

    <article class="pub" data-role="first">
      <div class="yr">2024</div>
      <div>
        <div class="meta"><span class="badge">ACM MM 2024</span><span class="role">First author</span></div>
        <h3><a href="https://dl.acm.org/doi/abs/10.1145/3664647.3681367" target="_blank" rel="noopener">Shapley Value-based Contrastive Alignment for Multimodal Information Extraction</a></h3>
        <p class="au"><span class="me">Wen Luo</span>, Yu Xia, Tianshu Shen, et al.</p>
        <a class="src" href="https://dl.acm.org/doi/abs/10.1145/3664647.3681367" target="_blank" rel="noopener">ACM DL<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2024</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2024</span><span class="role">First author</span></div>
        <h3><a href="https://arxiv.org/abs/2406.07070" target="_blank" rel="noopener">HalluDial: A Large-Scale Benchmark for Automatic Dialogue-Level Hallucination Evaluation</a></h3>
        <p class="au"><span class="me">Wen Luo</span>, Tianshu Shen, Wei Li, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2406.07070" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

  </div>
</section>

<section id="honors-and-awards" aria-labelledby="h-honors">
  <h2 class="eyebrow" id="h-honors">Honors &amp; Awards<span class="count">04</span></h2>
  <div class="rows">
    <div class="row">
      <div class="when">2025</div>
      <p class="what"><b>President's Scholarship, Peking University</b><span class="honor-rank">Top 1%</span></p>
    </div>
    <div class="row">
      <div class="when">2025</div>
      <p class="what"><b>BOSS Zhipin Scholarship</b></p>
    </div>
    <div class="row">
      <div class="when">2025</div>
      <p class="what"><b>Award for Scientific Research, Peking University</b></p>
    </div>
    <div class="row">
      <div class="when">2022</div>
      <p class="what"><b>Ubiquant Scholarship</b></p>
    </div>
  </div>
</section>

<section id="education" aria-labelledby="h-edu">
  <h2 class="eyebrow" id="h-edu">Education</h2>
  <div class="rows">
    <div class="row">
      <div class="when">2024.09 — 2029.06<br>(expected)</div>
      <p class="what"><b>Ph.D., Peking University</b><small>Institute of Computational Linguistics, School of Computer Science</small></p>
    </div>
    <div class="row">
      <div class="when">2020.09 — 2024.06</div>
      <p class="what"><b>Undergraduate, Peking University</b><small>School of Electronics Engineering and Computer Science</small></p>
    </div>
  </div>
</section>

<section id="internships" aria-labelledby="h-intern">
  <h2 class="eyebrow" id="h-intern">Internships</h2>
  <div class="rows">
    <div class="row">
      <div class="when">2025.08 — Present</div>
      <p class="what"><b>Microsoft Research Asia<span class="now">Now</span></b><small>Beijing</small></p>
    </div>
    <div class="row">
      <div class="when">2023.05 — 2024.08</div>
      <p class="what"><b>Beijing Academy of Artificial Intelligence (BAAI)</b><small>Beijing</small></p>
    </div>
  </div>
</section>
