---
title: Work
permalink: "/work/"
date: '2016-03-23T11:48:41.000-04:00'
layout: default
page_sections:
- template: block-gallery
  project:
  - title_project: Master of All Baths
    project_cover_image: "/images/257-merlin-road4.jpg"
    project_link: master-of-all-baths
  - title_project: Material Minutia
    project_cover_image: "/images/img_2990.jpg"
    project_link: ''
  - title_project: Summit Grill Waldo
    project_cover_image: "/images/20180412-summit-0230-edit_hr.jpg"
    project_link: ''
  - title_project: Pool Party
    project_cover_image: "/images/20190920-dscf1172-lr.jpg"
    project_link: ''
  - title_project: South of Summi
    project_cover_image: "/images/ex8b1192.jpg"
    project_link: ''
  - title_project: Lightbox
    project_cover_image: "/images/img_0626.jpg"
    project_link: ''
  - title_project: Summit Grill Gladstone
    project_cover_image: "/images/20190918-dscf0869-lr.jpg"
    project_link: ''
  - title_project: Waldo Home
    project_cover_image: "/images/dining1.jpg"
    project_link: ''
  - title_project: Hanover House
    project_cover_image: "/images/5_huntley_finaledit_62_sm.jpg"
    project_link: ''

---
<!-- --include feature_row-- -->
<div class="row" style="margin: 15px 30px;">
{% for block in page.page_sections %}
    {% assign template = block.template %}
    {% case template %}
        {% when 'block-gallery' %}
        {% include {{template}}.html %}
    {% endcase %}
{% endfor %}
</div>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script>
$( document ).ready(function() {
    document.querySelectorAll('.project').forEach((project) => {
      console.log(project);
      project.addEventListener("mouseover", function(){
        project.children[0].children[0].style.visibility = "hidden";
      });
      project.addEventListener("mouseout", function(){
        project.children[0].children[0].style.visibility = "visible";
      });
    });
});
</script>