---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 👋

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  <strong>Hey there! </strong> So glad you found your way to this little corner of the internet. <br><br>
  This little nook is all about the exciting world of Machine Learning, Deep Learning, and Artificial Intelligence. Buckle up and get ready for an awesome journey!
</p>

This website started as a personal project —a humble GitHub gist where I kept track of the amazing ML resources I stumbled upon while learning the ropes. But hey, why keep all the good stuff to myself? I decided to share it with all of you struggling souls out there who are as eager to dive into ML as I am.

Now, let me tell you a secret 🤫 : I'm still learning every single day. That's right! I'm right there with you, absorbing knowledge, tackling challenges, and discovering mind-blowing concepts. And guess what? I'll be sharing it all right here, with you and the rest of our awesome community.

This website is not your average stuffy educational platform 👎 . No way! It's a friendly hub where you can find curated collections of Machine Learning, Deep Learning and AI resources *(and all the stuff in-between)* that will make your learning experience a whole lot smoother. From beginner-friendly tutorials to mind-expanding research, I've got you covered 👊.
  
But wait, there's more! I'll be sprinkling this place with my own insights , tips, and experiences as I navigate this ever-evolving landscape. Expect regular blog posts and updates that will keep you in the loop and help you stay ahead of the curve. 💪
  
So, grab a cup of coffee (or tea, we don't judge 😉), kick off your shoes, and get ready to embark on an exciting ML adventure with me! We're here to support each other, cheer each other on, and grow together.

Let's learn, laugh, and unleash the power of AI together 😀!

### Getting Started



<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
