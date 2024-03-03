---
layout: post
title: Giới thiệu nhóm
date: 2024-03-01 22:10 +0700
tags: [team, introduction]
author: [loi, nhat]
excerpt: "Trong bài viết này, chúng tôi xin giới thiệu đến các bạn nhóm của chúng tôi"
pin: true
image:
    path: /assets/img/posts/2024-03-01-giới-thiệu-nhóm/intro.svg
---


Nhóm chúng tôi gồm những thành viên đam mê công nghệ và đang học tập tại trường Đại học Công nghệ thông tin.

## Thành viên

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

## Slogan

***We are the sick ones***

## Mục tiêu

- Tích lũy kinh nghiệm, kiến thức trong quá trình học tập.
- Tiếp xúc với những công nghệ mới.
- Have fun.

## Hoạt động

- Seminar về spring framework, spring boot.
- Đồ án sử dụng swing java với đề tài về một app đặt đồ ăn.
