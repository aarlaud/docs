---
title: ""
languages:
  - name: "Node.js"
    logo: "https://res.cloudinary.com/snyk/image/upload/v1495652282/node-logo.svg"
    link: "/docs/snyk-for-nodejs"
  - name: "Ruby"
    logo: "https://res.cloudinary.com/snyk/image/upload/v1495652283/ruby-logo.svg"
    link: "/docs/snyk-for-ruby"
  - name: "Java"
    logo: "https://res.cloudinary.com/snyk/image/upload/v1495652282/java-logo.svg"
    link: "/docs/snyk-for-java"
---

<!-- <div class="alert alert--inline u--centered"><b class="h3">Snyk continuously finds and fixes vulnerabilities in your dependencies.</b></div> -->

<div class="layout-cols layout-cols--3 u--centered">
    
    {% for lang in page.languages %}
    <div class="layout-cols__item">
        <a href="{{lang.link}}"><img class="lang-img" src="{{lang.logo}}" alt="{{lang.name}}"></a>
        <a class="h6" href="{{lang.link}}">Snyk for {{lang.name}}</a>
    </div>
    {% endfor %}
    
</div>

