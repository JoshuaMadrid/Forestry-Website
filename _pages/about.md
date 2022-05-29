---
title: About
permalink: "/about/"
excerpt: 
last_modified_at: 
layout: default
page_sections:
- template: block-page-description
  page_headline: about lo design
  page_description: Lo to call attention or to express wonder or surprise. At Lo.Design
    we approach every project with enthusiasm and joy. We work thoughtfully. We create
    beautiful spaces. We respect our clients. We dream big while designing down to
    earth. This is Lo.Design.
- template: block-about-image
  about_image: "/images/5_huntley_finaledit_24-medium.jpg"
- template: block-accordion
  personal_bios:
  - name: Brian
    bio: "<p>Brian is an architect and urban designer whose experience is with projects
      of a wide range of scales. His work focuses on the interrelation of architecture
      and urban design, shaping the built environment through the creation of vibrant
      and engaging places that are both environmentally sustainable and intensely
      site-specific. He has completed regional master plans, large-scale watershed
      plans, governmental and collegiate campus plans, non-profit community center
      feasibility studies and multi-family housing site plans. In addition, he has
      designed, detailed and built projects as small as single-family row home renovations
      to large-scale, multi-family housing projects, with a constant eye on the intersection
      and interrelation of architecture and urbanism.<br><br>Education: Bachelor of
      Arts, English; Bachelor of Arts, Art History; Williams Collage, MA<br><br>Master
      of Architecture; Master of Urban Design; Washington University, St. Louis<br><br>Experience:
      </p><p>El Dorado, Inc, Kansas City, MO:  July 2016 - February 2021<br><br>HOK,
      Kansas City, MO:  August 2014 - July 2016</p><p>MGA Partners, Philadelphia,
      PA:  January 2013 - July 2016</p><p>WRT, Philadelphia, PA:  September 2009 -
      January 2013</p>"
  - name: Laura
    bio: "<p>Laura Bauers is a registered architect who has been practicing for over
      10 years. She has experience in a wide array of typologies including healthcare,
      labs, academic, adaptive reuse, corporate, residential, and hospitality. She
      is both an optimist and a skeptic. She will buy the occasional Power Ball ticket,
      but needs peer reviewed evidence for everything else.<br><br>Education: University
      of Missouri - Columbia BA in English; Minor in Environmental Design<br><br>Washington
      University in St. Louis; Master of Architecture<br><br>Experience: Hufft Project,
      Kansas City, MO January 2018- September 2014<br><br>Voith and Mactavish Architects,
      Philadelphia, PA August 2014- February 2013<br><br>Ballinger, Philadelphia,
      PA February 2013 - August 2009<br><br>Cannon Design, St. Louis, MO July 2009
      - June 2008</p>"

---
{% for block in page.page_sections %}
    {% assign template = block.template %}
    {% case template %}
        {% when 'block-page-description' %}
{% include {{template}}.html %}
        {% when 'block-about-image' %}
{% include {{template}}.html %}
        {% when 'block-accordion' %}
<div class="row" style="margin: 15px 30px; padding-top: 20px;">
{% include {{template}}.html %}
</div>
    {% endcase %}
{% endfor %}