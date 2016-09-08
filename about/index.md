---
layout: template1
title: About
comments: false
---

<div class="jumbotron">
    <p>{{ site.desc }}</p>
    <p><a class="btn btn-lg btn-primary" href="https://github.com/uhlibraries-digital/bcdams-map" role="button">View {{ site.title }} Code on Github &raquo;</a></p>
</div>

# Description

The {{ site.title }} builds on the University of Houston Digital Library's [Metadata Dictionary](http://digital.lib.uh.edu/about/metadata). It aligns closely with the [DPLA MAP v4.0](https://dp.la/info/wp-content/uploads/2015/03/MAPv4.pdf). 


# API

```
\api\dptf.json
```
Returns DPTF metadata elements as JSON

```
\api\damstf.json
```
Returns DAMSTF metadata elements as JSON

```
\api\graph.jsonld
```
Returns BCDAMS-MAP graph as JSON-LD
