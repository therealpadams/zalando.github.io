---
layout: default
title: Documentation
description: Zalando's Open Source Documentation
permalink: /docs
banner:
  image: laptop.jpg
---

<section class="page-section page-section--padding">
  <div class="dc-container dc-container--limited article documentation">
    <div class="article__content">
      <div class="dc-column__contents dc-column__contents--center">

      <h1 class="dc-h1">Documentation</h1>
      
      <h4>Despite widespread use, there are still many misconceptions and uncertainties
      for Zalando employees engaging in Open Source. Questions on legal issues, licensing and what is 
      deemed confidential or internal information is common. 
      </h4>

      <p>This website is therefore a guide, primarily for Zalando employees, on how to adopt, modify and release Open Source code. There are a few references to internal Zalando sites or services, but with an effort to limit our use of internal lingo or acronyms.
      </p> 

      <h4>Topics</h4>
      
      <ul>
    

      <li><a href="{{"docs/using/index" | relative_url }}">Adopting open source code</a><br>
      <p>
      Policies on what to be aware of when adopting open source code in a Zalando project. This applies to both adding dependencies and to contributing upstream.</p>
      </li>

       <li><a href="{{"docs/releasing/index" | relative_url }}">Releasing an open source project</a> <br>
        <p>A step by step guide on what to do before you can release a project and guidelines on how to
        maintain a project</p>
        </li>

        <li><a href="{{ "docs/reports/june-2018" | relative_url}}">State of open source at Zalando</a> <br>
          <p>The latest report on how open source is doing at Zalando with key numbers and insights, as well
            as a roadmap forward. 
          </p>
        </li>


      </ul>

      
      
      </div>
    </div>
    <div class="article__sidebar">
      <div class="dc-column__contents dc-column__contents--center">
        {% include docs-list.html %}
      </div>
    </div>

  </div>
</section>
