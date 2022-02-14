---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

We are an interdisciplinary team of collaborative researchers which includes students at all levels. 

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: mphil, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% include section.html dark=true %}

We are expanding and always looking for new team members! 

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/team/image.png"
  link1="https:/link"
  tooltip1="thankyou"

 %}

