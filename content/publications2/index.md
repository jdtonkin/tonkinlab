---
Title: "Publications2"
disable_mathjax: true
disable_highlight: true
disable_comments: true
---
<!-- <center> -->
<!-- <a target="_blank" href="https://scholar.google.com/citations?user=0I2wXJQAAAAJ&hl=en"><i class="ai ai-google-scholar ai-2x"></i></a>  -->
<!-- <a target="_blank" href="https://www.researchgate.net/profile/Daijiang_Li"><i class="ai ai-researchgate ai-2x"></i></a>  -->
<!-- <a target="_blank" href="https://publons.com/a/719613/"><i class="ai ai-publons ai-2x"></i></a> -->
<!-- </center> -->

<!-- # In press -->

<!-- <ol> -->
<!-- <li> <b></b>. , et al. <i></i>. In press. <a href="https://" target="_blank" title="Text through DOI"><i class="ai ai-doi"></i></a> </li>  -->
<!-- </ol> -->

# Published

{% for p in site.data.pubs %}
{% include paper.html %}
{% endfor %}
