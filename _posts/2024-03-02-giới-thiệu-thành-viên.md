---
layout: post
title: Giới thiệu thành viên
date: 2024-03-02 10:55 +0700
excerpt_separator: .
tags: [introduction]
image:
  path: /assets/img/posts/2024-03-02-thành-viên/intro-member.svg
---

Tóm lược về những thành viên của nhóm Team1Six.

{% for member in site.data.member %}

## {{ member.name }}

![img-description](https://avatars.githubusercontent.com/{{member.github}}){: .normal w="100" h="100" }

- Mssv: {{ member.mssv }}
- Vị trí: {{ member.position }}
- GitHub: [{{ member.github }}](https://github.com/{{member.github}})
- Sở thích: {{ member.hobby }}

{% endfor %}
