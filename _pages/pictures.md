---
title: "Li Group - Pictures"
layout: piclay
excerpt: "Li Group -- Pictures"
permalink: /pictures/
---
# Gallery

## 2024 Fall
<div class="row">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/2024Fall.jpg" class="img-responsive" style="display: block; margin: auto; width: 50%; height: auto;" />
</div>

## 2024 Summer
<div class="row">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/2024Summer1.jpg" class="img-responsive" style="display: block; margin: auto; width: 50%; height: auto;" />

<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/2024Summer2.jpg" class="img-responsive" style="display: block; margin: auto; width: 50%; height: auto;" />
</div>

## 2023 Summer
<div class="row">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/2023summer.png" class="img-responsive" style="display: block; margin: auto; width: 50%; height: auto;" />
</div>




[//]: # (# Pictures)

[//]: # (Jump to: [Leiden]&#40;#leiden&#41;, [ETHZ]&#40;#ethz&#41;, [Cornell]&#40;#cornell&#41;, [St Andrews]&#40;#st-andrews&#41;)

[//]: # ()
[//]: # (#### Gallery)

[//]: # (&#40;Right-click *'view image'* to see a larger image.&#41;)

[//]: # ({% assign number_printed = 0 %})

[//]: # ({% for pic in site.data.pictures_Leiden %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 4 %})

[//]: # ()
[//]: # ({% if even_odd == 0 %})

[//]: # (<div class="row">)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<div class="col-sm-3 clearfix">)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />)

[//]: # (</div>)

[//]: # ()
[//]: # ({% assign number_printed = number_printed | plus: 1 %})

[//]: # ()
[//]: # ({% if even_odd > 2 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ()
[//]: # ({% endfor %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 4 %})

[//]: # ({% if even_odd == 1 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ({% if even_odd == 2 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ({% if even_odd == 3 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<p> &nbsp; </p>)

[//]: # (First advertisement.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >)

[//]: # (</figure>)


[//]: # (## ETHZ)

[//]: # (From the [group of Andreas Wallraff]&#40;http://www.qudev.ethz.ch/&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">)

[//]: # (</figure>)

[//]: # ()
[//]: # (## Cornell)

[//]: # (From the [group of Seamus JC Davis]&#40;http://davisgroup.lassp.cornell.edu&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">)

[//]: # (</figure>)

[//]: # ()
[//]: # (## St Andrews)

[//]: # (From the [group of Felix Baumberger]&#40;http://dqmp.unige.ch/baumberger/&#41; &#40;now at University of Geneva&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">)

[//]: # (</figure>)
