---
layout: default
title: "Members"
permalink: /members/
---
<h1>Authors</h1>

<ul>
  {% for author in site.authors %}
    <li>
      <h2>{{ author.name }}</h2>
      <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

## Consulting

The Consulting Service tier has 4 messaging templates.

- P0 Incident Response Priority Messaging

- P1 The first 48 Hours

- P2 The Seven Day Theory

- P3 Two Weeks

## Community

Share your journey!

- Discord
- What's App
- LinkedIn
- YouTube
- Reddit
- Meetup
- X
