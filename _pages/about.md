---
title: The Lab
description: About the MAKinteract lab at KAIST - HCI, Korea, Haptics, VR, Digital Fabrication, Prototyping tools
---
<head>
<meta name=”robots” content="index, follow">
</head>

Hello. **MAKinteract** (**MAK**E + **interact**ion) is a research lab in the department of [Industrial
Design](http://id.kaist.ac.kr) at [KAIST](http://www.kaist.edu/html/en/index.html) working at the intersection of design and engineering, in the field of Human-Computer Interaction (**HCI**).

Using user-centered design to define requirements, iterative prototyping, digital fabrication, and users studies to better understand users, we create **novel mechatronic systems and fabrication toolkits** for helping designers inventing yet unseen interactions.

---

### Meet the makers

{% assign prof = site.data.people[0] %}

<div class="container-fluid">
    <div class="row">
        <div class="col-lg-4 col-md-4 col-sm-4 text-center people">
            <div class="service-box">
                <img src="/images/people/{{ prof.name | append: '_' | append: prof.lastname | append: '.jpg' | downcase  }}"
                    alt="{{prof.name}}" class="rounded-circle">
                <h5>{{prof.name}}<br>{{prof.lastname}}</h5>
                <b>{{prof.position}}<br>Director</b>
                <div class="icons">
                    {% if prof.homepage %}<a href="{{prof.homepage}}"><i class="fas fa-home" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.github %}
                    <a href="http://github.com/{{prof.github}}"><i class="fab fa-github" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.linkedin %}
                    <a href="https://www.linkedin.com/in/{{prof.linkedin}}"><i class="fab fa-linkedin-in" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.facebook %}
                    <a href="https://www.facebook.com/{{prof.facebook}}"><i class="fab fa-facebook" aria-hidden="true"></i></a>
                    {%endif%}
                    {% if prof.scholar %}
                    <a href="https://scholar.google.co.kr/citations?user={{prof.scholar}}"><i class="fas fa-graduation-cap" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.email %}
                    <a href="#" onclick="(function(){window.open('mailto:{{ prof.email }}');})()"><i class="fas fa-envelope"></i></a>
                    {% endif %}
                </div>
            </div>
        </div>

        <!-- OTHER MEMBERS -->
        {% include people_grid.html %}
    </div>

</div>

<!-- IMAGE  -->
<!-- <div class="img-container">
    <img src="/images/people/group.jpg" alt="The Lab" style="width:100%;">
    <h5 class="text-overlay">Few hours before the CHI deadline...</h5>
</div> -->

### Collaborators

Our research was possible also thanks to numerous collaborators:
[Michel Pahud](https://www.microsoft.com/en-us/research/people/mpahud/) and [Mike Sinclair](https://www.microsoft.com/en-us/research/people/sinclair/) (Microsoft Research), [Ian Oakley](http://interactions.unist.ac.kr) (UNIST), [Daniel Ashbrook](http://danielashbrook.com) (University of Copenhagen), [Artem Dementyev](http://www.artemdementyev.com) (Google), [Jean-Charles Bazin](https://scholar.google.com/citations?user=XPZLx-8AAAAJ&hl=en) (now at Apple), [Pedro Lopes](http://plopes.org) (University of Chicago), [Xing-Dong Yang](https://www.cs.dartmouth.edu/~xingdong/) (Dartmouth College), [Liwei Chan](https://scholar.google.co.uk/citations?user=yF0Cw1EAAAAJ&hl=en) (National Chiao Tung University), [Aaron Quigley](https://sachi.cs.st-andrews.ac.uk/people/faculty/aaron-quigley/) and [Hui-Shyong](https://hsyeo.com) (University of St Andrews), [Hamed Alavi](http://hamedalavi.com) and [Himanshu Verma](http://human-ist.unifr.ch/people-and-team/himanshu-verma) (University of Fribourg), [Youngjun Cho](https://youngjuncho.com) (UCL), [Hyeon-Jeong Suk](Suk http://color.kaist.ac.kr) and [Tek-Jin Nam](http://cidr.kaist.ac.kr) (KAIST Design),[Geehyuk Lee](http://hcil.kaist.ac.kr/?page_id=349) (KAIST School of Computing), [Hyoungshick Kim](https://seclab.skku.edu) (SKKU).

If you are interested in collaborating with us, please reach out.

<a href="contact.html" class="button button--large">Contact us</a>
