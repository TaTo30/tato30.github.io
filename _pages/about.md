---
permalink: /
title: "Welcome to my digital corner!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! My name is Aldo Hernandez and this is my personal space in the internet. Do not expect to find serious or formal content here, I create this site just to leave my fingerprint in the digital space and write down some thoughts or ideas of multiple topics across the time. A journal where I can check to remember what (and why) I was doing during those days and maybe somebody may find this content useful for whatever reason, who knows.

I am a Guatemalan living in Guatemala City and I have been working in the tech industry since 2022 as software engineer creating applications and solutions using differents stacks and architectures. Typical SWE stuff, nothing special to be honest. I also have contributed and authored open-source project mostly in Vue ecosystem which is the framework that I love use for personal projects, you can find my main contributions in my portfolio. Nowadays I keep doing SWE stuff but from time to time I am doing other types of activities like hiking or motorcycle routes, we can't be productive all the time, can we?.

---

### Links

[Portfolio](/portfolio). <br/>
[CV](/cv).

---

## Recent Posts

{% include base_path %}
{% if site.posts.size > 0 %}
  {% for post in site.posts limit:5 %}
    {% include archive-single.html %}
  {% endfor %}
  {% if site.posts.size > 5 %}
    <p><a href="/blog/">View all posts →</a></p>
  {% endif %}
{% else %}
  <p>No posts yet.</p>
{% endif %}