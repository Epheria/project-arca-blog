---
title: About
permalink: /about/
layout: page
excerpt: Developers who love pixels and make games.
comments: false
image: /assets/img/avatar.png
---

<style>
  .special-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column; /* 세로 정렬 */
    margin: 20px; /* 외부 여백 */
    padding: 10px; /* 내부 여백 */
    border: 2px solid #ccc;
    border-radius: 8px;
    transition: transform 0.2s;
  }

  .special-container:hover {
    transform: scale(1.05); /* 마우스 오버 시 확대 */
  }

  .special-img {
    width: 200px;
    height: 200px;
    border-radius: 50%; /* 원형 이미지 */
    object-fit: cover;
    margin-bottom: 10px;
  }

  .about-text {
    text-align: center;
    font-size: 18px;
    line-height: 1.6;
  }

  .about-links {
    margin-top: 15px;
    text-align: center;
  }

  .about-links a {
    margin: 0 10px;
    text-decoration: none;
    color: #007acc;
    font-weight: bold;
  }

  .about-links a:hover {
    text-decoration: underline;
  }
</style>

<figure>
  <div class="special-container">
    <img class="special-img" src="{{ site.baseurl }}{{ page.image }}" alt="profile image">
    <figcaption class="about-text">
      Developers who love pixels and make games.
    </figcaption>
  </div>
</figure>

  You can [report](https://github.com/Epheria/project-arca-blog/issues/new) 
  if there is a broken link or something else.

  **May you need ✨**

  - {{ site.author.email }}
  - [GitHub](https://github.com/{{ site.author.github }})
