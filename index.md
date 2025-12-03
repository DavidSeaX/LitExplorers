---
title: "Discover, Discuss, and Dive Deeper into Every Story"
layout: splash

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/image/waitlist/ship.jpg
  actions:
    - label: "Discover"
      url: "/discover/"
    - label: "Learn More"
      url: "#more"
    # - label: "Join the Waitlist"
    #   url: "/waitlist/"
  caption: "[&copy;](https://unsplash.com/@zoltantasi)" # zoltan-tasi-sJGvoX_eVhw-unsplash
  excerpt: "Join the waitlist for a new way to experience books like never before."

intro: 
  - excerpt: "**<a id='more'></a>LitExplorers isn't just another reading app;** it's a community where every page turn leads to new connections, insights, and adventures."

feature_row:
  - image_path: /assets/image/waitlist/sea1.jpg
#    alt: "A group of stylized avatars in a circle, like a book club meeting."
    title: "Connect with Fellow Book Lovers"
    excerpt: "Create or join book clubs where you can discuss chapters, share insights, and explore themes with guided prompts.<br><br>Turn reading into a social adventure."
  - image_path: /assets/image/waitlist/sea2.jpg
#    alt: "A book with a progress bar or a checklist."
    title: "Track Your Reading Journey"
    excerpt: "Set your reading goals, track your progress, and earn badges for your achievements. Whether it's pages or books, we help you see your growth as a reader."
  - image_path: /assets/image/waitlist/sea3.jpg
    image_caption: "[&copy;](https://unsplash.com/@matthardy)" # body-of-water-under-sky-6ArTTluciuA
#    alt: "Forum threads or speech bubbles."
    title: "Engage in Lively Discussions"
    excerpt: "Dive into forums where you can debate, discuss, and delve into the nuances of literature. From plot twists to character development, share your thoughts or learn from others."

feature_row2:
  - image_path: /assets/image/waitlist/man.jpg
    image_caption: "[&copy;](https://unsplash.com/@zoltantasi)" # zoltan-tasi-kC3wXDtLSLs-unsplash
#    alt: "A silhouette with books, bookmarks, or badges."
    title: "Showcase Your Reading Identity"
    excerpt: "Your profile is your reading legacy. Highlight your favorite quotes, books, and the badges you've earned.<br><br>Connect with others who share your literary tastes."

feature_row3:
  - image_path: /assets/image/waitlist/explore.jpg
    image_caption: "[&copy;](https://unsplash.com/@zoltantasi)" # a-black-and-white-photo-of-a-tunnel-W-bs1dL8wew 
#    alt: "A lightbulb or a magnifying glass."
    title: "More to Explore"
    excerpt: 'Look forward to features like AI-driven insights, gamified reading challenges, and collaborative annotations.<br><br>Your reading experience will only get richer.'

feature_row4:
#  - image_path: /assets/image/x.jpg
#    alt: ""
-   title: "Get Updates on Our Launch"
    excerpt: ""
    url: /waitlist/
    btn_label: "Join the Waitlist"
    btn_class: "btn--primary"
---
<style type="text/css">
  #site-nav > ul.visible-links > li:nth-child(2),
  #site-nav > ul.visible-links > li:nth-child(3),
  #site-nav > ul.visible-links > li:nth-child(4) {
    display: none;
  }
  #site-nav > ul:after {
    background-color: unset;
    content: "";
  }
</style>
{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

<a id="join"></a>
{% include feature_row id="feature_row4" type="center" %}
{% comment %}
{% endcomment %}
