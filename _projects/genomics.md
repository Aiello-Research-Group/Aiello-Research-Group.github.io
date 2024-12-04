---
layout: page
title: Genomics
description: some description
img: assets/img/genomics.jpg
importance: 1
category: work
related_publications: true
---

The quickly evolving field of genomics has created an exciting opportunity to identify the molecular mechanisms by which the social environment influences health outcomes.  However, this requires proper integration of data from disparate fields and appropriate design of epidemiological studies.  By integrating DNA methylation data into our existing Detroit Neighborhood Health Study (DNHS) dataset since 2009, we have created a rare population-based study for assessing the social, environmental and biological risk factors for mental health among adults living in Detroit.  This work resulted in some of the first evidence for an association between PTSD and alterations in epigenetic markers related to immune function and immune response to cytomegalovirus (Uddin et al.Proc Natl Acad Sci 2010).  It also led to the discovery of novel genome-wide epigenomic signatures in PTSD cases (Ratanatharathorn et al. Am J Med Genet B Neuropsychiatr Genet2017) that likely form through immune mechanisms and together influence DNA methylation age- a marker of immune aging (Wolf et al. Psychoneuroendocrinology 2018).  In another collaboration, we identified microRNA regulation of DICER1expression in PTSD and comorbid depression (Wingo et al. Nat Commun 2015).  These findings suggest a potential brain-immune pathway given the connection between DICER1 expression and regulation of the innate immune system. Together, our genomic work is laying the foundation for identifying new immune pathways linking stressors, immunity, and mental health.

What is the DNHS Study? The Detroit Neighborhood Health Study (DNHS) is a prospective, representative longitudinal cohort study of  adults living in Detroit, Michigan. Although recent work has shown that stressors at multiple levels may be important determinants of psychopathology and behavior, there has been very little systematic effort to understand the contributions of ecologic stressors to the risk of incident post-traumatic stress disorder (PTSD) or drug abuse/dependence while concurrently accounting for individual stressors. The overall goal of the DNHS is to determine whether ecologic stressors (concentrated disadvantage, income distribution, residential segregation, quality of the built environment) influence the risk of PTSD and drug abuse/dependence. Our central hypothesis is that exposure to ecologic factors is a fundamental determinant of population mental health, particularly in the urban context. Additionally, we will begin to assess the relationship between exposure to ecologic stressors, PTSD, and specific immune and inflammatory responses in order to elucidate the potential biological pathways underlying the relationship between psychosocial stress, PTSD, and consequent physical morbidity. This study combines multiple waves of interviews, ecological assessments, and blood samples from 1500 residents from Detroit’s 54 neighborhoods. Bringing together a team with expertise in urban health, survey research, epidemiology and psychoneuroimmunology, this study stands to make a substantial contribution to our understanding of the etiology of PTSD, drug abuse/dependence, and their consequences.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
