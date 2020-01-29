---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---


<p class="date">
  Added to the listing on <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
    <p>
      This page was created on behalf of <a href="https://twitter.com/{{ HostoneTwitter }}">{{ HostoneTwitter }}</a> and may contain mistakes and/or be out of date. If you feel something is incorrect or should be removed, <a href="https://github.com/iChris/saskpodcasts/issues/new">please submit an issue</a>.
    </p>
  </div>
</main>
