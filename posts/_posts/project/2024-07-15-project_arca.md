---
layout: post
title:  "Project Arca"
description: 
date: 2024-07-15 09:29:20 +0700
tag: "project"
categories: project
project_id: proj_01
usemathjax: true
img: "/posts/images/project/arcathumb.png"
sitemap :
  changefreq : daily
  priority : 1.2
---

> Project start date : 2024-07-21

<figure>
    <img class="title-image" src="{{site.image_location}}/project/projectarcathumbnail.png" alt="title img">
</figure>

<figure>
    <a href="{{site.image_location}}/project/projectarcathumbnail.png" target="_blank">
        <img class="title-image" src="{{site.image_location}}/project/projectarcathumbnail.png" alt="title img">
    </a>
</figure>

<figure>
    <div class="special-container">
        <img class="special-img" src="{{site.image_location}}/devlogs/jump.gif" alt="thumbnail img">
    </div>
</figure>

<figure>
    <img class="title-image" 
         src="{{site.image_location}}/project/projectarcathumbnail.png" 
         alt="title img" 
         onclick="openModal(this)">
</figure>

<!-- 모달 구조 -->
<div id="imageModal" class="modal" onclick="closeModal()">
    <img class="modal-content" id="expandedImg" alt="Expanded Image">
    <div id="modal-caption"></div>
</div>