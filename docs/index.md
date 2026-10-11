---
layout: default
title: Vicky's Guide to Berkeley
---

# # Vicky's Guide to Berkeley

Welcome to Berkeley! This guide introduces useful places and services to help new students explore the campus, find study spaces, and enjoy their daily lives.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
