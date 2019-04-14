---
layout: master
image: /solidworks-macro.svg
permalink: "/"
---
{% capture md %}

<div id="overview" data-aos="fade-up" markdown="1" style="margin-bottom: 100px">

# {{ page.sections.overview.title }}

![{{ page.sections.overview.icon_alt }}](/solidworks-macro.svg){: .center-medium}

{% include_relative res/overview.md %}

</div>

<div id="vba" data-aos="fade-up" markdown="1" style="margin-bottom: 100px">

# {{ page.sections.vba.title }}

{% comment %}
![{{ page.sections.vba.icon_alt }}](/solidworks-macro.svg){: .center-medium}
{% endcomment %}

{% include_relative res/vba.md %}

</div>

<div id="recording" data-aos="fade-up" markdown="1" style="margin-bottom: 100px">

# {{ page.sections.recording.title }}

{% comment %}
![{{ page.sections.recording.icon_alt }}](/solidworks-macro.svg){: .center-medium}
{% endcomment %}

{% include_relative res/recording.md %}

</div>

<div id="troubleshooting" data-aos="fade-up" markdown="1" style="margin-bottom: 100px">

# {{ page.sections.troubleshooting.title }}

{% comment %}
![{{ page.sections.troubleshooting.icon_alt }}](/solidworks-macro.svg){: .center-medium}
{% endcomment %}

{% include_relative res/troubleshooting.md %}

</div>

<div id="library" data-aos="fade-up" markdown="1" style="margin-bottom: 50px">

# {{ page.sections.library.title }}

{% comment %}
![{{ page.sections.library.icon_alt }}](/solidworks-macro.svg){: .center-medium}
{% endcomment %}

{% include_relative res/library.md %}

</div>

{% for macro in page.sections.library.featured %}
{% capture thecycle %}{% cycle 'odd', 'even' %}{% endcapture %}
{% if thecycle == 'odd' %}
{% assign effect = 'fade-right' %}
{% else %}
{% assign effect = 'fade-left' %}
{% endif %}
<div data-aos="{{ effect }}" markdown="1" style="margin-bottom: 50px">

## {{ macro.title }}
    
{{ macro.summary }}

[Get Macro]({{ macro.url }})
    
</div>
{% endfor %}

{% endcapture %}
{{ md | markdownify }}