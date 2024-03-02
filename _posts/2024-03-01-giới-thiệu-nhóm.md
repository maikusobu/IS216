---
layout: post
title: Giới thiệu nhóm
date: 2024-03-01 22:10 +0700
tags: [team, introduction]

pin: true
---



Trong bài viết này, chúng tôi xin giới thiệu đến các bạn nhóm của chúng tôi. Nhóm chúng tôi gồm những thành viên đam mê công nghệ và đang học tập tại trường Đại học XYZ.

### Team1Six


<table>
  <tr>
    <th style="text-align:center">Thành viên</th>
    <th style="text-align:center">Vai trò</th>
    <th style="text-align:center">Mã số sinh viên</th>
  </tr>
  {% for member in site.data.member %}
  <tr>
    <td style="text-align:center">{{ member.name }}</td>
    <td style="text-align:center">{{ member.position }}</td>
    <td style="text-align:center">{{ member.mssv }}</td>
  </tr>
  {% endfor %}
</table>



Chúng tôi là một nhóm đồng đội sáng tạo và hướng tới mục tiêu xây dựng những sản phẩm công nghệ tốt nhất. Hy vọng rằng bạn sẽ thích những gì chúng tôi đang làm và ủng hộ chúng tôi trong hành trình phát triển
