---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Here is a snapshot of each one of our highly valued and skilled team members in the Albrecht lab.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include list.html data="members" component="portrait" filters="role: biosci2" %}
{% include list.html data="members" component="portrait" filters="role: biosci1" %}
{% include list.html data="members" component="portrait" filters="role: agasst" %}
{% include list.html data="members" component="portrait" filters="role: datascientist" %}
{% include list.html data="members" component="portrait" filters="role: programmer" %}
<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %} -->

{% include section.html background="images/background.jpg" dark=true %}

# Former Lab Personnel
In addition to our current lab personnel, we have had the privilege of having many other students, staff, and interns over the years. Here is a list of our former lab members along with their current positions.

## Post Doctoral Associates
* Dr. Anas Fadli
* Dr. Aditi Satpute
* Dr. Indu Tripathi

## Ph.D. Students
* Dr. Leigh Archer
* Dr. Shahrzad Bodaghi-Parker

## Master's Students
* Sudip Kunwar
* Sameer Pokhrel
* Susmita Gaire

## Staff
* Adam Hoeffner
* Gustavo Basaglia
* Thang Kim
* Blessing Chukwuaja
* Murilo Piccin

## Interns
* Respect Musiyiwa

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
