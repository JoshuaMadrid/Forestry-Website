---
title: About
permalink: "/about/"
excerpt: 
last_modified_at: 
layout: default
page_sections:
- template: block-page-description
  page_headline: about lo design
  page_description:
    Lo to call attention or to express wonder or surprise.

    At Lo.Design we approach every project with enthusiasm and joy. We work thoughtfully. We create beautiful spaces. We respect our clients. We dream big while designing down to earth. This is Lo.Design.
- template: block-about-image
  about_image: ''
- template: block-accordion
  personal_bios:
  - name: Brain
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
      Hufft Project, Kansas City, MO January 2018- September 2014<br><br>Voith and
      Mactavish Architects, Philadelphia, PA August 2014- February 2013</p>"
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
<h2>template</h2>
<p>
{% for block in page.page_sections %}
    {% assign template = block.template %}
    {% case template %}
        {% when 'block-page-description' %}
            <p>this is a test</p>
            <h4>{{ template }}</h4>
        {% when 'block-about-image' %}
            <p>image test</p>   
    {% endcase %}
{% endfor %} 
</p>

<div class="row" style="margin: 15px 0px; border-top: solid 1px #2b2b2b; padding-top: 20px;">
    <div class="col-sm-6 col-lg-6" style="font-size: 25px;">
        <p>about lo design</p>
    </div>
    <div class="col-sm-6 col-lg-6" style="font-size: 25px;">
        <p></p>
    </div>
</div>
<div class="row" style="margin: 15px 0px;">
<div class="col-sm-6 col-lg-6" style="font-size: 25px;">
        
</div>
<div class="col-sm-6 col-lg-6" style="font-size: 25px;">
    <p>Lo to call attention or to express wonder or surprise.
    <br><br>
    At Lo.Design we approach every project with enthusiasm and joy. We work thoughtfully. We create beautiful spaces. We respect our clients. We dream big while designing down to earth. This is Lo.Design.
    </p>
</div>
</div>
<div class="row" style="margin: 15px 0px;">
    <img src="https://via.placeholder.com/1980x1080/2b2b2b/ffffff" height="auto" width="100%" style="width:100%; height: auto;">
</div>
<div class="row" style="margin: 15px 0px; padding-top: 20px;">
    <div class="col-sm-6 col-lg-6" style="font-size: 25px;">
        <div style="position: relative; border-bottom: solid 1px #2b2b2b; padding: 0px 0px 40px 0px; margin-top: 50px;">
            <p style="font-size: 50px; font-weight: normal; line-height: 0px;">Brain </p>
            <span class="parentPlus expand brain" style="position: absolute; right: 0px;"><a class="plusMin"></a></span>
        </div>

<p class="hide BrainCopy">
    Brian is an architect and urban designer whose experience is with projects of a wide range of scales. His work focuses on the interrelation of architecture and urban design, shaping the built environment through the creation of vibrant and engaging places that are both environmentally sustainable and intensely site-specific. He has completed regional master plans, large-scale watershed plans, governmental and collegiate campus plans, non-profit community center feasibility studies and multi-family housing site plans. In addition, he has designed, detailed and built projects as small as single-family row home renovations to large-scale, multi-family housing projects, with a constant eye on the intersection and interrelation of architecture and urbanism.
    <br><br>
    Education: Bachelor of Arts, English; Bachelor of Arts, Art History; Williams Collage, MA
    <br><br>
    Master of Architecture; Master of Urban Design; Washington University, St. Louis
    <br><br>
    Experience:
    Hufft Project, Kansas City, MO
    January 2018- September 2014
    <br><br>
    Voith and Mactavish Architects, Philadelphia, PA
    August 2014- February 2013
</p>
</div>
<div class="col-sm-6 col-lg-6" style="font-size: 25px;">
    <div style="position: relative; border-bottom: solid 1px #2b2b2b; padding: 0px 0px 40px 0px; margin-top: 50px;">
        <p style="font-size: 50px; font-weight: normal; line-height: 0px;">Laura </p>
        <span class="parentPlus expand laura" style="position: absolute; right: 0px;"><a class="plusMin"></a></span>
    </div>
    <p class="hide LauraCopy" >
        Laura Bauers is a registered architect who has been practicing for over 10 years. She has experience in a wide array of typologies including healthcare, labs, academic, adaptive reuse, corporate, residential, and hospitality. She is both an optimist and a skeptic. She will buy the occasional Power Ball ticket, but needs peer reviewed evidence for everything else. 
        <br><br>
        Education: University of Missouri - Columbia
        BA in English; Minor in Environmental Design
        <br><br>
        Washington University in St. Louis; Master of Architecture
        <br><br>
        Experience:
        Hufft Project, Kansas City, MO
        January 2018- September 2014
        <br><br>
        Voith and Mactavish Architects, Philadelphia, PA
        August 2014- February 2013
        <br><br>
        Ballinger, Philadelphia, PA
        February 2013 - August 2009
        <br><br>
        Cannon Design, St. Louis, MO
        July 2009 - June 2008</p>
</div>
</div>

