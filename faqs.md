---
layout: page
title: Frequently Asked Questions About Whiskey
---

<section class="section">
  <div class="container">
    <div class="content">
      <ul class="faqs-list">
        {% for faq in site.faqs %}
          <li>
            <a href="{{ faq.url | relative_url }}" class="is-size-5 has-text-link">{{ faq.title }}</a>
          </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</section>
