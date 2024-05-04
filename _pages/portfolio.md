---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

### Certificates

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px;">

![Certificate 1] <br/><img src='/images/portfolio/Certificate1.png' alt=''>
*Master's of Science in Medical Biochemistry from Addis Ababa University*

![Certificate 2](https://github.com/mezgebulegese/mezgebulegese.github.io/raw/main/images/portfolio/Certificate2.png)
*Description of certificate 2.*

![Certificate 3](https://github.com/mezgebulegese/mezgebulegese.github.io/raw/main/images/portfolio/Certificate3.png)
*Description of certificate 3.*

![Certificate 4](https://github.com/mezgebulegese/mezgebulegese.github.io/raw/main/images/portfolio/Certificate4.png)
*Description of certificate 4.*

![Certificate 5](https://github.com/mezgebulegese/mezgebulegese.github.io/raw/main/images/portfolio/Certificate5.png)
*Description of certificate 5.*

</div>

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
