+++
# A Featured Publications section created with the Featured Content widget.
# This section displays publications from `content/publication/` which have
# `featured = true` in their front matter.

widget = "custom"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = ""
subtitle = "Working Paper"

+++

<script type="text/javascript">
<!--
    function toggle_visibility(id) {
       var e = document.getElementById(id);
       if(e.style.display == 'none')
          e.style.display = 'block';
       else
          e.style.display = 'none';
     return false;
    }
//-->
</script>

<div class="card-simple">

  <div class="article-metadata">
    <div>
      <span>Wei Guo, Ruqian Chen, Yen-Chi Chen and Ashis G. Banerjee</span>
    </div>
    <span class="article-date"><time>April 2020</time></span>
    <span class="middot-divider"></span>
    <span class="pub-publication">Working paper</span>
  </div>

  <h3 class="article-title mb-1 mt-3">
    <a href="/publication/network-tda/">Efficient Community Detection in Large-Scale Dynamic Networks Using
      Topological Data Analysis</a>
  </h3>

  <div class="article-style">
    We develop a framework for analyzing communitity structures in dynamic
    networks based on the established community tree representation. With the
    information revealed by community trees and the corresponding persistence
    diagrams, our proposed approach can efficiently detect clique communities
    and keep track of the major structural changes during their evolution
    given a stability threshold.
    <a href="javascript:void(0)" onclick="return toggle_visibility('sms-evolution');" class="expand"><p>[+/-] Key
      figure</p></a>
    <div id="sms-evolution" style="display: none;">
      <img src="/publication/network-tda/sms_evolution.png" style="width: 100%;" class="center" />
    </div>

  <div class="btn-links">
    <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/w-guo/Network-TDA" target="_blank"
        rel="noopener">
      <i class="fab fa-github mr-1"></i>
      code
    </a>
  </div>
</div>
