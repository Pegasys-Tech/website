---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: index
title: Home
---
<!--- This line is for the call to action section with a button edit the text between the quotes --->
{% include components/call-to-action.html text="This is placeholder" buttonText="Click Me" %}

<!--- The data for blurbs can be edited in src/_data/blurbs.yml --->
{% include components/6-blurb-sections.html %}


{% include components/dark-section-cta.html title="Title text" description="change me" url="/contact" buttonText="click me" image="/assets/images/browser-set.png"  %}

{% include components/services-snippet.html %}
