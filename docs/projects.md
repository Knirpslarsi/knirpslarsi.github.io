---
layout: default
title: Projects
---

<section>
    <div class="container">
        <h2>My Projects</h2>
        <div class="content-grid">
            {% for project in site.projects %}
            <div class="card">
                <h3>{{ project.title }}</h3>
                <p>{{ project.description }}</p>
            </div>
            {% endfor %}
        </div>
    </div>
</section>
