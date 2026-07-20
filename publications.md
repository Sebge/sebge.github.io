---
layout: default
title: Publications
---

## Publications

All Publications can be found in the [BibLaTeX file]({{ "/bibliography/references.bib" | relative_url }})

<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/pcooksey/bibtex-js@1.0.0/src/bibtex_js.js"></script>
<bibtex src="{{ "/bibliography/references.bib" | relative_url }}"></bibtex>
<div class="bibtex_structure">
  <div class="group year" extra="DESC number">
        <div class="templates"></div>
  </div>
</div>
<div class="bibtex_template">
  <div class="bibtex_entry" style="margin-bottom:1.25em; padding-bottom:1em; border-bottom:1px solid #eee;">
    <!--<span class="if article"><strong>[<span class="year"></span>]</strong></span>
    <span class="if inproceedings"><strong>[<span class="year"></span>]</strong></span>
    <span class="if !article !inproceedings"><strong>[<span class="year"></span>]</strong></span>-->
    <span class="title" style="font-weight:bold;"></span><br/>
    <span class="author"></span><br/>
    <span class="if journal"><em><span class="journal"></span></em><span class="if volume">, vol. <span class="volume"></span></span><span class="if pages">, pp. <span class="pages"></span></span></span>
    <span class="if booktitle"><em><span class="booktitle"></span></em><span class="if pages">, pp. <span class="pages"></span></span></span>,
    <span class="year"></span>.
    <div class="if doi">
      <a class="bibtexVar" target="_blank" rel="noopener noreferrer" href="http://dx.doi.org/+DOI+" extra="doi">
        https://dx.doi.org/<span class="doi"></span>
      </a>
    </div>
    <div class="if abstract" style="margin-top:0.4em; font-size:0.92em; color:#555;">
      <em>Abstract:</em> <span class="abstract"></span>
    </div>
  </div>
</div>

<div id="bibtex_display" class="bibtex_display"></div>



<noscript>
  <p><em>JavaScript is required to render the publication list. You can view the raw BibTeX file <a href="{{ "/bibliography/references.bib" | relative_url }}">here</a>.</em></p>
</noscript>

Bibtex Support by [bibtex-js](https://github.com/pcooksey/bibtex-js)