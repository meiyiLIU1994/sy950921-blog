---
layout: home
---

<div class="index-content project">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/sy950921-blog"><span>博客</span></a></li>
            <li style="text-align:center"><a href="/sy950921-blog/dump"><span>简历</span></a></li>
            <li class="on" style="text-align:right"><a href="/sy950921-blog/project"><span>联系</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.project %}
            <li>
                <h2>
                    <a href="/sy950921-blog{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
