--- 
id: endpoints
title: Endpoints
<!-- permalink: /endpoints/ -->
---
    
{% for endpoint in site.endpoints %}
    ## {{ endpoint.name }} - {{ endpoint.type }}
    `{{ endpoint.api_url}}`
    {{ endpoint.content | markdownify }}
{% endfor %}